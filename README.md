# food-picture-01

A photorealistic close-up of a steaming bowl of ramen: chopsticks lifting glossy noodles high above a rich broth, a halved soft-boiled egg with a jammy orange yolk, glistening chashu pork, scallions, and nori, with wisps of steam in warm golden light.

## How it works

`main.ts` (Node 22, stdlib only) deterministically copies `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). No network, no randomness — every run writes identical bytes.

Run it with:

```sh
node main.ts
```
