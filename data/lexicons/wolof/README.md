## Pronunciation lexicon ##

### Folder tree

    .    
    ├── README.md    
    ├── wol_g2p_ipa.fst    
    ├── wol_g2p_xsampa.fst    
    └── wol_lexicon.xsampa.txt       

### File description

- **wol\_g2p\_xsampa.fst**: the G2P model trained from the lexicon provided in the OpenSLR archive [SLR25](https://www.openslr.org/resources/25/).     
It has been trained using [Phonetisaurus](https://github.com/AdolfVonKleist/Phonetisaurus) toolkit. 
Phonetisaurus allows to train and phonetize wordlists thanks to grapheme-to-phoneme FST models.     
This model is used to generate phonetic transcriptions of a words from a list.     
Output phonetic symbols will be in [X-SAMPA alphabet](https://en.wikipedia.org/wiki/X-SAMPA).    
    
- **wol\_g2p\_ipa.fst**: another G2P model but output phonetic symbols are [IPA](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet) characters.    

- **wol\_lexicon.xsampa.txt**: 49,132 phonetised entries from wolof text corpus and transcriptions (phonemes in X-SAMPA characters).

