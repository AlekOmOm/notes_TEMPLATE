# Guide to Note Collection Structure

This guide explains how to organize your learning notes using the provided templates.

## Folder Structure

```
topic-name/
├── README.md                       # Main entry point with learning path
├── 01-introduction.md              # First main topic
├── 02-core-concept.md              # Second main topic
├── 02a-core-concept-details.md     # Sub-topic for topic 2
├── 02b-core-concept-advanced.md    # Another sub-topic for topic 2
├── 03-another-concept.md           # Third main topic
├── 04-advanced-topic.md            # Fourth main topic
│   ...
└── assets/                         # Optional folder for images or other assets
    ├── diagram1.png
    ├── diagram2.svg
    └── ...
```

## Naming Conventions

- **Main topics**: Use a two-digit prefix followed by a kebab-case name
  - Example: `01-introduction.md`, `02-core-concepts.md`

- **Sub-topics**: Use the parent topic's number, a letter, and a descriptive name
  - Example: `02a-core-concept-details.md`, `02b-core-concept-advanced.md`

- **Additional levels**: For deeper hierarchies, add another letter
  - Example: `02aa-even-more-details.md`

## Template Usage

### For Main README.md

Use the `README.md` template to create the entry point for your note collection:

1. Replace `[Topic Name]` with your topic
2. Update the learning path to include all your main topics
3. For each path item, include a brief description of what it covers
4. Ensure links point to the correct files
5. Update any prerequisites or target audience information

### For Main Topic Notes (xx-note-name.md)

Use the `xx-note-name.md` template for each main topic:

1. Replace `[Number]` with the topic number (e.g., "1")
2. Replace `[Note Title]` with a descriptive title
3. Replace `[Emoji]` with a relevant emoji
4. Update navigation links to point to previous and next topics
5. Fill out each section with relevant content
6. Add or remove sections as needed for your specific topic
7. Update the Table of Contents to match your sections

### For Sub-Topic Notes (xxa-sub-note-name.md)

Use the `xxa-sub-note-name.md` template for sub-topics:

1. Replace `[Number]` with the parent topic number
2. Replace `[Letter]` with the sub-topic letter (a, b, c, etc.)
3. Replace `[Sub-Note Title]` with a descriptive title
4. Update navigation links to connect to the parent topic and other sub-topics
5. Fill each section with detailed information on the specific sub-topic
6. Ensure examples are practical and relevant
7. Connect back to the main topic in the summary section

## Best Practices

1. **Consistency**: Maintain consistent formatting and structure across all notes
   
2. **Progressive Detail**: Main topics should provide an overview, while sub-topics dive deeper into specific aspects

3. **Practical Examples**: Include relevant code examples and practical applications

4. **Navigation**: Ensure all navigation links work correctly between notes

5. **Completeness**: Each note should be self-contained but connected to the broader learning path

6. **Readability**: Use headings, code blocks, tables, and lists to enhance readability

7. **Emoji Usage**: Use emojis consistently to add visual cues (optional)

## Example Learning Paths

### Web Development Framework

```
framework-fundamentals/
├── README.md
├── 01-introduction.md
├── 02-core-components.md
├── 02a-component-lifecycle.md
├── 02b-component-composition.md
├── 03-state-management.md
├── 04-routing.md
├── 05-data-fetching.md
├── 06-deployment.md
└── 07-best-practices.md
```

### Programming Language

```
language-mastery/
├── README.md
├── 01-introduction.md
├── 02-syntax-basics.md
├── 03-data-structures.md
├── 03a-arrays-and-lists.md
├── 03b-maps-and-dictionaries.md
├── 03c-sets-and-trees.md
├── 04-functions.md
├── 04a-closures.md
├── 04b-higher-order-functions.md
├── 05-object-oriented-programming.md
├── 06-asynchronous-programming.md
├── 07-advanced-topics.md
└── 08-practical-projects.md
```

### Database System

```
database-system/
├── README.md
├── 01-introduction.md
├── 02-data-modeling.md
├── 03-querying.md
├── 03a-basic-queries.md
├── 03b-advanced-queries.md
├── 03c-optimization.md
├── 04-transactions.md
├── 05-indexing.md
├── 06-scaling.md
├── 07-security.md
└── 08-best-practices.md
```
