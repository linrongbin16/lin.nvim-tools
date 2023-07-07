# lin-nvim-colorscheme-collector

Auto-tool to collect color schemes for [lin.nvim](https://github.com/linrongbin16/lin.nvim).

## Dependency

```bash
pip3 install selenium
pip3 install tinydb
```

## Usage

```bash
./start
```

or

```bash
python3 fetch.py
python3 clone.py
python3 build.py
```

## Output

- [output/color-plugins.lua](https://github.com/linrongbin16/lin-nvim-colorscheme-collector/blob/e02f431120e7f3a3b823d34bf2e2f065e4af15e1/output/color-plugins.lua): Color scheme plugins list for plugin manager, e.g. `lazy.nvim`.
- [output/dark-color-names.lua](https://github.com/linrongbin16/lin-nvim-colorscheme-collector/blob/e02f431120e7f3a3b823d34bf2e2f065e4af15e1/output/dark-color-names.vim): Dark color scheme names as candidate list.
- [output/primary-colors.lua](https://github.com/linrongbin16/lin-nvim-colorscheme-collector/blob/e02f431120e7f3a3b823d34bf2e2f065e4af15e1/output/primary-color-names.vim): Primary color scheme names as candidate list.
- [repo.json](https://github.com/linrongbin16/lin-nvim-colorscheme-collector/blob/e02f431120e7f3a3b823d34bf2e2f065e4af15e1/repo.json): File-based database for building color schemes list.
