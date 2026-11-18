# Drawing Notes and Tags

**Last revised:** November 18, 2026

## Placement

| Information | Applies To | Placement |
| --- | --- | --- |
| General Notes | The entire project | A0 series |
| Sheet Notes | The drawing type, trade, phase, or work shown generally, rather than one specific item or location | Applicable sheet |
| Keyed Notes | A specific item, location, or condition requiring clarification | Marker on the drawing, with text in the same sheet's keynote list |
| Item Tags | A scheduled product, item, or fabricated unit | At the item, referencing its schedule or product definition |
| Assembly Tags | A defined construction assembly | At the assembly, referencing its legend, build-up, or construction detail |

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

### Item Tag Format

Use an **elongated hexagon** for scheduled products, items, and fabricated units. Windows, doors, lights, and fans retain their category-specific tags. Construction assemblies use the square **Assembly Tag** described below.

The Item Tag contains a **two-letter category designator followed immediately by one or two numerals**. Do not insert a dash, period, or space. Examples: `AP1` or `AP01`, `BI3` or `BI03`.

The full identifier references the applicable instance, product type, or fabricated unit in its schedule or detail.

### Item Category Designators

| Code | Item Category | Includes |
| --- | --- | --- |
| **AP** | Appliances | Kitchen, laundry, and specialty appliances |
| **FP** | Fireplaces + Inserts | Fireplaces, inserts, and scheduled fireplace units |
| **CB** | Cabinetry | Cabinet groups, vanities, and cabinet systems |
| **BI** | Custom Built-ins | Benches, shelving, closets, and custom storage units |
| **PF** | Plumbing Fixtures + Fittings | Sinks, faucets, toilets, tubs, shower components, hose bibbs, and exterior showers |
| **ME** | Mechanical Equipment | Heating, cooling, ventilation, dehumidification equipment, and controls |
| **ED** | Specialty Electrical + Low-Voltage Devices | Selected devices, charging equipment, communications/security equipment, and specialty controls |
| **HA** | Hardware + Accessories | Bath accessories, hooks, rods, and specialty hardware |
| **GL** | Glass + Glazing Assemblies | Scheduled shower enclosures, screens, partitions, and fabricated glazing units |
| **MR** | Mirrors + Medicine Cabinets | Mirrors, frames, and medicine cabinets |
| **FN** | Finishes + Surface Materials | Flooring, tile, wall/ceiling finishes, countertops, and backsplashes |
| **WT** | Window Treatments | Shades, blinds, draperies, tracks, and motorized systems |
| **EX** | Exterior Accessories | House numbers, mailboxes, and other exterior accessories without a more specific category |
| **FU** | Furniture | Scheduled or space-defining furniture requiring drawing coordination |
| **SE** | Structural Members + Foundation Elements | Individually identified beams, posts, columns, footings, and similar elements, when included in the drawing scope |

Categorize by function rather than location: an exterior faucet uses **PF**, not **EX**. Keep any structural consultant's identifiers coordinated with their drawings and schedules.

Standard receptacles and similar devices normally use symbols rather than individual item IDs. Add product tags only where a specific selection or installation requires one. Door hardware group references normally appear in the door schedule rather than at each hardware component.

## Assembly Tags

Use a **square tag** to reference a defined construction assembly. This expands the former Wall Tag to cover walls, floors, roofs, ceilings, and specialty construction assemblies.

Use one letter followed immediately by one or two numerals, with no separator: `W1`, `F2`, or `R01`.

| Code | Assembly Category | References |
| --- | --- | --- |
| **W** | Wall Assembly | Wall or partition build-up |
| **F** | Floor Assembly | Floor build-up |
| **R** | Roof Assembly | Roof build-up |
| **C** | Ceiling Assembly | Defined ceiling build-up; a finish alone uses an FN reference |
| **S** | Specialty Assembly | Specialty construction definitions, such as stair or railing assemblies |

Foundation conditions are documented through specific construction details rather than a foundation assembly tag.

### Choosing Item or Assembly Tags

Choose the shape by **what the tag references**, not by the number of components in the object.

- **Square:** references a construction assembly definition, build-up, or assembly detail.
- **Elongated hexagon:** references a scheduled product, item, or fabricated unit. A cabinet group or built-in remains an item even though it contains many components.
- A stair, railing, or glazing unit uses the square tag when referencing its construction assembly, or the Item Tag when referencing a scheduled fabricated unit.

Room labels, grid references, and drawing callouts have separate identification functions.

## Identifier Types

| Identifier | What It Identifies | Typical Item Types | Example |
| --- | --- | --- | --- |
| **Instance** | One particular installed element or opening. Each instance has its own mark, even when several share the same product or type. | Doors, windows, and equipment or structural elements requiring individual tracking | Door `101`; window `1.01` |
| **Type** | A repeatable product, configuration, material, or construction definition. All matching occurrences may share the mark. | Door/window types; lighting and fan types; appliances; plumbing products; hardware groups; finishes; wall/floor/roof types; repeatable furniture or equipment selections | A light type used at several locations; door type `A` assigned to several door instances |
| **Assembly** | A coordinated group documented as one unit. The identifier references the complete group rather than each component. | Construction build-ups and specialty assemblies; fabricated units such as built-ins | Square `W1` references a wall build-up; elongated-hexagon `BI01` identifies a complete storage bench |

**Instance and type identifiers can work together.** Doors `101` and `102` are separate instances but may both be door type `A` and use the same numeric hardware group. A repeated light type may need only its type tag unless individual tracking is required.

**Instance/type describes how an identifier is reused; assembly describes the scope being identified.** A construction assembly can be a repeatable type. A fabricated built-in can be a unique instance. Use the square or elongated hexagon according to the reference destination; do not add a competing ID merely because an item has multiple components.

## Item-Specific Tagging Rules

| Item | Primary Location | Identification and Coordination |
| --- | --- | --- |
| Construction Assemblies | Plans, sections, or details where the assembly is most clearly identified | Use the square tag to reference the assembly legend, build-up, or detail. |
| Windows + Skylights | Floor plans | Use normal window numbering, such as `1.01` and `2.01`; the leading digit identifies the level. Identify grouped windows and skylight assemblies as one item. Repeat tags on elevations only where stacked openings or complex arrangements need clarification. |
| Doors | Floor plans | Use normal door numbering, such as `101` and `201`. One identifier covers the complete assembly, including multi-leaf, folding, and specialty doors. Show swing and handing on plans; use the Door Type Legend for appearance/configuration. Repeat IDs on elevations only where needed. |
| Cabinetry + Built-ins | Interior elevations | Identify cabinet groups or complete built-ins rather than every cabinet box. Plans establish arrangement; elevations establish composition, dimensions, finishes, and appliance relationships; shop drawings provide fabrication information where required. Use plan tags selectively. |
| Appliances | Floor plans | Refer to the Appliance Schedule for manufacturer, model, and requirements. Use interior elevations to clarify cabinet and appliance relationships. |
| Mechanical Equipment | Mechanical plans, or architectural plans where coordination requires | Keep equipment specifications in one coordinated schedule. Use sections or elevations to clarify clearances and spatial relationships. |
| Lights + Fans | Reflected ceiling plans | Identify fixture types; repeated occurrences may share a type mark. RCPs establish fixture locations, ceiling relationships, beams, soffits, and alignment. Electrical plans establish switching, circuits, and controls. Use elevations for wall-mounted fixture heights. Combine RCP/electrical information on small projects when legible. |
| Receptacles | Electrical power plans | Use symbols for standard duplex, GFCI-protected, weather-resistant exterior, floor, dedicated appliance, 240V, and USB devices. Use a product tag only for a specialty selection or installation. Add elevations for precise relationships to backsplashes, vanities, desks, or cabinetry. |

Product families and finishes belong in the applicable schedule or selections documentation. Detailed door/window schedule requirements remain in [Door Schedule Protocol](../schedules/door-schedule-protocol.md) and [Window Schedule Protocol](../schedules/window-schedule-protocol.md).

## Tag Coordination

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
