# my-tools

Personal skills and commands.

## comandos/

Shell scripts installed in `~/.local/bin/`.

### project

Manages GitHub projects in `~/workfolder/`.

```
project create <name>   Create a new project and push to GitHub
project start           Select and clone a GitHub repo to work on
project exit            Save all work to GitHub and clean workfolder
```

**Install:**
```bash
cp comandos/project ~/.local/bin/project
chmod +x ~/.local/bin/project
```

**Dependencies:**
```bash
sudo apt install gh fzf -y
gh auth login
```

## skills/

Claude Code skills (`SKILL.md` files), reusable across projects.

### challenge-assertions

General behavioral skill: push back on claims/proposals with reasoning instead of defaulting to agreement.
