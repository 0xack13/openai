# A go wrapper for OpenAI Platform APIs

This is a wrapper around OpenAI APIs that means to simplify the creation of
tooling that interacts with OpenAI and other Go code in fun, novel ways. There
is also a generic fun cli in `cmd/openai` that exposes library code to the CLI
as well as providing some usage examples for the library.

[Docs](https://pkg.go.dev/github.com/andrewstuart/openai)

```bash
go install github.com/andrewstuart/openai/cmd/openai@latest

openai chat --personality "Lady Gaga"
openai chat --prompt "You answer in the style of a super chill surfer from southern california."
```

```go
cli := openai.NewClient(token)

cli.NewC
