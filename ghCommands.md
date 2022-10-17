## Transfer files from this repo to ea-ecosystem

```
gh issue list --label "TASK" -L 500 --json number | jq -r '.[] | .number' | xargs -I% gh issue transfer % https://github.com/excelerate-america/ea-ecosystem

```
