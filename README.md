# AltIBMTTSDictionaries
An alternative set of dictionaries for IBMTTS.
Smaller than other dictionaries, but tries to be less agressive about modifying words.
## Standards
Here are some standards I generally like to follow when writing entries for this dictionary.
* If a name is written as two separate capitalized words, it won't be added, as screen readers generally split up the string. An exception can be made if the incorrect case is used enough in the real world, however.
* Words should not be added if they are tied to rules in the synthesizer, because altering the pronunciation will break them, or if the pronunciation is more of a dialectal variation than an error.. Examples of words like this include identification, tied to identification number, exit, and princess (emphasis changes if the word is capitalized and a name follows it). Some dictionary entries that predate this standard can remain because of their real world popularity, though if a rule is discovered that is tied to the default pronunciation, the entries can be removed.
* If a word sounds different in a dictionary than it does when said in context, how it sounds in context should take priority.
* For name pronunciations, ideally the person with the name should be the source on how to pronounce it, or if that can't be found, secondary sources such as news reports could be consulted. Applies to companies and products as well.
* Consider the actual sound of the word along with phonetic correctness. There are some phoneme combinations that can sometimes sound unnatural when said in context, and in those cases it may be appropriate to change phonemes slightly.
## ViaVoice dictionary
This project contains dictionary files specifically optimized for ViaVoice TTS 6.7, the same version used in IBMTTS for Linux, but also available for Windows, which are located in the ViaVoice TTS 6.7 folder in this repository. The ViaVoice dictionaries fix a number of IBMTTS-specific pronunciation issues, and remove over 280 words that IBMTTS pronounces correctly. To use the dictionaries on Linux, rename enumain.dic and enuroot.dic to main.dct and root.dct, respectively, and place them in /var/opt/IBM/ibmtts/dict, or /var/opt/IBM/ibmtts/dict/en, or /var/opt/IBM/ibmtts/dict/en_US. Enuabbr.dic is compatible with IBMTTS as well, and can be renamed to abbreviation.dct.
