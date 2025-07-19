# My LLM-Based Resources: Knowledge, Prompts, and More

Since OpenAI released ChatGPT on November 30, 2022, I've steadily invested time and energy into extracting powerful outputs from these large language models for both my personal and professional life. I've decided to share these valuable insights here, as I believe a community-driven effort is the most effective way to foster excellent developments in software, hardware, and even groundbreaking ideas.

---

## Repository Structure

This repository is organized to help you quickly find resources related to Large Language Models (LLMs).

* **[Generative AI Knowledge](generative-ai-knowledge/README.md)**: Dive into core concepts and structures behind generative AI.
    * [Prompt Anatomy](generative-ai-knowledge/prompt-anatomy.md): Understand the fundamental components of effective prompts.
    * [Coding Prompt Anatomy](generative-ai-knowledge/coding-prompt-anatomy.md): Specifically for prompts related to code generation.

* **[Prompt Storage](prompt-storage/README.md)**: A collection of various prompts for different use cases.
    * [AI Profiles](prompt-storage/ai-profiles/perplexity-profile.md): Prompts tailored for specific AI personas or platforms (e.g., Perplexity AI).
    * [Czech-Focused](prompt-storage/czech-focused/correct-czech-text.md): Prompts designed for Czech language tasks.
    * [Generic Translator](prompt-storage/generic-translator.md): A versatile prompt for general translation needs.
    * [Make My English Just Perfect](prompt-storage/make-my-english-just-perfect.md): Enhance your English text for clarity and correctness.
    * [Personal Lawyer](prompt-storage/personal-lawyer.md): A prompt to simulate legal assistance or generate legal-style text.
    * [Prompt Expander](prompt-storage/prompt-expander.md): Expand short prompts into more detailed ones.
    * **[Text Processing](prompt-storage/text-processing)**: Prompts specifically for summarizing and processing text.
        * [Bullet Point Summary](prompt-storage/text-processing/bullet-point-summary.md): Condense text into concise bullet points.
        * [Coherent Text Summary](prompt-storage/text-processing/coherent-text-summary.md): Generate a fluent and coherent summary of a given text.
    * [Update Prompt Github Readme](prompt-storage/update-prompt-github-readme.md): A prompt to update your GitHub README.md based on repository changes.

* **[LICENSE](LICENSE)**: Licensing information for this repository.

---

### How This README Was Generated

Curious how this was made? It's an example of using an LLM with Unix tools. I ran `tree` in the repo root, then pasted the output into **Gemini 2.5 Flash** with the prompt:

```
Based on tree generate description and clickable library for my main README in GitHub to help users understand and navigate quicker. My current README contains this:

# My LLM-Based Resources: Knowledge, Prompts, and More

Since OpenAI released ChatGPT on November 30, 2022, I've steadily invested time and energy into extracting powerful outputs from these large language models for both my personal and professional life. I've decided to share these valuable insights here, as I believe a community-driven effort is the most effective way to foster excellent developments in software, hardware, and even groundbreaking ideas.
```

> Future updates to this page are entirely automated by **Update Prompt GitHub Readme**.