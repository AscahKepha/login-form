# .gitignore Cheatsheet

This table explains common patterns used in a `.gitignore` file.

| Pattern          | Description                                  | Example Matches           |
| ---------------- | -------------------------------------------- | ------------------------- |
| `*.log`          | Ignore all `.log` files                      | `error.log`, `debug.log`  |
| `.env`           | Ignore environment variable files            | `.env`                    |
| `node_modules/`  | Ignore dependencies folder (Node.js)         | `node_modules/express/`   |
| `*.tmp`          | Ignore temporary files                       | `test.tmp`, `backup.tmp`  |
| `.DS_Store`      | Ignore macOS system files                    | `.DS_Store`               |
| `*.swp`          | Ignore Vim swap files                        | `main.js.swp`             |
| `/dist`          | Ignore the `dist` folder at the project root | `dist/index.html`         |
| `*.zip`          | Ignore zip archives                          | `project.zip`, `code.zip` |
| `!important.txt` | **Include** `important.txt` even if excluded | Overrides ignore rule     |
| `lib/name.file`  | Ignore a specific file in a specific folder  | `lib/name.file`           |
