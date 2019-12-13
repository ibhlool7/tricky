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
  - use **https://emojipedia.org/hot-springs/** to choose and copy imoji
  - have fun in vscode and git commits ✌️
