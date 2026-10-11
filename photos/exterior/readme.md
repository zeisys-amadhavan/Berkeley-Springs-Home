# Exterior Photo Orientation Index

This file defines the compass reference system to be used when indexing exterior photographs of the Berkeley Springs home.

## Primary orientation reference

When standing **inside the house and facing outward toward the deck**, the measured compass heading is:

- **131°**
- Cardinal direction: **SE (southeast)**

This heading is the primary reference axis for all exterior-photo orientation metadata.

## Derived house-facing directions

Using 131° as the deck-facing axis:

| House reference | Azimuth | Approx. cardinal direction |
|---|---:|---|
| Deck / rear-facing direction | **131°** | SE |
| Opposite / front-facing direction | **311°** | NW |
| Left side when standing inside facing the deck | **41°** | NE |
| Right side when standing inside facing the deck | **221°** | SW |

These are geometric 90°/180° offsets from the measured 131° deck-facing reference.

## 360° indexing convention

Exterior photos should be indexed by **camera viewing azimuth**, clockwise from true/magnetic north as reported by the phone compass:

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

- **Deck / SE sector:** centered near 131°
- **Left / NE sector:** centered near 41°
- **Front / NW sector:** centered near 311°
- **Right / SW sector:** centered near 221°

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

The **131° measurement describes the direction from inside the house toward the deck**. It does not automatically give the camera heading of every exterior photograph. Individual photographs should be assigned azimuths from their visible geometry, sequence around the house, EXIF heading data if present, or additional compass measurements.

## Reference evidence

The source compass screenshot supplied on 2026-10-11 shows:

- Heading: **131° SE**
- Location label: Berkeley Springs, WV
- Elevation displayed: 730 ft

The compass screenshot itself is conversation evidence and should be retained separately if later committed to the repository.
