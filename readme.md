### Speaker gender classification
We evaluate several models for the standard task of speaker gender classification using speechaudio data from [LibriSpeech](http://www.openslr.org/12/). We are using the Mel-Frequency Cepstral Coefficients (**MFCC**) which are a small set of features which describe the overall shape of the spectral envelope of our audio signal.

#### How to run
* Make sure to have the following libraries: `soundfile`, `python_speech_features`, `seaborn`, `tqdm`. Otherwise `pip install <library_name>` 
* Open and run the jupyter notebook `sgc.ipynb` (*Run -> Run All Cells*). 

#### Content
- **`LibriSpeach`** : folder which contains speech audio samples.
- **`sgc.ipynb`** : notebook with speaker gender classification models.
- **`id_gender.csv`** : table that contains information about the mapping *(speaker_id, gender)*.



