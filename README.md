## This is my vim config

Configure your vim through the following steps:

* Clone this repository:

	```shell
	cd ~
	git clone https://github.com/wtyuan96/dotvim.git
	```

* Install the latest `nodejs` for `coc.nvim`:

    ``` shell
    wget https://nodejs.org/dist/v16.17.1/node-v16.17.1-linux-x64.tar.xz # replace with latest link from https://nodejs.org/en/download/ 
    sudo apt-get install xz-utils
    sudo tar -C /usr/local --strip-components 1 -xJf node-v16.17.1-linux-x64.tar.xz
    ```

* Install vim plugins via vim-plug by running `PlugInstall` command in vim.

* Install coc extensions by running `CocUpdate` command in vim.

* Sometimes we need to update `vimrc` according to [Example vim configuration](https://github.com/neoclide/coc.nvim#example-vim-configuration) of `coc.nvim`.

* Maybe you should install `jedi-language-server` by `pip install -U jedi-language-server`.
