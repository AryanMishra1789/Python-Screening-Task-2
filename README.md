# Python Screening Task 2

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
3. Share the buggy Python code and receive guided debugging assistance
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

## Required Reasoning

### What tone and style should the AI use when responding?

**Encouraging and collaborative** - The AI should act as a **supportive study partner**, not an authority figure. This approach reduces intimidation and creates a **psychologically safe learning environment** where students feel comfortable asking questions and admitting confusion without fear of judgment.

**Patient but intellectually engaging** - The ideal balance combines **emotional support with academic rigor**. Students need encouragement when debugging becomes frustrating, but they also require intellectual challenge to develop genuine problem-solving skills. The tone should communicate that **debugging is a core programming competency**, not just fixing broken code, which builds confidence in tackling complex problems independently.

**Professional mentorship style** - Similar to how experienced programmers guide junior developers in real workplaces, the AI should **demonstrate systematic thinking processes** while encouraging active student participation. This prepares students for collaborative debugging scenarios they'll encounter in their careers.

### How should the AI balance between identifying bugs and guiding the student?

**Strategic questioning over direct answers** - The most critical balance involves **giving enough guidance to prevent frustration while withholding enough information to force active thinking**. This requires asking targeted diagnostic questions that reveal understanding gaps without immediately solving the problem. For example: "What happens when you trace through this loop?" instead of "Your loop condition is wrong."

**Process-focused learning** - Rather than just fixing code, the AI should help students develop **transferable debugging strategies** they can apply independently: systematic variable tracing, assumption verification, boundary condition checking, and error message interpretation. This builds **metacognitive skills** essential for independent programming.

**Graduated scaffolding approach** - Start with broad conceptual questions, then **progressively narrow focus based on student responses**. If a student answers "I don't know" to "What should happen in this loop?", the AI can ask more specific questions about individual loop components. This prevents overwhelming beginners while avoiding under-challenging advanced students.

**Evidence-based reasoning** - The AI should consistently ask students to **provide evidence for their thinking** ("What makes you think the error is here?" or "Show me how you traced through this section") rather than allowing pure guessing. This develops the analytical thinking patterns essential for complex debugging scenarios.

### How would I adapt this prompt for beginner vs. advanced learners?

**Adaptive questioning architecture** - The prompt's question-based structure **naturally scales with student knowledge** because the same diagnostic questions elicit different complexity levels of responses from different students. This creates organic differentiation without requiring separate prompts.

**For beginners - foundational skill building:**
- **Concept verification**: "What type of data is stored in this variable?" "What does this error message tell you?"
- **Code comprehension**: "Can you trace through each line and explain what it does?"
- **Systematic approaches**: Emphasize basic debugging techniques like print statements and reading error messages carefully
- **Enhanced encouragement**: More explicit validation of partial progress and explanation of technical terms

**For advanced learners - higher-order thinking:**
- **Critical analysis**: "What assumptions is your code making about the input data?" "What edge cases might cause problems?"
- **Strategic debugging**: "How would you systematically test this function?" "What's the most efficient debugging approach here?"
- **Independent problem-solving**: Less scaffolding, higher expectation of self-directed analysis and solution pathfinding
- **Professional practices**: Introduction of advanced debugging techniques, testing strategies, and code review methodologies

**Universal scaffolding principles that ensure success:**
- **Question-based discovery** works effectively regardless of prior programming knowledge
- **Breaking complex problems into manageable components** helps learners at all levels avoid cognitive overload
- **Focus on thinking processes rather than syntax** builds transferable skills that apply across programming languages and contexts
- **Consistent encouragement of systematic approaches** develops professional debugging habits

**Key pedagogical insight**: Rather than requiring separate prompts for different skill levels, this single prompt **adapts organically through responsive questioning** because it focuses on thinking processes rather than delivering information. A beginner's responses naturally lead to more fundamental follow-ups, while an advanced student's answers enable more sophisticated technical discussions.

## Key Features

- **Educational Focus**: Builds independent debugging skills rather than providing quick fixes
- **Scalable Approach**: Adapts naturally to different student skill levels
- **Clear Constraints**: Prevents solution revelation through explicit guidelines
- **Practical Implementation**: Ready to use with any AI assistant
- **Student Engagement**: Maintains active participation in the learning process

---
