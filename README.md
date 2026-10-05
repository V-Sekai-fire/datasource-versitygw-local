# datasource-versitygw-local

An Elixir library that runs a local object-storage gateway over a plain directory and hands back the endpoint config for a storage client.

## What it is for

It provisions the `versitygw` gateway binary, starts and stops a gateway serving a posix directory, and returns a keyword list the caller passes to its own object-storage client. It holds no bucket or object logic. The `VersitygwLocal` module documentation shows the entry point.

## Build

```sh
mix test
```

## Licence

MIT; see `LICENSE`.
