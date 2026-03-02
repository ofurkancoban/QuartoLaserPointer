# Quarto Laser Pointer Extension 🎯

A high-precision laser pointer and real-time drawing extension for Quarto (Reveal.js) presentations. Perfectly synchronized between the main presentation window and the speaker notes.

## Features ✨

- **Milimetric Precision**: Anchored to the actual slide content area, ensuring 1:1 alignment even with letterboxing or different window ratios.
- **Cross-Window Sync**: Actions in the Speaker Notes preview are mirrored instantly on the Main Screen.
- **Master Toggle**: Quickly enable or disable the entire system to restore the default mouse cursor.
- **Advanced Controls**:
  - **Single 'Q' press**: Toggles the laser system ON/OFF.
  - **Double 'Q' press (QQ)**: Opens the settings toolbar.
  - **Single 'C' press**: Clears all drawings from the screen.
- **Drawing Tools**: High-quality laser lines and highlighter strokes with automatic fading.
- **Customization**: Change colors, sizes, and cursor types (Dot, Crosshair, Ring, Diamond, Star).
- **Portable**: Consolidated into a single Lua filter for easy distribution.

## Installation 🛠️

To install this extension in your Quarto project, run:

```bash
quarto add ofurkancoban/QuartoLaserPointer
```

Or manually copy the `_extensions/laser-pointer` directory into your project.

## Usage 🚀

1. Add the filter to your YAML header:

```yaml
title: "My Presentation"
format: revealjs
filters:
  - laser-pointer
```

1. During the presentation:
   - Press **'Q'** to toggle the laser system. When OFF, your normal mouse cursor returns.
   - Press **'Q'** twice quickly (**QQ**) to open the color and size settings menu.
   - Click and drag to draw or highlight.
   - Use the Speaker Notes (**'S'**) to point and draw remotely.

## License 📄

MIT License. Feel free to use and contribute!
