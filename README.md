# AMA Office Standards

Public architectural documentation conventions for Aaron Maret Architect.

Website: https://standards.aaronmaret.com/

## Preview

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Validate with `mkdocs build --strict`.

## Publishing

GitHub Actions validates pull requests and deploys successful builds from `main`. In repository Settings → Pages, select **GitHub Actions** as the source and set the custom domain to `standards.aaronmaret.com`. DNS requires a CNAME record with host `standards` and target `aaronmaret.github.io`. Enable **Enforce HTTPS** when the certificate is ready.

Content lives in `docs/`; navigation and theme configuration live in `mkdocs.yml`. The manual includes 42 protocols imported from the November 17, 2026 conversation export. Each page retains confirmed, proposed, partial, or unresolved source status; source limitations and pending decisions are documented. DD/CD sheet numbers use A plus two digits (for example A20).

Only public-safe standards and fictional examples belong in this repository, including its history. No client, financial, contractual, or credential information.
