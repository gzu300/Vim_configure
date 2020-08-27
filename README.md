### This is a simple script on auto configuring my Vim.

### Prerequisites:
1. It's assumed that Vim has been pre-insatlled. YouCompleteMe claimed that it's incompatble with pre-installed Vim on Mac, I haven't encountered this problem. Maybe this is due to Vim is installed in a isolated conda environment.
2. Conda is also recommanded to manage the environment.

### How to it works:
`setup` script can be executed by entering `bash setup` in the terminal. Or you may `chmod setup` to executable script and execute `setup` only.

`vimrc` as it's shown is the copy of `~/.vimrc` file to be replaced. So if you still want to keep a copy of your original `~/.vimrc`, you'll have to manually move it to somewhere else before executing `setup`.

'Go', 'Node.js' and 'cmake' will be installed into your current conda environment. So modify the script accordingly if you are not using conda.

'GOCACHE' path will be changeed to `~/.cache/go-build` directory since the default cache directory is permission restriction.

#### Setting up working envvironment on terminal isn't easy. Hope this will save some effort to configure your Vim.
### Note: This script is still naive and not robust. It's not platform specific. If any improvement you can come up with, feel free to go ahead. You can also make pull request, but I won't garentee to promptly make and action.

