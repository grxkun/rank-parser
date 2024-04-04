# rank-parser

```markdown
# Rank Parser

This Rust program parses and ranks open-source software (OSS) registered at the Tea Protocol based on security and the absence of evil code.

## Installation

1. Make sure you have Rust installed. If not, you can install it from [rustup.rs](https://rustup.rs/).

2. Clone this repository:

    ```bash
    git clone https://github.com/grxkun/rank-parser.git
    ```

3. Navigate to the project directory:

    ```bash
    cd rank-parser
    ```

4. Use Cargo to build the project and install dependencies:

    ```bash
    cargo build --release
    ```

5. Add dependencies from the app.tea.xyz registry to your `Cargo.toml`. For example:

    ```toml
    [dependencies]
    reqwest = "0.12.2"
    scraper = "0.19.0"
    cornfig = "0.3.0"
    ```

   Replace `"example-package"` with the actual name of the package and `"1.0.0"` with the desired version.

## Usage

To run the program, execute the following command:

```bash
cargo run
```

The program will fetch data from the Tea Protocol registry, parse it, rank the OSS projects based on security and the absence of evil code, and then display the ranked list.

## Example Output

```
1. Project A: Score: 9.5
2. Project B: Score: 8.2
3. Project C: Score: 7.9
...
```

## Dependencies

- [reqwest](https://crates.io/crates/reqwest): HTTP client for making requests.
- [scraper](https://crates.io/crates/scraper): HTML parsing library.
- Add dependencies from app.tea.xyz here

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE).
```
