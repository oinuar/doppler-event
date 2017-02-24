# Doppler Event

Provides event types for high level Doppler packages.

## How to build?

The project (`doppler-css`) contains only event depedency sources.
We can create and configure a sandbox for the project.

```
cd doppler-event
cabal sandbox init
cabal install --only-dep
cabal configure
```

You can then build the project.

```
cabal build
```

This will build the library.
