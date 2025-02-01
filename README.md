
# Gemini CLI

A command-line tool for interacting with the Gemini language model.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/gemini-cli.git`
2. Make the script executable: `chmod +x gemini-cli/gemini.sh`
3. (Optional) Add the script to your PATH: This allows you to run the tool from anywhere in your terminal.

## Usage

1. Obtain a Gemini API key from Google AI Studio.
2. Set the `GEMINI_API_KEY` environment variable in your shell configuration:

    ```bash
    export GEMINI_API_KEY="YOUR_API_KEY"
    ```

3. Run the tool:

    ```bash
    gemini.sh gemini "your prompt here"
    ```

## Examples

```bash
gemini gemini "what is the capital of France?"
gemini gemini "write a short story about a cat"
