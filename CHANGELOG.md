# Changelog

## 1.0.0

First release of Blast Shield, forked from Blast Radius (see NOTICE).

- Holds `git checkout`/`restore` with paths, `git push -uf`, `git branch -D`, `git stash drop/clear`, `find` with its delete action, `xargs rm`.
- Holds `kubectl delete`, `terraform`/`tofu destroy`, `docker`/`podman` prune and volume removal, destructive SQL, recursive `chmod`/`chown`/`chgrp`.
- Sees through `timeout`, `doas`, `env` and `time` wrappers.
- Pane shows why the command was held and whether it can be undone.
- Stops counting dotfiles in `rm` globs that the shell would not expand.
- Adds classifier tests and a real-process verification script.
