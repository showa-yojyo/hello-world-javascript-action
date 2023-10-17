# Hello world javascript action

Creating a JavaScript action - GitHub Docs https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: showa-yojyo/hello-world-javascript-action@v1.2
with:
  who-to-greet: 'プレハブ小屋'
```
