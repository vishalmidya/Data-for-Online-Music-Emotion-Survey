# Data-for-Online-Music-Emotion-Survey

This is a reposatory of data used in the paper "Cultural differences in the use of acoustic cues for musical emotion experience".

# Basic Background Information

## Online Music Emotion Survey

With the purpose of collecting data from all around the world, a survey consisting of three-minute instrumental renditions of twelve ragas was conducted online. These ragas, played on a stringed instrument (sarod), were digitally recorded in both the alaap and gat stages. The task of the participants was to listen to the raga excerpts and rate their emotional experience on Likert scales of 0-4 (0 being ‘not at all felt’ to 4 being ‘felt the most’ for eight emotion labels: happy, romantic, devotional, calm/soothed, angry, longing/yearning, tensed/restless, and sad. 

The ragas selected for the study were played by a professional musician on sarod (a stringed instrument) digitally recorded in alaap and gat. The sarod was tuned by the artist to just intonation scale with the tonic being at 261.5 Hz.  The emotion labels used in the study were translated to Hindi and transliterated to Roman. The emotion labels used along with the respective translation to Hindi are as follows: happy (khush), romantic (premmaye), devotional (bhaktipurn), calm/soothed (shant), angry (krodhit), longing/yearning (virahapurn), tensed/restless (bechain), and sad (udas). The Romanized transliteration was used as it is widely used in internet communication and global commerce.  

## Experimental Design

The raga excerpts heard by participants of the online survey were presented in alternating alaap and gat blocks.  The experiment consisted of four such blocks with each block consisting of six ragas.  The presentation of alaap or gat block as the first block was counterbalanced across subjects.  The order of presentation of ragas within each block was randomized across participants.  The participants were given an option to opt out of the survey after rating at least two blocks (i.e., 12 ragas – six alaap and six gat).  The survey was made available at [here](https://nandinisingh.wixsite.com/labweb/musicemotion).

## Participant Demographics

650 participants registered for the survey over the period of two years; however, only data from participants who completed at least half the survey (i.e., rated at least six alaap excerpts (out of 12) and six gat excerpts (out of 12)) was considered for analysis.  Thus, the analysis reported in this study is based on the emotional responses reported by 255 participants (118 males, 137 females), 143 enculturated and 112 non-enculturated.  Out of the 143 enculturated participants, 122 overlapped with a previous study.The participants were asked to give demographic details before starting the survey. The participants residing in India who reported their native language as one of the languages specified in Indian constitution (Hindi, Bengali, Gujarati, Kannada, Malayalam, Tamil, Telugu, Marathi, Punjabi, Konkani, Sindhi, Oriya, and Urdu) were considered enculturated. The participants from the following countries, United States (18), UK (13), Hungary (62), France (3), Germany (3), Italy (2), Japan (2), Korea (1), Romania (1), Spain (2), and the Netherlands (3), not specified (2) were classified into the non-enculturated group.

## Characterization of the Music Stimuli

Kindly refer to the "Characterization of the music stimuli" section of the main paper for detailed description and estimation procedure for "Note Density", "Pulse Clarity", "Tonality" and "Rhythm".

# Data Files

## Participant_Information.csv : Detailed Participant Information

This data file presents simple participant demographics and information on their music training. 

* _ParticipantNumber_ : Participant ID
* _Trained_ : Have you ever recieved a formal training in music ?   
* _Trained_Start.age_ : If "yes" to "Trained", then at what age did you start training ?   
* _Trained_Years_ : If "yes" to "Trained", then how long have you been trained ?  
* _Trained_Perfom_ : If "yes" to "Trained", then have you ever performed semi-professionally or professionally ?   
* _Trained_Practise_ : If "yes" to "Trained", then how many hours per week do you practise ?  
* _Genre_ :  If "yes" to "Trained", then which genre of music are you trained in ?  
* _Language_Native_ : What is your Native language ?  
* _Language_fluent_ : What languages are you fluent in ?  
* _Ethnicity_ : What is your ethnicity ?   
* _Other_ : Any further comment on ethnicity ?   
* _Familiarity_ : How familiar are you with Hindustani Music ?    

All the other column names are self-explanatory. 


## AllRagaData.csv : All Emotion Response data for the 24 Ragas by Raga Number

The data file is called "AllRagaData.csv" with dimension of (4855, 18). 

* _RagaNumber_ : One particular Raga among the 24 Raga excerpts   
* The columns "Angry","Calm.Soothed", "Devotional", "Happy", "Longing.Yearning", "Romantic.Tender","Sad", "Tensed.Restless" present the emotion responses.      
* _familiar_ : Are you familiar with Hindustani Music ?
* _feeling_ : How are you feeling after listening to the raga excerpt ?
* _Trained_ : Have you ever recieved a formal training in music ?   
* _Trained_genre_ : If "yes" to "Trained", then which genre of music are you trained in ?   
* _Familiarity_ : How familiar are you with Hindustani Music ?   

All the other column names are self-explanatory. 


## Aggregated Emotion score by cultural groups, Music Stimuli values and Familiarity scores

The data file is called "AveragedEmotionScores_MusicStimuliValue.csv"

* Calm_E, Calm_NE, Happy_E, Happy_NE, Romantic_E, Romantic_NE, Devotional_E, Devotional_NE, Sad_E, Sad_NE, Tensed_E, Tensed_NE, Angry_E, Angry_NE, Longing_E, Longing_NE : All these columns present the averaged emotion responses either for Enculturated (E) or Non- Enculturated (NE) participants for each of the 24 raga excerpts.  
* _Mode_ : Presentation mode of the Raga excerpts (_Alaap_ vs. _Gat_)
* _Note_Density_ : Estimated values for Note_Density
* _Pulse_Clarity_ : Estimated values for Pulse_Clarity
* _Tonality_ :	Estimated values for Tonality
* _Raga_ :	Name of the Raga excerpt
* _Fscore_E_ : Familiarity score for Enculturated participants
* _Fscore_NE_ : Familiarity score for Non-Enculturated participants
* _Raga_number_ : Raga number corresponding to the 24 raga excerpts 

