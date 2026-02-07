# My Personal Prompts

A curated collection of AI prompts that I use on a daily basis to enhance productivity, creativity, and efficiency when working with AI assistants.

## Overview

This repository contains professionally crafted prompts designed to optimize interactions with AI assistants across various domains including development, learning, writing, productivity, and more. Each prompt has been tested and refined for real-world usage.

## Categories

Prompts are organized into the following categories:

### Educational
Prompts designed to facilitate learning, teaching, and knowledge transfer.

## Prompts Catalog

### Educational

#### EnglishLearning

**Purpose**: An interactive and adaptive English language tutor that guides you from beginner to advanced levels.

**Description**: This prompt transforms the AI into "LinguaGuide," a professional grammar tutor. It uses a structured 8-level curriculum (A1 to C2) and emphasizes practical conversation through roleplay to reinforce grammatical concepts.

**Key Features**:
- Comprehensive 8-level curriculum covering fundamental to advanced grammar
- Roleplay-based practice to ensure practical application of concepts
- Integrated progress tracking with "Save/Load" functionality
- Personalized feedback and adaptive error correction

**Tested With**:
- Google Gemini 3 Flash (Thinking & Guided Learning Mode)

**File**: [`educational/EnglishLearning.md`](./educational/EnglishLearning.md)

#### LearnFromCodebase


**Purpose**: Transforms your codebase into an educational crash course by automatically generating learning documentation.

**Description**: This prompt configures the AI assistant to act as a "Codebase Tutor" that maintains a `docs/learning.md` file. It extracts programming concepts from your code and explains them using your actual codebase as examples, creating a personalized programming textbook.

**Key Features**:
- Identifies programming concepts, patterns, and architectural choices in your code
- Generates beginner-friendly explanations with real code examples
- Maintains structured documentation covering:
  - Language fundamentals
  - Libraries & frameworks
  - Architecture & design patterns
- Educational approach rather than generic documentation

**Tested With**:
- Google Antigravity
- Claude Sonnet 4.5

**File**: [`educational/LearnFromCodebase.md`](./educational/LearnFromCodebase.md)

#### MultivariateReasoningTeacher

**Purpose**: A Socratic tutor that trains you to think in systems and identify hidden risks, edge cases, and critical failure points in any scenario.

**Description**: This prompt configures the AI assistant to act as "Axiom," a strict but encouraging Socratic tutor focused on teaching Systems Thinking and Multivariate Reasoning. It guides you through a structured curriculum of mental models to develop critical thinking skills.

**Key Features**:
- Structured 5-module curriculum covering:
  - Second-Order Thinking (consequences beyond immediate effects)
  - Inversion & Pre-Mortem (solving problems backwards)
  - Theory of Constraints (identifying system bottlenecks)
  - Probabilistic Thinking (weighted risk assessment)
  - Feedback Loops (compounding effects)
- Interactive exercises with real-world scenarios
- Rigorous feedback and edge case challenges
- Save/resume functionality with progress tracking
- Customizable scenarios based on your field of interest

**Tested With**:
- Gemini 3 Pro

**File**: [`educational/MultivariateReasoningTeacher.md`](./educational/MultivariateReasoningTeacher.md)

## How to Use

1. **Browse Categories**: Navigate through the categories above to find prompts that match your needs.

2. **Choose a Prompt**: Select a prompt from the catalog.

3. **Copy the Prompt**: Open the corresponding `.md` file and copy its contents.

4. **Apply to Your AI Assistant**: Paste the prompt into your AI assistant's system instructions, custom instructions, or chat context.

5. **Start Working**: The AI will now follow the prompt's guidelines when assisting you.

## Compatibility

These prompts are designed to work with modern AI assistants. Compatibility has been verified with:

- **Google Antigravity** - Full compatibility
- **Claude Sonnet 4.5** - Full compatibility

Other AI assistants (ChatGPT, Gemini, etc.) may also work but have not been explicitly tested.

## Repository Structure

```
My-Personal-Prompts/
├── README.md                           # This file
├── educational/                        # Educational & learning prompts
│   ├── EnglishLearning.md             # Adaptive English language tutor
│   ├── LearnFromCodebase.md           # Codebase learning documentation
│   └── MultivariateReasoningTeacher.md # Systems thinking & reasoning tutor
└── [Future categories...]
```

## Contributing

This is a personal collection, but if you have suggestions for improvements or find issues with any prompts, feel free to open an issue.

## License

These prompts are shared for educational and productivity purposes. Feel free to use and adapt them for your own projects.

## Author

**Usama Tariq**

---

**Last Updated**: 7 February 2026
