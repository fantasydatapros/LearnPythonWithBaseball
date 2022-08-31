This section uses [pybaseball](https://github.com/jldbc/pybaseball#readme)

To use pybaseball first install and import it.

```ruby
%pip install pybaseball
import pybaseball as pyb
```
In this section we use 2021 `batting_stats`, which is full year batting stats for qualifying players.
```ruby
pyb.batting_stats(2021, qual = 0)
```
- year: first argument is the year as an int
- qual: second argument is minimum number of at bats for a player to qualify

We also use `standings` data.
```ruby
pyb.standings(2021)
```
- year: first argument is the year as an int
