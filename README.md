# The Center and Noah's Quest

## Noah's Quest (`quest/index.html`)

A 2-minute anime-style film for Noah: a sketchbook intro, then five game levels (Created, The Squad, Game Day, The Boss, The Mission) and a sing-along finale. The score opens with an epic build and drops into a 128 BPM groove, with a minor-key boss battle. Everything is drawn with Canvas 2D and synthesized with Web Audio.

Style and music samples live in `samples/index.html`.

## The Center (`index.html`)

A 58-second hand-drawn animation about the purpose of life, with Jesus at the center, made for Michael, his wife Kristina, and their son Noah.

It is one file of plain JavaScript (`index.html`): Canvas 2D draws the pictures and Web Audio plays the music. No libraries and no image or audio files.

## Watch it

Open `index.html` in a browser and press **Begin, sound on**.

- Space: play or pause
- Left and right arrows: skip 5 seconds
- R: restart
- **Save video** plays the film once and downloads it as a `.webm` file with sound (desktop Chrome, Edge, or Firefox).

## Personalize

Add URL parameters to change the names:

```
index.html?son=Noah
index.html?dad=Michael&wife=Kristina&son=Noah
index.html?t=28        (start at 28 seconds)
```

## Scenes

| Time | Scene | Verse |
|---|---|---|
| 0:00 | Why are we here? | |
| 0:06 | Creation | Genesis 1:1, Psalm 139:14 |
| 0:13 | The family, hand in hand | Matthew 22:37-39 |
| 0:20 | Noah's ark and a boy named Noah | Genesis 6:9 |
| 0:28 | The cross, then every part of life around it | John 3:16, Colossians 1:17 |
| 0:40 | Backyard football with Dad, Mom cheering | Joshua 1:9 |
| 0:49 | The family walks toward the cross at sunrise | Joshua 24:15 |

## Music

"Amazing Grace" (public domain), synthesized in the browser as a soft piano with pads, bells and reverb. The melody's second half lifts right as the cross appears.

## How the hand-drawn look works

- Every line is a wobbly pencil stroke that re-jitters 8 times a second ("line boil"), the way hand-drawn animation shimmers.
- Strokes draw themselves progressively, with a pencil following the tip.
- Colors are layered watercolor washes on a generated paper texture.
