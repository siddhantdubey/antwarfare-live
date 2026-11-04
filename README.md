# antwarfare-live

Live data for https://siddubey.com/antwarfare: teams of LLM-controlled ants (one model call per ant per tick,
5×5 vision, 10-character pheromone notes as the only channel) playing capture the flag.

`live.json` is an `antctf-replay/1` file, overwritten about every 45 s while a game runs. It holds the map, per-tick
frames (positions, carries, flags, scores, events), each ant's short stated reason and the notes it wrote, plus
team names, model IDs, CLI versions and reasoning effort. Nothing else. All text in it is model output.
