# LingoMacBar Support

This repository can be used for public LingoMacBar bug reports and feature requests.

## Before opening an issue

Please check whether a similar issue already exists.

For bugs, include enough information to reproduce the problem:

- LingoMacBar version
- macOS version
- translation provider: Google Translate or DeepL
- source and target languages, when relevant
- whether you opened LingoMacBar from the menu bar or keyboard shortcut
- whether selected-text retrieval was involved
- what you expected to happen
- what actually happened
- steps to reproduce the problem
- screenshot or screen recording, when useful

## Selected-text translation issues

LingoMacBar relies on the macOS Accessibility API when retrieving selected text from other applications.

Some applications do not expose their current selection in a way LingoMacBar can access. If the problem only occurs in a specific application, please include that application's name in the issue.

You can still open LingoMacBar and type or paste text manually when selected-text retrieval is unavailable.

## Google Translate or DeepL interface issues

Translation content is provided through Google Translate and DeepL inside the app.

Provider-side interface changes, availability issues, or behaviour changes can occasionally affect the translation view.

When reporting one of these issues, mention:

- which provider was selected
- the affected language pair
- whether the problem also appears when using that provider directly

## Feature requests

Feature requests are welcome when they support LingoMacBar's core goal:

> Make everyday translation on macOS fast and easy without turning it into a full translation workspace.

Please describe the problem you want solved, not only the feature you want added.

## Security issues

Do **not** post security vulnerabilities publicly.

Follow the private reporting instructions in [`SECURITY.md`](SECURITY.md).

## Private support

For requests that should not be discussed publicly, use:

https://mustafaramx.com/contact/
