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

All personally identifiable information (PII) has been removed from the data files by the APPLES DCC.


## Data overview

#### Covariate/phenotype datasets (CSV)

The [covariate dataset files](:files_path:/datasets) (apples-dataset-0.1.0.csv and apples-harmonized-dataset-0.1.0.csv) contain 1,516 rows each. The first column (**appleid**) is the unique APPLES subject identifier that can be linked with PSG signal filenames. 

The dataset columns are described in the accompanying data dictionary files. The **variables** data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated “domain” (e.g., 1=Female, 0=Male), which are described in the **domains** data dictionary file. The **forms** data dictionary files provide links between variables and the sleep questionnaire form.

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/apples-data-dictionary). 

The harmonized-dataset contains many of the most frequently used demographic and sleep variables. These variables were curated by the NSRR team to allow ready inter-operability with other NSRR datasets. Key variables include:

* [nsrr_age](https://sleepdata.org/datasets/answers/variables/nsrr_age) -  Subject age
* [nsrr_sex](https://sleepdata.org/datasets/answers/variables/nsrr_sex) -  Subject sex
* [nsrr_race](https://sleepdata.org/datasets/answers/variables/nsrr_race) -  Subject race
* [nsrr_bp_diastolic](https://sleepdata.org/datasets/answers/variables/nsrr_bp_diastolic) -  Diastolic blood pressure
* [nsrr_bp_systolic](https://sleepdata.org/datasets/answers/variables/nsrr_bp_systolic) -  Systolic blood pressure
* [nsrr_current_smoker](https://sleepdata.org/datasets/answers/variables/nsrr_current_smoker) -  Currently smoking cigarettes
* [nsrr_ever_smoker](https://sleepdata.org/datasets/answers/variables/nsrr_ever_smoker) -  Ever smoked cigarettes
* [nsrr_ahi_ chicago1999](https://sleepdata.org/datasets/answers/variables/nsrr_ahi_chicago1999) -  Apnea-Hypopnea Index: (All apneas + hypopneas with >50% flow reduction or discernible flow reduction with $\geq$ 3% desat or arousal) / hour of sleep
* [nsrr_phrnumar_f1](https://sleepdata.org/datasets/answers/variables/nsrr_phrnumar_f1) -  Arousal Index: Number of arousals per hour of sleep from polysomnography
* [nsrr_ttldursp_f1](https://sleepdata.org/datasets/answers/variables/nsrr_ttldursp_f1) -  Total Sleep Duration: the interval between sleep onset and sleep offset while the participant is asleep from polysomnography
* [nsrr_pctdursp_s1](https://sleepdata.org/datasets/answers/variables/nsrr_pctdursp_s1) -  Percentage of total sleep duration (i.e., total sleep time, TST) in stage 1 from polysomnography
* [nsrr_pctdursp_s2](https://sleepdata.org/datasets/answers/variables/nsrr_pctdursp_s2) -  Percentage of total sleep duration (i.e., total sleep time, TST) in stage 2 from polysomnography
* [nsrr_pctdursp_s3](https://sleepdata.org/datasets/answers/variables/nsrr_pctdursp_s3) -  Percentage of total sleep duration (i.e., total sleep time, TST) in stage 3/4 from polysomnography
* [nsrr_pctdursp_sr](https://sleepdata.org/datasets/answers/variables/nsrr_pctdursp_sr) -  Percentage of total sleep duration (i.e., total sleep time, TST) in REM from polysomnography
* [nsrr_ttldurws_f1](https://sleepdata.org/datasets/answers/variables/nsrr_ttldurws_f1) -  Wake After Sleep Onset: the total duration being awake between sleep onset and lights-on/out-bed time from polysomnography
* [nsrr_ttleffsp_f1](https://sleepdata.org/datasets/answers/variables/nsrr_ttleffsp_f1) -  Sleep Efficiency: the ratio of total sleep duration (i.e., total sleep time) to in-bed period (i.e., time in bed) from polysomnography
* [nsrr_ttllatsp_f1](https://sleepdata.org/datasets/answers/variables/nsrr_ttllatsp_f1) -  Sleep Latency: the interval between lights-out/in-bed time and sleep onset from polysomnography
* [nsrr_ttlprdbd_f1](https://sleepdata.org/datasets/answers/variables/nsrr_ttlprdbd_f1) -  Total In-bed Period: the interval between lights off/in-bed time and lights on/out-bed time from polysomnography
* [nsrr_ttlprdsp_s1s4](https://sleepdata.org/datasets/answers/variables/nsrr_ttlprdsp_s1s4) -  REM Sleep Latency: the interval between the first sleep epoch and REM sleep including wake

#### PSG signal files (EDF/XML)

Raw signal data are shared as EDF files using the European Data Format (https://www.edfplus.info/). 

Staging and event-level scoring annotations are shared in two XML formats (‘profusion’ and ‘nsrr’). These files contain the same underlying information. Staging in the profusion files is coded as follows: 0=Wake, 1=N1, 2=N3, 3=N3-4, 5=REM.


## Access and usage restrictions
No restriction for access.


## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
>
> [Quan SF, Chan CS, Dement WC, Gevins A, Goodwin JL, Gottlieb DJ, Green S, Guilleminault C, Hirshkowitz M, Hyde PR, Kay GG, Leary EB, Nichols DA, Schweitzer PK, Simon RD, Walsh JK, Kushida CA. The association between obstructive sleep apnea and neurocognitive performance--the Apnea Positive Pressure Long-term Efficacy Study (APPLES). Sleep. 2011 Mar 1;34(3):303-314B. doi: 10.1093/sleep/34.3.303. PMID: 21358847; PMCID: PMC3041706.](https://pubmed.ncbi.nlm.nih.gov/21358847/)

Users must include the following text in any Acknowledgements:

 > The Apnea Positive Pressure Long-term Efficacy Study (APPLES) was supported by the National Heart, Lung, and Blood Institute (U01HL68060).


## References

-	APPLES on the National Sleep Research Resource (NSRR): https://sleepdata.org/datasets/apples/
- APPLES on ClinicalTrials.gov: https://clinicaltrials.gov/ct2/show/results/NCT00051363 
-	APPLES GitHub Data Dictionary: https://github.com/nsrr/apples-data-dictionary
-	APPLES GitHub Documentation: https://github.com/nsrr/apples-documentation


## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.


