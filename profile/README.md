<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/app-torq/torq/main/docs/assets/torq-logo-w-title-dark.svg">
  <img alt="torq" src="https://raw.githubusercontent.com/app-torq/torq/main/docs/assets/torq-logo-w-title-light.svg" width="240">
</picture>

**The maintenance logbook and repair tracker for people who work on their own cars.**

Self-hosted · one small Docker container · your data stays on your server

[Demo](https://demo.torq-app.tech) · [Repository](https://github.com/app-torq/torq) · [Wiki](https://github.com/app-torq/torq/wiki) · [Releases](https://github.com/app-torq/torq/releases)

</div>

## Projects

| Repository | What it is |
|---|---|
| [**torq**](https://github.com/app-torq/torq) | The app: service logbook, self-repair projects, reminders, offline vehicle catalog and webhook notifications. Go + React, shipped as `ghcr.io/app-torq/torq`. |

## Try it

```bash
docker run -d --name torq -p 8080:8080 -v torq-data:/data ghcr.io/app-torq/torq:latest
```

Or log in to the [public demo](https://demo.torq-app.tech) as `demo` / `password123`. It resets every night.

## Get involved

Bug reports, ideas and fixes are welcome. Read the [contribution guide](https://github.com/app-torq/.github/blob/main/CONTRIBUTING.md) first, and report security issues privately as described in the [security policy](https://github.com/app-torq/.github/blob/main/SECURITY.md).
