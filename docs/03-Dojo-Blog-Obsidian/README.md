# Organize your knowledge in the age of AI.

How to capture YouTube, LinkedIn, and other sources into a local Obsidian vault — and search it with Codex, Claude, or Cursor.

## Article

- **HTML:** `html/organize-knowledge-ai-era.html`
- **Source:** `Organize your knowledge in the age of AI.md` (from `Doc1.docx`)
- **Images:** `images/` (`image1.png` … `image5.png`)

## Python (uv, 3.14)

```powershell
cd 3-Dojo-Blog-Obsidian
uv sync --python 3.14
```

Regenerate HTML from Markdown (Dojo dark theme, images inlined):

```powershell
uv run python code/export_md_to_html.py -o html/organize-knowledge-ai-era.html
uv run python code/export_md_to_html.py -o html/organize-knowledge-ai-era.html --open
```

Optional PDF export (requires `playwright`):

```powershell
uv add playwright
uv run playwright install chromium
uv run python code/export_md_to_pdf.py -o html/organize-knowledge-ai-era.pdf
```
