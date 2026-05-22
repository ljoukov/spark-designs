# designs review UI

Objective: create a review page for the UI brainstorming agent that groups every generated design image by the student learning example it is meant to solve.

The page should help the reviewer judge whether each design closes the actual next thinking gap before giving a full answer. For each of the four example groups, show:

- the real task or question the student was working on
- what the student wrote or asked for
- the specific gap identified from grading or chat data
- the design intent for closing that gap
- every generated image, labelled with source and filename

Output artifact: `gallery.html` in this folder.

Constraint: keep exactly four top-level groups, matching the four examples from the research summary. Related late images from broader student data should be placed inside the nearest group and clearly labelled as related variants, not split into extra groups.
