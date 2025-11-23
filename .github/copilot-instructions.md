# GitHub Copilot Instructions for Human Behavior Genetics OER

This repository contains Open Educational Resources (OER) for PSYC 408 Human Behavior Genetics, an advanced undergraduate/introductory graduate course. The materials are primarily educational content in Markdown format, built with Jekyll for web presentation.

## Repository Purpose

This is an educational materials repository containing:
- Weekly lecture notes and reading materials
- Student activities and assignments
- Course project templates and instructions
- Scholarly resources on behavior genetics topics

The content is designed to help students critically evaluate behavior genetics research while considering ethical implications and historical context.

## Writing Style & Tone

When creating or editing content:

### General Principles
- Use an educational, informative tone that is accessible to advanced undergraduates
- Write from a first-person perspective when appropriate (following the author's pedagogical approach)
- Be explicit about the ethical dimensions of behavior genetics research
- Acknowledge the field's problematic history with eugenics and discrimination
- Present content that encourages critical thinking rather than neutral/detached presentation
- Maintain academic rigor while being conversational and engaging

### Voice and Perspective
- Use second person ("you") when addressing students directly in activities and assignments
- Use first person ("I", "we") in lecture notes to reflect the instructor's perspective
- Be clear when presenting facts vs. interpretations or opinions

### Language
- Use American English spelling and grammar
- Define technical terms on first use
- Avoid jargon when simpler terms suffice
- Be precise with genetic and statistical terminology

## Content Guidelines

### Academic Content
- Always cite sources properly using standard academic citation formats
- Distinguish between:
  - Empirical research articles (data-driven studies)
  - Review articles (synthesis of literature)
  - Popular sources (science communication)
- Include DOI links when referencing scholarly articles
- Mark open access articles with "(open access)" notation

### Educational Materials
- Structure learning materials with clear learning objectives
- Provide scaffolding for complex concepts
- Include concrete examples when introducing abstract ideas
- Balance rigor with accessibility

### Ethical Considerations
- Address the ethical implications of genetic research
- Be explicit about how research can be misused
- Include diverse perspectives, especially from marginalized communities
- Discuss disability rights perspectives on genetic research
- Acknowledge uncertainty and ongoing debates in the field

## Markdown Formatting

### File Organization
- Weekly materials go in `week_XX/` directories
- Use descriptive filenames with underscores: `activity_topic_description.md`, `lecture_notes_topic.md`
- Course project files use prefix: `course_project_description.md`
- Templates go in `materials/` directory with prefix: `template_description.md`

### Document Structure
- Use proper heading hierarchy (start with `##` in weekly content since page title is `#`)
- Include descriptive headings that help students navigate content
- Break long content into logical sections

### Links
- Use descriptive link text, not "click here"
- Format external links with full URLs in Markdown: `[Title](https://url)`
- Use relative links for internal repository content
- Include DOIs as full URLs: `[https://doi.org/10.xxxx/xxxxx](https://doi.org/10.xxxx/xxxxx)`

### Lists
- Use numbered lists for sequential steps or processes
- Use bullet lists for non-sequential items
- Maintain consistent list formatting within a document
- Include introductory text before lists

### Code Formatting
- Use code blocks for R code examples with language specification: ` ```r `
- Use inline code formatting for: filenames, variable names, function names, package names
- Include comments in code to explain purpose

### Emphasis
- Use **bold** for important terms or key concepts
- Use *italics* sparingly for subtle emphasis
- Don't overuse formatting - let content speak for itself

## File Types and Purposes

### Lecture Notes (`lecture_notes_*.md`)
- Provide conceptual frameworks and context
- Include historical perspectives
- Explain methodological approaches
- Raise critical questions for consideration

### Activities (`activity_*.md`)
- Provide clear instructions for student tasks
- Specify expected time commitment (typically 1 hour = 1 point)
- Include learning objectives
- Provide evaluation criteria when applicable

### Course Projects (`course_project_*.md`)
- Provide detailed rubrics and expectations
- Include point values and deadlines
- Offer examples or templates
- Explain how assignments build on each other

### Templates (`materials/template_*.md`)
- Provide structured formats for student work
- Include prompts and guidance
- Be clear about what goes in each section

## Special Considerations

### Sensitive Topics
When working with content about:
- Eugenics and scientific racism
- Genetic differences between populations
- Heritability of behavioral traits
- Genetic engineering and selection
- Mental health and disability

Ensure content:
- Provides appropriate historical context
- Acknowledges harm done to marginalized communities
- Distinguishes between scientific findings and their misuse
- Presents multiple perspectives
- Encourages critical thinking about social implications

### Statistical and Genetic Concepts
- Define heritability properly (proportion of variance, not determinism)
- Clarify difference between correlation and causation
- Explain what GWAS findings mean (and don't mean)
- Be precise about genetic vs. environmental influences
- Acknowledge complexity and limitations of methods

### Student Support
- Provide multiple pathways to earn points
- Offer flexibility in assignment choices
- Include resources for mental health and academic support
- Create inclusive learning environment

## Jekyll/Web Considerations

- Front matter is minimal (only `permalink` if needed)
- Content renders on GitHub Pages using Minima theme
- Ensure Markdown is standard and will render correctly
- Images should be in `img/` directory with descriptive names
- Test that links work in both GitHub and Jekyll contexts

## Quality Standards

When reviewing or creating content:
- Ensure factual accuracy of scientific claims
- Verify that citations are complete and accessible
- Check that content aligns with learning objectives
- Confirm that ethical considerations are addressed
- Maintain consistency with existing course materials
- Ensure accessibility of language and concepts

## Don't

- Don't present genetics as deterministic
- Don't ignore the ethical dimensions of research
- Don't use the field's problematic history as just background trivia
- Don't assume all students have the same background knowledge
- Don't create content that could perpetuate scientific racism
- Don't oversimplify complex topics to the point of inaccuracy
- Don't add content without considering its pedagogical purpose
