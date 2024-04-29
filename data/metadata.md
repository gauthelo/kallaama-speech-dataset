# Audio Set Details

## Metadata

### Whole set
|Dataset statistics     |Wolof   |Pulaar  |Sereer  |
|-----------------------|-------:|-------:|-------:|
|Min (sec.)             |21      |20      |25      |
|Max (sec.)             |3,014   |3,033   |3,461   |
|Mean (sec.)            |1,299   |1,384   |1,306   |
|Total audio (h:m:s)    |55:11:41|31:55:10|38:12:10|
|Total speech* (h:m:s)  |51:08:50|30:06:43|36:35:46|
|Female speech* (h:m:s) |05:44:20|03:12:52|07:27:47|
|Male speech* (h:m:s)   |45:24:30|26:53:51|29:07:59|
|Female speech* (%)     |11.22   |10.67   |20.39   |
|Male speech* (%)       |88.78   |89.33   |79.61   |
|#Turn-taking           |46,907  |16,558  |9,007   |
|#Files                 |153**   |83**    |105**   |

*\*extracted from annotations*
*\*\*Number of audio files only (there is the same amount of transcriptions)*

-------------------------------
-------------------------------

### Checked set
|Dataset statistics     |Wolof   |Pulaar   |Sereer   |
|-----------------------|-------:|--------:|--------:|
|Min (sec.)             |21      |117      |444      |
|Max (sec.)             |2,849   |3,033    |2,907    |
|Mean (sec.)            |1,283   |1,472    |1,250    |
|Total audio (h:m:s)    |12:49:35|11:02:28 |11:06:52 |
|Total speech* (h:m:s)  |11:47:34|10:56:15 |10:51:33 |
|Female speech* (h:m:s) |01:15:37|00:10:53 |02:16:41 |
|Male speech* (h:m:s)   |10:31:56|10:45:22 |08:34:51 |
|Female speech* (%)     |10.69   |1.66     |20.98    |
|Male speech* (%)       |89.31   |98.34    |79.02    |
|#Turn-taking           |11,968  |3,583    |1,796    |
|#Files                 |36**    |27**     |32**     |

*\*extracted from annotations*
*\*\*Number of audio files only (there is the same amount of transcriptions)*

-------------------------------
-------------------------------

### Recordings
The recordings  are from various types of programmes and are rated on a scale of 1 to 5 based on their potential complexity for speech processing.
This rating is subjective and takes into account factors such as recording duration, number of talking speakers, and recording conditions.
A rating of 1 indicates relatively low complexity, while a rating of 5 indicates relatively high complexity.

|Type  ID|Type         |Wolof|Pulaar|Sereer|
|:------:|-------------|----:|-----:|-----:|
|1       |push message |9    |1     |0     |
|2       |voice message|0    |0     |14    |
|3       |interview    |22   |10    |15    |
|4       |radio show   |120  |72    |67    |
|5       |focus group  |2    |0     |9     |



## Naming convention
The files of the speech dataset are named according a precise structure.
Filename format: <ISO 639-2 code>\_<type_id>\_<dirname_id>\_<file_id>\_<subpart_number>
- **<ISO 639-2 code>**: either 'wol', 'fuc' or 'srr'.
- **<type_id>**: type of programme (see [Recordings](#recordings) for details).
- **<dirname_id>**: parent folder identifier (Integer).
The audio files have been supplied in a parent directory.
A directory can contain several broadcasts from the programme.
We have therefore chosen to retain the information relating to this hierarchy.
- **<file_id>**: file identifier (Integer).
- **<subpart_number>**: file subpart identifier (Integer).
Some audio recordings have been divided into parts because they were too long to be loaded into the transcription tool.
Therefore, we maintain continuity between recordings using a sub-part number.
If 0, there is no sub-section. If 1, it is the first part of a record. If 2, it is the second part. And so on.

### Example
`wol_43612` can be decomposed in:  `wol   4   36  1   2`
Just by reading the file name, you can deduce that:
- It is from radio show.
- It is in folder 36, perhaps with other recordings of the same radio programme.
- It is the first file of the folder.
- It is the second part of a recording, so the start of the programme recording must be the previous file.
