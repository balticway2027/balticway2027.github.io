# Baltic Way 2027 website

The website for the 38th Baltic Way mathematical team contest, Stockholm, 4–8 November 2027.

## How it works

Plain HTML and one stylesheet. There is no build step and nothing to install: every `.html` file in this folder is a page, and `style.css` styles all of them. All links are relative, so the folder works at any address and when opened straight from disk.

On GitHub, a repository named `balticway2027.github.io` in the `balticway2027` organisation is served at `https://balticway2027.github.io/` once Pages is switched on (Settings → Pages → deploy from the `main` branch).

## Editing

- To change text, edit the page's `.html` file. On GitHub, open the file, press the pencil, change the text between the tags and commit.
- Put PDFs (problems, solutions, results) in `files/` and link to them as `files/name.pdf`.
- The menu is repeated in every page, with Home and Schedule on their own and the rest grouped under Information, Contest and People. To add or rename a page, change the `<nav>` block in all of them.
- Text marked "To be announced" is a placeholder.
- The serif typeface is Charter, stored in `fonts/` with its licence. It was downloaded from practicaltypography.com/charter.html. Nothing is loaded from other servers.

## Preview on your own computer

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and go to `http://localhost:8000`.
