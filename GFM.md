# GitHub Flavored Markdown
### Syntax Highlighting
---
#### SH of javascript
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
#### simple code indentation by 4 spaces
    Fun = fun() ->
            io:format("Boom"),
            io:format("Blasted")
          end.
#### SH of erlang code
```erlang
Fun = fun() ->
        io:format("Boom"),
        io:format("Blast!!!")
      end.
```
#### SH of elixir code
```elixir
name = "abc"
sample = fun ->
          IO.puts "hi #{name}"
          IO.puts "welcome to elixir world!"
         end
```
### Tasks Lists
---
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Tables
---
Firat Header | Second Header
-------------|--------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

### Username @mentions
---
@ShivaKumarT
### Automatic linking for URLs
---
http://www.github.com/
### Strikethrough
---
~~Strikethrough~~

