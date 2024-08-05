---
tags:
  - index
---

# My Obsidian Workflow

Even the longest journey starts with a single step. I was searching for a way to organize knowledge and remember it, and there are many very good systems that can help. The best option might be to find a system you like and then customize and reorganize it to fit your needs.

## Directories

> [!Note] Underscores and Private Directories
> Inspired by the programming concept of private variables, these directories are used by the system to store things that the general public (or readers) need not bother with. Examples include:
> - `_assets`: Storage of images or other files used in notes
> - `_templates`: Storage of note templates
> - `_calendar`: Storage of daily notes
> - And so on...

- **00_Fleeting_inbox**
    - Fleeting notes or inbox directory is a place where fresh notes start. This is a starting point for notes that still need to be refined, quick thoughts, and work in progress. Conduct a weekly review; completed notes should move forward into one of the following categories.

- **01_Reference**
    - This directory is for practical knowledge. From tools and software to life and philosophy, reference notes are direct notes from someone else's work. They should have a front matter written in YAML with properties like tags, source, and author.

- **02_Ideas_and_projects**
    - These are my own ideas and personal thoughts. A place to start and manage personal projects, akin to a cooking pot with different ingredients, almost ready to be served. Unlike references, these are my own views on particular subjects which can but don't have to be right.

- **03_Knowledge**
    - Here I have broader texts about single topics—a permanent knowledge base. Even though I can consider this to be a complete set of articles or texts, I will always expand and adapt each article as I learn more about the subject. Think of it as a living organism, providing a high-level overview of certain areas.

- **04_Expressions**
    - After collecting enough knowledge and different ideas, when there is enough to encapsulate written words into my own expressions, I will share them online. This is the directory where everything comes together.

- **05_Archive**
    - **Never delete notes, archive them**
    - Place for all notes that you wish to remove from the current structure. Never delete them; keep them in the Archive so you can search them, read them, and maybe even revive them in the future.

## Plugins

- **Dataview**
    - Treat your Obsidian Vault as a database which you can query. Create dynamic views of your notes. For instance, you can create a table of all notes tagged with `#project` or a list of all `#reference` notes with a specific tag. It provides a JavaScript API and pipeline-based query language for filtering, sorting, and extracting data from Markdown pages. More info can be found at [GitHub](https://github.com/blacksmithgu/obsidian-dataview).

- **Templater**
    - Templater is a template language that lets you insert variables and function results into your notes. It also lets you execute JavaScript code manipulating those variables and functions. With Templater, you can create powerful templates to automate manual tasks. Documentation is available at [silentvoid13.com](https://silentvoid13.github.io/Templater/).

- **Excalidraw**
    - The Obsidian-Excalidraw plugin integrates Excalidraw, a feature-rich sketching tool, into Obsidian. You can store and edit Excalidraw files in your vault, embed drawings into your documents, and link to documents and other drawings. For a showcase of Excalidraw features, browse the [GitHub repository](https://github.com/excalidraw/excalidraw).

## Linking Notes

I'm still looking for a well-structured way to link notes. Options include:
- Footnotes with all possible relations
- Tags and front matter
- Inline styled wiki links

Each method has pros and cons. Currently, the most organized approach seems to be a combination of front matter tags and linking everything at the bottom as a footnote or reference section.
