# Discord Translate

A Tampermonkey userscript that adds translation capabilities to Discord's browser interface.

## Features

- **Multiple Translation Engines**: LLM (any OpenAI-compatible endpoint), LibreTranslate, DeepL
- **Bidirectional Translation**: Translate both incoming messages and your outgoing text
- **Easy Integration**: Adds translation buttons directly to Discord's UI

## Installation

### Prerequisites

1. Install [Tampermonkey](https://www.tampermonkey.net/) browser extension
2. Have Discord Web open in your browser

### Install the Script

#### Approach 1

- Install it from [GreasyFork](https://greasyfork.org/en/scripts/543665-discord-translate)

#### Approach 2

1. Open Tampermonkey dashboard
2. Click "Create a new script"
3. Copy and paste the entire script content
4. Save (Ctrl/Cmd + S)
5. Refresh Discord

## Usage

### Configuration

1. Click the translate button in Discord's channel header to open settings
2. Select the preferred translation engine
3. Input your API key and any relevant configurations

### Translating Messages

1. Hover over any message in Discord
2. Click the translate button that appears in the hover toolbar
3. Translation appears below the original message

### Translating Your Input

1. Type your message in any language
2. Click the translate button next to the input field
3. Translation is copied to clipboard
4. Paste (Ctrl/Cmd + V) to replace your text

## Supported Languages

Language support depends on your chosen translation engine:

- **LLM**: Any language supported by your model
- **LibreTranslate**: [See supported languages](https://libretranslate.com/languages)
- **DeepL**: [See supported languages](https://www.deepl.com/docs-api/translating-text/)
