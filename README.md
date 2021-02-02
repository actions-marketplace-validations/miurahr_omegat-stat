# OmegaT statistics report Action

This action script check OmegaT project's `omegat/porject-stats.txt` and report it
as an output variable `coverage` in percent.
When specified a Github token, the action also add a comment to the commit.

## Usage

```yaml
uses: miurahr/omegat-stat@v1
with:
  token: ${{ secrets.GITHUB_TOKEN }}
  min-coverage: 30.0
  target-coverage: 70.0
```
