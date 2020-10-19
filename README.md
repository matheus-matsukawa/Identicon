# Identicon

Identicon generator app built during "The Complete Elixir and Phoenix Bootcamp" by Stephen Grider

## How it works

The app works via the command line, accepting a string to the main method and generating a .png identicon file on the root directory.

```elixir

> iex -S mix
iex> Identicon.main("something")

```

This simple app was built using Elixir and EDG's Erlang module, elixir and erlang must be installed in order to run it
