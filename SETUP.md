# Setup (one-time)

1. Copy README.md to the root of your public `itratjassani/itratjassani` repository.
2. Add `assets/approach.svg` at the same path.
3. Add `.github/workflows/contributions.yml` at the same path.
4. Under repository **Settings → Actions → General → Workflow permissions**, enable **Read and write permissions** if needed.
5. Open **Actions → Update contribution graph → Run workflow**. The first successful run creates the `output` branch and the real contribution graph image. Before that first run, the graph image cannot appear.
6. The workflow will refresh the image once daily. If a company policy or rate limit blocks it, check the workflow logs.

The `assets/approach.svg` diagram is bundled and displays immediately. Do not upload only the README: its diagram requires the separate SVG file.
