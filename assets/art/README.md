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
| `cover.png` | Box front, landing page hero, art-edition cover card | Brass desk lamp over a fan of index cards, magnifying glass, fountain pen |
| `back.png` | Deck back when printed double-sided (deck name overlaid at render time) | Ornate gold linework card back; central emblem is a balance scale and compass rose medallion |
| `banner.png` | Social preview (1280×640-safe), landing page banner, course slides | Wide desk scene with dark left third for a title overlay |

## ill/ — the concept-keyed vignette library

Five landscape vignettes, one per category, keyed by concept (not by card).
The art edition (`deck/judgement-deck-50-art.html`) places the category
vignette as a banner on every card face and duotone-tints it in the category
colour at render time (CSS hue-rotate from a sepia base): gold Judge,
teal Brief, coral Check, blue Deliver, green Practise — category = subject,
colour = tint. The tint keeps the deck readable as five families at a glance.

| File | Category | Subject |
|---|---|---|
| `judge.png` | Judge | Magnifying glass held over a single index card |
| `brief.png` | Brief | Fountain pen on a freshly written card, ink still wet |
| `check.png` | Check | Brass pocket watch held over a table of figures |
| `deliver.png` | Deliver | Finished cards in an outbox tray, top card lifted into the light |
| `practise.png` | Practise | Worn rubber-banded deck on a shelf beside a closed notebook |

Regenerate with the canonical prefix + subject + `no text, no letters, no
words`, at `1344x768`.

## Future: full art edition faces

If the boxed deck goes to print with illustrated faces, follow incident-zero's
discipline: a concept-keyed vignette library (five categories: judge, brief,
check, deliver, practise — plus per-card overrides), greyscale art tinted in
the category colour at render time, art only in the banner zone, and text
never shrinks to make room.
