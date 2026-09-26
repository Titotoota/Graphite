# Changelog

All notable changes to Graphite. Each version has a matching [GitHub release](https://github.com/Titotoota/Graphite/releases).

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
