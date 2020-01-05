# tricky
Programming trick from code to IDE !!!


## VS code
- expand-region : select code's block based on programming logic with expanding ability.
  1. install **expand-region** plugin
  2. **crtl+shift+p** and open **keyboard shortcuts**
  3. open the JSON file
  4. add following code 
  ```
   {
     "key": "ctrl+w","command": "expand_region", "when": "editorTextFocus"
   },
   {
     "key": "ctrl+shift+w","command": "undo_expand_region", "when": "editorTextFocus && editorHasSelection"
   }
  ```
- emoji
  - install **https://marketplace.visualstudio.com/items?itemName=devzstudio.emoji-snippets**
  - use **https://emojipedia.org/hot-springs/** to choose and copy emoji
  - have fun in vscode and git commits ✌️
##python formatter in vscode
- a boilerplate for python formater
  1. add following text in pipfile:
  ```
  [[source]]
  name = "pypi"
  url = "https://pypi.org/simple"
  verify_ssl = true

  [dev-packages]
  autopep8 = "*"
  pylint = "*"

  [packages]

   [requires]
  python_version = "3.7"
```
  2. use `pipenc sync` in command line
