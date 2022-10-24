# Noslate Project Repository Manifests

## Install Repo

Repo, a Google-built repository management tool that runs on top of Git. See
[Source Control Tools][] for an explanation of the relationship between Repo
and Git and links to supporting documentation for each tool.

```bash
# macOS
$ brew install repo

# Debian/Ubuntu.
$ sudo apt-get install repo

# Gentoo.
$ sudo emerge dev-vcs/repo
```

You can install it manually as well as it's a single script.

```bash
$ mkdir -p ~/.bin
$ PATH="${HOME}/.bin:${PATH}"
$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.bin/repo
$ chmod a+rx ~/.bin/repo
```

See [Repo Command Reference][] for command line reference for repo.

## Get Started

```bash
$ cd workspace/noslate
$ repo init -u https://github.com/noslate-project/manifest.git
$ repo sync
```

[Source Control Tools]: https://source.android.com/setup/develop
[Repo Command Reference]: https://source.android.com/setup/develop/repo
