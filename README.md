Sturdy garbanzo
===============
###### I have no idea what that means :)

Bunch of useful (but not very well documented) PHP tools, including:

  - **phpxt** - toogles xdebug, by (un)commenting extension loading `zend_extension` line
  - **phpsw** *\<version\>* - switches PHP versions between those installed by `brew`, 
                              accepts either `7.0` and `70` as input

Installation
------------

This package can be easily installed by using Composer! Just run:

```sh
composer global require pamil/sturdy-garbanzo
```

If you haven't installed any global binaries, it may be needed to customize your `~/.bashrc` / `~/.zshrc` 
by adding Composer binaries path to your `$PATH` environmental variable:

```sh
PATH="$PATH:/path/to/your/composer/home/vendor/bin"
```

Then just run `source ~/.bashrc` / `source ~/.zshrc` or start a new shell to start using those 
magnificient commands! Have fun!
