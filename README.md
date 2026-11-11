# goda-cmp-ui-native.vim

The UI `native` of [goda-cmp.vim](https://github.com/Shougo/goda-cmp.vim):
Vim's popup menu (ddc-ui-native).

## Requirements

- [goda-cmp.vim](https://github.com/Shougo/goda-cmp.vim)

## Usage

Add it in the configuration of goda-cmp.vim:

```go
import "github.com/Shougo/goda-cmp-ui-native.vim/ext/ui/native"

b.AddUI(native.New())
b.PatchGlobal(cmp.Config{UI: "native"})
```

See `:help goda-cmp-ui-native`.
