# Exterior Photo Orientation Index

This file defines the compass reference system to be used when indexing exterior photographs of the Berkeley Springs home.

## Calibrated primary orientation reference

Multiple compass readings were taken while facing the same house-to-deck orientation:

- 131°
- 128°
- 126°
- 129°
- 127°

The mean heading is **128.2°**. For indexing purposes, use:

- **128° SE** as the calibrated deck-facing axis
- Expected handheld compass variation from the observed readings: approximately **±3°**

The earlier 131° reading remains valid as one observation, but the multi-reading average is the better reference.

## Derived house-facing directions

Using **128°** as the calibrated deck-facing axis:

| House reference | Azimuth | Approx. cardinal direction |
|---|---:|---|
| Deck / rear-facing direction | **128°** | SE |
| Opposite / front-facing direction | **308°** | NW |
| Left side when standing inside facing the deck | **38°** | NE |
| Right side when standing inside facing the deck | **218°** | SW |

These are geometric 90°/180° offsets from the calibrated 128° deck-facing reference.

## 360° indexing convention

Exterior photos should be indexed by **camera viewing azimuth**, clockwise from north as reported by the phone compass:

- 000° / 360° = North
- 045° = Northeast
- 090° = East
- 135° = Southeast
- 180° = South
- 225° = Southwest
- 270° = West
- 315° = Northwest

Where exact headings are not available, photos may be grouped into approximate sectors using the house orientation above.

### Suggested sector labels

- **Deck / SE sector:** centered near 128°
- **Left / NE sector:** centered near 38°
- **Front / NW sector:** centered near 308°
- **Right / SW sector:** centered near 218°

## File-index format

For each exterior photograph, the eventual index should record:

| Field | Description |
|---|---|
| Filename | Repository image filename |
| Camera position | Approximate point around the house where the photographer stood |
| Camera azimuth | Direction the camera was facing, in degrees |
| Sector | NE / SE / SW / NW or more precise cardinal sector |
| House face shown | Front / deck / left / right / corner |
| Description | Visible features, work items, landscaping, tile, etc. |
| Notes | Any uncertainty or special context |

## Important distinction

The **128° calibrated measurement describes the direction from inside the house toward the deck**. It does not automatically give the camera heading of every exterior photograph. Individual photographs should be assigned azimuths from visible geometry, sequence around the house, EXIF heading data if present, or additional compass measurements.

## Reference evidence

Compass screenshots supplied on 2026-10-11 show the following deck-facing readings:

| Reading | Heading | Elevation shown |
|---|---:|---:|
| 1 | 131° SE | 730 ft |
| 2 | 128° SE | 730 ft |
| 3 | 126° SE | 750 ft |
| 4 | 129° SE | 750 ft |
| 5 | 127° SE | 740 ft |

All screenshots identify Berkeley Springs, WV. The small spread in headings is consistent with ordinary handheld compass variation and supports using **128° SE** as the working house orientation.
