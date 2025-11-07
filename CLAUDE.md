# CLAUDE.md - ADHD Medication Access Research Repository

This repository is an open source research notebook that implements a pattern for working with Claude Code on "deep research" projects 

Research, in this context, means using you (Claude!) or other LLMs to conduct first pass research - in this case into the topic of drug access policy for ADHD medications.

## Folder Map

I use a precise arrangement of files and folders to organise research projects, including this one. Here's what they are and how to use them:

Unless otherwise stated, all paths are relative to repo root:

### Context Storage

context
This is where I will gather any context data. Context data is background information that should be used to contexualise your responses. It is persistent information that will be useful across sessions. 

You may add to the context pool periodically; chunk it into smaller files for easier readability; prune it to remove outdated context. It is a living entity of information.

### Prompts

This folder contains a log of prompts I have run or am working on - organised into /drafting, /run, /to-run.

Slash commands and subagents will handle archiving etc. 

### Outputs

This is where you should create your responses to my prompts (where responses = turns/completions in response to prompts).

The outputs folder will be gradually organised as it assembles and will be used as the basis for concatenation and, in turn, further human validated research.

### Data

In the course of our research, you, or I, may supply data as a source, or an output. 

Data in document format is a borderline case and is best handled by routing to a dedicated folder at data/docs so that originals can be preserved and then distilled into structured data. 

### Lobby

This repository exists to organise some research into a problem which I believe is of significane: drug access for adults with ADHD.

I have no immediate plans to lobby for this cause mostly because I lack the time. However, it is important to me and this notebook may provide source material for somebody else who does want to take on the project in a more organised manner. 

For that reason, I've created a folder called 'lobby' which is where we will create outputs for our hypothetical lobby that - were it to exist - would advocate for the type of policy that I think would be reasonable.

## Research Workflow

Here's how we will work together, approximately:

- Now and again, I'll come up with a research question. I'll put that in the prompts folder. I'll run a slash command to send that to you as a task outline. 
- You'll output your analysis to outputs. We might run a few cycles in quick succession. 
- I'll probably take a little bit of time to read through what you've come up with and validate and research it. 
- Now and again I'll ask you to create content in the 'lobby' folder. But I'll do this only after I've thought over your outputs and have thought about what I'd like to write. I may write this content myself and then ask you to review it. Or I may you to flesh out some parts. 

Other fun tasks:

Sometimes, I like to listen to information rather than read it. Sometimes I like to package up a lot of outputs into a PDF and print it to read over the weekend. For the latter, I have a workflow for creating a podcast that uses some output reformatting and  TTS in a chain. For the latter - it's usually just a simple script that batches up a folder of markdown files and sends out a PDF. I'll get round to writing slash commands to ask you to run specific scripts to generate either/or at times.

## Objective 

My overarching objective: this is a long term project. There's no prescriptive answer to what approrpriate drug policy should look like - much less for ADHD. Nevertheless, I think it merits thoughtful consideration. I'm also particularly interested to see how various jurisdictions have approaches this question. 

We'll work on this project every now and again. And over time maybe even build the foundations for something more!