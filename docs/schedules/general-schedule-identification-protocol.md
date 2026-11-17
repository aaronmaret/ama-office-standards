# General Schedule Identification Protocol

**Protocol:** SS-03  
**Last revised:** November 17, 2026

!!! note "Source and status"
    Imported from the November 17, 2026 conversation export. Its status labels are retained; some earlier decisions were recovered from summaries rather than complete original discussions. Proposed and unresolved material is not adopted office policy.

**Status:** Proposed

## Identifier categories

| Identification | Example           | Meaning                                             |
| -------------- | ----------------- | --------------------------------------------------- |
| Instance ID    | Door `101`        | One specific door assembly                          |
| Instance ID    | Window `1.01`     | One specific window assembly                        |
| Type ID        | Light `L-01`      | A fixture model used at multiple locations          |
| Type ID        | Appliance `AP-01` | A product selection potentially used more than once |
| Assembly ID    | Built-in `BI-01`  | A particular custom built-in assembly               |

## Recommended conventions

| Convention           | Rule                                                                |
| -------------------- | ------------------------------------------------------------------- |
| Identifiers          | Prefix + sequential number for product schedules, such as `AP-01`   |
| Repeated products    | Same product/type ID may appear at multiple locations               |
| Location             | Room name, room number, or keyed plan reference                     |
| Dimensions           | Inches, consistent with established office conventions              |
| Manufacturer / Model | Exact product when selected; `TBD` during design                    |
| Finish               | Include when finish affects the purchased product                   |
| Remarks              | Special conditions, exceptions, coordination requirements           |
| Drawings             | Control locations, quantities, installation geometry, relationships |
| General notes        | Capture shared installation and verification requirements           |

The prefix-plus-number format is a recommendation for new product schedules, not an approved replacement for the established door and window identifiers.

## Related standards

[General Scheduling Philosophy](general-scheduling-philosophy.md) · [SD/DD Selections Book](sd-dd-selections-book.md) · [SD/DD to CD Documentation Handoff](sd-dd-to-cd-documentation-handoff.md)
