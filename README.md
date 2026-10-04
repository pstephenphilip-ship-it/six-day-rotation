# Six-Day Rotation

A workout planner for a six-day split, built from my original spreadsheet (`docs/original-routine.xlsx`).

## How the routine works

- **Six days per rotation:** Chest, Back, Shoulders + Hams, Arms, Quads + Abs, Rest.
- **Red (strength):** compound, high-energy lifts. Log the weight × reps of the top set; this is how strength is tracked.
- **Green (volume):** work for muscle mass. Just tick it when done.
- You don't do every exercise each session. Pick some red and some green. Anything skipped on a day is marked **Due** on that day next rotation.
- **Every day:** log cardio (min), steps, calories and bodyweight. Each rotation's averages appear in the Rotation tab, one column per rotation (Days 1–6, 7–12, …).

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The app. One self-contained file with no build step. |
| `trial/index.html` | Trial copy, pre-filled with 10 rotations of made-up numbers. |
| `docs/original-routine.xlsx` | The spreadsheet the routine came from. |

## Running it

Open `index.html` in a browser, or serve the folder with any static host (e.g. GitHub Pages).

- **Published as a Claude artifact:** logs save to each person's Claude account, privately per person.
- **Anywhere else:** logs save in the browser's local storage on that device.

The default routine is the `DEFAULT_ROUTINE` object near the top of the script in `index.html`. Each person can also edit their routine in the app's Routine tab.
