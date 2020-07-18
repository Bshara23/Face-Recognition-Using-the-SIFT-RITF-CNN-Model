# Face-Recognition-Using-the-SIFT-RITF-CNN-Model
Facial recognition model that combines CNN, rotation-invariant texture feature (RITF) and scale-invariant feature transform (SIFT) features to get 99% accuracy on LFW dataset

This is based mostly on the articles below (I also made some improvements based on my expirence):

1. Yu-Xin Yang, Chang Wen, Kai Xie, Fang-Qing Wen, Guan-Qun Sheng and Xin-Gong Tang - Face Recognition Using the SR-CNN Model
2. Ke Yan, Yaowei Wang, Dawei Liang, Tiejun Huang, Yonghong Tian - CNN vs. SIFT for Image Retrieval: Alternative or Complementary?
3. Mundher Al-Shabi, Wooi Ping Cheah, Tee Connie - Facial Expression Recognition Using a Hybrid CNN–SIFT Aggregator

Note:
The code generates and saves numpy arrays to your hard drive to improve the training speed, so it's important that you run the jupyter notebooks by order,
every notebook starts with a number that indicates the execution order (starting from 1).




## Accuracy (99%)
![Accuracy](/results/resultsModelAccuracy.png)
## Result with my images</h5>
![Accuracy](/results/resultsWithMyImages.png?raw=true)

## Resources

Libraries and APIs:
1. OpenCV docs and examples - https://scikit-learn.org/
2. Scikit-learn docs and examples - https://opencv.org/
3. Keras docs and examples - https://keras.io/
4. Matplotlib - https://matplotlib.org/
5. Numpy - https://numpy.org/


Helpful sites:
1. https://machinelearningmastery.com/
2. https://www.pyimagesearch.com/2015/12/07/local-binary-patterns-with-python-opencv/

Database (LFW): https://www.kaggle.com/atulanandjha/lfwpeople
