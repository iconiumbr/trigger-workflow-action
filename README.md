# Trigger workflow action

This action triggers workflow on another repository.

## Inputs

### `token`

**Required** Personal access token.

### `repository`

**Required** Repository to trigger workflow on.

### `workflowId`

**Required** ID of workflow to trigger.

### `branch`

**Optional** Branch to use workflow from. Defaults to `'main'`.

## Example usage

```
uses:@v1
with:
  token: ${{ secrets.PERSONAL_ACCESS_TOKEN }}
  repository: 'owner/repo'
  workflowId: 12345
```
