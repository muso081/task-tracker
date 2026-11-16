# Taskbench

A small browser-based workspace for organizing work by week and task, writing code across multiple files, and running a live preview.

## Use it

Open `index.html` in a modern browser, or enable GitHub Pages for this repository. Add weeks and tasks, create files such as `index.html`, `style.css`, and `app.js`, paste your code into the editor, and choose **Run preview**. Each task keeps its own files. Changes are saved automatically in the current browser using local storage; use Export/Import to move a workspace between browsers.

## React

For a React preview, create an HTML file containing a root element such as `<div id="root"></div>`, then add a `.jsx` file that renders into it. Taskbench loads React 18 and Babel from unpkg in the preview iframe, so React previews require an internet connection. Plain HTML, CSS, and JavaScript previews work without a build step.

The preview runs in a sandboxed iframe and is intended for code you trust. It does not execute Node.js, npm scripts, or server-side code.
