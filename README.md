# portfolio
# Ekaterina Selivanova

Personal portfolio of Ekaterina Selivanova, Senior Product Designer based in Berlin. The site presents selected case studies, work experience, a resume and contact details.

## Selected work

- **From Browsing to AI-Guided Shopping** (Telefónica Deutschland, password protected)
- **Connecting Loyalty & Commerce** (KaDeWe Group)
- **Redesigning the Document Editing Experience** (Xara)
- **Making Gamification Work for Finance** (TWINT Spin & Win)
- **Simplifying Complex Campaign Management** (TWINT admin tool)

## Project structure

```
index.html          the whole website (HTML, CSS and JavaScript in one file)
resume.html         resume page in English and German, linked from the About section
resume-en.pdf       resume download (English)
resume-de.pdf       resume download (German)
o2-prototype.html   interactive prototype opened from the O2 case study (Testing & Validation)
media/              images and videos used by the site
```

The site is a static page. Case studies open on the same page and have their own addresses, for example `index.html#twint-spin-win`. No build step or server is needed.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a browser.

Keep the `media` folder, `resume.html`, the PDFs and `o2-prototype.html` next to `index.html`, otherwise images, videos and links will not work.

## Publish with GitHub Pages

1. Push all files and the `media` folder to the root of a GitHub repository.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then save.
4. The site will be available at `https://<username>.github.io/<repository>/`.

## Notes

- Fonts (Bricolage Grotesque and Instrument Sans) are loaded from Google Fonts, so an internet connection is needed to see them. Without it the site falls back to a standard system font.
- One case study is password protected. Its content is encrypted inside `index.html`. Contact me for access.
- The O2 prototype (`o2-prototype.html`) is a separate file that is not password protected. Anyone with the address can open it, so remove it from the repository if it should stay private.
- The prototype loads its font from Telefónica's server and is in German.
- The site is responsive and works on desktop, tablet and phone.

## Contact

- Email: selivanova.uxui@gmail.com
- LinkedIn: https://www.linkedin.com/in/ekaterina-selivanova-31a40315a/
- Location: Berlin, Germany

## Copyright

© 2026 Ekaterina Selivanova. All rights reserved. The case study content, images and videos may not be copied or reused without permission. Product and company names belong to their respective owners.
