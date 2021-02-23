# terraform cloud workspaces action
TBD

## quickstart
To get started with this action:

```yaml
- id: deploy
```

## calls


## contributing
The default version of this action is currently hardcoded to `v1`. If action parameter names are changed, removed, or required new parameters are added then the action version will need to be updated to prevent any dependencies from breaking. Basically, be mindful if making changes to `action.yml`.

See `.github/workflows` for build and publishing instructions.

_NOTE_: GitHub actions does not currently support private actions to be shared across projects. No sensitive information should be hardcoded in this action.

Some useful documetation for creating actions:
- [`action.yml` documentation](https://help.github.com/en/articles/metadata-syntax-for-github-actions)
- [GitHub webhook event types](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/events-that-trigger-workflows#webhook-events)
- [TypeScript definitions for webhooks](https://github.com/octokit/webhooks.js)
