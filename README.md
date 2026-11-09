# TOP SHOVEL — Tom Cruise vs. The Critics

A retro shovel-platformer parody. Tom Cruise grabs a shovel and digs, pogos, and
sprints his way through a gauntlet of film critics, all the way to the premiere,
where the Critic-in-Chief, **Mortimer Snobb**, waits to deliver his verdict.

Everything (pixel art, sound effects, chiptune music) is generated in code, so
`index.html` is the whole game. There's no build step and no dependencies.

## Play

Open `index.html` in any modern browser. To serve it locally instead:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | Arrow keys / A, D | ◀ ▶ |
| Jump (hold for higher) | Z / Space / Up / W | JUMP |
| Shovel swing / dig | X / K | DIG |
| Pogo bounce | Hold Down while in the air | ▼ |
| Sprint | Shift (or just keep running: *Cruise Control* kicks in) | automatic |
| Pause / Mute | P or Esc / M | |

## How it plays

- **Dig** dirt blocks with your shovel to uncover gems (box office money).
- **Pogo** on enemies' heads and on dirt blocks by holding Down mid-air. Chain
  three bounces without landing and Tom reminds everyone that he does his own stunts.
- **Deflect** thrown reviews and rotten tomatoes with a well-timed swing.
- **Clapperboards** are checkpoints. Dying yells "CUT!" and costs you 20% of
  the box office, then it's on to the next take.

### The critics

- **Critic** (beret, notepad): patrols and hurls one-star reviews.
- **Blogger** (propeller cap, laptop): hovers and swoops in. Great for pogo chains.
- **Rotten Critic** (trench coat): lobs tomatoes in arcs from ledges.
- **Mortimer Snobb, Critic-in-Chief** (boss): charges with a giant red pen,
  belly-flops out ink shockwaves, and throws tomato volleys. He gets angrier at
  half health. Bait his charge into a wall, then hit him while he's dizzy.

### The level

1. The red carpet
2. The pit of bloggers
3. The dirt wall
4. The pencil pit (sharpened pencils make for very pointed criticism)
5. The review gauntlet
6. The stunt sequence: a pogo chain over a bottomless drop
7. The premiere: boss fight

Win to earn a **100% FRESH** critics consensus.

---

*An affectionate fan-made parody. It isn't affiliated with or endorsed by Tom Cruise or any studio.*
