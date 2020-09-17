# Slack-Emojis

![snyk](https://img.shields.io/snyk/vulnerabilities/npm/slack-emojis?style=for-the-badge)
![package version](https://img.shields.io/npm/v/slack-emojis?style=for-the-badge)
![package version](https://img.shields.io/npm/l/slack-emojis?style=for-the-badge)
![Downloads](https://img.shields.io/npm/dt/slack-emojis?style=for-the-badge)
![Is Maintained](https://img.shields.io/badge/Maintained-Yes-green?style=for-the-badge)

This packages exposes all the possible emojis available in a slack chat.

# Possible Usages
One out of many possibilities is that you are writing a webhook feature which integrates with slack and you would like to use emojis,
you would have to use a magic string in your code(e.g :boom:).

`slack-emojis` is here for the rescue!

# Package Usage
```
const slackEmojis = require('slack-emojis');
console.log(slackEmojis.RELAXED); // outputs :relaxed:
```
