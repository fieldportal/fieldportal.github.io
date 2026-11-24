# Field Portal short links

These pages only forward people to the Field Portal (a Google Apps Script web app).

- `/`     → the portal (people choose their survey)
- `/lfs`  → the portal with the Labour Force Survey already chosen

**If the portal ever moves:** edit the long Google link in `index.html` and in each survey folder (`lfs/index.html`). Every short link people already have keeps working.

**To add a survey:** copy the `lfs` folder, rename it (for example `eicv`), and change `?s=LFS` to the new survey's ID.
