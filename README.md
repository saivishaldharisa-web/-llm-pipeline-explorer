# 🧠 LLM Pipeline Explorer

**An interactive, in-browser lab that shows how a language model turns text into numbers.**

🔗 **Live demo:** https://llm-pipeline-explorer-vishal-fe67.vercel.app

## Features

1. **Tokenizer:** build a vocabulary from training sentences, then encode new text. Unknown words are split into smaller pieces, and anything still missing maps to `[UNK]` (ID 0).
2. **Embeddings in 3D:** embed sentences using spelling-based or meaning-based vectors and explore them in an interactive 3D plot.
3. **Similarity:** see the closest sentence pairs by cosine similarity, which is computed on the full vectors rather than the 3D projection.
4. **Try your own text:** tokenize and embed any sentence, add it to the plot, and see its 3 nearest neighbours.

## Why I built it

Tokenization and embeddings are the first steps of every LLM pipeline, but they're hard to picture. This project makes them visual and hands-on for students who are just getting into AI.

## Tech

- HTML, CSS, vanilla JavaScript (single page, no build step)
- Deployed on Vercel

## Run locally

```bash
git clone https://github.com/saivishaldharisa-web/-llm-pipeline-explorer.git
cd -llm-pipeline-explorer
open index.html   # or just double-click it
```

> Educational demonstration, not a complete language model.

---
Built by [Sai Vishal Dharisa](https://www.linkedin.com/in/sai-vishal-dharisa-58b82a416/)
