# KV

This is the hello world.

## How to create a new project

```
$ mix new kv --module KV
```
this tell Mix that our main module should be the all-uppercase KV, instead of the default kv.

## How to compile

```
$ cd kv
$ mix compile
```

All compilation artifacts are placed inside the _build directory

## Run with iex

```
$ iex -S mix
```

## Recompile it

```
iex> recompile()
```

## Test

```
$ mix test
```

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `kv` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:kv, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/kv](https://hexdocs.pm/kv).

## Reference

[Getting started](https://elixir-lang.org/getting-started/structs.html)