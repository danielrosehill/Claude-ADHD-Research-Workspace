# Generate Podcast from Outputs

You are converting research outputs to podcast-ready format and generating audio.

## Task

1. Ask user which outputs to convert to audio
2. Reformat the markdown content for spoken delivery:
   - Convert to conversational narrative
   - Remove or describe tables/charts
   - Add natural transitions
   - Structure as podcast episode(s)
   - Include introduction and conclusion
3. Save reformatted script to `audio/scripts/` as: `YYYY-MM-DD-topic-script.md`
4. Check for TTS tools (piper, coqui, elevenlabs API, etc.)
5. Generate audio files and save to `audio/episodes/`
6. Create metadata file with:
   - Episode title
   - Duration
   - Source outputs
   - Key topics covered
   - Timestamp

## Podcast Script Format

- **Opening**: Brief intro to the research topic
- **Context**: Background and why this matters
- **Main Content**: Key findings in narrative form
- **Examples**: Concrete illustrations of points
- **Implications**: What this means practically
- **Closing**: Summary and what's next

## Audio Generation Options

- Single voice narration
- Multi-voice if discussing different perspectives
- Insert pauses for emphasis
- Adjust pacing for comprehension
- Target 15-30 minute episodes for typical outputs

## Guidelines

- Use plain language, avoid dense academic style
- Explain acronyms and technical terms
- Maintain engagement with varied pacing
- Include verbal citations ("according to...")
- Make transitions clear ("Now let's consider...")
