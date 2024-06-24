# long-context-malaysian-QA

Generate synthetic Long Context beyond 100k context length for Malaysian QA using Gemini 1.5 Flash.

## how we do it?

1. Combine multiple contexts and chunk it to at least 100k tokens.

2. Generate complex question and answer based on the chunk context.

3. Post CoT based on the question and answer by giving the context.

For reference, [long-context-synthetic-dataset-malaysia-ejudgement-generation.ipynb](long-context-synthetic-dataset-malaysia-ejudgement-generation.ipynb), this notebook to generate for Malaysia Ejudgement dataset, should be quick to replicate it for another contexts.

This notebook developed by https://x.com/oscarnazhan, https://x.com/hlmshkr and https://x.com/FaiqAdzlan

## download

All dataset published at https://huggingface.co/collections/malaysia-ai/open-dataset-6677a97b20ff491d3811c8e9