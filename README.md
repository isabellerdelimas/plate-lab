# Plate Lab · Earth Builder

An independent plate tectonics game with 12 interactive missions, XP, stars, hints, and browser-local progress.

- `/`: the original free-play simulator, opening on editable My Crust controls.
- `/?game=1`: optional Earth Builder game.
- `/?lab=1`: free-play worksheet lab with crust controls, density probe, eight plate-boundary experiments, a 50 Myr timeline, and downloadable observation notes.
- `npm test`: simulator and game checks.
- `npm run build`: validate and package `dist/index.html` for Vercel.

Open `index.html` directly to use the simulator offline. No external libraries, accounts, or backend are required. Progress stays in the current browser. The geological models are simplified teaching illustrations, with references in the page footer.

This project is separate from Free Studies and has its own repository and deployment.

## Follow the worksheet

Choose a question or table row in **Follow your worksheet**:

- **Q8:** change My Crust temperature, composition, and thickness one at a time; restore the baseline between comparisons.
- **Q9:** move Zoom to the bottom, then drag the density dial through Earth's layers.
- **Tables A–C:** drag crust cards onto the left and right slots (or select a card and click a slot). Drag and hold a red handle inward, outward, or downward to converge, diverge, or transform. Boundary buttons and Play are also available.
- **Both** shows cross-section and top views. **New Crust** clears the plate choices; **Rewind** keeps them and resets time. Table B can stop automatically at 25 million years.

Record observations and the model's elapsed time in the notebook. These are results from this simplified model, not measurements from the original PhET simulator.
