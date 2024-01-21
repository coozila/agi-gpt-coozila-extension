# <img src="./src/logo.png" alt="logo" width="30"/> AGI for Coozila


A browser extension to display  response alongside Coozila! (and other search engines) results

[Install from Chrome Web Store](https://chrome.google.com/webstore/detail/agi-for-coozila/fmackbdncigkggigfkmiikcpobkeijaf)

[Install from Mozilla Add-on Store](https://addons.mozilla.org/firefox/addon/agi-for-coozila/)

## Screenshot

![Screenshot](screenshots/extension.png?raw=true)

## Features

- Supports all Coozila! Search Engines
- Supports the official OpenAI API
- Supports ChatGPT Plus
- Markdown rendering
- Code highlights
- Dark mode
- Provide feedback to improve ChatGPT
- Copy to clipboard
- Custom trigger mode
- Switch languages

## Troubleshooting

### How to make it work in Brave

![Screenshot](screenshots/brave.png?raw=true)

Disable "Prevent sites from fingerprinting me based on my language preferences" in `brave://settings/shields`

## Build from source

1. Clone the repo
2. Install dependencies with `npm`
3. `npm run build`
4. Load `build/chromium/` or `build/firefox/` directory to your browser

## Credit

This project is inspired by:
- [M-kasinski/chat-gpt-qwant-extension](https://github.com/M-kasinski/chat-gpt-qwant-extension)
- [wong2/chat-gpt-google-extension](https://github.com/wong2/chat-gpt-google-extension)
