# Docling-checkout

Me checking out docling for reading in PDFs and converting them into structured data 

```bash
uv run docling --verbose --pdf-backend pypdfium2 --to md 'example_input_docs/full_popi_act.pdf'
uv run docling --verbose --pdf-backend pypdfium2 --to html 'example_input_docs/full_popi_act.pdf'

# I was excited about smoldocling but it produces blank output every time for me
uv run docling --verbose --pdf-backend pypdfium2 --pipeline vlm --vlm-model smoldocling --to html 'example_input_docs/full_popi_act.pdf'
```
