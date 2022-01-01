## shef

*shef* is a **s**elf-**h**osted, offline-first recipe/notes manager in a single **sh**ell script.

It is a simple PWA and is designed to run on your home server; modifications while offline will be synced back to a git repo on the server when the server is reachable again.

*shef* is a toy, it is not supposed to be performant. It might serve as an example of a minimal functional PWA.

### Dependencies

- `lighttpd` to serve itself
- `git` for notes storage
- `jq` to prepare JSON for the frontend
- `rsvg-convert` to display its icon
- other standard shell tools like `cat`, `xargs`, `flock`

