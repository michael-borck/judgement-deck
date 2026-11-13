# The Judgement Deck — Art Assets

**Style decision:** the deck's visual identity is the night masthead of the
course handouts — deep ink-navy with a single warm gold accent. All generated
art uses the locked **brass-lamp noir** identity. Every prompt starts with this
canonical prefix:

```
moody editorial noir photograph, deep ink-navy night palette, dramatic
chiaroscuro, a single warm gold glow as the only color accent, soft film
grain, elegant minimal composition, generous dark negative space
```

Every prompt ends with:

```
no text, no letters, no words
```

Card faces stay typographic by design; art lives on the box, the back, and
promotion only.

## Regenerating

```sh
limn generate -s 768x1024 -o assets/art/cover.png "<prefix>, <subject>, no text, no letters, no words"
```

Provider: the default SwarmUI (`juggernautXL_v9`). Each `.png.json` sidecar
records the exact prompt and parameters — regenerate any asset from its
sidecar.

## Files

| File | Use | Subject |
|---|---|---|
| `cover.png` | Box front, landing page hero, cut-card cover background if ever used | Brass desk lamp over a fan of index cards, magnifying glass, fountain pen |
| `back.png` | Deck back when printed double-sided (deck name overlaid at render time) | Ornate gold linework card back; central emblem is a balance scale and compass rose medallion |
| `banner.png` | Social preview (1280×640-safe), landing page banner, course slides | Wide desk scene with dark left third for a title overlay |

## Future: full art edition faces

If the boxed deck goes to print with illustrated faces, follow incident-zero's
discipline: a concept-keyed vignette library (five categories: judge, brief,
check, deliver, practise — plus per-card overrides), greyscale art tinted in
the category colour at render time, art only in the banner zone, and text
never shrinks to make room.
