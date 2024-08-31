# UC ENCE260 Style

clang-format/tidy rules for the UC ENCE260 C Programming Style Guidelines Version 1.3, July 2015.

Various rules aren't implemented, but the majority which get enforced by pre-check are.


## Usage

```sh
# clone
git clone https://github.com/HexF/UC-ENCE260-style styleguide

# symlink into your project
ln -s styleguide/.clang-format .clang-format
ln -s styleguide/.clang-tidy .clang-tidy

# Run to re-format code and check styles
clang-format -i file.c
clang-tidy file.c
```
