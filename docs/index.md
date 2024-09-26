# Director Style Sheets (DSS)

!!! note "Clarification"

    This is the core specification docs. Any supported implementation can be found [here](https://github.com/orgs/DirectorStyleSheets/repositories).

## Introduction

Stories are a fundamentally human activity. Fundamentally, sharing stories are the act of compressing complex, multi-sensory ideas into a format that can move others.

Unfotunately, with the advent of generative AI, this societal standard has become overly simplified - resulting in a wave of ill-formated stories. These tools have created an ecosystem with 4 main issues.

1. **Inconsistent Output:** Generative AI commonly produces unpredictable results. Users often have to try multiple times ("re-roll") to get satisfactory output, making the process inefficient and frustrating.
2. **Interoperability Issues:** AI systems use proprietary methods of interfacing, making it hard to integrate them without significant rework. This lack of a common language hinders collaboration and complicates the creation of larger projects with multiple systems.
3. **Limited Control:** AI mostly relies on simple text prompts, which don’t offer fine control over creative elements like cinematography or character design. This often results in outputs that don’t fully match the user’s expectation.
4. **Black Box Effect:** Without a standardized way to interact with AI, users can’t see how their inputs are interpreted, leading to unpredictable outcomes. This "black box" nature of AI can cause outputs to diverge significantly from the user's intent.

DSS is a framework that attempts to solve these problems by defining a standard way for creators to communicate their ideas, whether they’re working with AI tools or human collaborators.

## Breakdown

We separate out 2 core concepts of the standard, defined by [assets](#assets) and [story](#story). These pieces can be thought of as the ingredients to a meal (_assets_) and the instructions that declare how these come together (_story_).

### Assets

The _assets_ structure is where all of your created content and accomponying information sit. Character model files, dialog audio, sound effects, sets, and more. These components will be referenced by the _story_ structure to create your true masterpiece.

Dig into the assets definition here.

### Story

The _story_ structure is designed to be a timeline of commands that any renderer could implement to display your story.

Explore the usable commands here.

---

Further reading can be found in <a href="https://pickfordai.medium.com/pickford-dev-blog-003-2d421151e515" target="_blank">this blog post</a>.

Any questions should be directed to [cole@pickford.ai](mailto:cole@pickford.ai?subject=DSS Interest).
