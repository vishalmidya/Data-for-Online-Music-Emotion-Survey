# Data-for-Online-Music-Emotion-Survey

This is the online repository of data used in the paper **Cultural differences in the use of acoustic cues for musical emotion experience**.

# Data Files

## Participant_Information.csv : Detailed Participant Information

This data file presents simple participant demographics and information on their music training. 

* **_ParticipantNumber_** : Participant ID
* **_Trained_** : Have you ever recieved a formal training in music ?   
* **_Trained_Start.age_** : If _yes_ to _Trained_, then at what age did you start training ?   
* **_Trained_Years_** : If *yes* to *Trained*, then how long have you been trained (in years) ?  
* **_Trained_Perfom_** : If _yes_ to _Trained_, then have you ever performed professionally or semi-professionally ?   
* **_Trained_Practise_** : If _yes_ to *Trained*, then how many hours per week do you usually practice ?  
* **_Genre_** :  If *yes* to *Trained*, then which genre of music are you trained in ?  
* **_Language_Native_** : What is your Native language ?  
* **_Language_fluent_** : What languages are you fluent in ?  
* **_Ethnicity_** : What is your ethnicity ?   
* **_Other_** : Any further comment on ethnicity ?   
* **_Familiarity_** : How familiar are you with Hindustani Raga Music ?    

All the other column names are self-explanatory. 


## AllRagaData.csv : All Emotion Response data for the 24 Ragas by Raga Number

The data file is called "AllRagaData.csv" with dimension of (4855, 18) 

* **_RagaNumber_** : One particular Raga among the 24 Raga excerpts   
* The columns "Angry","Calm.Soothed", "Devotional", "Happy", "Longing.Yearning", "Romantic.Tender","Sad", "Tensed.Restless" present the emotion responses.      
* **_familiar_** : Are you familiar with this particular raga excerpt ?
* **_feeling_** : How are you feeling after listening to the raga excerpt ?
* **_Trained_** : Have you ever recieved a formal training in music ?   
* **_Trained_genre_** : If *yes* to *Trained*, then which genre of music are you trained in ?   
* **_Familiarity_** : How familiar are you with Hindustani Raga Music ?   

All the other column names are self-explanatory. 


## Aggregated Emotion score by cultural groups, Music Stimuli values and Familiarity scores

The data file is called "AveragedEmotionScores_MusicStimuliValue.csv"

* Calm_E, Calm_NE, Happy_E, Happy_NE, Romantic_E, Romantic_NE, Devotional_E, Devotional_NE, Sad_E, Sad_NE, Tensed_E, Tensed_NE, Angry_E, Angry_NE, Longing_E, Longing_NE : All these columns present the averaged emotion responses either for Enculturated (E) or Non- Enculturated (NE) participants for each of the 24 raga excerpts.  
* **_Mode_** : Presentation mode of the Raga excerpts (_Alaap_ vs. _Gat_)
* **_Note_Density_** : Estimated values for Note_Density
* **_Pulse_Clarity_** : Estimated values for Pulse_Clarity
* **_Tonality_** :	Estimated values for Tonality
* **_Raga_** :	Name of the Raga excerpt
* **_Fscore_E_** : Familiarity score for Enculturated participants
* **_Fscore_NE_** : Familiarity score for Non-Enculturated participants
* **_Raga_number_** : Raga number corresponding to the 24 raga excerpts 

# How to download these csv files ?

Directly go to Zenodo.org through this DOI link <a href="https://zenodo.org/badge/latestdoi/205243713"><img src="https://zenodo.org/badge/205243713.svg" alt="DOI"></a>

# License (CC-BY-SA-4.0)

Please refer to **LICENSE.txt** in this Repository.


