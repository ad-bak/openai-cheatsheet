# Simple Cheatsheet Repository

This repository contains a simple cheatsheet. It includes an AI agent that can answer queries based on the information it's provided with. The agent uses OpenAI's GPT-3.5-turbo-1106 model to generate responses.

## Files

- `index.js`: This is the main file where the AI agent is implemented. It uses functions from the `tools.js` and `beta.tools.js` files to gather information and generate responses.
- `beta.index.js`: This is a beta version of the main file where the AI agent is implemented. It uses a different method to run functions and generate responses.
- `tools.js` and `beta.tools.js`: These files contain helper functions used by the AI agent in `index.js` and `beta.index.js` respectively.

## Usage

To use this repository, you need to have an OpenAI API key. Once you have the key, you can run the `agent` function in `index.js` or `beta.index.js` with your query as an argument.

Example:

```js
await agent("What's the current weather in my current location?");
```
