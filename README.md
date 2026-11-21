# From Prompting to Reasoning: LLM-Based Long-Form Story Generation

Individual short-story assignment package

## Submission links

Replace these placeholders before submission:

- GitHub repository: https://github.com/SankalpWr/Learning-to-Reason-for-Long-Form-Story-Generation
- Medium article: https://medium.com/@wahanesankalp29/from-prompting-to-reasoning-llm-based-long-form-story-generation-8fd9012944b0?sharedUserId=wahanesankalp29
- SlideShare presentation: https://docs.google.com/presentation/d/1FlBb2NYPedNQ5ch6_XP2FFl34EkvOW1oW-JGfzOU1Ik/edit?usp=sharing
- Presentation video: https://loom.com/share/folder/42b92af32d4549aa9f8d7312d0542bc6

## Topic and research question

This project studies how large language models generate coherent long-form stories. It asks: **How are modern systems moving from one-shot prompting toward structured planning, memory, multi-agent collaboration, and learned reasoning?**

The central technical paper is Gurung and Lapata's COLM 2025 paper, *Learning to Reason for Long-Form Story Generation*. It is paired with recent survey work so that the submission satisfies the survey requirement while still explaining one technically important method in depth.

## Paper set

1. Liu, Joshi, and Dawson (2026), *Narrative theory-driven LLM methods for automatic story generation and understanding: a survey*. Published October 30, 2026. Primary recent survey.
2. Teleki et al. (2025), *A Survey on LLMs for Story Generation*. Findings of EMNLP 2025. Taxonomy reference.
3. Gurung and Lapata (2025), *Learning to Reason for Long-Form Story Generation*. COLM 2025. Anchor research paper.

The anchor paper is a research contribution rather than a survey. The two surveys provide the field-level taxonomy; the anchor paper provides the detailed architecture, reward design, ablations, and human evaluation.

## Folder guide

- `article/medium_article.md` - original Medium-ready article written from scratch
- `article/taxonomy_and_technical_summary.md` - survey taxonomy and technique notes
- `slides/story_generation_deck.pptx` - editable presentation deck
- `slides/story_generation_deck.pdf` - PDF version for recording and submission
- `notes/speaker_script.md` - approximately 10-15 minute narration
- `references/references.md` - source list and access links
- `references/claim_check.md` - factual claim audit and source mapping
- `submission_checklist.md` - final upload checklist

## Main taxonomy

The literature can be organized along five system layers:

1. **Generation mode:** independent LLM authoring versus author-assistance systems.
2. **Planning and control:** direct prompting, outlines, hierarchical planning, chapter planning, and narrative-theory constraints.
3. **State and memory:** global story sketches, summaries, character sheets, retrieved prior chapters, and structured story state.
4. **Collaboration and training:** single-model generation, role-based multi-agent pipelines, supervised fine-tuning, preference optimization, and reinforcement learning with proxy or verifiable rewards.
5. **Evaluation:** human pairwise judgments, coherence and consistency checks, creativity/originality judgments, language quality, and theory-based narrative metrics.

## Originality statement

The article and slides are original synthesis written for this assignment. They paraphrase and compare the cited research rather than reproducing an existing Medium article. Any direct quotations should be added only after checking the source and keeping them brief.

## Publishing note

The package is ready for public GitHub upload. Medium and SlideShare URLs must be added after publishing. The presentation video must be recorded by the student and uploaded separately; the script is included to support a 10-15 minute recording.
