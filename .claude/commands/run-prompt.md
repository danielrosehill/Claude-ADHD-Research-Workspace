# Run Research Prompt

You are executing a research prompt from the to-run queue and generating outputs.

## Task

1. List available prompts in `prompts/to-run/`
2. Ask user which prompt to execute (or accept a filename)
3. Read the prompt file and any referenced context
4. Generate a comprehensive research output following the prompt's specifications
5. Save output to `outputs/` with format: `YYYY-MM-DD-topic-slug-output.md`
6. Move the executed prompt from `to-run/` to `run/`
7. Update output file with metadata:
   - Generation date
   - Prompt source file
   - Model used
   - Key sources consulted

## Output Structure

Each output should include:
- Executive summary
- Main analysis sections
- Sources and citations
- Recommendations or conclusions
- Related research questions to explore

## Guidelines

- Cite sources where possible
- Flag claims that need verification
- Suggest follow-up research questions
- Note jurisdictions that merit deeper investigation
- Cross-reference existing outputs when relevant
