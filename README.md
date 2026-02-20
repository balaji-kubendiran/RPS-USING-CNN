# RPS-USING-CNN
The system was evaluated using a test dataset consisting of 437 gesture images. The model achieved an overall classification accuracy of 98%, indicating a high success rate in correctly identifying gesture classes.
| Gesture  | Precision | Recall | F1-Score | Samples |
| -------- | --------- | ------ | -------- | ------- |
| Paper    | 0.96      | 0.97   | 0.97     | 139     |
| Rock     | 0.99      | 0.99   | 0.99     | 158     |
| Scissors | 0.99      | 0.98   | 0.98     | 140     |
The system demonstrated the highest classification performance for the Rock gesture.

Minor misclassifications were observed between Paper and Scissors, likely due to similarities in finger positioning and hand orientation.

Overall results indicate that the system is capable of reliably distinguishing between the three gesture classes under the evaluated test conditions.
Another model using pretrained model : https://github.com/balaji-kubendiran/RPS-Pretraiined-model/blob/main/RPS%20using%20mobilev3net.ipynb
       precision    recall  f1-score   support

       paper       0.99      0.99      0.99       139
        rock       1.00      0.99      1.00       158
    scissors       0.99      1.00      1.00       140

    accuracy                           1.00       437
   macro avg       1.00      1.00      1.00       437
weighted avg       1.00      1.00      1.00       437
<img width="513" height="470" alt="image" src="https://github.com/user-attachments/assets/bdba6160-e598-4512-8605-a77a83d4f51e" />
