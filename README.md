# Part 5: Your first automated test

This is the **completed worked example** for Part 5 of IS117's first web server textbook. The current branch is `learn/05-first-test`.

**Checkpoint:** Run one passing HTTP test with npm test.

## Read, then build

Start with [this part's lesson](docs/lessons/05-first-test.md). It explains the commands, code, expected output, and practice steps. Build the lesson in your own `is117-web-server` folder; use this separate `is117-reference` clone to compare completed work.

Start your own work from Part 4. This reference branch already includes earlier parts and this part's completed changes; do not run `npm init` again in the reference clone.

## Run this reference

Install the tools using [setup](docs/setup.md). Open a terminal in this repository folder, then run these commands one at a time:

```bash
npm ci
npm test
npm start
```

`npm ci` installs the versions in this branch's lockfile. Use it in the reference clone after switching branches; use `npm install` when building your own project and adding packages.

The server prints `Server running at http://localhost:3000`. Keep it running while visiting that address in your browser. Press **Ctrl+C** in the terminal to stop it.

Expect **one passing test** from `npm test`. Tests start and stop their own server, so `npm start` does not need to be running first.

Also visit `/about` for the server explanation and `/missing` for `Page not found.` with status `404`.

## Read the parts completed so far

- [Part 1: Node and the terminal](docs/lessons/01-node-and-terminal.md)
- [Part 2: An npm project](docs/lessons/02-npm-project.md)
- [Part 3: Your first web server](docs/lessons/03-first-server.md)
- [Part 4: Routes and status codes](docs/lessons/04-routes-and-status.md)
- [Part 5: Your first automated test](docs/lessons/05-first-test.md)

## Continue

After completing the lesson and saving your work, read [Part 6](https://github.com/kaw393939/is117-basic-web-server/blob/main/docs/lessons/06-complete-tests.md). The next reference branch is [`learn/06-complete-tests`](https://github.com/kaw393939/is117-basic-web-server/tree/learn/06-complete-tests). Stop any running server, check `git status`, and follow [branch navigation](docs/branches.md) before switching.

[Setup](docs/setup.md) · [Branch navigation](docs/branches.md) · [Glossary](docs/glossary.md) · [Troubleshooting](docs/troubleshooting.md)
