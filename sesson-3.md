**Linux Code Editors: Vi**
Here's a simple guide to help you navigate the Vi editor:

1. Open a file by typing `vi filename` in your terminal.
2. To start making changes, press `i` to enter Insert mode.
3. Once you've made the desired modifications, press the `Esc` key to exit Insert mode.
4. To save your changes and exit, type `:wq` and hit Enter.
5. If you want to exit without saving any changes, simply type `:q!` and press Enter.

To view the contents of a file, use the following commands:

- `cat filename` will display the file contents.
- `cat -n filename` will show the file contents along with line numbers.

### Filter Commands for File Manipulation

When working with files in a command-line environment, filtering the content can be incredibly helpful. Below are some essential commands:

- **head**: The `head` command is used to display the first few lines of a file. By default, it shows the top 10 lines. This is useful for quickly reviewing the initial content of a file.

- **head -n 2 [filename]**: You can specify the number of lines you want to see by using the `-n` option. For example, `head -n 2 [filename]` will display just the first 2 lines of the specified file, allowing for a more focused examination of its contents.

- **tail**: Conversely, the `tail` command shows the last 10 lines of a file. This is particularly useful for checking the most recent entries or outputs in a log file or similar document.

- **tail -n 3 [filename]**: Just like with `head`, you can control the number of lines displayed by tailing. Using `tail -n 3 [filename]` will give you the last 3 lines of the specified file, making it easy to capture the latest information at a glance.

These commands offer efficient methods to sift through large files, helping you to quickly access the information you need.

