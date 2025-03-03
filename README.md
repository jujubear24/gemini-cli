
# Gemini CLI

A command-line tool for interacting with the Gemini language model.

## v1.0.0 - Initial Release

This is the initial release of the Gemini CLI tool. It provides a basic command-line interface for interacting with the Gemini language model.

**Features:**

* Send prompts to the Gemini API and display the generated text.
* Supports the `gemini-1.5-flash` or  `gemini-1.5-pro` model.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/gemini-cli.git`
2. Change to the cloned directory: `cd gemini-cli`
3. update the model you want to use in the script
4. Make the script executable: `chmod +x gemini`
5. (Optional) Add the script to your PATH: This allows you to run the tool from anywhere in your terminal. For example, on a Unix-like system, you can add the following line to your shell configuration file (e.g., `~/.bashrc` for Bash, `~/.zshrc` for Zsh):

```bash
`export PATH="$HOME/Desktop/projects/cli-tools/gemini-cli:$PATH"`
```

## Usage

1. Obtain a Gemini API key from Google AI Studio.
2. Set the `GEMINI_API_KEY` environment variable in your shell configuration:

```bash
export GEMINI_API_KEY="YOUR_API_KEY"
```

3. Install "jq" in your shell. This is a command-line JSON processor that will be used to extract the generated text from the API response. You can install "jq" using your system's package manager or by downloading it from the official website.
4. Run the tool:

    ```bash
    gemini "your prompt here"
    ```

## Examples

```bash
gemini "what is the capital of France?"
gemini "write a short story about a cat"
```

## Development Dependencies

This project uses the following linters for code quality:

* ShellCheck
* Bashate
* shfmt

You can install them using:

```bash
brew install shellcheck shfmt
pip install bashate
```

## License

This tool is released under the MIT License.

## Contributions

[Jules Bahahanyi](https://github.com/julesbahanyi)  initiated this project, and we enthusiastically welcome contributions of all kinds! If you find any bugs or have suggestions for improvements, please submit an issue on the GitHub repository.

## Contact

For any questions or inquiries, please contact Jules Bahanyi at <julesbahanyi@gmail.com>.

I hope this helps! Let me know if you have any other questions.
