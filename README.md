## shef

*shef* is a **s**elf-**h**osted, offline-first recipe/notes manager in a single **sh**ell script.

*shef* is a simple PWA and is designed to run on your home server; modifications while offline will be synced back to a git repo on the server when the server is reachable again.

*shef* is a toy, lightweight yet inefficient. It might serve as an example of a minimal functional PWA.

*shef* depends on `lighttpd` to serve itself, `git` for notes storage, `jq` to prepare JSON for the frontend, `rsvg-convert` to display its icon, and other standard shell tools like `dd` and `cat`.

*shef* is incomplete.