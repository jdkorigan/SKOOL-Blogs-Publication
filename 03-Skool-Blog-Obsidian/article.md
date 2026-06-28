# Organize your knowledge in the age of AI.

*This post is not directly about Microsoft Fabric â€” it is about organizing our knowledge in the age of AI.*

For several years, I have spent quite a lot of time browsing the Internet to learn, whether on YouTube, LinkedIn, blogs, and so on.

I have spent just as much time looking for ways to retrieve that information later: notes, Chrome shortcuts, organizing videos in YouTube, etc.

A few days ago, I decided to find a system that is more appropriate and better suited to the AI world, especially as Markdown (.md) files have become central to how LLMs and coding agents work. I tested â€œObsidianâ€ (itâ€™s free, and there are many other competitors), and it seems quite good when combined with Codex, Claude, Cursor, and similar tools.

So there is this tool, which according to my sources dates back to 2022 for version 1.0. Here is a summary:

- **Obsidian is a local-first note-taking tool**: your notes are stored on your computer as Markdown files.
- **It helps you build a personal knowledge base**: you can link notes together with internal links, a bit like a personal wiki.
- **It provides a graph view**: you can visualize the connections between your ideas, documents, projects, or concepts.
- **It is highly extensible**: many plugins let you add features such as tasks, calendars, Kanban boards, AI, sync, web publishing, and more.
- **It is popular for documentation and knowledge management**: useful for organizing ideas, preparing articles, managing projects, or structuring technical watch/technology monitoring.

There is a lot of information about this topic on the Internet, but for this post Iâ€™ll take an example from one of Willâ€™s videos, especially one about â€œontologyâ€. If you donâ€™t have the right tools, it becomes difficult to remember whether it was on the YouTube channel, Fabric Dojo, AI Dojo, and so on.

---

## Installation and usage

I'll describe how to install the tool and then how to run a search.

### 1. Download and install Obsidian

Go to the official download page â€” [obsidian.md/download](https://obsidian.md/download) â€” and install the version for your operating system (Windows, macOS, Linux, iOS, or Android).

### 2. Create a Vault

Open Obsidian and create a Vault â€” choose a folder somewhere on your hard drive (for example `C:\Users\...\Documents\My Obsidian Vault`). Obsidian stores all your notes as Markdown files in that folder.

### 3. Create a template

Ask Codex or Claude to prepare a template for you. For example:

*â€œCreate Obsidian Web Clipper templates for YouTube and LinkedIn and export them so I can import them.â€*

In principle, inside your vault you should see a folder structure like this (`Obsidian > My Obsidian Vault > 90 Templates`):

![Vault template folder structure](images/image6.png)

### 4. Install the Obsidian Web Clipper extension

In your browser (Chrome Web Store for me), install the â€œObsidian Web Clipperâ€ extension.

![Obsidian Web Clipper extension](images/image1.png)

### 5. Import both templates into Obsidian

Import both templates via **Web Clipper Imports** â€” click **Options** in the Web Clipper extension to open the window.

![Web Clipper Options menu](images/image7.png)

![Obsidian templates](images/image2.png)

### 6. Capture a YouTube video into the Vault

While watching the video, click to open the Obsidian plugin and add the note to your local Vault.

![Web Clipper on YouTube](images/image3.png)

### 7. Verify the note was created

Check that your note was created successfully â€” open Obsidian and go to **10 Sources** > **YouTube**.

![Note created in Obsidian](images/image4.png)

### 8. Point your coding agent or LLM to the Vault

Tell your coding agent or LLM (for example in `AGENTS.md`) to use Obsidian as searchable memory â€” and where your vault lives. For example:

*â€œUse my Obsidian vault at `C:\Users\...\Obsidian\My Obsidian Vault` as your knowledge base when I ask you to search my notes.â€*

For a search, you can write:

*â€œFabric Ontologies + Will search Obsidian return sourceâ€*

![Source found in Obsidian](images/image5.png)

### 9. Other sources and Markdown files

If you want to do this for LinkedIn or other sources, just try it out and read a bit of the documentation.

Then there is the question of .md files that need to be managed for LLMs, which seems to me an important point to keep in mind for the future.
