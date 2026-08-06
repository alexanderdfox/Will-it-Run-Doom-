# 10x10 and 12x12 Overlapping Centered 3D Lissajous Matrix with Live Audio

An interactive, browser-based audiovisual application featuring overlapping 10x10 and 12x12 matrices generating 3D Lissajous curves and real-time synthesized audio via the Web Audio API.

---

## Features

* **3D Lissajous Matrices**: Dual overlapping grids (10x10 and 12x12) rendering real-time miniature oscilloscope visualizers.
* **Flow Physics Modes**: Switch between **Laminar**, **Oscillating**, **Turbulent**, and **All Combined** motion profiles.
* **Live Audio Synthesis**: Generates polyphonic audio responding dynamically to spatial movements and wave frequencies.
* **Customization & Randomization**:
* Randomize spatial layouts, sound frequencies, and node colors with dedicated controls.
* Assign a random color to all nodes using the **Randomize Colors** button.
* Pick custom colors for individual grids.


* **Data Import/Export**: Export and import graphics layouts, sound frequencies, and node colors via CSV, as well as export real-time audio to a 3D WAV file.
* **HUD Toggle**: Hide or show the control interface on demand using the `[H]` key or the floating toggle button.

---

## How to Use

1. **Launch the Application**:
* Save the code into an HTML file (e.g., `index.html`) and open it in any modern web browser.


2. **Acknowledge Warning**:
* Read the epilepsy warning on startup and click **I Understand, Enter** to access the main interface.


3. **Start the System**:
* Click the **Start System** button to initialize the audio context and begin the real-time visual animation.


4. **Interact and Customize**:
* **Flow Modes**: Use the top control bar buttons (`Laminar`, `Oscillating`, `Turbulent`, `All Combined`) to alter matrix motion behavior.
* **Randomization**: Click **Randomize Data** to scramble spatial positioning and audio frequencies, or click **Randomize Colors** to assign a unique random color palette across all blocks.
* **Color Customization**: Use the color pickers (`Grid 1 Color` / `Grid 2 Color`) to style the visualizer grids.


5. **Export & Import Data**:
* Export or load your custom configurations using the CSV Export/Import tools for graphics, sound, and colors.
* Use **Export 3D WAV** to render and download a synthesized audio file of the current session.


6. **Toggle HUD**:
* Press the `H` key on your keyboard or click the **Hide HUD / Show HUD** button in the top right corner to clear the interface for an unobstructed view.
