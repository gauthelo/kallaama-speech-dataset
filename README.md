# KALLAAMA

This repository contains data gathered for the KALLAAMA project.    
This project was funded for 1 year in 2023 by [Lacuna Fund](https://lacunafund.org/).    
It was led by [Jokalante](https://jokalante.com/) (Dakar, Senegal). [Orange Innovation](https://www.orange.com/) (Lannion, France) and [Ecole Polytechnique de Thiès](https://ept.sn/) (Thiès, Senegal) were also involved as stakeholders.    

### Project description 
KALLAAMA was a collaborative project which aims to create resources required for the development of speech technologies. This project is exclusively interested in the three most widely spoken languages in Senegal: Wolof, Pulaar and Sereer.    

This work was carried out with the aim of creating resources that will one day make it possible to access information and all the digital resources available today, simply by querying one's device, using one's voice and language of daily use. This is something that can be done by developing robust speech-to-text (ASR) and text-to-speech (TTS) models, that are fundamental units of voicebots.     
Currently, numerous Senegalese people are excluded from digital information due to the lack of development in this field.    

As a result, this repository provides the created datasets required for the ASR modeling process.    
Resources involve spoken recordings along with orthographic transcriptions, open source text collection gathered from the Web and wordlists along with phonetic transcription. We also provide a grapheme-to-phoneme model trained to phonetize out-of-vocabulary words for Wolof.    

### Data description
The main topic of the recordings is about agriculture.   
Audio files initially belong to Jokalante SARL.     
- The Wolof (ISO Code 639-2: wol) speech dataset contains 55 hours of transcribed speech, including almost 13 hours of validated content check by an expert.    
- The Pulaar (ISO Code 639-2: fuc) speech dataset contains nearly 32 hours of transcribed speech, including almost almost 11 hours of validated content check by an expert.    
- The Sereer (ISO Code 639-2: srr) speech dataset contains 38 hours of transcribed speech, including almost 11 hours of validated content check by an expert.    

In total, we provide 125 hours of transcribed speech, including 35 hours of checked transcriptions.    

### Citation
See the following publication for more details on data collection (please cite the bibtex if you use the data):    
```
@inproceedings{kallaama2024dataset,    
  title={Kallaama: A Transcribed Speech Dataset about Agriculture in the Three Most Widely Spoken Languages in Senegal}    
  author={Gauthier, Elodie and Ndiaye, Aminata and Guissé, Abdoulaye}    
  booktitle={Proceedings of the Fifth workshop on Resources for African Indigenous Languages (RAIL 2024)},    
  year={2024}    
}  
```  

### Repository structure

.    
├── LICENSE    
├── README.md    
└── data/    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ├── README.md    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ├── lexicons/    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ├── text_corpora/    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; └── transcriptions/    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ├── checked/    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; └── raw/    


### Contacts
- Aminata NDIAYE DIALLO (Jokalante, Dakar, Senegal - amina.ndiaye@jokalante.com)
- Elodie GAUTHIER (Orange Innovation, Lannion, France - elodie.gauthier@orange.com)
- Abdoulaye GUISSÉ (École Polytechnique de Thiès, Thiès, Senegal - aguisse@ept.sn)


