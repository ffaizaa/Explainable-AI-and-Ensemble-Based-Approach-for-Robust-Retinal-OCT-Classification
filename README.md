In this study, we implemented and evaluated five deep learning models - ResNet50,
DenseNet121, EfficientNet-b3, Xception with custom layers, and a Custom CNN to sort OCT
retinal images into four disease classes: CNV , DME, Drusen, and Normal. We introduced
Grad-CAM for model explainability and evaluated robustness using adversarial black patches.
Moreover, we applied an ensemble technique using the collective strength of our two best
models, Custom CNN and DenseNet121, to improve classification and model robustness. For
classification, the Custom CNN achieved the highest overall performance with an accuracy of
92.66%, precision of 92.78%, recall of 92.64%, and F1-score of 92.71%. However, DenseNet121
showed strong robustness under adversarial patch testing, as measured through confidence
scores, but slightly lower accuracy. On the other hand, the ensemble model outperformed both
best models and achieved an accuracy of 93.60%, precision of 93.63%, recall of 93.60%, and
F1-score of 93.58%. Furthermore, the ensemble model demonstrated strong robustness by
correctly classifying DRUSEN when the adversarial patch was placed inside the highlighted
heatmap region, whereas all the other models misclassified DRUSEN into either NORMAL or
CNV under the same condition.
