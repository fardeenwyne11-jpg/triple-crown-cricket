# ⚠️ This is build output — NOT the source

The `index.html` on this branch (`main`) is the **obfuscated, minified build** that serves
**whitewash.app**. It is generated, not hand-written — **do not edit it or treat it as source.**

## The real source of truth

- **Franchise game source → the private repo [`shahzainhtc-maker/whitewash-src`](https://github.com/shahzainhtc-maker/whitewash-src).**
  Clone that and work there; `npm run build` turns its `src/index.html` into the obfuscated file that lands here.
- **World Cup mode source → the [`worldcup`](https://github.com/whitewashcricket/whitewashcricket.github.io/tree/worldcup) branch of *this* repo** (readable; deployed to the locked beta `beta.whitewash.app`).
- Old name `fardeenwyne11-jpg/triple-crown-cricket` just **redirects** here.

## If you (or your Claude) intend to change game logic

**Stop and switch to `whitewash-src`** (or the `worldcup` branch for World Cup mode), and
`git pull` first. Editing this `main` branch directly means editing obfuscated build output —
your changes will be overwritten by the next build and you'll be working blind.
