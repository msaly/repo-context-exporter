# 📦 repo-context-exporter - Build clean repo context files

[⬇️ Download from GitHub Releases](https://github.com/msaly/repo-context-exporter/releases)

## 🧭 What this app does

repo-context-exporter helps you turn a code repository into a compact Markdown file you can use with an LLM. It can gather the key parts of a project and place them in one easy-to-read context file.

It is made for people who want to:

- export a codebase into one file
- include a source bundle for review
- add a directory tree for quick scan
- prepare cleaner prompts for AI tools
- keep project context in a simple Markdown format

## 💻 What you need

To run this app on Windows, you need:

- A Windows PC
- A web browser
- Permission to download files
- Enough free disk space for the repository you want to export
- A source folder that contains the code you want to process

Most users will only need the release file from GitHub and do not need to set up a developer toolchain.

## 🚀 Download and install

1. Open the releases page here: [https://github.com/msaly/repo-context-exporter/releases](https://github.com/msaly/repo-context-exporter/releases)
2. Find the latest release at the top of the page
3. Under the Assets section, download the Windows file
4. Save the file to a folder you can find again, such as Downloads or Desktop
5. If the file is in a .zip archive, right-click it and choose Extract All
6. Open the extracted folder
7. Double-click the app file to run it

If Windows shows a security prompt, choose the option that lets you run the file

## 🪟 How to use it on Windows

After you open the app, you will usually follow this flow:

1. Pick the repository folder you want to export
2. Choose where the output Markdown file should go
3. Select what you want included in the export
4. Start the export process
5. Wait for the app to finish creating the context file

The app is built to make a repo easier to read in an LLM prompt. A good output usually includes:

- a short project overview
- the folder tree
- key source files
- selected code snippets
- file names and paths
- optional supporting files

## 📁 What the output looks like

The exported Markdown file is designed to stay compact and useful. It usually includes:

- a title for the repository
- a tree view of the directory structure
- grouped file content
- clean Markdown sections
- source text that is easier to paste into an LLM prompt

This format helps you share only the parts of a codebase that matter most.

## ⚙️ Common settings

You may see options like these in the app:

- include or skip hidden files
- set a maximum file size
- choose file types to include
- exclude folders like build output or dependencies
- bundle source files into one export
- add a directory tree to the top of the file

These settings help keep the exported context small and readable.

## 🧩 Best ways to use it

Use repo-context-exporter when you want to:

- ask an LLM about a codebase
- make a compact handoff file for a teammate
- review a project without opening many files
- collect code context for debugging
- prepare a prompt with source files and folder structure

It works well for small projects and larger repositories where you only need the most useful parts.

## 📌 Tips for a good export

- Use a clean source folder
- Remove files you do not want in the output
- Keep large build folders out of the export
- Pick only the file types that matter
- Use the directory tree to help navigate the project
- Save the output in a clear folder name

If you want a prompt-ready result, keep the export focused on the code that answers your question.

## 🛠️ Troubleshooting

### The file does not open

- Make sure you downloaded the Windows release
- Check that the file finished downloading
- If the app came in a zip file, extract it first
- Try running it again from the extracted folder

### Windows blocks the app

- Right-click the file
- Open Properties
- Look for an Unblock option, if present
- Apply the change and run the app again

### The export is too large

- Exclude big folders like node_modules, dist, build, or target
- Limit the file types you include
- Skip files that are not needed for the task
- Use a smaller source folder if possible

### The output is missing files

- Check the folder filter settings
- Make sure the files are not excluded
- Confirm the file type is included
- Verify the source folder path is correct

## 📚 Typical workflow

1. Download the release from GitHub
2. Open the app on Windows
3. Select the repository folder
4. Choose export options
5. Generate the Markdown context file
6. Open the output in a text editor
7. Paste the file into your LLM prompt

## 🔗 Download

Visit this page to download the Windows release: [https://github.com/msaly/repo-context-exporter/releases](https://github.com/msaly/repo-context-exporter/releases)

## 🗂️ Repository topics

automation, cli, codebase-analysis, context-extraction, developer-tools, llm, markdown, prompt-engineering, python, repository-tools