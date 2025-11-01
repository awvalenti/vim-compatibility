# vim-compatibility

## legend
- ✅ full support
- 🟡 partial support
- 🚫 no support, ignores it
- ❗ no support, handles incorrectly
- 💥 blows up
- ⚪ don't know

## categories

### mappings
| feature                     | code | eclipse | idea | lin term | lin gvim | win term | win gvim |
|-----------------------------|------|---------|------|----------|----------|----------|----------|
| `<A-🎹>`                    | ⚪   | ✅      | ⚪   | ✅       | ✅       | ✅       | ✅       |
| `<C-S-🎹>`                  | ⚪   | ⚪      | ⚪   | 🚫       | ✅       | ❗       | ❗       |
| `<C-A-🎹>`                  | ⚪   | ⚪      | ⚪   | ❗       | ✅       | ⚪       | ⚪       |
| `<C-A-S-🎹>`                | ⚪   | ⚪      | ⚪   | ❗       | ✅       | ⚪       | ⚪       |
| `<expr>`                    | 🚫   | 💥      | ⚪   | ✅       | ✅       | ✅       | ✅       |
| `<Cmd>`                     | 🟡   | 🟡      | ❗   | ✅       | ✅       | ✅       | ✅       |
