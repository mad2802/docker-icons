# docker-icons

PNG icons for Docker containers, mirrored here so they don't
disappear when third-party template repos are abandoned or deleted.

<p>
  <img src="https://raw.githubusercontent.com/mad2802/docker-icons/main/docker/redis.png" width="48" alt="redis">
  <img src="https://raw.githubusercontent.com/mad2802/docker-icons/main/docker/immich-logo.png" width="48" alt="immich">
  <img src="https://raw.githubusercontent.com/mad2802/docker-icons/main/docker/mariadb-logo.png" width="48" alt="mariadb">
  <img src="https://raw.githubusercontent.com/mad2802/docker-icons/main/docker/valkey-logo.png" width="48" alt="valkey">
</p>

## Usage

Point your container's icon setting at the raw URL:

    https://raw.githubusercontent.com/mad2802/docker-icons/main/docker/<icon>.png

For Unraid Docker Compose stacks:

```yaml
labels:
  net.unraid.docker.icon: "https://raw.githubusercontent.com/mad2802/docker-icons/main/docker/<icon>.png"
```

All icons are PNG. Filenames match the service they represent.

See [SOURCES.md](SOURCES.md) for the full list and where each one came from.

## Why

Container icons are commonly linked from personal template repos
that go stale. When one disappears, the icon breaks with no way
to recover it. This repo is a local copy of the ones I use.

## Attribution

These logos belong to their respective projects and are
redistributed here unmodified, for convenience only. No ownership
or authorship is claimed.

If you own one of these logos and would like it removed,
open an issue and I'll take it down.
