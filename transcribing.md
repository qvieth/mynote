
- transcription:
  - model like whisper: focus on __what being said__, not **who said it**
- speaker diarization - who spoke when - 3 main steps:
  1. segmentation: audio divided to small chunks
  2. feature extraction/ embeddings: (pyannote/embedding converts audio into speaker embedding - numerical vectors - represent speaker voice characteristics)
  3. clustering: compare embeddings, group similar voice characteristics -> produce  speaker labels


- ASR: automatic speech regconition: turning spoken audio into text
  - streaming ASR + diarization 
    - ASR: what was said
    - diarization: who said

- Q: what service provide like Zoom captions with speaker names in real time. what are the leader out there. i want to use this for studying in university
  - otter.ai
  - ava
  - ...
