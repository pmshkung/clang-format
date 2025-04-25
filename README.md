# Use clang-format to format code on macOS.
1. brew install clang-format
2. which clang-format
3. cp .clang-format ~/Documents/Workspace/example/
4. cd ~/Documents/Workspace/example/
5. /usr/local/bin/clang-format -i *.[ch]

# Use clang-format to format code on Ubuntu.
1. sudo apt install clang-format
2. which clang-format
3. cp .clang-format ~/Documents/Workspace/example/
4. cd ~/Documents/Workspace/example/
5. /usr/bin/clang-format -i *.c *.h
