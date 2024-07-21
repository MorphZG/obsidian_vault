---
tags:
  - index
---

# My Obsidian Workflow

Even the longest journey starts with a single step. I was searching for way to organise knowledge and remember it somehow and there is a lot of very good systems that can help. But maybe the best option is to find the system you like and then customise it and reorganise it to fit your needs.

## Directories


> [!Note] Underscores and private directories
> This idea is inspired by programming concept of private variables. Something that general public, in this case a reader should not bother with. These are private directories used by a system to store things. Directories like: `_assets` which is used for storage of images or other files used when creating notes. `_templates` to store note templates, `_calendar` for daily notes and so on....


- **00_Fleeting_inbox**
Fleeting notes or inbox directory is a place where fresh notes start. This is a starting point for notes that still needs to be refined, quick thoughts and work under progress.
- **01_Reference**
This directory is for practical knowledge. From tools and software to life and philosophy. Reference notes are direct notes from someone else work. Reference notes should have a front matter written in [[01_Reference/YAML|YAML]] with properties like tags, source and author.
- **02_Ideas_and_projects**
These are my own ideas, personal thoughts about something. Place to start and manage personal projects. Like a cooking pot with different ingredients, almost ready to be served. As opposed to references, these are my own views of particular subject which can but don't have to be right.
- **03_Knowledge**
Here i have more broad texts about single topic. Permanent knowledge base. Even though i can consider this to be a complete set of articles or texts i will always expand and adapt each article as i learn more about the subject. Like a living organism. Maybe like some sort of high level overview of the certain area.
- **04_Expressions**
After collecting enough knowledge and different ideas, when there is enough to encapsulate the written words into expression of my own.  Something i am willing to share to the online word. This is the directory where everything comes together.
- **05_Archive**
**Never delete notes, archive them**
Place for all notes that you wish to remove from the current structure. You never delete them, keep them in Archive so you can search them, read them and maybe even make them alive again. 

## Possible improvements

Improving my Obsidian workflow involves refining the current system, ensuring clarity in categorisation, and enhancing organisation for better efficiency. Here are some possible improvements i could work on.

### Enhance note clarity and organisation

#### Fleeting Notes
- **Daily Review:** Set a specific time each day to review and process these notes. Decide whether they should move to Reference, Ideas_and_projects, or Knowledge.
- **Tagging:** Use specific tags to quickly identify the context of each fleeting note (e.g., `#idea`, `#task`, `#quote`).

#### Reference
- **Consistent Front Matter:** Ensure every note here has a standardised YAML front matter. Consider adding fields like `created_date`, `reviewed_date`, `relevance`, and `related_topics`.
- **Categorisation:** Create sub-directories or use tags for different types of references (e.g., `#software`, `#philosophy`).

#### Ideas and Projects
- **Project Management:** Use templates for different projects to maintain consistency. Include sections like objectives, milestones, tasks, and deadlines.
- **Idea Development:** Use the Zettelkasten method or link related ideas to facilitate deeper connections between notes.

#### Knowledge
- **Hierarchical Structure:** Organise notes into a hierarchical structure with folders and sub-directories for different domains or topics (e.g., `Technology/AI`, `Health/Nutrition`).
- **Note Templates:** Use templates for knowledge notes to ensure consistency, including sections for definitions, key points, insights, and references.

#### Expressions
- **Publishing Checklist:** Create a checklist template for finalising notes before sharing (e.g., proofreading, adding images, ensuring all references are cited).
- **Custom Properties:** Most of expressions will probably go live on multiple platforms but you can add additional properties like `current_reach`, `feedback`, 

## Categorisation strategies

### Decision criteria for categorisation
- **Context-Based Tags:** Use context-based tags to quickly decide where a note should go (e.g., `#draft`, `#final`, `#personal`).
- **Purpose-Driven Categories:** Ask yourself what the primary purpose of the note is. Is it a reference for future use, an idea you're developing, or knowledge you want to solidify?

### SUb-directories and tags
- **sub-directories:** Break down categories into more specific sub-directories. For instance, within `02_Ideas_and_projects`, have sub-directories like `Work`, `Personal`, `Creative`.
- **Tags:** Use tags for cross-referencing and multi-faceted categorisation. For example, a note in `01_Reference` about a new app can have tags like `#software`, `#productivity`.

## Automation and plugins

### Automation
- **Templates:** Use templates for different types of notes to ensure consistency and save time.
- **Daily Note:** Use the Daily Note plugin to capture fleeting thoughts, which can then be categorised later.

### Plugins
- **Dataview:** To create dynamic views of your notes. For instance, you can create a table of all notes tagged with `#project` or a list of all `#reference` notes with a specific tag.
- **Templater** Templater is a template language that lets you insert variables and functions results into your notes. It will also let you execute JavaScript code manipulating those variables and functions. With Templater, you will be able to create powerful templates to automate manual tasks. There is a well written documentation available at [silentvoid13.com/documentation](https://silentvoid13.github.io/Templater/)

## Regular reviews

- **Weekly Review:** Set aside time each week to review your notes in the `00_Fleeting_inbox` and ensure they are properly categorised.
- **Monthly Cleanup:** Once a month, review each main directory (`01_Reference`, `02_Ideas_and_projects`, `03_Knowledge`, `04_Expressions`) and declutter any outdated or redundant notes.

## Visualisation and linking

- **Backlinks:** Leverage Obsidian's backlinking feature to interlink notes, creating a rich web of interconnected knowledge. Using graph to visualise relations can be useful even when creating new content, ideas and projects. Most important connections will probably come from projects and knowledge directories since these can inspire you to complete projects faster and continue with what you started.

>[!Note] Linking systems
>Still looking for well structured way to link notes. Will connections be written as a footnote with all possible relations, will relations come through tags and front matter or just keep it as inline styled wiki link. There is ofcourse pros and cons which i should wage. Somehow most organised seems the combination of front matter tags and linking everything and the bottom, as a footnote or reference section.

## Markdown syntax

Obsidian uses a standard markdown with few of it's own additions: [[01_Reference/obsidian markdown|obsidian markdown]]
