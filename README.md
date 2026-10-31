# Purdue QCASE Lab website

Static site served by GitHub Pages at https://qcase-lab.github.io/ — no build step. Edit `index.html` directly.

## How publishing works

Every commit to the `main` branch is published automatically (Settings → Pages → Deploy from a branch → main, / (root)).

## Images to add

Put these files in place (JPG; square crops of about 400×400 px work best for people):

| File | What |
|---|---|
| `assets/img/qcase-logo.jpg` | Lab logo |
| `assets/img/areas.jpg` | Research-areas diagram |
| `assets/img/people/armin-moin.jpg` | Dr. Armin Moin |
| `assets/img/people/nazanin-siavash.jpg` | Nazanin Siavash |
| `assets/img/people/chinmayananda-ma.jpg` | Chinmayananda M A |
| `assets/img/people/laura-baird.jpg` | Laura Baird |
| `assets/img/people/aarav-bhatnagar.jpg` | Aarav Bhatnagar |
| `assets/img/people/hiba-naikwadi.jpg` | Hibatullah “Hiba” Naikwadi |
| `assets/img/people/carla-herdoiza.jpg` | Carla Herdoiza |
| `assets/img/people/andrew-weiland.jpg` | Andrew Weiland |

Anyone without a photo shows a gold-on-black initials circle. If the logo or diagram file is missing, that block is simply hidden.

## Adding a member

Copy one `<div class="person">…</div>` block in the Members section, change the name, role, dates,
initials (`data-initials`) and photo file name. To move someone to Alumni, delete their card and add
an `<div class="alum">` entry in the right Alumni group. Lab members can propose changes through pull requests.
