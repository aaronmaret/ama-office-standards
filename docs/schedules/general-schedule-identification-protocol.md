# General Schedule Identification Protocol

**Last revised:** November 24, 2026

## Drawing Tags and Schedule IDs

Use compact drawing tags without hyphens and readable schedule IDs with hyphens. Keep the category and sequence consistent: `AP01` ↔ `AP-01`, `HA01` ↔ `HA-01`, `EQ01` ↔ `EQ-01`.

Door and window instance numbering retain their established formats. Material/finish references use the separate [Materials + Finishes Legend](materials-finishes-legend.md) classification.

## Identifier categories

| Identification | Example           | Meaning                                             |
| -------------- | ----------------- | --------------------------------------------------- |
| Instance ID    | Door `101`        | One specific door assembly                          |
| Instance ID    | Window `1.01`     | One specific window assembly                        |
| Type ID        | Lighting type mark      | A fixture model used at multiple locations          |
| Type ID        | Appliance `AP-01` | A product selection potentially used more than once |
| Assembly ID    | Built-in `BI-01`  | A particular custom built-in assembly               |

## Recommended conventions

| Convention           | Rule                                                                |
| -------------------- | ------------------------------------------------------------------- |
| Identifiers | Drawing tags omit separators; schedules insert a hyphen between the category and the same sequence, such as `AP01` and `AP-01` |
| Repeated products    | Same product/type ID may appear at multiple locations               |
| Location             | Room name, room number, or keyed plan reference                     |
| Dimensions           | Inches, consistent with established office conventions              |
| Manufacturer / Model | Exact product when selected; `TBD` during design                    |
| Finish               | Include when finish affects the purchased product                   |
| Remarks              | Special conditions, exceptions, coordination requirements           |
| Drawings             | Control locations, quantities, installation geometry, relationships |
| General notes        | Capture shared installation and verification requirements           |

General Item Tags use elongated hexagons; construction Assembly Tags use squares. Windows, doors, lights, and fans retain their category-specific tags. See [Drawing Notes and Tags](../drawing-standards/drawing-notes-and-tags.md) for the category codes and identification rules.

## Related standards

[General Scheduling Philosophy](general-scheduling-philosophy.md) · [SD/DD Selections Book](sd-dd-selections-book.md) · [SD/DD to CD Documentation Handoff](sd-dd-to-cd-documentation-handoff.md)
