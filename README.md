# interactor-aria-town

An Elixir application that keeps a town's non-player characters, its game clock and its persistence under one supervision tree.

## What it is for

Callers spawn, update, list and despawn characters, and the clock advances game time on a tick. Both are described as JSON-LD through RDF context schemas. Persistence is a stub, and the characters have no behaviour of their own yet. `decisions/` holds the design record.

## Build and run

    mix deps.get
    mix test

## Licence

MIT, as the SPDX headers in the source state.
