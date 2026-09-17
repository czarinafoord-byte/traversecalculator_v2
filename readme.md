[readme.md](https://github.com/user-attachments/files/32344746/readme.md)
# Traverse Calculator v2

A browser based calculator for traverse coordinates, misclosure, error of closure, and area. It supports straight segments, circular curves, quick bearing adjustments, and a formatted PDF report.

## Bearing format

Enter azimuths using `D.MMSS` format.

Examples:

* `90` means 90 degrees, 0 minutes, 0 seconds
* `175.5800` means 175 degrees, 58 minutes, 0 seconds
* `265.58` means 265 degrees, 58 minutes, 0 seconds
* `358.3719` means 358 degrees, 37 minutes, 19 seconds

To adjust a bearing, select its entry field and use the shared Bearing Adjustment toolbar above the table. Choose `+180`, `-180`, `+90`, or `-90`, or enter another D.MMSS angle and select `+ Angle` or `- Angle`. Results wrap around the full 360 degree circle while preserving the minutes and seconds.

## Run locally

Open `index.html` in a web browser.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload all files from this project to the root of the repository.
3. Open the repository Settings page.
4. Select Pages under Code and automation.
5. Under Build and deployment, choose Deploy from a branch.
6. Select the `main` branch and the root folder, then save.

GitHub will display the published website address after deployment finishes.
