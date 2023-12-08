# Word_Predictor_using_GMM
Predicting words from given audio file with 80% accuracy using gaussian mixture models
# Model
Using gaussian mixture model with mfcc as features we train a model on 60,000 audio files of 30 words namely
class_mapping = {'right': 0, 'eight': 1, 'cat': 2, 'tree': 3, 'bed': 4, 'happy': 5, 'go': 6, 'dog': 7, 'no': 8, 'wow': 9,
                 'nine': 10, 'left': 11, 'stop': 12, 'three': 13, 'sheila': 14, 'one': 15, 'bird': 16, 'zero': 17,
                 'seven': 18, 'up': 19, 'marvin': 20, 'two': 21, 'house': 22, 'down': 23, 'six': 24, 'yes': 25,
                 'on': 26, 'five': 27, 'off': 28, 'four': 29}
