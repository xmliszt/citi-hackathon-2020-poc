# citi-hackathon-2020-poc
A proof of concept UI for Citi Hackathon 2020 solution

## opencv

This folder is a POC model for individualised lip tracking and prediction as an alternative form of authentication which was not included in the website itself.

### Running from /opencv/

1. Obtain `shape_predictor_68_face_landmarks.dat` and put into `/models/` directory

2. Install dependencies from `requirements.txt`

2. `python lip_movement_net.py -v ../videos/044598381-carl-rowan-delivering-speech-a.mp4 -p ./models/shape_predictor_68_face_landmarks.dat -m ./models/1_32_False_True_0.25_lip_motion_net_model.h5`

