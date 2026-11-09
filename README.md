# DIGGER: DIGG. OR DIE. (Tom Cruise vs. The Critics)

A retro shovel-platformer parody of the movie *Digger*. Tom Cruise is **Digger**:
silver swept-back hair, a burgundy western suit with suede yokes, a turquoise bolo
tie, a gold belt buckle, cowboy boots and a trusty D-handle spade. The critics
who panned the movie are lining up to call it "ALL STYLE, NO SUBSTANCE", and
Digger is going to dig, stomp and boot his way through every one of them.

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
| Spade swing / dig | X / K | DIG |
| **Boot Stomp** (pogo) | Hold Down while in the air | ▼ |
| **THE DIGGER BOOT** (super) | C / L when the boot meter is full | BOOT |
| Sprint | Shift (or just keep running: *Cruise Control* kicks in) | automatic |
| Pause / Mute | P or Esc / M | |

## The Digger Boot

- **Boot Stomp:** hold Down in mid-air to come down heel-first on critics' heads
  and on dirt blocks, bouncing off them. Chain three for "I DO MY OWN STUNTS!",
  five for "DIGG. OR DIE!"
- **THE DIGGER BOOT:** dig dirt, grab oil and gold, beat critics and land hits
  on the boss to fill the boot meter (top-left). Press **C** and a giant
  gold-stitched cowboy boot with a spinning spur falls from the sky and stomps
  every critic on screen. It takes a big chunk out of the boss and leaves him dizzy.

## The critics

- **Critic** (beret, notepad): patrols, yells "C MINUS!", "NO SUBSTANCE!",
  "TOO MUCH LATEX!", and throws C- grade cards.
- **Blogger** (propeller cap, laptop): hovers and posts "#DIGGERFAIL". Perfect
  for stomp chains.
- **Rotten Critic** (trench coat): lobs rotten tomatoes from ledges.
- **Mortimer Snobb, Critic-in-Chief** (boss): charges with a giant red grading
  pen, belly-flops out ink shockwaves, and throws tomatoes and grade cards.
  At half health he declares "I'M GIVING IT A D!" Bait his charge into a wall
  (or the platforms), then dig in while he's dizzy.

Beaten critics have a change of heart ("TRANSFORMATIVE!", "AWARDS SEASON!").
Clapperboards are checkpoints. Dying yells "CUT!" and costs 20% of the box office.

## The level

1. The red carpet
2. The pit of bloggers
3. The dirt wall
4. The pencil pit (sharpened pencils make for very pointed criticism)
5. The review gauntlet
6. The stunt sequence: a stomp chain over a bottomless drop
7. The premiere: boss fight

All set against a sunset of searchlights, the HOLLYDIG sign and nodding oil
pumpjacks. Win to earn a **100% FRESH** critics consensus. And the cat is safe.

---

*An affectionate fan-made parody. It isn't affiliated with or endorsed by Tom
Cruise, the filmmakers, or any studio. All critics in the game are fictional.*
