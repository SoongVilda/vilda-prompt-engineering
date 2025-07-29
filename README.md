# My LLM-Based Resources: Knowledge, Prompts, and More

Since OpenAI released ChatGPT on November 30, 2022, I've steadily invested time and energy into extracting powerful outputs from these large language models for both my personal and professional life. I've decided to share these valuable insights here, as I believe a community-driven effort is the most effective way to foster excellent developments in software, hardware, and even groundbreaking ideas.

## Repository Structure

This repository is organized to help you quickly find resources related to Large Language Models (LLMs).

* **[Generative AI Knowledge](generative-ai-knowledge/README.md)**: Dive into core concepts and structures behind generative AI.
    * [Coding Prompt Anatomy](generative-ai-knowledge/coding-prompt-anatomy.md): Learn the components of effective prompts for code generation.
    * [Prompt Anatomy](generative-ai-knowledge/prompt-anatomy.md): Understand the fundamental building blocks of any good prompt.

* **[Prompt Storage](prompt-storage/README.md)**: A collection of ready-to-use prompts for different use cases.
    * **[AI Profiles](prompt-storage/ai-profiles/)**: Prompts designed to give the AI a specific persona or expertise.
        * [Perplexity Profile](prompt-storage/ai-profiles/perplexity-profile.md): A prompt to make the AI act like Perplexity's conversational search engine.
        * [Gemini Profile](prompt-storage/ai-profiles/gemini-factual-profile.md): This prompt configures the AI to act as a factual engine: it delivers sourced answers and functional code, avoids all opinions, and adds a disclaimer for subjective queries.
    * **[Czech-Focused](prompt-storage/czech-focused/)**: Prompts specifically for Czech language tasks.
        * [Correct Czech Text](prompt-storage/czech-focused/correct-czech-text.md): A prompt to proofread and correct Czech text.
    * **[Text Processing](prompt-storage/text-processing/)**: A suite of prompts for manipulating and summarizing text.
        * [Bullet Point Summary](prompt-storage/text-processing/bullet-point-summary.md): Condense long text into concise bullet points.
        * [Coherent Text Summary](prompt-storage/text-processing/coherent-text-summary.md): Generate a fluent, paragraph-style summary.
    * [Generic Translator](prompt-storage/generic-translator.md): A versatile prompt for general-purpose translation.
    * [Make My English Just Perfect](prompt-storage/make-my-english-just-perfect.md): Enhance English text for clarity, correctness, and style.
    * [Personal Lawyer](prompt-storage/personal-lawyer.md): A prompt to simulate legal assistance or generate legal-style text.
    * [Prompt Expander](prompt-storage/prompt-expander.md): Take a simple idea and expand it into a detailed, structured prompt.
    * [Update Prompt Github Readme](prompt-storage/update-prompt-github-readme.md): The meta-prompt used to update this very README file.

* **[LICENSE](LICENSE)**: Licensing information for this repository.

### How This README Was Generated

This `README.md` is generated automatically. A prompt reads the output of `tree -F --dirsfirst` and builds this navigable file structure. Future updates to this page will be automated using the **[Update Prompt Github Readme](prompt-storage/update-prompt-github-readme.md)** prompt.