# Character artwork

Bird reuses `../birds.png` (two 887 × 887 frames). All other sprites were created
with the built-in image_gen tool, using Bird as the style reference. The original
transparent PNGs are preserved at 1254 × 1254 pixels. Artwork and accessory
composition remain at native source resolution.

Fury uses an original black, green-eyed arcade dragon design. Its Light skin is a dedicated pearl-white/ice-blue recolor with dark outlines and a blue eye, using the same pose and accessory anchors.

| Character | Source | Final generation prompt |
| --- | --- | --- |
| Owl | [owl.png](owl.png) | [owl.prompt.txt](owl.prompt.txt) |
| Duck | [duck.png](duck.png) | [duck.prompt.txt](duck.prompt.txt) |
| Penguin | [penguin.png](penguin.png) | [penguin.prompt.txt](penguin.prompt.txt) |
| Fish | [fish.png](fish.png) | [fish.prompt.txt](fish.prompt.txt) |
| Squid | [squid.png](squid.png) | [squid.prompt.txt](squid.prompt.txt) |
| Turtle | [turtle.png](turtle.png) | [turtle.prompt.txt](turtle.prompt.txt) |
| Starfish | [starfish.png](starfish.png) | [starfish.prompt.txt](starfish.prompt.txt) |
| Bee | [bee.png](bee.png) | [bee.prompt.txt](bee.prompt.txt) |
| Beetle | [beetle.png](beetle.png) | [beetle.prompt.txt](beetle.prompt.txt) |
| Butterfly | [butterfly.png](butterfly.png) | [butterfly.prompt.txt](butterfly.prompt.txt) |
| Lobster | [lobster.png](lobster.png) | [lobster.prompt.txt](lobster.prompt.txt) |
| Lion (Chimera) | [chimera.png](chimera.png) | [chimera.prompt.txt](chimera.prompt.txt) |
| Unicorn | [unicorn.png](unicorn.png) | [unicorn.prompt.txt](unicorn.prompt.txt) |
| Ninetails | [ninetails.png](ninetails.png) | [ninetails.prompt.txt](ninetails.prompt.txt) |
| Phoenix | [phoenix.png](phoenix.png) | [phoenix.prompt.txt](phoenix.prompt.txt) |
| Dragon | [dragon.png](dragon.png) | [dragon.prompt.txt](dragon.prompt.txt) |
| Wyvern | [wyvern.png](wyvern.png) | [wyvern.prompt.txt](wyvern.prompt.txt) |
| Fury | [night-fury.png](night-fury.png) | [night-fury.prompt.txt](night-fury.prompt.txt) |
| Fury — Light skin | [fury-light.png](fury-light.png) | [fury-light.prompt.txt](fury-light.prompt.txt) |
| Shenlong | [chinese-dragon.png](chinese-dragon.png) | [chinese-dragon.prompt.txt](chinese-dragon.prompt.txt) |

`../../../src/characters.ts` defines roster order, framing, recolors, texture masks,
and accessory attachment points in a shared 1000-unit art space. Base sprites face
right; P2 is mirrored. Arena, HUD, selection portraits and accessory previews use
the same appearance composer.
