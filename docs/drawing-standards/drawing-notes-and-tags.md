# Drawing Notes and Tags

**Last revised:** November 18, 2026

## Placement

| Information | Applies To | Placement |
| --- | --- | --- |
| General Notes | The entire project | A0 series |
| Sheet Notes | The drawing type, trade, phase, or work shown generally, rather than one specific item or location | Applicable sheet |
| Keyed Notes | A specific item, location, or condition requiring clarification | Marker on the drawing, with text in the same sheet's keynote list |
| Item Tags | An identified element, product type, or assembly | At the item, referencing its schedule, type legend, or other definition |

A keyed note explains an item or condition; a tag identifies it. An item may require both.

## Keyed Notes

Use keynotes to keep drawings clear: place a numbered marker at the relevant item or location and put the explanatory text in the sheet's keynote list.

- Use numerals only: `1`, `2`, `3`. Do not use drawing-type letter prefixes.
- Start numbering at 1 on each sheet. Use one keynote list for all views on that sheet.
- Reuse the same number wherever the same note applies on that sheet.
- Numbers may have different meanings on different sheets; each sheet's list controls.
- When referring to a keynote outside the drawing, identify both the sheet and number: **Keynote 4 on A2.01**.
- Keep issued numbers stable. Append new notes and do not repurpose deleted numbers.
- Maintain reusable note wording in an office reference library; assign keynote numbers within each sheet.

This system applies to plans, elevations, sections, and details. Keynote numbers do not encode a drawing type or CSI specification section. Add a specification reference to the note text when useful.

## Item Tags

Tag each item primarily on the drawing where its location and installation are most clearly communicated. Repeat tags on other views only when they improve coordination.

### Item Types

Use item tags for the following categories when they reference a schedule, type legend, or defined assembly. Identify types, groups, or assemblies rather than every component unless individual identification is needed.

| Item Category | Includes |
| --- | --- |
| Doors | Interior and exterior doors, including multi-leaf and sliding assemblies |
| Windows + Skylights | Individual openings and window assemblies |
| Cabinetry + Built-ins | Cabinet groups, vanities, shelving, benches, closets, and custom storage |
| Appliances + Fireplaces | Kitchen and laundry appliances, specialty appliances, fireplaces, and inserts |
| Plumbing Fixtures + Fittings | Sinks, faucets, toilets, tubs, shower components, and specialty fixtures |
| Lighting | Interior and exterior luminaires, including wall-mounted fixtures |
| Fans | Ceiling fans, exhaust fans, and combination fan/light units |
| Mechanical Equipment | Heating, cooling, ventilation, dehumidification equipment, and controls |
| Specialty Electrical + Low-Voltage Devices | Selected devices, controls, charging equipment, and communications or security equipment requiring a specific product reference |
| Hardware + Accessories | Bath accessories, hooks, rods, specialty hardware, and door hardware groups |
| Glass + Mirrors | Shower enclosures, screens, partitions, mirrors, and medicine cabinets |
| Finishes + Surface Materials | Flooring, wall and ceiling finishes, tile, countertops, and backsplashes |
| Window Treatments | Shades, blinds, draperies, tracks, and motorized systems |
| Exterior Fixtures + Accessories | Hose bibbs, exterior showers, house numbers, mailboxes, and other scheduled site/building accessories |
| Furniture | Scheduled or space-defining furniture requiring drawing coordination |
| Construction Assembly Types | Wall, partition, floor, roof, and ceiling assemblies defined in a type legend or assembly schedule |
| Structural Members + Foundation Elements | Beams, posts, columns, footings, and other elements identified in structural schedules or details, when included in the drawing scope |

Standard receptacles and similar devices normally use symbols rather than individual item IDs. Add product tags only where a specific selection or installation requires one. Door hardware group references normally appear in the door schedule rather than at each hardware component.

Room labels, grid references, and drawing callouts have separate identification functions.

### Identifier Types

| Identifier | What It Identifies | Typical Item Types | Example |
| --- | --- | --- | --- |
| **Instance** | One particular installed element or opening. Each instance has its own mark, even when several share the same product or type. | Doors, windows, and equipment or structural elements requiring individual tracking | Door `101`; window `1.01` |
| **Type** | A repeatable product, configuration, material, or construction definition. All matching occurrences may share the mark. | Door/window types; lighting and fan types; appliances; plumbing products; hardware groups; finishes; wall/floor/roof types; repeatable furniture or equipment selections | A light type used at several locations; door type `A` assigned to several door instances |
| **Assembly** | A coordinated group of components documented as one unit. The reference leads to the assembly's drawings, schedule entry, or fabrication requirements. | Custom built-ins, cabinet groups, stairs, railing assemblies, and custom glazing or other multi-component installations | A built-in assembly mark identifies a complete storage bench, not each cabinet box or hardware component |

**Instance and type identifiers can work together.** Doors `101` and `102` are separate instances but may both be door type `A` and use the same numeric hardware group. A repeated light type may need only its type tag unless individual tracking is required.

**Assembly describes the scope of the identified item.** An assembly may have a unique instance mark or a repeatable type mark; it does not automatically need an additional competing ID. A door instance mark can identify the entire door assembly, while a custom built-in uses its assembly mark.

### Primary Tag Locations

| Item | Primary Location | Secondary Use |
| --- | --- | --- |
| Windows | Floor plans | Repeat selectively on exterior elevations |
| Doors | Floor plans | Repeat on elevations only where needed for clarity |
| Cabinets + Built-ins | Interior elevations | Use plan tags selectively |
| Appliances | Floor plans | Supplement with interior elevations where needed |
| Mechanical equipment | Mechanical plans or floor plans | Use sections or elevations to clarify spatial relationships |
| Lights + Fans | Reflected ceiling plan (RCP) | Coordinate with the electrical plan |
| Receptacles | Electrical power plan | Use symbols rather than individual IDs; supplement with elevations where needed |

### Tag Coordination

- Use consistent identifiers between drawings and schedules.
- Use secondary tags to resolve ambiguity, and avoid unnecessary duplicate annotation.

## Note and Schedule Block Placement

Organize note and schedule blocks within the sheet's modular grid. Align block edges and headings with grid boundaries to create consistent, readable bands of information.

- Use single-module widths for note and keynote blocks; span adjacent modules for wider schedules.
- Align neighboring block headings along a common horizontal line.
- Place schedule-specific notes directly below the schedule they explain.
- Group related blocks and keep their placement consistent across sheets, adjusting the arrangement to suit the drawings and available space.

## Related Standards

[Drawing Set Organization](drawing-set-organization.md) · [Drawing Title Naming Convention](drawing-naming.md) · [General Schedule Identification Protocol](../schedules/general-schedule-identification-protocol.md)
