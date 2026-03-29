# README - Enhancing Medical Web Search Through Visual Feedback and High-Performing Query Examples

## General Information
* **Study Title:** Enhancing Medical Web Search Through Visual Feedback and High-Performing Query Examples
* **Authors:** Susen Bloos (susen.bloos@stud.uni-regensburg.de), Simone Pfeiffer (simone.pfeiffer@stud.uni-regensburg.de), Erik Reiswig (erik.reiswig@stud.uni-regensburg.de)
* **Institution, Course:** University of Regensburg, *Informationsverhalten Verstehen*
* **Date:** 31.03.2026

## Description
* **Research Question:** This study investigates how visual feedback and high-performing query examples influence users' ability to retrieve helpful medical information. Specifically, it examines whether these supports improve independent search performance in a transfer setting without system assistance.
* **Methodology:** We conducted a randomized between-subjects pilot study with three conditions (no support, visual feedback, and feedback plus query examples) across a learning phase and a test phase. Participants completed multiple medical search tasks using condition-specific SERPs, followed by a final unsupported task to assess transfer of learning. 
* **Analysis:** Performance was assessed using helpful-compatibility@10 based on participants' final queries in the test phase, reflecting alignment with high-quality medical information, and compared across conditions. Additional variables (e.g., query behavior and demographics) were used for descriptive and exploratory analyses. No responses were excluded from the dataset.

## Contents of this Repository


* **/data/clicks.csv** - Contains all user click interactions on search results, including participant ID, topic ID, clicked URL, and timestamp.
* **/data/demographics.csv** - Contains participant-level demographic information collected prior to the experiment, including participant ID, submission timestamp, educational level, age, gender, English proficiency, and experimental condition.
* **/data/queries.csv** - Contains all submitted search queries, including participant ID, topic ID, condition, query text, computed helpful- and harmful-compatibility scores, and timestamp.
* **/data/tasks.csv** - Contains aggregated task-level data for each participant, including participant ID, condition, topic ID, number of submitted queries, total task time, time to first click, submitted answer, prior familiarity, and helpful- and harmful-compatibility scores for the final query.
* **/materials/forms/** - Full-page screenshots of the Google Form for each condition.
* **/materials/serp/** - Full-page screenshots of the SERPs for each condition

*Note:* Links to the original Google Forms and SERPs are not included. Screenshots are provided to ensure long-term accessibility.

## Data Acquisition
* **Method:** Online questionnaires (Google Forms) and condition-specific SERPs
* **Time Period:** 11.03.2026 - 22.03.2026
* **Sample:** N = 17 participants
* **Recruitment:** Convenience sampling (University of Regensburg and surrounding networks)

## Data Protection and Ethics
All data were pseudo-anonymized prior to publication.
Potentially identifying information (e.g., email addresses) was removed.
The dataset does not allow identification of individual participants.

## Usage and Citation
The dataset may be used for academic and research purposes. Please cite the study as follows:

Bloos, S., Pfeiffer, S., & Reiswig, E. (2026). *Enhancing Medical Web Search Through Visual Feedback and High-Performing Query Examples*. University of Regensburg.

## Contact
For questions, please contact: susen.bloos@stud.uni-regensburg.de
