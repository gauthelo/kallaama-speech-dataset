# Data

### Description
This directory contains the whole data collected during the KALLAAMA project.    
It is composed of texts gathered from the Web, orthographic transcriptions of audio, and a phonetic transcriptions of words in the 3 most widely spoken languages in Senegal: Wolof, Pulaar and Sereer.    
It is organized as follows:    

.    
├── lexicons/    
├── text_corpora/    
└── transcriptions/    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ├── checked/    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; └── raw/    

       
### Composition
- **lexicons/**    
    - This folder contains the data relative to word pronunciation.     
    The file is a pronunciation lexicon, often used in ASR and TTS modeling.     
    Each line consists of a word followed by its phonetic transcription (the pronunciation).    
    We also provide the Grapheme-to-Pronunciation (G2P) model that were trained to generate  phonetic transcriptions from a list of words.    
    
- **text_corpora/**    
    - This folder contains texts gathered from the Web.    
    There is one file per language.    
    
- **transcriptions/**    
    - This folder contains transcriptions of recordings (hosting URL to come).        
    Transcriptions validated by supervisors (someone other than the transcriber) are in *checked/* subfolder.    
    Original transcriptions made by native speaker linguists are in *raw/* subfolder.    
    For each subfolder, transcriptions are organized by language, in separate folders (i.e: `transcriptions_fuc` for Pulaar, `transcriptions_srr` for Sereer, `transcriptions_wol` for Wolof).    
    
     
### Notes
- Textual dataset creation was carried out by Boubacar DIALLO (Université Assane Seck, Ziguinchor, Sénégal) during its final year intership in NLP during the summer 2023 at Jokalante (Dakar, Senegal). Boubacar speaks Pulaar and Wolof.   
 
- Transcription work was carried out by Maimouna DIALLO (Université Cheikh Anta Diop, Dakar, Sénégal) for Wolof, Houleye Amadou KANE (Université Cheikh Anta Diop, Dakar, Sénégal) for Pulaar and Fatou DIOUF (Université Cheikh Anta Diop, Dakar, Sénégal) for Sereer, during their summer internship, as part of their linguistics studies, in 2023 at Jokalante.    
