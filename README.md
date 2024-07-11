# Conf Wisdom

The main idea behind this repository is that a person cannot watch all the presentations of any big conference, not to mention of all the interesting conferences that happen during the year. Based on experience, picking the videos by the title isn't as efficient as it seems, since the content will likely differ from the expectations, and we will likely miss other great content.

One alternative is to ask some LLM (in this case `llama3:8b`) to extract the key insights, ideas, references and recommendations in an easily and quickly digestible way. We can learn from these notes, if the content is worth, watch the talk later.

[For a more detailed explanation of the reasoning behind this experiment, please check my blog post.](https://blog.ovalerio.net/archives/2900)

## Contents

This repository contains the generated notes for the videos of multiple conferences. Soon, the code to generate these notes from any YouTube playlist will be added to the repository.

### Notes

You can find all the notes in the `data` directory, organized by conference (aka YouTube playlist). All of them are generated locally by running the models, instead of relying on online APIs.

### Tools

This repository relies on [ollama](https://ollama.com/) and [fabric](https://github.com/danielmiessler/fabric/) to achieve its goal. Especially the `extract_wisdom` pattern created by [Daniel Miessler](https://github.com/danielmiessler)
