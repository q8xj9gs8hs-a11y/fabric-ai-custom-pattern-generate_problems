# fabric-ai-custom-pattern-generate_problems
Custom fabric-ai pattern to generate practice problems for general chemistry or differential equations

This pattern has served as an aid to my studying for university finals. Here is how to set it up, and most of all, use it properly.

# Set up
You'll find in this repository that there is (1) the "training" data I used in conjunction with `fabric-ai -p create_pattern` (a patttern to create more patterns) in order to refine the prompts, (2) the actual prompts as `system.md`. I've done it this way so you can see part of the process of how I create these patterns.

Whenever I refer to 'data', I am referring to all the info I ultimately dump into `fabric-ai -p create_prompt` as the finale. I also have an alias set for `fabric-ai` as `fabric` (`alias fabric='fabric-ai'`)
## This is how I set it up:
I used combinations of `pbpaste | fabric -p improve_prompt` with the training data being the clipboard
or
`pbpaste | fabric -p clean_text | fabric -p summarize` whenever the data was messy pasted content.

Just like my previous repo, setting up the pattern is the exact same:
- download the `system.md` for each pattern and put them in your custom patterns directory

- You can use LLMs run off your device, but cloud models from vendors such as `Cerebras` and `Ollama` are also great. I particularly like `Cerebras'` `qwen-3-235b-a22b-instruct-2507` or `Ollama's` `qwen3-vl:235b-cloud`. By doing so, you are opting in for faster speeds.
# Usage
## diff_applications

## chem_problems

# Notes
