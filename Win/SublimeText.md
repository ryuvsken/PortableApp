

## MacOS

// [MacOS Key Binding](https://gist.github.com/ihor-lev/120e4c822d145f690f90a3fee77e2e53)

[
  { "keys": ["home"], "command": "move_to", "args": {"to": "bol"} },
  { "keys": ["end"], "command": "move_to", "args": {"to": "eol"} },
  { "keys": ["shift+end"], "command": "move_to", "args": {"to": "eol", "extend": true} },
  { "keys": ["shift+home"], "command": "move_to", "args": {"to": "bol", "extend": true } },
  { "keys": ["command+home"], "command": "move_to", "args": {"to": "bof" } },
  { "keys": ["command+end"], "command": "move_to", "args": {"to": "eof" } },
  { "keys": ["shift+command+home"], "command": "move_to", "args": {"to": "bof", "extend": true } },
  { "keys": ["shift+command+end"], "command": "move_to", "args": {"to": "eof", "extend": true } },
  { "keys": ["alt+m"], "command": "open_markdown_preview" },
]


{
  "ignored_packages":
  [
    "Vintage",
  ],
  "index_files": true,

  // Additional spacing at the top of each line, in pixels
  "line_padding_top": 2,

  // Additional spacing at the bottom of each line, in pixels
  "line_padding_bottom": 2,

  // The number of spaces a tab is considered equal to
  "tab_size": 2,

  // Set to true to insert spaces when tab is pressed
  "translate_tabs_to_spaces": true,
  "theme": "auto",
  "dark_theme": "Default Dark.sublime-theme",
  "light_theme": "Default Dark.sublime-theme",
  "color_scheme": "Mariana.sublime-color-scheme",
}




## Windows

// https://coderap.tistory.com/505

{
  "font_face": "D2Coding",
  /*"font_size": 12,*/
  /*"font_size": 14,*/
  "font_size": 12,
  "line_padding_top": 1,
  "line_padding_bottom": 1,
  "translate_tabs_to_spaces": true,
}
