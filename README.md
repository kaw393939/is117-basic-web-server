# Part 4: Routes and status codes

This is the **completed worked example** for Part 4 of IS117's first web server textbook. The current branch is `learn/04-routes-and-status`.

**Checkpoint:** Check two successful pages and a missing page with status 404.

## Read, then build

Start with [this part's lesson](docs/lessons/04-routes-and-status.md). It explains the commands, code, expected output, and practice steps. Build the lesson in your own `is117-web-server` folder; use this separate `is117-reference` clone to compare completed work.

Start your own work from Part 3. This reference branch already includes earlier parts and this part's completed changes; do not run `npm init` again in the reference clone.

## Run this reference

Install the tools using [setup](docs/setup.md). Open a terminal in this repository folder, then run these commands one at a time:

```bash
npm ci
npm start
```

`npm ci` installs the versions in this branch's lockfile. Use it in the reference clone after switching branches; use `npm install` when building your own project and adding packages.

The server prints `Server running at http://localhost:3000`. Keep it running while visiting that address in your browser. Press **Ctrl+C** in the terminal to stop it.

There are no Jest tests at this checkpoint; testing begins in Part 5.

Also visit `/about` for the server explanation and `/missing` for `Page not found.` with status `404`.

## Read the parts completed so far

- [Part 1: Node and the terminal](docs/lessons/01-node-and-terminal.md)
- [Part 2: An npm project](docs/lessons/02-npm-project.md)
- [Part 3: Your first web server](docs/lessons/03-first-server.md)
- [Part 4: Routes and status codes](docs/lessons/04-routes-and-status.md)

## Continue

After completing the lesson and saving your work, read [Part 5](https://github.com/kaw393939/is117-basic-web-server/blob/main/docs/lessons/05-first-test.md). The next reference branch is [`learn/05-first-test`](https://github.com/kaw393939/is117-basic-web-server/tree/learn/05-first-test). Stop any running server, check `git status`, and follow [branch navigation](docs/branches.md) before switching.

[Setup](docs/setup.md) · [Branch navigation](docs/branches.md) · [Glossary](docs/glossary.md) · [Troubleshooting](docs/troubleshooting.md)
