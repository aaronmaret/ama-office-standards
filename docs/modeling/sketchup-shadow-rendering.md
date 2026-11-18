# SketchUp Shadow Rendering

**Last revised:** November 18, 2026

!!! note "Version-dependent behavior"
    Troubleshooting findings describe the reported software environment; verify behavior in the version being used.

A rendering artifact was resolved by disabling Fast Shadows in SketchUp.

## Confirmed finding

Turning off Fast Shadows corrected the unwanted shadow patterns.

## Additional observed behavior

LayOut preview shadows sometimes differed from the shadows shown in SketchUp.

The exported PDF displayed the correct shadows even when the LayOut preview did not.

## Proposed QA procedure

For shadow-sensitive presentation views:

1. Confirm scene shadow settings in SketchUp.
2. Disable Fast Shadows if artifacts occur.
3. Save the SketchUp model.
4. Update the model reference in LayOut.
5. Verify the final exported PDF rather than relying exclusively on LayOut's preview.

This is a recommended production check, not a formally adopted universal office standard.

## Related standards

[SketchUp / LayOut Documentation Environment](sketchup-layout-documentation-environment.md) · [ConDoc Drawing Production](condoc-drawing-production.md) · [LayOut Annotation Maintenance](layout-annotation-maintenance.md) · [Construction Documentation Quality Checks](../project-delivery/construction-documentation-quality-checks.md)
