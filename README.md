# tikz

Example of using tikzpictures - Render tikzpictures as HTML/SVG to be able to use them in HTMLs or Markdowns.

## Usage

To avoid browser security errors like `Not allowed to load local resource` or `Timeout: Did not receive an init message from worker`, you must serve the files through a local web server rather than opening `index.html` directly as a file.

### Option 1: Using Python

Run the following command in this directory:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

### Option 2: Using Node.js (npx)

```bash
npx serve
```

### Option 3: VS Code "Live Server"

If you use VS Code, you can install the "Live Server" extension and click "Go Live" at the bottom right.

