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

💡 **6. Why is Batch Normalization important in CNNs?**

💡 **7. What role did Dropout play in improving your model?**

💡 **8. How did Early Stopping prevent overfitting?**

**C. Performance Comparison**

💡 **9. What improvements were observed after modifying the model?**

💡 **10. Which enhancement contributed the most to performance improvement? Why?**

💡 **11. Did the gap between training and validation accuracy decrease? Explain.**

**D. Explainability (Grad-CAM Integration)**

💡 **12. How did Grad-CAM help in understanding model predictions?**

💡 **13. Did the improved model focus on more relevant regions? Provide evidence.**

💡 **14. Why is explainability important in real-world AI applications?**







