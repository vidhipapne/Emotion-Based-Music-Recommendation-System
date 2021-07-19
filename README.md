# Emotion-Based-Music-Recommendation-System
Music is always an important part of human life . It helps to reduce stress , it makes us feel better and helps in mental calmness . Sometimes , we are able to define our emotions of what we are feeling , so facial emotions are the best way to depict and to know what the person’s mood is and what he/she is feeling . So , this system will recognise facial emotion and recommend those music that help them feel better . So , i think of combining both the systems together for this cause .ie the Facial Emotion Recognition and music recommendation based on that emotion .

 Facial Detection   - Ability to detect the location of face in any input image or frame. The output is the bounding box coordinates of the detected faces.
 Facial Recognition - Compare multiple faces together to identify which faces belong to the same person. This is done by comparing face embedding vectors.
 Emotion Detection  - Classifying the emotion on the face as happy, angry, sad, neutral, surprise, disgust or fear.
 Music Detection    - The resultant emotion is then searched in the songs database and when the related song is found , the music is played.

run the retrain.py file with following command in the terminal - 
python retrain.py --output_graph=retrained_graph.pb --output_labels=retrained_labels.txt --architecture=MobileNet_1.0_224 --image_dir=images

#And , after training the model , run the music_player_webcam.py file.
#Also, add the songs dataset and images dataset for training the model.
