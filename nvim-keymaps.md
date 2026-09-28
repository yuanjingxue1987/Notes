# Neovim Keymaps

Leader: `Space`

## Essentials

- `jk` insert: leave insert mode
- `<F2>` normal/insert: toggle paste mode
- `<Tab>` insert: select next completion item when the menu is visible
- `<Space>hl` normal: toggle highlighted search results
- `<Space>ll` normal: toggle Limelight focus mode

## Claude Code

- `<Space>ac` normal: toggle Claude Code terminal
- `<Space>af` normal: focus Claude Code terminal
- `<Space>ar` normal: resume a Claude session
- `<Space>aC` normal: continue latest Claude session
- `<Space>am` normal: select Claude model
- `<Space>ab` normal: add current buffer to Claude context
- `<Space>as` visual: send selected text to Claude
- `<Space>aa` normal: accept Claude diff
- `<Space>ad` normal: deny Claude diff
- `<Space>ax` normal: close all Claude diffs
- `<C-,>` terminal: hide Claude Code terminal panel

## Window Navigation

- `<C-h>` normal/terminal: move to the left window
- `<C-j>` normal/terminal: move to the lower window
- `<C-k>` normal/terminal: move to the upper window
- `<C-l>` normal/terminal: move to the right window
- `<C-\><C-n>` terminal: leave terminal input mode

## Quitting

- `:q` command: close the current window only
- `:qa` command: quit all Neovim windows
- `:Q` command: close Claude/diff windows, then quit all
- `<Space>q` normal: close the current window
- `<Space>Q` normal: close Claude/diff windows, then quit all

## Files And Search

- `<C-P>` normal: find files
- `<Space>ff` normal: find files
- `<Space>fg` normal: search text with ripgrep
- `<Space>fb` normal: list buffers
- `<Space>fh` normal: file/search history
- `<F7>` normal: toggle NERDTree
- `<F8>` normal: toggle Tagbar

## Markdown

- `<Space>mr` normal: toggle inline Markdown rendering
- `<Space>mp` normal: open rendered Markdown preview split

Commands:

- `:RenderMarkdown toggle`
- `:RenderMarkdown preview`
- `:TSInstall markdown markdown_inline`

## Language / CoC

- `gd` normal: go to definition
- `gy` normal: go to type definition
- `gi` normal: go to implementation
- `gr` normal: find references
- `K` normal: show hover docs
- `<Space>rn` normal: rename symbol
- `[g` normal: previous diagnostic
- `]g` normal: next diagnostic
- `<Space>ap` normal: previous diagnostic
- `<Space>an` normal: next diagnostic
- `<Space>d` normal: open diagnostics list

## Cross-Instance Copy

- `,y` visual: save selection to `/tmp/vitmp`
- `,p` normal: paste from `/tmp/vitmp`

## Insert Abbreviations

- `qw` insert: inserts `jki`
- `qa` insert: inserts `jkla`

## Open This Note

- `:Keymaps`
- `<Space>?`
- `<Space>hk`

## Notes

- Preferred shared copy: `~/dev_environment/Notes/nvim-keymaps.md`
- Local fallback copy: `~/customConfigs/vim_setting/nvim-keymaps.md`
- Run `:PlugInstall` after plugin changes.
- Run `:checkhealth claudecode` if Claude Code does not connect.
- `<Space>fg` needs `ripgrep` installed.

