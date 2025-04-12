# Style Guide for "Intentional Prompting"

This document outlines the writing style, formatting conventions, and structural patterns to maintain consistency throughout the book.

## Chapter Structure

### Standard Sections

Each chapter should include:

1. **Introduction** - A brief overview of the chapter's content and why it matters
2. **Main Content Sections** - The core material divided into logical sections
3. **Key Takeaways** - A summary of the most important points at the end
4. **Moving Forward** - A bridge to the next chapter (except in the final chapter of each part)

### Heading Levels

- **Level 1 (#)**: Chapter title only
- **Level 2 (##)**: Main section headings
- **Level 3 (###)**: Subsections
- **Level 4 (####)**: Used sparingly for nested subsections

## Writing Style

### Voice and Tone

- Use second person ("you") to address the reader directly
- Maintain a professional but conversational tone
- Avoid overly academic language or jargon without explanation
- When explaining complex topics, use analogies and real-world examples

### Formatting Conventions

- **Bold** for emphasis and key terms when first introduced
- *Italics* for secondary emphasis or titles of works
- `Code font` for inline code, variable names, and function names
- Use blockquotes for important notes or asides

## Code Examples

### Formatting

- Use triple backticks with language specification for syntax highlighting
- Include comments to explain non-obvious parts
- Keep examples concise and focused on the concept being taught
- Indent code consistently (4 spaces for Python, 2 spaces for JavaScript)

### Example Structure

```python
# Begin with a brief comment explaining the purpose
def example_function(parameter):
    """Include docstrings for functions in examples"""
    # Add comments for complex logic
    result = parameter * 2
    return result

# Show example usage
result = example_function(5)  # Returns 10
```

## AI-Human Conversation Examples

Format AI-human conversations consistently:

```
**Human prompt:**
```
I'm trying to understand X. Can you explain how it works?
```

**AI response:**
> Your explanation requires understanding Y first.
> 
> Here's how Y works:
> 1. First step
> 2. Second step
> 
> Now for X...
```

## Lists and Enumerations

### Bullet Lists

- Use for unordered collections of related items
- Keep parallel structure (start with same part of speech)
- Capitalize the first word of each bullet
- End each bullet with a period if it's a complete sentence

### Numbered Lists

- Use for sequential steps or prioritized items
- Begin with action verbs when describing steps
- Maintain parallel structure across items
- Include brief explanations after each step when needed

## Tables

Format tables with proper headers and alignment:

| Concept | Description | Example |
|---------|-------------|---------|
| Term A  | Explanation of Term A | `code_example()` |
| Term B  | Explanation of Term B | `another_example()` |

## Images and Diagrams

- Include descriptive captions
- Reference images in the text
- Use consistent style across all diagrams
- Ensure all images are accessible (include alt text)

## Citations and References

- Use consistent citation format (e.g., APA)
- Include DOI when available
- For websites, include access date
- Maintain all citations in references.bib

## Cross-References

- Use Quarto cross-reference syntax for referring to other chapters
- Include page numbers for print version
- Make cross-reference text descriptive

## Terminology

Maintain consistent terminology throughout:

- "AI coding assistant" (not "AI", "LLM", "model", etc.)
- "Intentional prompting" (not "deliberate prompting", "mindful prompting", "intentional coding", etc.)
- "Six-step methodology" (not "six-step process", "six steps", etc.)

## Examples and Case Studies

- Begin with a problem statement
- Show both the process and the solution
- Highlight key learning points
- Connect to broader concepts