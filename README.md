# Karpathy: Neural Networks Zero to Hero

Interactive, slide-by-slide walkthroughs of Andrej Karpathy's from-scratch teaching codebases — from a tiny autograd engine to a full ChatGPT pipeline.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_Karpathy_Zero_to_Hero/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [micrograd — A Tiny Autograd Engine](https://github.com/BrendanJamesLynskey/micrograd_presentation) | live | Backpropagation from scratch — the scalar `Value` object, the expression graph, the chain rule, and a small MLP trained by gradient descent. ~150 lines that explain every deep-learning framework. |
| 02 | [makemore — Character-Level Language Models](https://github.com/BrendanJamesLynskey/makemore_presentation) | live | From a bigram counting model to a Bengio-2003 MLP, then the deep-dive on initialisation, activations, gradients and BatchNorm, and finally a WaveNet-style hierarchy — all generating new name-like words. |
| 03 | [minbpe — Let's Build the GPT Tokenizer](https://github.com/BrendanJamesLynskey/minbpe_presentation) | live | Byte-pair encoding from first principles — UTF-8 bytes, the merge algorithm, the BasicTokenizer and RegexTokenizer, the GPT-2/GPT-4 split patterns, special tokens, and reproducing the GPT-4 tokeniser. Includes a live in-browser BPE demo. |
| 04 | [minGPT — A Clean, Educational GPT](https://github.com/BrendanJamesLynskey/minGPT_presentation) | live | The library-structured predecessor of nanoGPT — CausalSelfAttention, the Block and GPT modules, the config system, loading GPT-2 weights, and the framework-agnostic Trainer. |
| 05 | [nanoGPT — GPT From Scratch, Step by Step](https://github.com/BrendanJamesLynskey/nanoGPT_presentation) | live | Every one of the ~200 lines of Karpathy's nanoGPT lecture code — tokenisation, self-attention, the transformer block, the full model, training and generation. The canonical "Let's build GPT" walkthrough. |
| 06 | [llm.c — LLM Training in Raw C/CUDA](https://github.com/BrendanJamesLynskey/llm_c_presentation) | live | Training GPT-2/GPT-3 with no PyTorch and no dependencies — the parameter/activation buffers, hand-written forward and backward kernels, AdamW by hand, and the CUDA / mixed-precision / multi-GPU path that matches and beats PyTorch. |
| 07 | [nanochat — The Best ChatGPT $100 Can Buy](https://github.com/BrendanJamesLynskey/nanochat_presentation) | live | The capstone — an entire ChatGPT pipeline in one hackable repo: a Rust BPE tokeniser, base pretraining, midtraining, SFT, optional RL, evaluation and a chat web UI, stitched together by a single speedrun script. |

## How to read this series

The decks follow Karpathy's "Zero to Hero" arc: start with **micrograd** for backpropagation, build a language model with **makemore**, learn tokenisation with **minbpe**, then study the GPT itself through **minGPT** and **nanoGPT**. Go closer to the metal with **llm.c**, and assemble the whole ChatGPT pipeline with **nanochat**.

Each deck is a single-page interactive [Reveal.js](https://revealjs.com/) presentation served on GitHub Pages. Use `→` to advance, `↓` for sub-sections, and `Esc` for the slide overview.

## Where this fits

Based on the open-source teaching code of [Andrej Karpathy](https://github.com/karpathy). Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
