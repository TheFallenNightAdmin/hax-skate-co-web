# HAX Skate Co.
Static site, no build step. Pages: index, boards, story, out-there, newsletter.
- **Vercel:** import the repo. `vercel.json` enables clean URLs (/boards).
- **GitHub Pages:** links use /boards, so change them to `boards.html` etc. or use Vercel.
- **Images:** dashed boxes are blank image slots. Put files in `images/` and add `<img src="images/hero.png" alt="...">` inside the slot `div` (see the comment in each one). The box shape stays and the dashed border/label disappear.
- Colors are variables at the top of `styles.css` (`--ink`, `--plate`, `--v` purple, `--red`).
- Newsletter form is a placeholder; connect an email service in `newsletter.html`.
