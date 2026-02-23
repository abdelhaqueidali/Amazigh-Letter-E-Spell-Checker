# Amazigh-Letter-E-Spell-Checker
https://abdelhaqueidali.github.io/Amazigh-Letter-E-Spell-Checker/
A simple pattern-based spell checker for Amazigh written in Latin script (Moroccan orthography). It helps restore missing e letters, which often disappear when Tifinagh is converted to Latin or when writing in Moroccan orthography. So to restore it like the Amgerian orthography, this tool can help doing that.

This tool does not rely on a dictionary or grammatical tagger, thus the changes are always manually checked. No batch or automatic replace for all the words with their suggestions. Each word may have more than one suggestion, onmy one may be correct. 

I always forget the patterns, so I made this tool to help me in doing so, I can easily notoce the correct form and accept it, not having to remember and try to see if it seems suitable.

This tool is just a part of a spell checker. For a full one, one needs to implement part of speech tagger for letter e and dash mark, as well as a dictionary for letter e insertion, and the patterns like these in this tool are probabmy suitable for words not found in the dictionary. 
