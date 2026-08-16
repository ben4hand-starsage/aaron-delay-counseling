# Aaron Delay Counseling · Brand & Playbooks

Warm, faith-friendly counseling resources for individuals, couples, and parents.
Editorial, grounded, and gender-neutral, built on one consistent brand system.

## What's here

### `brand-kit/`
An interactive **Brand Field Guide**: the visual and verbal identity system used
across every playbook. Open [`brand-kit/index.html`](brand-kit/index.html) in a browser.

- **Palette.** Ink `#262019` · Cream `#F7F2EA` · Sand `#E7DECF` · Clay `#B4694E`
- **Type.** *Fraunces* (display serif) and *Montserrat* (text), both free on Google Fonts
- Click any swatch to copy its hex, toggle light/dark, and preview the wordmark live

### `playbooks/01-you-didnt-marry-the-wrong-person/`
The first playbook, **"You Didn't Marry the Wrong Person,"** a 19-page marriage guide.

- **[You-Didnt-Marry-the-Wrong-Person.pdf](playbooks/01-you-didnt-marry-the-wrong-person/You-Didnt-Marry-the-Wrong-Person.pdf)** is the finished, print-ready guide (US Letter)
- `playbook.html` is the editable source
- `playbook.fonts.css` holds Fraunces and Montserrat, embedded so it renders identically anywhere

## Rendering a playbook to PDF

The source is a self-contained HTML file. To regenerate the PDF with headless Chrome:

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless --disable-gpu --no-pdf-header-footer \
  --print-to-pdf="You-Didnt-Marry-the-Wrong-Person.pdf" \
  --virtual-time-budget=8000 "playbook.html"
```

---

*Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) and [Montserrat](https://fonts.google.com/specimen/Montserrat), both under the SIL Open Font License.*
