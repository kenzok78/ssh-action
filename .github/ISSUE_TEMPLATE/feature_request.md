---
name: Feature request
about: Suggest an idea for this action
title: ""
labels: enhancement
assignees: appleboy
---

## Is your feature request related to a problem?

A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]

## Describe the solution you'd like

A clear and concise description of what you want to happen.

## Example Yaml Config

If applicable, show how you would expect to use the new feature:

```yaml
- name: executing remote ssh commands
  uses: appleboy/ssh-action@v1
  with:
    host: ${{ secrets.HOST }}
    username: ${{ secrets.USERNAME }}
    key: ${{ secrets.KEY }}
    script: whoami
```

## Additional context

Add any other context about the feature request here. Note that SSH connection
behavior (ciphers, timeouts, proxy, etc.) is implemented in
[drone-ssh](https://github.com/appleboy/drone-ssh) - feature requests for
connection behavior may belong there.
