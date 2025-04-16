# Telegram Watchdog Organization

<div align="center">
  
![Telegram Watchdog](https://img.shields.io/github/v/release/Astrian/tg-watchdog?label=Latest%20Release)
![License](https://img.shields.io/github/license/Astrian/tg-watchdog)
![Bot Status](https://img.shields.io/uptimerobot/status/m792170701-ebdaa3087e981bf3114d557f?label=Bot%20Status)

**The modern solution for anti-abuse protection in Telegram group chats**

</div>

## About Us

The Telegram Watchdog organization develops and maintains tools to help Telegram group administrators protect their communities from spam, abuse, and unwanted content. Our flagship product is the Telegram Watchdog bot, a sophisticated solution that verifies new members before they join your groups.

## Our Projects

### Telegram Watchdog Bot

Our main project is a Telegram bot that implements a privacy-first approach to member verification:

- **Private Verification**: Uses private chats to verify users instead of cluttering group conversations
- **Modern CAPTCHA**: Implements Cloudflare Turnstile for effective, user-friendly verification
- **Multilingual Support**: Available in multiple languages including English, Chinese (Simplified and Traditional), Japanese, Russian, and Turkish
- **Privacy-Focused**: Doesn't store or share user data
- **Self-Deployable**: Can be deployed on your own infrastructure for complete control

[Repository](https://github.com/tg-watchdog/tg-watchdog) | [Try the Bot](https://t.me/WatchdogVerifyBot)

### TrustRank

A new reputation system in development, inspired by PageRank, designed to evaluate user trustworthiness within social networks.

- **Innovative Algorithm**: Calculates trust scores based on the endorsements of other trusted users
- **Spam Detection**: Helps identify spam accounts through community feedback
- **Normalized Scoring**: Maps trust scores to a meaningful range using Sigmoid functions
- **Graph-Based**: Leverages the social graph structure to determine user reputation

[Repository](https://github.com/tg-watchdog/trustrank)

## Technical Architecture

Our architecture consists of several components:

- **Backend (Node.js/TypeScript)**: Powers the core functionality of our bots
- **Frontend (Vue.js)**: Handles the web interfaces for verification and administration
- **Verification System**: Integrates with Cloudflare Turnstile for CAPTCHA verification
- **Internationalization**: Supports multiple languages through fluent translations
- **Telegram Bot API Integration**: Communicates with Telegram's bot platform

## Get Involved

We welcome contributions from developers, translators, and Telegram community managers!

### How to Contribute

1. Check out our repositories and documentation
2. Join our [community chat](https://t.me/tgwatchdog_chat) for discussions
3. Submit issues, feature requests, or pull requests on GitHub
4. Help with translations for broader language support

### Resources

- [Documentation](https://tgwatchdog.astrian.moe/)
- [Community Chat](https://t.me/tgwatchdog_chat)
- [Updates Channel](https://t.me/tgwatchdog_update)

## License

Our projects are primarily released under the MIT License, allowing for wide use and adaptation in various contexts.

## Acknowledgements

We are grateful to all contributors, translators, and community members who help make Telegram Watchdog better. Special thanks to those who provide feedback, report issues, and help improve our documentation.

---

<div align="center">
  
**Protecting Telegram communities, one verification at a time.**

</div>
