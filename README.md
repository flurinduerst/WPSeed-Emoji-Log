## WPSEED EMOJI LOG
**Version 1.3.0** (23.07.2019)

This is a git commit log standard called `WPSEED-EMOJI-LOG`

We all know that a well-crafted Git commit message is the best way to communicate context about a change to fellow developers and our future selves. A diff will tell you what changed, but only the commit message can properly tell you why.

## PHILOSOPHY
When looking at a full page of git-commits it can be hard to get an overview of what was done. By using categorized emojis, we can quickly see what's going on. Instead of using [too many emojis](https://gitmoji.carloscuesta.me/) which takes too much time and leads to inconsistent usage, we're keeping the categories small and simple. Also there are some guidelines on how we write messages.

## EMOJI USAGE
Always use one of the following emojis followed by the category in uppercase when writing a commit subject.

Commit Type | Emoji / Example
----------  | --------------
NEW | 📦  NEW: add navigation html/css
IMPROVE | 💎  IMPROVE: add animation for button hover state
CLEANUP | ✨ CLEANUP: remove unused functions
FIX | 🐛 FIX: position of submit button on mobile devices
HOTFIX | 🚑 HOTFIX: remove faulty comment function - needs update for PHP7
CONTENT | 📚 CONTENT: rename strings at team-page
DOC | 📖 DOC: Update readme
ENVIRONMENT | ⚙️ ENV: Update package.json
RELEASE | 🚀 RELEASE: 2.1.0 (also used for initializing a new repo)




hint: use your Autocomplete Functions (Settings -> Keyoard -> Text on OSX) so you don't have to type/search the emojis:

<img src="/assets/autocomplete.jpg" with="300">


## GENERAL GUIDELINES
* **IMPERATIVE**
  - Make your Git commit messages imperative.
  - Write commit message like you're giving an order.
  - E.g., Use `add` instead of `added`.
  - E.g., Use `create` instead of `creating`.
* **Limit the subject line to 50 characters**
  - Keeping subject lines at this length ensures that they are readable.
* **NO PERIOD**
  - Do not end the subject line with a period. Trailing punctuation is unnecessary in subject lines.
* **USE THE BODY IF NEEDED**
  - If the subject doesn't make 100% clear what was changed, and why, use the body to give context.
* **DO NOT REPEAT THE ACTION-TYPE IF UNNECESSARY**
  - If the leading description-word can be used as part of the commit message, use it.
  - E.g., Use `🐛 FIX: display-bug in navigation` instead of `🐛 FIX: fix display-bug in navigation`
  - E.g., Use `💎  IMPROVE: performance on hover-animations` instead of `💎  IMPROVE: improve performance on hover-animations`


## 🏖 About
Author: Flurin Dürst

License: [WTFPL2](https://en.wikipedia.org/wiki/WTFPL)
