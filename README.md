<div>

# VS Code + Latex + Git Template

![VSLeaf](/.vscode/VSLeaf.png)

> Work In Progress Overleaf Replacement With ACM Template

## Basic Setup

- Make sure you have Latex Installed
  - I like MiKTeX (you'll need perl) but MacTeX, TeX live, TinyTeX, etc. should work
- Then, open this repo in VSCode.
- It should prompt you to install all extensions needed.
  - If not, they're in `extensions.json`
  - The `settings.json` file has some parameters to check out.

## Editor Instructions

- Everything should *hopefully* just work, assuming all the above is done.
- Depending on existing VS Code setup you might have conflicts to resolve.

## Live Collaboration

- In addition to Git Sync, we can also live collaborate with an extension.
- Just click on the **Live Share** Sidebar button
- Share the link, approve, then you can live collaborate and chat etc.

## PDF Viewer

- Pressing `Ctrl+S` will save the document and generate PDF in the **PDF** folder
- To check the generated PDF click "View LaTeX PDF file" in your preview bar or press "Ctrl+alt+v"
- If it shows **Error showing PDF** or in case of any inconvenience, just reload the browser or press `Ctrl+R`
- PDF will autoupdate when saving the tex file, buy you can turn that off in `settings.json`.
- The pdf viewer will preview the pdf in light Mode by default.
- You can **uncomment** the noted lines from `settings.json` to switch to dark.

</div>
