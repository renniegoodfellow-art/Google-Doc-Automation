Hey everyone! 👋

I’ve been building a workflow for my family business using n8n. The goal is to automatically take client information from an emailed document (usually a PDF) and populate that data into multiple Google Docs templates using placeholders.

I’m still pretty new to both coding and n8n, so I’d really appreciate any help or examples if someone has done something similar.

The issue I’m stuck on is that the text extracted from the emailed PDF isn’t populating the placeholders in Google Docs. The workflow duplicates the templates fine, but the placeholders aren’t being replaced with the actual values (like client names). I suspect the problem is that my “Fill Document” node is using an expression instead of plain text, and the workflow is passing a code string instead of readable text.

This workflow is meant to fill up to five different documents, but I’m not sure whether it’s better to handle them all in one node or use multiple “fill document” nodes—one per file.

I’m using Claude Opus 4.1 to help design and debug, but I haven’t been able to get it working yet.

I’ve attached a screenshot of my workflow and can share more details if needed. Any advice, node examples, or debugging tips would mean a lot. Thanks so much for your time! 🙏
