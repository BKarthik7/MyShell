
# MyShell

This is a simple shell implemented in Rust that supports basic command execution, pipes (|), and changing directories <code>(cd)</code>. The shell continues to execute commands until you explicitly exit using the exit command.

## Features

- **Command Execution**: Execute basic system commands like <code>ls</code>, <code>echo</code>, <code>cat</code>, etc.
- **Piping**: Supports piping between multiple commands using <code>|</code>.
- **Change Directory**: Allows changing the working directory with <code>cd</code>.
- **Exit**: Exit the shell with the <code>exit</code> command.


## Usage
1. Clone the repository:

```sh
git clone https://github.com/BKarthik7/my_shell.git
cd my_shell
```

2. Install rust (Installation method may be different):

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

```

3. Build the project:

```sh
cargo build
```

4. Run the shell:

```sh
cargo run
```

5. Use the shell interactively:

```bash
> ls
> echo "Hello World" | cat
> cd ..
> exit
```

## Contributing

Contributions are always welcome!

Feel free to contribute by submitting a pull request or opening an issue. Contributions to improve features and fix bugs are always welcome!

## Reference
[Build Your Own X](https://build-your-own-x.vercel.app/)
