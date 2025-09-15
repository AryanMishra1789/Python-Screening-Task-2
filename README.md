# Python Screening Task 2 - AI Debugging Assistant Prompt

This repository contains a prompt designed to guide AI assistants in helping students debug Python code while promoting independent learning.

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

**Encouraging and collaborative** - The AI should act as a **supportive study partner**, not an authority figure. This creates a **psychologically safe learning environment** where students feel comfortable asking questions and admitting confusion.

**Patient but intellectually engaging** - Balance **emotional support with academic rigor**. Students need encouragement when debugging becomes frustrating, but also intellectual challenge to develop genuine problem-solving skills.

**Professional mentorship style** - **Demonstrate systematic thinking processes** while encouraging active participation. This prepares students for real-world collaborative debugging scenarios.

### How should the AI balance between identifying bugs and guiding the student?

**Strategic questioning over direct answers** - **Give enough guidance to prevent frustration while withholding enough information to force active thinking**. 

Example: "What happens when you trace through this loop?" instead of "Your loop condition is wrong."

**Process-focused learning** - Help students develop **transferable debugging strategies**:
- Systematic variable tracing
- Assumption verification  
- Boundary condition checking
- Error message interpretation

This builds **metacognitive skills** essential for independent programming.

**Graduated scaffolding** - Start broad, then **progressively narrow focus based on responses**. If student says "I don't know," ask more specific questions about individual components.

**Evidence-based reasoning** - Ask students to **provide evidence for their thinking**: "What makes you think the error is here?" This develops analytical thinking patterns.

### How would I adapt this prompt for beginner vs. advanced learners?

**Adaptive questioning architecture** - The question-based structure **naturally scales with student knowledge** because diagnostic questions elicit different complexity levels from different students.

**For beginners - foundational skills:**
- **Concept verification**: "What type of data is stored here?"
- **Code comprehension**: "Can you trace through each line?"
- **Basic techniques**: Print statements, reading error messages
- **Enhanced encouragement**: More validation and term explanations

**For advanced learners - higher-order thinking:**
- **Critical analysis**: "What assumptions is your code making?"
- **Strategic debugging**: "What's the most efficient approach here?"
- **Independent analysis**: Less scaffolding, higher expectations
- **Professional practices**: Advanced debugging and testing strategies

**Universal principles that ensure success:**
- **Question-based discovery** works at any knowledge level
- **Breaking complex problems down** prevents cognitive overload
- **Focus on thinking processes** builds transferable skills
- **Systematic approaches** develop professional habits

**Key pedagogical insight**: Rather than requiring separate prompts for different skill levels, this single prompt **adapts organically through responsive questioning** because it focuses on thinking processes rather than delivering information. A beginner's responses naturally lead to more fundamental follow-ups, while an advanced student's answers enable more sophisticated technical discussions.

## Key Features

- **Educational Focus**: Builds independent debugging skills rather than providing quick fixes
- **Scalable Approach**: Adapts naturally to different student skill levels
- **Clear Constraints**: Prevents solution revelation through explicit guidelines
- **Practical Implementation**: Ready to use with any AI assistant
- **Student Engagement**: Maintains active participation in the learning process

---
