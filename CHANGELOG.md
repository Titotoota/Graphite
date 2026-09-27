# Changelog

All notable changes to Graphite. Each version has a matching [GitHub release](https://github.com/Titotoota/Graphite/releases).

## v2.1.0

### New
- **Preset library**: ☰ → **Preset library** opens nearly 40 ready-made graphs to explore, grouped into Algebra, Trigonometry, Exponential and log, Conic sections, Calculus, Inequalities, Polar, Piecewise and Fun.
- **Save your own presets**: ☰ → **Save as preset…** (or ⋯ on any line) saves your graph to the library. Tick the lines you want to group together; any sliders they use are included automatically, along with the view and settings.
- **Share presets**: copy a preset as text or save it as a file, then use **Import…** in the library to add it on another device.
- **Select part of an expression**: double-tap to select one side of the = sign, or press and hold then drag (click and drag with a mouse; Shift + arrows or Ctrl/⌘ A on a keyboard). Pressing d/dx, √, |a|, ( ), ÷, powers or any function wraps the selection. For example, select x³ − 3x and press d/dx. Typing replaces the selection and delete removes it.
- **Resizable list on iPad, computers and phones in landscape**: drag the bar between the list and the graph left or right. Drag it all the way left to hide the list, and tap it to bring the list back.

### Changed
- More space at the top of the screen on iPhone and iPad, so buttons and expressions no longer sit under the clock, Wi-Fi and battery icons.
- The menu is reorganised: presets now sit below Display, the old tip is gone, and the version number is up to date.
- Keypad: the √ and ⁿ√ keys now draw the root with its roof, and the ✕ in the delete key is centred.

### Fixed
- Guide examples now show every line their **Add** button inserts. For example, the piecewise example shows both of its pieces, and examples that add sliders say so.

## v2.0.0

### New
- **Graphite icon**: the home-screen icon is now dark graphite grey and white, with the same graph, tangent line and point as before.
- **iPad and computer support**: side-by-side layout (list on the left, graph on the right), and a wider list panel on large monitors.
- **Phones in landscape**: the graph now sits beside the list with a more compact keypad. Before, it shrank to almost nothing when the keypad opened.
- **Keyboard on a computer**: start typing to create a new line, and use ↑ / ↓ to move between lines.
- **Mouse and trackpad**: scroll to zoom, a grab cursor when dragging the graph, and hover highlights on buttons.
- The version number is shown at the bottom of the ☰ menu.
- The guide explains how to install on iPhone, iPad, Android and computers.

### Fixed
- **Dashed edges on `<` and `>` inequalities**: dashes are now evenly spaced all the way along the curve. Before, they broke up into long gaps or solid runs on curves.
- **Curves near the y-axis disappearing when zoomed out**: functions like `ln(x)` and `log(x)` now plunge all the way down to the edge of the screen at any zoom, and `√x` and `∛x` meet the origin exactly.
- **Flickering reciprocal trig graphs when zoomed out**: `tan`, `sec`, `csc` and `cot` no longer draw random spikes that jump around as you zoom. Every asymptote line reaches the edge of the screen, and when the lines get too close together to tell apart, the curve becomes a steady see-through fill.
- Steep curves right next to an asymptote are no longer cut short.
- Zooming far out on a selected trig curve no longer covers the screen in grey intercept dots.

### Updating
Installed copies update the next time the app is opened (open it twice if you don't see the changes straight away). On iPhone and iPad, remove the app from the home screen and add it again to get the new icon.

## v1.0.0

- First release: a graphing calculator for algebra, trig and calculus that works offline and installs to the home screen.
- Functions, sideways graphs, circles and conics, polar graphs, points, inequalities with shading, piecewise functions and derivatives.
- Sliders with play/animate, tracing, intercepts, turning points, intersections and tangent lines.
- Examples, a built-in guide, radians/degrees, π axis labels, a unit circle, light/dark themes and image export.
