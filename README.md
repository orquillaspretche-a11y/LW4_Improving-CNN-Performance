 # 📁 LW4_Improving-CNN-Performance

 **Google Colab link here:** https://colab.research.google.com/drive/1xu27K-ZxpcyjsF-snyOjj0zzXdBqDVED?usp=sharing
 
# :memo: GUIDE QUESTIONS (Student Explanation & Reflection) :memo:

**A. Model Evaluation Analysis**

💡 **1. What were the weakest-performing classes based on the confusion matrix?**

-Based on the confusion matrix, these are the weakest-performing classes Buttercrunch Lettuce, Bibb Lettuce, Lactuca Sativa and Batavia Lettuce.

💡 **2. How did Precision, Recall, and F1-score vary across classes?**

-The Precision, Recall, and F1-score vary across different classes like for Arugula Lettuce has the high recall 0.9483 but lower precision 0.705128 resulting in an F1-score of 0.8088. While Batavia Lettuce shows good precision 0.8049 but relatively low recall 0.5789, leading to an F1-score of 0.6735.

💡 **3. What does a low recall indicate in your model?**

-A low recall indicates that the model is missing a significant portion of the actual positive cases. If a class has a low recall, it means that many instances belonging to that class are being incorrectly classified as belonging to other classes.

💡 **4. How does AUC score reflect model performance compared to accuracy?**

-Accuracy gives a quick overview of correct prediction, AUC provides a more robust and nuanced evaluation of a model's ability to discriminate between classes, particularly useful in scenarios with varying class distributions or when the cost of different types of errors is not uniform.

**B. Model Improvement**

💡 **5. How did data augmentation affect validation accuracy?**

-The validation accuracy for the baseline model was 0.7677. After implementing data augmentation and other enhancements in the improved custom CNN, the validation accuracy increase to 0.8131 This represents an increase of approximately 0.0454 in validation accuracy, suggesting that data augmentation contributed positively to the model's performance on unseen data. 

💡 **6. Why is Batch Normalization important in CNNs?**

-Batch Normalization makes deep CNNs much easier and faster to train, leading to better overall performance and generalization.

💡 **7. What role did Dropout play in improving your model?**

-Dropout is a smart study technique for my model to avoid memorizing the answers which mo result og Overfitting instead truly understand material(generalize).

💡 **8. How did Early Stopping prevent overfitting?**

-Early stopping serves as  a crucial regularization technique within the machine learning training paradigm, primarily designed to mitigate overfitting. Overfitting occurs when a model learns the training data, including its noise, too well, thereby losing its ability to generalize effectively to unseen data. Early stopping addresses this by continuously monitoring the model's performance on a separate validation dataset during the training process.

**C. Performance Comparison**

💡 **9. What improvements were observed after modifying the model?**

-An increase in validation accuracy from 0.7677 to 0.8131, and a decrease in Validation loss from 0.8399 to 0.6545. The average performance across all classes also improved, with macro precision rising from 0.7708 to 0.8297, macro recall from 0.7660 to 0.8142, and macro F1-score from 0.7635 to 0.8141. These improvements indicate a better generalized and more accurate model, surpassing both the initial baseline and the Teachable machine benchmark.

💡 **10. Which enhancement contributed the most to performance improvement? Why?**

-The biggest improvements came from the combination of the more sophisticated model architecture with deeper convolutional layers and Batch Normalization and the robust regularization techniques Dropout and L2 Regularization, alongside the enhanced Data Augmentation.

💡 **11. Did the gap between training and validation accuracy decrease? Explain.**

-Yes, the gap between training and validation accuracy did change, and it increased for the improved model. Despite the improved model's notably better performance on validation data, the widening generalization gap indicates a more intense learning of the training set compared to the baseline, resulting in a slightly greater difference between its performance on familiar versus novel data.

**D. Explainability (Grad-CAM Integration)**

💡 **12. How did Grad-CAM help in understanding model predictions?**

-Grad-CAM is a method used to figure out the reasoning behind a Convolutional Neural Network's (CNN) predictions. It achieves this by creating a general heat map that pinpoints and emphasizes  the key areas within an input image that the model focused on to arrive at its classification outcome.

💡 **13. Did the improved model focus on more relevant regions? Provide evidence.**

-Grad-CAM visualization showed that the improved CNN concentrated more on diagnostically relevant regions of the image compared to the baseline model, indicating improved feature localization and interpretability.

💡 **14. Why is explainability important in real-world AI applications?**

-Explainability is important in real-world AI applications because it helps people understand how and why an AI systems makes decisions. When users can understand the process behind the results, they are more likely to trust the system. It is also important in fields like healthcare, finance, education, and security where AI decisions can greatly affect people's lives.

