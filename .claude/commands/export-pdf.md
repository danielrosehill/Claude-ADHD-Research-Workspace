# Export Outputs to PDF

You are batch converting markdown outputs to PDF for reading.

## Task

1. Ask user what to export:
   - Specific output file(s)
   - All outputs from a directory
   - Synthesized research documents
   - Custom selection
2. Check for required tools (pandoc, wkhtmltopdf, or similar)
3. Generate PDFs with:
   - Clean formatting
   - Table of contents
   - Page numbers
   - Metadata (title, date, source file)
4. Save PDFs to `exports/pdf/` with format: `YYYY-MM-DD-topic.pdf`
5. Optionally concatenate multiple outputs into a single PDF with:
   - Cover page
   - Full table of contents
   - Section breaks between documents

## Formatting Guidelines

- Use readable fonts (serif for body text)
- Include source file path in footer
- Add generation timestamp
- Preserve markdown formatting (headers, lists, quotes, code blocks)
- Include hyperlinks where applicable
- Optimize for printing or screen reading based on user preference

## Batch Options

- Concatenate all outputs from a specific topic area
- Create jurisdiction-specific compilations
- Generate chronological collections
- Build thematic readers
