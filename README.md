# AltIBMTTSDictionaries
An alternative set of dictionaries for IBMTTS.
Accepts community contributions, but generally aims to be a minimalist project.
## ViaVoice dictionary
This project contains dictionary files specifically optimized for ViaVoice TTS 6.7, the same version used in IBMTTS for Linux, but also available for Windows, which are located in the ViaVoice TTS 6.7 folder in this repository. The ViaVoice dictionaries fix a number of IBMTTS-specific pronunciation issues, and remove over 300 words that IBMTTS pronounces correctly. To use the dictionaries on Linux, rename enumain.dic and enuroot.dic to main.dct and root.dct, respectively, and place them in /var/opt/IBM/ibmtts/dict, or /var/opt/IBM/ibmtts/dict/en, or /var/opt/IBM/ibmtts/dict/en_US.
# Contributing
If you'd like to contribute words to this dictionary, please create an issue or pull request with the word you would like to be corrected, as well as your suggested pronunciation, and provide sources for it, whether that would be dictionaries, YouTube videos or similar. However, before you suggest a change, make sure that the word you want changed is actually pronounced incorrectly, and that the original pronunciation is not less common but otherwise acceptable, as your entry will get removed if this turns out to be the case. Additionally, entries that will not be accepted include, but are not limited to:
* Domain names, file names, usernames, social media handles and similar words
* Compound words that have very few real world examples, E.G. a compound that only appears on one blog post on one website
* Dictionary entries that could be interpreted as forcing a personal preference on users, E.G. an entry in the main dictionary that expands an abbreviation that you like
* Abbreviation dictionary entries. For various reasons, including the limitations of the abbreviation dictionary format, and the possibility of abbreviations having several meanings and/or conflicting with real words/acronyms, abbreviation dictionary entries are not accepted for any language
* Very large dictionary contributions in one issue or pull request. This project values careful sourcing and quality over quantity, so lots of entries at once, e.g. in the hundreds or thousands, are unlikely to be accepted, unless evidence is provided that the entries match the standards that are expected here

## Letter representation in main dictionaries
In entries that use SPRs, I don't really care how they're written, as long as the resulting pronunciation is valid.  However, in the main dictionary, for consistency and to guard against sentence bugs, letters should be represented by [this set of misspellings](https://github.com/Mohamed00/AltIBMTTSDictionaries/blob/master/doc/main%20dictionary%20spellings.md).
