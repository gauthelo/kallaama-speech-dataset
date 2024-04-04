# Transcriptions

## Description
This folder contains transcriptions of recordings.     
- Transcriptions validated by supervisors (someone other than the transcriber) are in `checked/` subfolder.    
- Original transcriptions made by native speaker linguists are in `raw/` subfolder.    
     
For each subfolder (*raw/* and *checked/*), transcriptions are organized by language, in separate folders :     
- `transcriptions_fuc` for Pulaar
- `transcriptions_srr` for Sereer
- `transcriptions_wol` for Wolof   

We provide both TRS (Transcriber format) and STM (NIST format) files.    
Read [3.12 What are the reference transcript data formats?](https://www1.icsi.berkeley.edu/Speech/faq/transfmts.html) for further informations.

### Tree
Folder is organized as follows:    

	.
	├── checked
	│	├── transcriptions-fuc
	│	│	├── stm
	│	│	└── trs
	│	├── transcriptions-srr
	│	│	├── stm
	│	│	└── trs
	│	└── transcriptions-wol
	│		 ├── stm
	│		 └── trs
	└── raw
		 ├── transcriptions-fuc
		 │	├── stm
		 │	└── trs
		 ├── transcriptions-srr
		 │	├── stm
		 │	└── trs
		 └── transcriptions-wol
			  ├── stm
			  └── trs


## Transcription rules

### Disfluencies labelling
- A token starting with `%` should refer to a disfluency, such as hesitations, etc. 
    - Examples of labels: `%e`,  `%hum`
    - Examples in corpus:     
         - *wol_43611.trs:*  **%e** prévision : fra météo :fra yi xibaar yi si jaww ji
         - *fuc_42111.trs:*  **%hum** **%hum** céréal

        
### Loanword labelling
- A token starting with `:` should refer to a language tag. It should comes after a loanword.     
The language tag is composed such as `:<lang_name>`    
    - Example: `accompagnement :fra`
    - Examples in corpus:     
        - *wol_43611.trs:*   météo **:fra** yi xibaar yi si jaww ji
        - *fuc_41812.trs:*  ndokka mo microphone **:fra**
        - *srr_3610.trs:*  Maaga i mbaaga consulter **:fra** météo **:fra** bo andoona ye 

#### Notes 
- We asked to use the ISO 639-2 code for naming the language but it hasn't always been respected. Therefore, you'll also find the ISO 639-1 code.    
    - Example: `accompagnement :fr`
    - Examples in corpus:     
        - *srr_4410.trs:*  a refaanga o manquer **:fr**
        - *wol_4613.trs:*  marketing **:en** 
        - *wol_43112.trs:*  bisimilah **:ar** donc :fra looy yok

- We asked to use a whitespace between the word and the tag, but not between the colon (`:`) and the `lang_name`.     
Nonetheless, we notice that a whitespace have been added sometimes between the lang tag and the colon.    
    - Example: `accompagnement : fra`
    - Examples in corpus:     
        - *fuc_4911.trs:*  tottaaɗo machine **: fra** nani sara mum
        - *wol_4611.trs:*  comme :fra business **: en** 
        - *srr_4210.trs:*  fumier **: fra** feene 

