# Software Crafters - Montreal

Repository for the GitHub Pages site for the Montreal chapter of the Software Crafters community.

Check out https://rangzen.github.io/software-crafters-montreal/ for the rendered site.

## Preparation

### Resize

```shell
for i in *.jpg; do convert "$i" -resize 20% "${i%.*}.jpg"; done
```

### Tag

```shell
for i in *.jpg; do convert "$i" -fill white -pointsize 32 -annotate +50+50 "Software Crafters - Montreal - 2024" "${i%.*}.jpg"; done
```

### Arrows

Annotate with Ksnip.
