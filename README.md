# interactor-vertex

An experimental Elixir web backend that serves user content, caches it, and signs users in.

## What it is for

It holds user accounts and the avatars, maps and props they upload, the privileges that gate
those uploads, and the list of running world shards a client reads to find one. It answers a
JSON API for clients and serves a dashboard and an admin interface in the browser.

## Build and run

```sh
mix deps.get
mix ecto.setup
mix phx.server
```

The browser assets install from `assets/` with `npm install`.

## Licence

MIT; see `LICENSE`.
