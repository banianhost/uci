# µCI
The CI that embeds in your containers, Written in pure bash

**Caution: This is an Alpha Release**

## Environment variables

Variable                    | Default           | Description
----------------------------|-------------------|------------------------------------------------------------------
UCI_WORKSPACE               | *pwd*             | Path to where git repo is located, will be created if not exists
UCI_REPO                    | -                 | Path to git repo url. currently only `https` supported
UCI_TOKEN                   | -                 | GitHub Personal Access Token
UCI_HOOK_SCRIPT             | -                 | The script to optionally called on *new* commits
UCI_WATCH_INTERVAL          | 60                | Interval between pulls on *watch* mode
UCI_DEBUG                   | -                 | Enable more verbose logs