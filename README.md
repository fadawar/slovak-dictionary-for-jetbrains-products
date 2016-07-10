# slovak-dictionary-for-jetbrains-products
Slovak dictionary for Jetbrains products (PyCharm, PhpStorm, IntelliJ IDEA...)

## How to build
```sh
sudo apt install aspell-sk
aspell --lang sk dump master | aspell --lang sk expand | tr ' ' '\n' > sk.dic
```