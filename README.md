# Claude Research Workspace: ADHD Drug Policy

## Note

Just in case you're wondering, this is a public repo for two reasons:

1) I love research and love using Claude Code for research. I also believe that agentic CLIs are ideal "companions" for this and that the repo structure - while code centric - is actually way more versatile than that. I have shared templates for using a repository as a holding workspace for deep research projects, but I figured it was worth open sourcing a real living project as well as the blueprint. 

2) This is really something that I care about. If you want to know the ins and outs of 'why' see the context folder. But if it were not for the above, this would probably have just remained a private repo. So it's a dual-pupose exhibit and workspace!

## Repo Structure

AI moves rapidly. But I draw comfort in the fact that my very primitive folder stucture for grouping what I think of as the foundational ingredients remains, mostly, the same as it did when I began to plump this rabbit hole sometime when ... does it matter!?

That is:

`/context` - A place for aggregating contextual data. I think of it as miniature RAG. Sometimes I use real RAG. But rarely. What I *do* do regularly, however, is try to implement the best practices of RAG in a folder: chunk context data as logically and cleanly as possible. 

`/prompts` - A simple base folder for prompts. I typically subdivide this into drafting, to-run, and run and map these onto workflows/scripts to support batch execution.

`/outputs` - A base folder for outputs. For output storage: the approach I like the most is perhaps best described as "gather and distill": pipe all runs into a folder. Prune cautiously. Organise carefully. Eventually these can be concatenated into meaty outputs. I tend strongly towards targeting PDF as my end delivery format. 

Those are the foundations. I then layer in (or on) some project specific components.

In this model/sketch:

- Lobby: Workflow mapped in CLAUDE.md. This structure is there to delineate between initial research (first drafts) and later more authoritative articulations of idealised policy. 
- Data: Some of my "day job" work - for clients - involves handling data. A common pipeline is going from document data (say, data in policy reports) to extracted structured data. For lineage, I like to keep both - so often subdivide between docs and data. 

 