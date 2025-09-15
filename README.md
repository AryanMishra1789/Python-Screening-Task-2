# Python-Screening-Task-2 AI Debugging Assistant Prompt

# AI Debugging Assistant Prompt

This repository contains a carefully crafted prompt designed to guide AI assistants in helping students debug Python code while promoting independent learning.

## Overview

The prompt transforms AI assistants into effective debugging mentors that guide students toward solutions rather than providing direct fixes. This approach builds critical thinking and problem-solving skills essential for programming.

## Files

- `prompt.txt` - The complete AI debugging assistant prompt ready for implementation
- `README.md` - This documentation with design rationale and usage instructions

## Setup Instructions

1. Copy the content from `prompt.txt`
2. Provide this prompt to any AI assistant (ChatGPT, Claude, Bard, etc.) at the beginning of your session
3. Students can then share their buggy Python code and receive guided debugging assistance
4. The AI will follow the guidelines to provide educational support without revealing solutions

## Design Explanation

### Why I Worded It This Way

**Simple, Action-Oriented Structure**: I used numbered steps because they give the AI a clear workflow while being simple enough to follow consistently across different debugging scenarios.

**Question-Based Approach**: The phrase "ask diagnostic questions rather than pointing out errors directly" ensures the AI guides discovery instead of providing answers. This builds critical thinking skills.

**Positive Framing**: Starting with "acknowledge their effort" creates a supportive learning environment that encourages students to keep trying rather than giving up when they encounter bugs.

### How It Avoids Giving Solutions

**Explicit Prohibition**: The constraint "Never provide corrected code or direct solutions" is stated clearly and unambiguously.

**Process Focus**: By emphasizing debugging techniques rather than fixes, students learn transferable skills instead of getting quick answers.

**Graduated Hints**: Even when students struggle, the prompt specifies "gradually increase your hints but still avoid giving the complete solution" - this prevents the AI from eventually just solving the problem.

### How It Encourages Student-Friendly Feedback

**Collaborative Language**: Words like "helping," "guide them," and "collaborative tone" create a partnership feeling rather than a teacher-student hierarchy.

**Manageable Chunks**: "Focus on one main issue at a time" prevents cognitive overload and reduces frustration.

**Engagement Maintenance**: Ending with questions keeps students actively involved in problem-solving rather than passively receiving information.

## Reasoning

### What tone and style should the AI use when responding?

**Encouraging and collaborative** - Because debugging is inherently challenging and students often feel frustrated when their code doesn't work. By positioning the AI as a supportive study partner rather than an authority figure, we reduce intimidation and create psychological safety for learning.

**Patient but intellectually engaging** - The AI should acknowledge that debugging requires persistence while maintaining academic rigor. This balance is crucial because students need both emotional support and intellectual challenge to develop genuine problem-solving skills. The tone should communicate that debugging is a core programming competency, not just fixing broken code.

**Professional mentorship style** - Similar to how experienced programmers guide junior developers, the AI should demonstrate problem-solving thinking processes while encouraging student participation. This prepares students for real-world collaborative debugging scenarios.

### How should the AI balance between identifying bugs and guiding the student?

**Strategic withholding of direct answers** - The most critical balance is giving enough guidance to prevent complete frustration while withholding enough information to force active thinking. This requires the AI to ask targeted diagnostic questions that reveal student understanding gaps without immediately solving the problem.

**Metacognitive development** - Rather than just fixing code, the AI should help students develop debugging strategies they can apply independently. For example, teaching systematic approaches like "trace variable values," "check boundary conditions," or "verify assumptions" builds transferable skills.

**Graduated scaffolding approach** - Start with broad conceptual questions, then narrow focus based on student responses. If a student answers "I don't know" to "What should happen in this loop?", the AI can then ask more specific questions about loop components. This prevents both overwhelming beginners and under-challenging advanced students.

**Evidence-based support** - The AI should ask students to provide evidence for their reasoning ("What makes you think the error is here?") rather than guessing. This builds analytical thinking essential for complex debugging scenarios.

### How would I adapt this prompt for beginner vs. advanced learners?

**Adaptive questioning depth** - The prompt's question-based structure naturally scales because the same diagnostic questions elicit different levels of response from different students.

**For beginners, focus on fundamental understanding:**
- "What type of data is stored in this variable?" (checking basic concept grasp)
- "What does this error message tell you?" (developing error interpretation skills)
- "Can you trace through each line and tell me what it does?" (building code reading skills)
- More explicit encouragement and validation of partial progress

**For advanced learners, emphasize higher-order thinking:**
- "What assumptions is your code making about the input data?" (edge case thinking)
- "How would you systematically test this function?" (testing strategy development)
- "What would be the most efficient way to debug this?" (debugging methodology)
- Less hand-holding, more expectation of independent analysis

**Universal scaffolding principles:**
- All students benefit from breaking complex problems into smaller components
- Question-based discovery works regardless of prior knowledge
- Encouraging persistence and systematic thinking applies across skill levels
- Focus on debugging process over specific syntax helps everyone develop transferable skills

**Key insight**: Rather than having separate prompts for different levels, this single prompt adapts organically because it focuses on thinking processes rather than delivering information. A beginner's answers to diagnostic questions will naturally lead to more basic follow-ups, while an advanced student's responses will lead to more sophisticated discussions.

## Key Features

- **Educational Focus**: Builds independent debugging skills rather than providing quick fixes
- **Scalable Approach**: Adapts naturally to different student skill levels
- **Clear Constraints**: Prevents solution revelation through explicit guidelines
- **Practical Implementation**: Ready to use with any AI assistant
- **Student Engagement**: Maintains active participation in the learning process

---
