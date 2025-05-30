This repository is intended to reproduce an issue in Weblate where XLIFF imports would falsely skip some translations.

Please do the following to reproduce this:
- Create a new component in Weblate and use this repository
- Select Localizable.strings for localization
- Export the English translation as XLIFF
- Translate
- Import the XLIFF file.

Now the translation for "Cash & Carry" will be skipped.
