# DIGGER: DIGG. OR DIE. (Tom Cruise vs. The Critics)

A retro shovel-platformer parody of the movie *Digger*. Tom Cruise is **Digger**:
silver swept-back hair, a burgundy western suit with suede yokes, a turquoise bolo
tie, a gold belt buckle, cowboy boots and a trusty D-handle spade. The critics
who panned the movie are lining up to call it "ALL STYLE, NO SUBSTANCE", and
Digger is going to dig, stomp and boot his way through every one of them.

Everything (pixel art, sound effects, chiptune music) is generated in code, so
`index.html` is the whole game. There's no build step and no dependencies.

The soundtrack is generative. Each scene has its own original track: the
platformer, the boss, the victory fanfare, breaking news, the lab, the smile,
the Agency corridors, a 5/4 spy theme for the fights, the chase, the cliff
jump and the ice ring. Every track is built from sections (intro,
verse, chorus, bridge, breakdown) with their own chords, bass lines and drum
patterns. Melodies grow from a motif that mutates each time a section returns,
phrases end in drum fills, the boss and battle music intensify when things get
dangerous, and each playthrough uses a fresh random seed. Tested over 5 minutes
per track, none of them ever repeats exactly.

## Play

Open `index.html` in any modern browser. To serve it locally instead:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Controls

| Action | Keyboard | Phone / tablet |
| --- | --- | --- |
| Move | Arrow keys / A, D | Roll your thumb on the round D-pad |
| Jump (hold for higher) | Z / Space / Up / W | JUMP (big gold button) |
| Spade swing / dig | X / K | DIG |
| **Boot Stomp** (pogo) | Hold Down while in the air | Thumb down on the D-pad |
| **THE DIGGER BOOT** (super) | C / L when the boot meter is full | BOOT (glows when ready) |
| Sprint | Shift (or just keep running: *Full Throttle* kicks in) | automatic |
| Pause / Mute | P or Esc / M | |

**Story scenes:** Z / Enter, or tap anywhere.

**Agency corridors:** move, Z to jump, X to shoot (touch: D-pad, JUMP, FIRE).
**Chase:** left/right to steer, or let go and the autopilot drives.
**Ice-ring puzzle:** arrows to pick a tile, Z to rotate, or just tap/click a tile.

**Turn-based battle:** it has its own controls. Arrow keys to choose, Z / Enter
to confirm, X / Esc to go back. On a phone the controls switch to ▲ ▼ BACK OK,
and you can also tap a menu item or an enemy directly (the mouse works for this too).

The touch controls track each finger separately, so you can hold a direction and
jump at the same time, and sliding off a button doesn't drop the input. In
portrait the game sits above the controls. In landscape the controls sit in the
side margins.

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

## The story (spoilers)

**The platformer.** The red carpet, the pit of bloggers, the dirt wall, the
pencil pit (stepping-stone platforms get you across safely; the bloggers
hovering low in the gaps are optional bounces and a safety net), and the
premiere boss fight with Mortimer Snobb. The **100% FRESH** score screen starts
typing itself out... and gets cut off mid-word by static and an alarm:
**WE INTERRUPT THIS PROGRAM.**

**The visual novel.** In a crisis lab, Dr. Frost explains to Tom Cruise (off
duty, in a plain grey tee) and Alejandro G. Iñárritu that the marketing game
was made with AI, and Tom gave **4,200,000 notes** ("AGAIN, BUT FASTER"). Each
one spun up more GPUs. Half of Europe is gone ("Which half?" "The left one.").
Alejandro admires the light on the burning map. Tom smiles exactly once in the
whole game. A certain tech CEO calls in, pleading for a few more gigawatts.
"Did you say... impossible?" Tom produces a black coat and sunglasses from
somewhere, and Ethan Hunt is in the building.

**The Agency.** *Your mission, should you choose to accept it: pull the plug.*
Tom, in his long-haired, sunglasses-wearing cliff-climbing look from the
opening of *Mission: Impossible 2*, sneaks down blinding-white vault corridors.
Jump the laser tripwires, and wait for the security cameras to look away
(their light turns green) before you cross. Alejandro follows with his camera.
Only Tom shoots: hit a data center and the turn-based combat begins.

| Tom | Alejandro |
| --- | --- |
| **Free Solo:** climb it with no rope, drop on it | **Long Take:** four hits on random foes |
| **Cable Drop:** drop from the ceiling on a wire and pull every plug (hits all, double vs. servers) | **CUT!:** a foe loses its next turn (cancels an overclock) |
| **Self-Destruct:** exploding sunglasses, with a countdown | **Catering:** heals the whole crew |

Items: **Iced Coffee** (+50 HP, revives) and **Solar Cell** (+20 SP). Data
center A is two server racks. Data center B adds a GPU cluster that overclocks
every third turn: defend, or yell CUT! Take both down and there's a motorcycle.

**The chase.** Top-down pursuit of Sam's van as he throws sticks of RAM at you
("HAVE SOME DDR5!"). Steer whenever you like. Let go and the autopilot drives
(and dodges) for you. It ends with both vehicles flying off a cliff and two
parachutes gliding down to a ring of ice.

**The ice ring.** Tom and Sam brawl on an ice ring that melts as the clock
runs. You're at the data center's terminal: rotate the tiles to route power to
the shutdown switch. The deal is simple: shut the
data center down and Tom and Sam both survive; leave it running and the ice
takes them both. The AI knows that, so it talks past Tom, straight to you, the
player: calm, a little too friendly, selling you on getting rid of Sam ("No more
keynotes. No more 'one more model'. Think about it.") while trying not to
mention that Tom goes with him. Behind it all, a drifting wall of Tom
Cruise's movies reminds you what you'd lose.

Whatever happens, the game cuts out: **THANKS FOR PLAYING THE DEMO. BUY THE
FULL VERSION ON STEAM.** Then a store page opens, with screenshots from your own
playthrough, reviews and an Add to Cart button. It's a parody page ("STEEM").
Nothing can actually be bought.

Every playable part is short: roughly half a minute of sneaking, two quick
fights, a 35-second chase and a 45-second puzzle.

---

*An affectionate fan-made satire. It isn't affiliated with or endorsed by Tom
Cruise, Alejandro G. Iñárritu, Sam Altman, OpenAI, the makers of *Digger* or
*Mission: Impossible*, Valve/Steam, or any studio. The movie titles on the wall
are just titles; the covers are original drawings. Their appearances are caricatures, the dialogue is invented, and all
critics, scientists and events in the game are fictional. The battle music is
an original composition.*
