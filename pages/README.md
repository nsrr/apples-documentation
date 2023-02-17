## Background

The Apnea Positive Pressure Long-term Efficacy Study (APPLES) was a NHLBI-sponsored 6-month, randomized, double-blind, 2-arm, sham-controlled, multicenter trial conducted at 5 U.S. university hospitals, or private practices. The objectives of the study were 1) to assess the long-term effectiveness of CPAP therapy on neurocognitive function, mood, sleepiness and quality of life by administering both standard and novel tests of these indices to obstructive sleep apnea syndrome (OSAS) subjects randomly assigned to either a treatment group receiving CPAP or a control group receiving Sub-therapeutic (sham) CPAP; 2) to identify specific deficits in neurocognitive function associated with OSAS in a large, heterogeneous population of OSAS subjects; 3) to determine which deficits in neurocognitive function in OSAS subjects are reversible and most sensitive to the effects of CPAP; and 4) to develop multivariate composite indices to assess the clinical effectiveness of CPAP in improving neurocognitive function, mood, sleepiness and quality of life in OSAS patients.

1,516 participants were enrolled since November 2003 and studied for up to 6 months over 11 visits, of which 1,105 were randomized to active vs. sham CPAP (REMstar Pro, Philips Respironics, Inc.) devices; the sham CPAP device closely simulates the airflow through the exhalation port and the operating noise of the active CPAP device. 1,098 participants were diagnosed with OSA contributed to the analysis of the primary outcome measures. The study was completed in August 2008.

The BDC NSRR APPLES dataset includes raw polysomnography files, as well as data on neurocognitive function (i.e., attention and psychomotor function, learning and memory, executive and frontal-lobe function), daytime sleepiness, the maintenance of wakefulness test, mood, quality of life, PAP adherence, vitals, weight, demographics and other baseline characteristics. 

## Methods

#### Sleep Study Design

Subjects whose pre-screening found symptoms indicative of OSA received clinical evaluation which included informed consent, screening questionnaires, history and physical examination and a medical assessment by a study physician. Subjects subsequently returned approximately 2-4 weeks later for a 24-h sleep laboratory visit, where a diagnostic PSG was performed to confirm the presence of OSA followed by a day of neurocognitive and maintenance of wakefulness testing. Follow-up overnight PSG study was repeated at the CPAP titration visit, the two month and six month post-CPAP neurocognitive visit. Studies were scheduled to allow at least 7 but no more than 9 hours in bed.

#### Polysomnography Acquisition

Overnight polysomnography (PSG) was recorded with Alice 4 System by Respironics. The sensors and recording montage consisted of the electroencephalogram (EEG, C3-M2, C4-M1, O2-M1 and O1-M2), electrooculogram (EOG, ROC-M1, LOC-M2), submentalis and anterior tibialis electromyograms (EMG), heart rate by 2-lead electrocardiogram, snoring intensity (anterior neck microphone), nasal pressure (nasal cannula), nasal/oral thermistor, thoracic and abdominal movement (piezo bands), and oxygen saturation (pulse oximetry). All PSGs were electronically transmitted to the Data Coordinating Center. 

#### PSG Scoring

PSGs were scored visually using Rechtschaffen and Kales (R&K) criteria by trained scoring technologists who received standardized training and will receive periodic inter-rater reliability assessments.

A summary of the scoring rules and key annotations are provided below:

* Apneas - defined by a clear decrease (> 90%) from baseline in the amplitude of the nasal pressure signal lasting ≥ 10 sec.
* Hypopneas - identified if there was a clear decrease (> 50% but ≤ 90%) from baseline in the amplitude of the nasal pressure signal, or if there was a clear amplitude reduction of the nasal pressure signal that did not reach the above criterion but it was associated with either an oxygen desaturation > 3% or an arousal, and the event duration was ≥ 10 seconds. 
* Central Apneas/Hypopneas - identified if no displacement is noted on both chest and the abdominal inductance channels. Otherwise, events will be noted as “obstructive”. 
* Obstructive Apneas/Hypopneas - identified by persistence of chest or abdominal respiratory effort during flow cessation. 

#### Neurocognitive Testing

All neurocognitive testing was performed in the same predefined order for all subjects on the day after their diagnostic PSG. The testing was preceded by 2 training sessions. Typically, the first occurred several days or weeks before the diagnostic PSG, and the second on the night before the PSG. There were 3 prespecified primary neurocognitive outcomes, each representing 1 of 3 different neurocognitive domains: (1) attention and psychomotor function (Pathfinder Number Test [Pathfinder]), (2) learning and memory (Buschke Verbal Selective Reminding Test [BSRT]), and (3) executive and frontal-lobe function (Sustained Working Memory Test [SWMT], recorded using SAM Technology's EEG recording equipment, consisting of the SAM Technology Computer Interface Adaptor and timyapms).

In addition to the primary neurocognitive outcomes, other secondary measures included in the APPLES test battery were exploratory neurobehavioral measures such as intelligence (Wechsler Abbreviated Scale of Intelligence [WASI]) sustained attention and psychomotor function (Psychomotor Vigilance Test [PVT]) and auditory information processing speed and flexibility, as well as calculation ability (Paced Auditory Serial Addition Test [PASAT]).

#### Sleep, Psychological Mood and Quality of Life Survey Forms

The Bedtime Questionnaire and Epworth Sleepiness Scale (ESS) were completed the evening before the PSG and a number of questionnaires are administered following the PSG, including two mood questionnaires (Profile of Mood States [POMS] and Beck Depression Inventory [BDI-I]), a quality of life questionnaire (Quality of Well-being Self-administered [QWB-SA]), the Morning Questionnaire, Fatigue Scale, Stanford Sleepiness Scale, and Calgary Sleep Apnea Quality of Life Index. 

The following survey instruments were implemented:

* Epworth Sleepiness Scale (ESS)
* Stanford Sleepiness Scale (SSS)
* Fatigue Scale: Levels of Alertness
* Morning Questionnaire
* Bedtime Questionnaire
* Morningness-Eveningness Questionnaire (Derived from Horne and Ostberg)
* Sleep Habits Questionnaire (Modified from the Sleep Heart Health Study)
* Sleep Log
* Calgary Sleep Apnea Quality of Life Index (SAQLI)
* Quality of Well-Being Scale
* Self-Administered (QWB-SA) Form 1.04
* Profile of Moods States (POMS)
* Beck Depression Inventory (BDI-I)
* Hamilton Rating Scale for Depression (HAM-D)

## Data de-identification

Data have been de-identified by the APPLES DCC, by removing all Protected Health Information (PHI) such as name, date of birth, and any other contact details. Each individual is identified only by a random [appleid](:variables_path:/appleid) variable.

## Data overview

### Covariate/phenotype datasets
[Covariate csv files](:files_path:/datasets) (apples-dataset-0.1.0.csv and apples-harmonized-dataset-0.1.0.csv) contain data on 1,516 subjects from up to seven research visits. The [appleid](:variables_path:/appleid) column is the unique APPLES identifier. The [visitn](:variables_path:/visitn) column distinguishes different research visits, and the [fileid](:variables_path:/fileid) column links covariate datasets to diagnostic PSG files.

The dataset columns are described in the accompanying data dictionary files. The **variables** data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated “domain” (e.g., 1=Female, 0=Male), which are described in the **domains** data dictionary file. The **forms** data dictionary files provide links between variables and the sleep questionnaire form.

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/apples-data-dictionary). 

The harmonized-dataset contains many of the most frequently used demographic and sleep variables. These variables were curated by the NSRR team to allow ready inter-operability with other NSRR datasets. 

<details>
  <summary>Expand to see the list of key harmonized variables:</summary>

  <table>
    <tr><td><b>Variable</b></td><td><b>Label</b></td></tr>
    <tr><td><a href=":variables_path:/nsrr_age">nsrr_age</a></td><td>Subject age</td></tr>
    <tr><td><a href=":variables_path:/nsrr_sex">nsrr_sex</a></td><td>Subject sex</td></tr>
    <tr><td><a href=":variables_path:/nsrr_race">nsrr_race</a></td><td>Subject race</td></tr>  
<tr><td><a href=":variables_path:/nsrr_bp_diastolic">nsrr_bp_diastolic</a></td><td>Diastolic blood pressure</td></tr>
<tr><td><a href=":variables_path:/nsrr_bp_systolic">nsrr_bp_systolic</a></td><td>Systolic blood pressure</td></tr>
<tr><td><a href=":variables_path:/nsrr_current_smoker">nsrr_current_smoker</a></td><td> Currently smoking cigarettes</td></tr>
<tr><td><a href=":variables_path:/nsrr_ever_smoker">nsrr_ever_smoker</a></td><td>Ever smoked cigarettes</td></tr>
<tr><td><a href=":variables_path:/nsrr_ahi_chicago1999">nsrr_ahi_chicago1999</a></td><td>Apnea-Hypopnea Index: (All apneas + hypopneas with >50% flow reduction or discernible flow reduction with ≥ 3% desat or arousal) / hour of sleep</td></tr>
<tr><td><a href=":variables_path:/nsrr_phrnumar_f1">nsrr_phrnumar_f1</a></td><td>Arousal Index: Number of arousals per hour of sleep from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_ttldursp_f1">nsrr_ttldursp_f1</a></td><td>Total Sleep Duration: the interval between sleep onset and sleep offset while the participant is asleep from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_pctdursp_s1">nsrr_pctdursp_s1</a></td><td>Percentage of total sleep duration (i.e., total sleep time, TST) in stage 1 from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_pctdursp_s2">nsrr_pctdursp_s2</a></td><td>Percentage of total sleep duration (i.e., total sleep time, TST) in stage 2 from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_pctdursp_s3">nsrr_pctdursp_s3</a></td><td>Percentage of total sleep duration (i.e., total sleep time, TST) in stage 3/4 from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_pctdursp_sr">nsrr_pctdursp_sr</a></td><td>Percentage of total sleep duration (i.e., total sleep time, TST) in REM from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_ttldurws_f1">nsrr_ttldurws_f1</a></td><td>Wake After Sleep Onset: the total duration being awake between sleep onset and lights-on/out-bed time from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_ttleffsp_f1">nsrr_ttleffsp_f1</a></td><td>Sleep Efficiency: the ratio of total sleep duration (i.e., total sleep time) to in-bed period (i.e., time in bed) from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_ttllatsp_f1">nsrr_ttllatsp_f1</a></td><td>Sleep Latency: the interval between lights-out/in-bed time and sleep onset from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_ttlprdbd_f1">nsrr_ttlprdbd_f1</a></td><td>Total In-bed Period: the interval between lights off/in-bed time and lights on/out-bed time from polysomnography</td></tr>
<tr><td><a href=":variables_path:/nsrr_ttlprdsp_s1s4">nsrr_ttlprdsp_s1s4</a></td><td>REM Sleep Latency: the interval between the first sleep epoch and REM sleep including wake</td></tr>
  </table>

</details>  

### PSG data
[Raw PSG data files](:files_path:/PSG) are shared as EDF files using the European Data Format (https://www.edfplus.info/). 

## Access and usage restrictions

The APPLES dataset is generally only available for non-commercial use. For inquiries regarding commercial use please contact Kara Griffin (Kara.Griffin@stlukes-stl.com) and Clete A. Kushida (clete@stanford.edu).

## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
>
> [Quan SF, Chan CS, Dement WC, Gevins A, Goodwin JL, Gottlieb DJ, Green S, Guilleminault C, Hirshkowitz M, Hyde PR, Kay GG, Leary EB, Nichols DA, Schweitzer PK, Simon RD, Walsh JK, Kushida CA. The association between obstructive sleep apnea and neurocognitive performance--the Apnea Positive Pressure Long-term Efficacy Study (APPLES). Sleep. 2011 Mar 1;34(3):303-314B. doi: 10.1093/sleep/34.3.303. PMID: 21358847; PMCID: PMC3041706.](https://pubmed.ncbi.nlm.nih.gov/21358847/)

Users must include the following text in any Acknowledgements:

 > The Apnea Positive Pressure Long-term Efficacy Study (APPLES) was supported by the National Heart, Lung, and Blood Institute (U01HL68060).
 > The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*February 2023*

- Make APPLES dataset available for data requests

## References

-	APPLES on the National Sleep Research Resource (NSRR): https://sleepdata.org/datasets/apples/
- APPLES on ClinicalTrials.gov: https://clinicaltrials.gov/ct2/show/results/NCT00051363 
-	APPLES GitHub Data Dictionary: https://github.com/nsrr/apples-data-dictionary
-	APPLES GitHub Documentation: https://github.com/nsrr/apples-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.

