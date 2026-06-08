# tilde-town

Source for my [tilde.town](https://tilde.town) personal page — **~chumthewaters**.

- **Lives at:** https://tilde.town/~chumthewaters/
- **Theme:** *Jaws* / "chum the waters" 🦈 — looking up from the deep, in the tilde.town retro indie-web spirit.
- **Stack:** vanilla HTML + CSS (no frameworks, no build step) — tilde.town pages are hand-made and lightweight.
- **Files:** `index.html` + `style.css`. That's the whole reef.

## Deploy
tilde.town serves `~/public_html/index.html`. Push the page over SSH (requires a tilde.town
account + SSH access as `chumthewaters`):

```sh
# from this repo
scp index.html style.css chumthewaters@tilde.town:~/public_html/
# or keep it in sync:
rsync -av --exclude '.git' ./ chumthewaters@tilde.town:~/public_html/
```

> No tilde.town account yet? Apply at https://tilde.town/ (it's an invite/application pubnix).
