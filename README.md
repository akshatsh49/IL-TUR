# IL-TUR: Benchmark for Legal Text Understanding and Reasoning


This repository contains the official release of the following paper:

**IL-TUR: Benchmark for Legal Text Understanding and Reasoning**<br>

**Authors:** Abhinav Joshi, Akshat Sharma, Shounak Paul, Pawan Goyal, Saptarshi Ghosh, Ashutosh Modi <br>

**Abstract:** 
*Legal systems worldwide are inundated with exponential growth in cases and documents. To streamline the legal system, there is an imminent need to develop NLP and ML techniques for automatically processing and understanding legal documents. However, evaluating and comparing various NLP models (e.g., LLMs) developed specifically for the legal domain is challenging. This paper address this challenge by proposing IL-TUR: Benchmark for Legal Text Understanding and Reasoning. We propose various domain-specific tasks that address different aspects of the legal domain from the point of view of understanding and reasoning. We also present baseline models for each task, outlining the gap between the LLM-based models and ground truth. A public leaderboard has been created where the research community can upload and test legal text understanding systems on various metrics, thus fostering research in the legal domain.*


## IL-TUR Leaderboard

Please find the updated leaderboard along with tasks details on the [🔗 IL-TUR Leaderboard Page](https://cse.iitk.ac.in/users/ashutoshm/IL-TUR/).


## Tasks

Table below shows **Tasks** currently available in the IL-TUR benchmark.


| Task | Links to dataset files | Evaluation Metric | Link to Evaluation Script | 
| :-----       | :---              | :-----   | :-----   
| L-NER |   [ 🔗 L-NER-Data ](https://1drv.ms/f/s!AuBOJ2hW9Gimgbl0-UY_ydhQvfF7_g?e=vcrHPD)   | Strict F1   | 
| RR |   [🔗 RR-Data](https://1drv.ms/f/s!AuBOJ2hW9GimgboYOG7ZQ99lKJg4Rg?e=Fui1GV)   | Strict F1   | 
| CJPE    |  [ 🔗 ILDC](https://1drv.ms/f/s!AuBOJ2hW9GimgbsPCVlE80TSfjk7Ig?e=pyCkAc)   | F1, BLEU, ROUGE   | 
| BAIL     |      [🔗 HLDC](https://1drv.ms/f/s!AuBOJ2hW9Gimgbol9ZZbin4eMxnp6g?e=DKo12s)   | F1   | 
| LSI      |      [🔗 ILSI](https://1drv.ms/f/s!AuBOJ2hW9GimgblvnEV3H715vhgCZQ?e=2CnaV1)   | F1   | 
| PCR     |       [🔗 IL-PCR](https://1drv.ms/f/s!AuBOJ2hW9GimgbotGnN0nwbXPUzg5Q?e=KDezhw)   | F1   | 
| SUMM     |          [🔗 In-Abs](https://1drv.ms/f/s!AuBOJ2hW9Gimgbl5s3AOFp54cTR1uQ?e=FcfR25)   | ROUGE, BERT-SCORE   | 


## Submission
For submitting to the Leaderbaord see the details proivded at [🔗 IL-TUR Leaderboard Page](https://cse.iitk.ac.in/users/ashutoshm/IL-TUR/). 


## License
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
The CISLR dataset follows [CC-BY-NC](CC-BY-NC) license. Thus, users can share and adapt our dataset if they give credit to us and do not use our dataset for any commercial purposes.


