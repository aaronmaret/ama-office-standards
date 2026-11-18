# Maintaining this manual

## Edit a protocol

1. Open the page and select its edit icon, or open the corresponding Markdown file in the GitHub repository.
2. Edit the text and update **Last revised**.
3. Review the change for accuracy and public suitability.
4. Commit to `main`. GitHub Actions builds the manual and publishes it to GitHub Pages after a successful build.

Changes proposed through a pull request are built for validation without being published. Merge an accepted change into `main` to publish it. The repository history records previous versions.

## Add a page

Create a Markdown file under `docs/`, add it to `nav` in `mkdocs.yml`, and link related standards. Include a revision date and the essential rules. Add examples or context where useful.

## Public content boundary

Publish general office standards and fictional examples. Keep client names, project addresses, private drawings, fees, financial records, agreements, credentials, and purchased reference materials outside this repository. Removing text later does not remove it from public version history.

## Local preview

The repository README includes installation and preview instructions. All core content is ordinary Markdown, so it remains portable if the publishing platform changes.
