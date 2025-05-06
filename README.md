# FastLLM-JS

[FastLLM](https://github.com/Rexhaif/fastllm) - High-performance parallel LLM API request tool with support for multiple providers and caching capabilities, ported to JavaScript for Node.js and Bun runtimes.

## Features

- **Parallel request processing** with configurable concurrency
- Process **20,000+ prompt tokens per second** and **1,500+ output tokens per second** even for extremely large LLMs
- Built-in **caching support** (in-memory and disk-based)
- **Progress tracking** with token usage statistics
- Support for multiple **LLM providers** (OpenAI, OpenRouter, etc.)
- OpenAI-style API for **request batching**
- **Retry mechanism** with configurable attempts and delays
- **Request deduplication** and response ordering

## Installation

Using npm:

```bash
npm install fastllm-js
```

Using yarn:

```bash
yarn add fastllm-js
```

Using Bun:

```bash
bun add fastllm-js
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
