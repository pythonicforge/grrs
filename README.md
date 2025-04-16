
# grrs

`grrs` is a simple command-line tool to search for a pattern in a file and display the lines that contain it.

<br/>

### Usage

Run the program with the following arguments:

- `pattern`: The pattern to search for in the file.
- `path`: The path to the file to read.

#### Example

```bash
grrs-hardik "search_pattern" /path/to/file.txt
```

This will search for the `search_pattern` in the specified file and print all lines containing the pattern.

#### Dependencies

This project uses the following dependencies:
- [`anyhow`](https://crates.io/crates/anyhow): For error handling.
- [`clap`](https://crates.io/crates/clap): For command-line argument parsing.

#### Error Handling

If the file cannot be read, the program will display an error message with context about the failure.

<br/>

### License

This project is licensed under the MIT License.
