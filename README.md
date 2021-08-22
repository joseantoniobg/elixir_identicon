# Identicon

\*\*
Idicon can be used to produce 5x5 user identifiable unique icons, also known as identicons.
These are similar to the default icons used with github.
Idicon supports 5x5 identicons in png.

(String eg. User name) -> Idicon -> Image that is (mostly) unique to the user.
Since the identicon can be produced repeatedly from the same input, it is not necessary
to save the produced image anywhere. Instead, it can be rendered each time it is requested.
\*\*

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

**On Windows, be shure you have rebar installed by running `mix local.rebar`**

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).
