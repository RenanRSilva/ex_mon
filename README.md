# ExMon

**ExMon, iex turn game**

## Installation

```elixir
mix deps.get
```

### Start iex shell

```elixir
iex -S mix
```

### Create a player

```elixir
player = ExMon.create_player("Player", :kick, :punch, :heal)
```

### Start game

```elixir
ExMon.start_game(player)
```

### Make move

```elixir
ExMon.make_move(:kick)
```

```elixir
ExMon.make_move(:heal)
```

```elixir
ExMon.make_move(:punch)
```
