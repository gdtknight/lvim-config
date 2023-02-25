# LunarVim Configuration

- `$HOME/.config/lvim/` 디렉토리 내에 위치시킨다.

## Directory Structure

- `ftplugin` : filetype별 설정 파일
- `lsp-settings` : lsp 관련 json 설정 파일
- `lua` : config.lua 에서 참조하는 각종 lua config 파일 위치
- `plugin` : packer (plugin management) 컴파일 파일 저장 위치. (자동생성)
- `config.lua` : Lunar Vim 실행시 자동으로 참조되는 환경설정 내용 저장.

## `lua/configs` Directory

- `basic-key.lua` : LunarVim overall key mapping configuration
- `dap.lua` : Debug Adapter Protocol configuration
- `dbui.lua` : vim-dadbod-ui plugin configuration
- `markdown-preview.lua` : Markdown Preview plugin configuration
- `rest.lua` : rest.nvim plugin configuration
- `symbols.lua` : symbols-outline plugin configuration
- `telescope.lua` : telescope plugin configuration
- `trouble.lua` : trouble plugin configuration

## LunarVim
```bash
LV_BRANCH='release-1.2/neovim-0.8' bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/fc6873809934917b470bff1b072171879899a36b/utils/installer/install.sh)
```
