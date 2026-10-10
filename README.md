# interactor-aria-town

An Elixir application that keeps a town's non-player characters, its game clock and its persistence under one supervision tree.

## What it is for

Callers spawn, update, list and despawn characters, and the clock advances when called; it has no tick and is a stub, like persistence. Both are described as JSON-LD through RDF context schemas. The characters have no behaviour of their own yet. `decisions/` holds the design record.

## Build and run

    mix deps.get
    mix test

## Licence

MIT. See [LICENSE](LICENSE).
