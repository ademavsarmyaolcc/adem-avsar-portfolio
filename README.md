# Grace Hopper Dedication Page

A responsive single-page dedication site honoring **Grace Murray Hopper** (1906–1992), a pioneering computer scientist, teacher, and U.S. Navy rear admiral.

## What the page includes

The site follows the final requirements shown in the project walkthrough video:

- A navy-blue, professional science-and-service visual theme
- A sticky top navigation bar linking to each page section
- An introduction with Grace Hopper's portrait and a short biography
- Detailed sections for **Impact**, **Early Life & Education**, **Career & Code**, **Retirement**, **Post-retirement**, and **News**
- Informational `.info-tile` components with borders, padding, margins, and box shadows
- A U.S. flag background with a dark overlay for readable hero text
- Responsive side-by-side layouts that collapse cleanly on smaller screens
- A News section containing an embedded 1982 Grace Hopper lecture from YouTube
- Arial/Helvetica typography and accessible image alt text, labels, and link behavior

## Run locally

No build tools are required. From the project folder, start a local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/index.html` in a browser.

## Project structure

```text
index.html                    Main single-page website
stylesheet/portfolio.css      Responsive layout and visual styles
images/grace-hopper.jpg       Public-domain U.S. Navy portrait
images/us-flag.png            Wikimedia Commons U.S. flag background
experiment-notes.md           Notes from the requested HTML/CSS line-removal experiments
```

## Sources and credits

Biographical details were cross-checked against institutional references including [Yale's biography of Grace Murray Hopper](https://president.yale.edu/biography-grace-murray-hopper), the [U.S. Naval History and Heritage Command](https://www.history.navy.mil/news-and-events/news/2026/code-commission-character-grace-hopper.html), and [Vassar's Grace Hopper biography](https://www.vassar.edu/grace-hopper/life).

The portrait is the high-resolution official U.S. Navy image [Commodore Grace M. Hopper, USN (covered)](https://commons.wikimedia.org/wiki/File:Commodore_Grace_M._Hopper,_USN_(covered).jpg), hosted by Wikimedia Commons and marked public domain in the United States. It is selected to keep Grace Hopper’s full uniform and portrait framing visible. The flag background is based on the [Wikimedia Commons Flag of the United States SVG](https://commons.wikimedia.org/wiki/File:Flag_of_the_United_States.svg).

The News embed links to [Captain Grace Hopper in 1982 on the Future of Computers](https://www.youtube.com/watch?v=ZCkswdK-3Lc).

## Author

Prepared for **Adem Avşar** as a Grace Hopper dedication page project.
