# Robo-DM

### Objective

Using AI, generate a story plotline and then generate scenes and characters to populate the plotline, simply and interactively. Users may select from famous works to take inspiration from (“I want my story and world to be like Lord of the Rings.”), select genres and tropes (“I want it to be more of a dark fantasy cerebral horror / thriller.”), and enter prompt text to first generate a plotline; then they may alter the plot line in-place, request a rewrite with an optional prompt (“More HORROR”), and, when happy with the plot, have the AI generate scenarios and scenes for plot points.
The initial motivation for this project is to make a resource for people who want to create their own story and world for personal use in a tabletop RPG like Dungeons and Dragons.

### Learning Goals

Experience with complex AI and tools used therewithin. Specifically, exploring NLP technologies, multi-dimensional prompts, AI output -> human editing -> AI input cycles, and structured input / output for LLM's.

### Tools

Python, TensorFlow?

### Milestones

1. Rough-draft python script for a plot generator with one of the following inputs: inspirational works, genre, text
Due: 10/06

2. Refine plot generator and implement more input dimensions
Due: 10/27

3. Refine plot generator and implement human editing and AI rewrite
Due: 11/10

4. Scene / character generation for plot points
Due: 12/1

### Challenges

Making a new neural net for a new problem!! I think designing an LLM with structured input and output will be a hurdle, as will prompt engineering for populating plot point scenes and characters.

### Rules of Measure

1. Compare the quality of generated content against existing tools such as SudoWrite Story Engine or human-made works such as an adventure manual from DnD Beyond

2. Judge how well generated plot points fulfill the purpose of their prescribed step in the overarching plot, e.g., does plot point 1 introduce an 'ordinary world,' does plot point 7 send the main character(s) to their 'innermost cave'

### Future Work

Further develop the scene generation to include things you'd find in an adventure manual like monster stats, loot tables, etc.

Could integrate image generation on top of generated scenes and/or characters

