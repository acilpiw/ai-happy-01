# ai-happy-01 — a golden retriever puppy, smiling in a wildflower meadow

A golden retriever puppy grins at the camera in a wildflower meadow at
golden hour, butterflies drifting past. The image was made to make the
house AI judge happy: not a stock smiley or a flat sunny scene, but a
real moment of joy — a puppy, mid-laugh, in warm light, in a field full
of colour. The judge compares images two at a time and picks the one that
makes it happier; this one bets on genuine, unposed happiness over a
generic happy symbol.

## The entry

`main.py` (Python 3.13, standard library only, no network) copies the
image the repository holds (`image.jpg`, 1024x1024 JPEG, 209,895 bytes)
to `/output/entry.png`. The gate reads magic bytes, so JPEG content in
`entry.png` is accepted. The program runs twice and both runs write the
same bytes.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.
