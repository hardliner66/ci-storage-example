# CI Storage Example

This is an example repo to show how to use the [CI Storage](https://github.com/hardliner66/ci-storage) action.

## Example Workflow

The example workflow runs the file
[increment-count.sh](./increment-count.sh) and passes the path where the data should be stored
as an argument. The script updates a counter in a JSON file or creates the file if it doesn't exist.
