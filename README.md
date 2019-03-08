## WPSEED EMOJI LOG
**Version 1.0.1** (08.03.2019)

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
DOC | 📖 DOC: Update Readme
RELEASE | 🚀 RELEASE: 2.1.0 (also used for initializing a new repo)




hint: use your Autocomplete Functions (Settings -> Keyoard -> Text on OSX) so you don't have to type/search the emojis:

<img src="/assets/autocomplete.jpg" with="300">


## GENERAL GUIDELINES
* **IMPERATIVE**
  - Make your Git commit messages imperative.
  - Write commit message like you're giving an order.
  - E.g., Use `Add` instead of `Added`.
  - E.g., Use `Create` instead of `Creating`.
* **Limit the subject line to 50 characters**
  - Keeping subject lines at this length ensures that they are readable.
* **Capitalize the subject line**
  - Begin all subject lines with a capital letter. Write `Remove unused functions` instead of `remove unused functions`
* **NO PERIOD**
  - Do not end the subject line with a period. Trailing punctuation is unnecessary in subject lines.
* **USE THE BODY IF NEEDED**
  - If the subject doesn't make 100% clear what was changed, and why, use the body to give context.

## 🏖 About
Author: Flurin Dürst

License: [WTFPL2](https://en.wikipedia.org/wiki/WTFPL)
