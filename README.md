# epsilon-ci-action

Github Action for the Committed Consulting [Epsilon CI Docker image](https://gitlab.com/committed-consulting/mde-devops/epsilon-ci-container/).

This action runs an Ant buildfile inside an [Eclipse Modelling](https://eclipse.dev/modeling/) distribution, with [Eclipse Epsilon](https://eclipse.org/epsilon) installed.

## Inputs

### `build-file`

**Required** The path to the Ant buildfile to run in your repository. Defaults to `build.xml`.

### `target`

**Required** The name of the Ant target to be executed. Defaults to `main`.

## Outputs

This action has no outputs at the moment.

## Example usage

```yaml
uses: committed-consulting/epsilon-ci-action@v1
with:
  build-file: build.xml
  target: main
```
