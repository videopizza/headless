# HEADLESS GAME

A satirical stacking game about faceless profiles on location-based dating apps.

Tiles fall into a three-column profile grid. Stack **legs → torso → silhouette** to complete a profile.
Add **feet** underneath for a Full Body super combo. Two identical tiles on top of each other burn
each other out. Press and hold a profile to ⊘ block it — you only get a few.

Run out of room and everyone ghosts you.

**Play:** https://videopizza.github.io/headless/

## Running it

It is one self-contained `index.html` with no build step, no dependencies and no tracking.
Open the file, or serve the folder:

```
python3 -m http.server 8000
```

## Controls

| | |
|---|---|
| Tap a column | move the falling tile there |
| Tap again / swipe down / `Space` | drop |
| `←` `→` | move |
| Press and hold a stacked tile | block it |

## Credits

By [Tomato Cappelletti](http://tomatocappelletti.com). Part of ongoing work on internet culture
with [Clusterduck](https://clusterduck.space).

Body tiles are drawn procedurally as SVG — no photographs of real people are used.

## License

Code under MIT. See `LICENSE`.
