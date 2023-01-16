# Preliminary

In this section, we would like to briefly present some preliminary knowledge of accent conversion.

## Background

## What is Accent ?

As the Cambridge dictionary shows, **accent** is the way in which people in a particular area, country, or social group pronounce words. For example, we can listen to some samples in different accents:

|  Accent   |   Wav |  
| :------: | :--------: | 
|    Arabic        |    <audio controls="controls"><source type="audio/wav" src="../../_static/wav/aba_0001.wav"></source><p>Your browser does not support the audio element.</p></audio>        |  
|Mandarin | <audio controls="controls"><source type="audio/wav" src="../../_static/wav/bwc_0001.wav"></source><p>Your browser does not support the audio element.</p></audio>       | 
| Hindi |   <audio controls="controls"><source type="audio/wav" src="../../_static/wav/asi_0001.wav"></source><p>Your browser does not support the audio element.</p></audio>     | 
|  Korean |    <audio controls="controls"><source type="audio/wav" src="../../_static/wav/hkk_0001.wav"></source><p>Your browser does not support the audio element.</p></audio>    |


## What is Accent Conversion ?
Accent conversion aims to transform the accent of speech while preserving the speaker timbre(who is speaking) and content(it means what is spoken). 

## Accent Converssion Example


|  Accent   |   Mandarin |  American | Accnet Converted | 
| :------: | :--------: |  :--------: |  :--------: | 
|    Wav        |    <audio controls="controls"><source type="audio/wav" src="../../_static/wav/media1.wav"></source><p>Your browser does not support the audio element.</p></audio>        |  <audio controls="controls"><source type="audio/wav" src="../../_static/wav/media2.wav"></source><p>Your browser does not support the audio element.</p></audio>        |  <audio controls="controls"><source type="audio/wav" src="../../_static/wav/media3.wav"></source><p>Your browser does not support the audio element.</p></audio>        |  

## How to Evaluate the Quality of Accent Conversion System ?

There are three evaluation metrics for accent conversion system:

### Accentedness

For the accentedness rating metric, listeners were instructed to rate every sentence using 9-point Likert scales(sometimes 5-point scale).
- 1-no non-native accent, 
- 9-strong non-native accent.

### Acoustic quality and naturalness

Audio quality and naturalness are rated on a five-point scale in the MOS test, aiming to evaluate the clarity and human-likeness of the speech samples.

- 1-bad
- 2-poor
- 3-fair
- 4-good
- 5-excellent

### voice similarity. 

For the voice similarity metric, listeners were also asked to rate their confidence level on a 7-point scale(sometimes 5-point scale). They were instructed to only focus on voice similarity while ignoring others.

- 1-not at all confident
- 7-extremely confident