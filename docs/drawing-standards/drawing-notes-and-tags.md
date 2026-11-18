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

### Item Tag Format

Use an **elongated hexagon** for general tagged items. Categories with their own tag types—windows, doors, wall assemblies, lights, and fans—retain those category-specific tags.

The general Item Tag contains a **two-letter category designator followed immediately by one or two numerals**. Do not insert a dash, period, or space. Format placeholders: `XX1` or `XX01`, where `XX` represents the category designator.

The tag shape and category designator identify the item category. The full identifier refers to the applicable instance, type, or assembly in its schedule, legend, or detail.

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

### Item-Specific Tagging Rules

| Item | Primary Location | Identification and Coordination |
| --- | --- | --- |
| Windows + Skylights | Floor plans | Use normal window numbering, such as `1.01` and `2.01`; the leading digit identifies the level. Identify grouped windows and skylight assemblies as one item. Repeat tags on elevations only where stacked openings or complex arrangements need clarification. |
| Doors | Floor plans | Use normal door numbering, such as `101` and `201`. One identifier covers the complete assembly, including multi-leaf, folding, and specialty doors. Show swing and handing on plans; use the Door Type Legend for appearance/configuration. Repeat IDs on elevations only where needed. |
| Cabinetry + Built-ins | Interior elevations | Identify cabinet groups or complete built-ins rather than every cabinet box. Plans establish arrangement; elevations establish composition, dimensions, finishes, and appliance relationships; shop drawings provide fabrication information where required. Use plan tags selectively. |
| Appliances | Floor plans | Refer to the Appliance Schedule for manufacturer, model, and requirements. Use interior elevations to clarify cabinet and appliance relationships. |
| Mechanical Equipment | Mechanical plans, or architectural plans where coordination requires | Keep equipment specifications in one coordinated schedule. Use sections or elevations to clarify clearances and spatial relationships. |
| Lights + Fans | Reflected ceiling plans | Identify fixture types; repeated occurrences may share a type mark. RCPs establish fixture locations, ceiling relationships, beams, soffits, and alignment. Electrical plans establish switching, circuits, and controls. Use elevations for wall-mounted fixture heights. Combine RCP/electrical information on small projects when legible. |
| Receptacles | Electrical power plans | Use symbols for standard duplex, GFCI-protected, weather-resistant exterior, floor, dedicated appliance, 240V, and USB devices. Use a product tag only for a specialty selection or installation. Add elevations for precise relationships to backsplashes, vanities, desks, or cabinetry. |

Product families and finishes belong in the applicable schedule or selections documentation. Detailed door/window schedule requirements remain in [Door Schedule Protocol](../schedules/door-schedule-protocol.md) and [Window Schedule Protocol](../schedules/window-schedule-protocol.md).

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
