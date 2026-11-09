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
| Sprint | Shift (or just keep running: *Full Throttle* kicks in) | automatic |
| Pause / Mute | P or Esc / M | |

## The Digger Boot

- **Boot Stomp:** hold Down in mid-air to come down heel-first on critics' heads
  and on dirt blocks, bouncing off them. Chain three for "YEEHAW!",
  five for "DIGG. OR DIE!"
- **THE DIGGER BOOT:** dig dirt, grab oil and gold, beat critics and land hits
  on the boss to fill the boot meter (top-left). Press **C** and a giant
  gold-stitched cowboy boot with a spinning spur falls from the sky and stomps
  every critic on screen. It takes a big chunk out of the boss and leaves him dizzy.

## The critics

- **Critic** (beret, notepad): patrols, yells "C MINUS!", "NO SUBSTANCE!",
  "SELF-INDULGENT!", and throws C- grade cards.
- **Blogger** (propeller cap, laptop): hovers and posts "#DIGGERFAIL". Perfect
  for stomp chains.
- **Rotten Critic** (trench coat): lobs rotten tomatoes from ledges.
- **Mortimer Snobb, Critic-in-Chief** (boss): charges with a giant red grading
  pen, belly-flops out ink shockwaves, and throws tomatoes and grade cards.
  At half health he declares "I'M GIVING IT A D!" Bait his charge into a wall
  (or the platforms), then dig in while he's dizzy.

Beaten critics have a change of heart ("TRANSFORMATIVE!", "AWARDS SEASON!").
Clapperboards are checkpoints. Dying yells "CUT!" and costs 20% of the box office.

## The story: three games in one

### Chapter 1: the platformer
1. The red carpet
2. The pit of bloggers
3. The dirt wall
4. The pencil pit: stepping-stone platforms get you across safely. The
   bloggers hovering low in the gaps are optional bounces (and a safety net),
   never required.
5. The premiere: boss fight with Mortimer Snobb

All set against a sunset of searchlights, the HOLLYDIG sign and nodding oil
pumpjacks. Beat the boss and the **100% FRESH** success screen rolls...
until static and an alarm cut in: **WE INTERRUPT THIS PROGRAM.**

### Chapter 2: the visual novel
Breaking news: data centers all over the planet are overheating, and the left
half of Europe is gone. In a crisis lab, Dr. Frost explains it to Tom Cruise
and Iñárritu. The marketing game was made with AI, and Tom kept asking for
"one more take": **4,200,000 versions**, each one spinning up more GPUs. The
request log scrolls on the wall, Tom flashes his famous smile ("Well... at
least the game is perfect"), and a certain tech CEO calls in to say one more
iteration will fix it, if he can just get a few more gigawatts.
Press **Z / Enter** (or tap) to advance.

### Chapter 3: Mission: Implausible
*Your mission, should you choose to accept it: pull the plug.* Tom, in his
long-haired, sunglasses-wearing cliff-climbing look from the opening of
*Mission: Impossible 2*, and Iñárritu break into the data center to face
**Sam Altman** and his GPU server racks in a turn-based battle, to an original
5/4 spy-thriller theme.

| Tom | Iñárritu |
| --- | --- |
| **Free Solo:** climb it with no rope, drop on it | **Long Take:** four hits on random foes |
| **Cable Drop:** drop from the ceiling on a wire and pull every plug (hits all, double vs. servers) | **CUT!:** a foe loses its next turn (cancels a charging gigawatt) |
| **Self-Destruct:** exploding sunglasses, with a countdown | **Catering:** heals the whole crew |

Items: **Iced Coffee** (+50 HP, revives) and **Solar Cell** (+20 SP).
Servers shield Sam (half damage), so pull their plugs first. When Sam starts
"scaling up", defend or yell CUT! Menus: arrows to choose, **Z/Enter** to
confirm, **X/Esc** to go back (touch: ◀ ▶ ▼, JUMP = OK, DIG = back).

Win, and Sam agrees to renewables and *no more iterations* ("Not even... one
more?"). The Alps refreeze, the cat is fine, and Iñárritu calls it: "Print it.
First take."

---

*An affectionate fan-made satire. It isn't affiliated with or endorsed by Tom
Cruise, Alejandro G. Iñárritu, Sam Altman, OpenAI, the filmmakers, or any
studio. Their appearances are caricatures, the dialogue is invented, and all
critics, scientists and events in the game are fictional. The battle music is
an original composition.*
