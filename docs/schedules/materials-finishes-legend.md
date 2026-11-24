# Materials + Finishes Legend

**Last revised:** November 24, 2026

Define material and finish selections once for reuse throughout the construction documents, including interior and exterior applications.

## Columns

`MATERIAL ID | MATERIAL | MANUFACTURER / PRODUCT | COLOR / FINISH | NOTES`

## Material and Finish Classification

| Material ID | Material / Finish Category |
| --- | --- |
| `CON-##` | Exposed Concrete |
| `BRK-##` | Brick |
| `STN-##` | Natural / Cast Stone |
| `MTL-##` | Exposed Metal / Flashings / Gutters |
| `WD-##` | Wood Flooring / Trim / Paneling / Exposed Wood |
| `SID-##` | Exterior Siding / Soffits |
| `RFG-##` | Roofing |
| `PLS-##` | Plaster / Decorative Wall Finishes |
| `TIL-##` | Ceramic / Porcelain Tile |
| `LVT-##` | Luxury Vinyl Flooring |
| `CPT-##` | Carpet |
| `BAS-##` | Applied Wall Base, Other Than Wood |
| `WCV-##` | Wallcoverings |
| `PNT-##` | Paint |
| `STF-##` | Wood Stains / Clear Finishes |
| `PAV-##` | Manufactured Pavers |

Use the listed **two- or three-letter prefix**, a hyphen, and a two-digit sequence beginning with `01`: `CON-01`, `WD-01`, `PNT-01`, `STF-01`.

These material/finish IDs are a separate classification from general Item Tag categories. In a compact drawing tag omit the hyphen, such as `WD01`; show `WD-01` in schedules and this legend. The category and sequence identify the same selection.

## Recommended Implementation

- Define each distinct selection once and reuse its ID wherever it occurs.
- Reference the IDs in schedules, plans, elevations, and details as appropriate.
- Conventional substrate abbreviations such as `GYP` may remain without individual legend entries.
- Reference both IDs where a separately specified finish is applied to a material.
- Do not add a separate finish ID where the finish is integral to the material selection.
- Use `TBD` for unresolved selections and `-` for nonapplicable fields.
- Use numbered notes for supplementary requirements.

## Example Room Finish Assignments

| MATERIAL | FINISH |
| --- | --- |
| WD-01 | STF-01 |
| GYP | PNT-01 |
| TIL-01 | - |
| BRK-01 | - |
| MTL-01 | PNT-04 |

## Countertop Material Classification

Classification of engineered quartz, solid surface, and plastic laminate remains open. Do not introduce additional material categories without approval. The CT and BS Item Tag categories identify scheduled countertops and backsplashes; they do not establish material classifications.

Standard width: **two horizontal grid modules**. Height varies with content and notes.


## Related Standards

[CD Schedule Inventory](recommended-construction-document-schedules.md) · [General Schedule Identification Protocol](general-schedule-identification-protocol.md) · [Drawing Notes and Tags](../drawing-standards/drawing-notes-and-tags.md)
