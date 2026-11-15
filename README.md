# ASCII Christmas Tree

A rotating 3D Christmas tree made entirely of coloured ASCII characters, with
snow, lights, fireworks and a countdown to Christmas.

One HTML file. No dependencies, no build step, works offline.

<p align="center"><img src="screenshot.png" alt="The ASCII Christmas tree" width="380"></p>

## Install

1. Download this repo: **Code > Download ZIP** and unzip it, or

   ```
   git clone https://github.com/Lucas-TR/ascii-christmas-tree.git
   ```

2. Open `index.html` in Chrome or Edge.
3. Press `F` for fullscreen.

It fits any screen, portrait or landscape.

## Make it yours

Add options to the address, for example
`index.html?gifts=Ana,Leo,Mia,Mom,Dad&from=Sam`.

| Option         | What it does                                      |
| -------------- | ------------------------------------------------- |
| `gifts=a,b,c`  | Name tag for each of the five gifts               |
| `msg=...`      | Greeting shown on Christmas Day (`MERRY CHRISTMAS`) |
| `from=Name`    | Signature under the banner                        |
| `countdown=0`  | Hide the countdown                                |
| `fireworks=0`  | No fireworks                                      |
| `fps=30`       | Cap the frame rate on slow machines               |

The same defaults live in the `CONFIG` block at the top of the script in
`index.html`.

## Keys

| Key | Action                           |
| --- | -------------------------------- |
| `F` | Fullscreen                       |
| `C` | Show the code being typed        |
| `H` | Status overlay                   |
| `R` | Grow the tree again              |
