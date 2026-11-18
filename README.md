# AMA Office Standards

Public architectural documentation conventions for Aaron Maret Architect.

Website: https://standards.aaronmaret.com/

Built with **Zensical 0.1.2** using its classic theme.

## Preview

Use Python 3.11 or newer (automated deployment uses Python 3.12).

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
zensical serve
```

Validate with `zensical build --strict`.

## Publishing

GitHub Actions validates pull requests and deploys successful builds from `main`. In repository Settings → Pages, select **GitHub Actions** as the source and set the custom domain to `standards.aaronmaret.com`. DNS requires a CNAME record with host `standards` and target `aaronmaret.github.io`. Enable **Enforce HTTPS** when the certificate is ready.

Content lives in `docs/`; navigation and theme configuration live in `mkdocs.yml`. The manual includes 42 protocols imported from the November 17, 2026 conversation export. Each page retains confirmed, proposed, partial, or unresolved source status; source limitations and pending decisions are documented. DD/CD sheet numbers use A plus two digits (for example A20).

Only public-safe standards and fictional examples belong in this repository, including its history. No client, financial, contractual, or credential information.

## Migration and recovery

Migrated from MkDocs Material to Zensical on November 18, 2026. `mkdocs.yml` remains the supported configuration filename; Markdown paths and public URLs are preserved. No Material package is required by the new build.

The pre-migration deployment is commit `d3349f5`. To roll back, revert the Zensical migration commit and push the resulting revert commit to `main`. This restores the earlier configuration, requirements, and deployment command without rewriting repository history.

Migration validation compared article text on all 48 generated HTML pages, including the 42 protocol pages. Navigation, search results, logo, light/dark themes, and representative tables were checked before publication.
