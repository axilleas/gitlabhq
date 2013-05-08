# GitLab directory structure

This is the directory structure you will end up with following the instructions in the Installation Guide.

    |-- home
    |   |-- git
    |       |-- .ssh
    |       |-- gitlab
    |       |-- gitlab-satellites
    |       |-- gitlab-shell
    |       |-- repositories


`/home/git/.ssh` - This is where `authorized_keys` reside.

`/home/git/gitlab` - The root directory of GitLab.

`/home/git/gitlab-satellites` - Contains a copy of all repositories with a working tree. It is used for merge requests, editing files, etc.

`home/git/gitlab-shell` - Manages `authorized_keys` and the git repositories.

`/home/git/repositories` - Holds all your repositories in bare format. This is the place Git uses when you pull/push to your projects.

You can change all these paths in your `config/gitlab.yml` file.
