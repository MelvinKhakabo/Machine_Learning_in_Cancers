**The Curse of Dimensionality: Views from Machine Learning and Data Science in Cancer Medicine**

The term "curse of dimensionality," coined by Richard Bellman in 1961, refers to the exponential increase in computational complexity as the dimensionality of a dataset grows.[<sup>1</sup>](#_enref_1 "Chandra, 2001 #313") Mathematically, this challenge arises when the number of variables (or dimensions) in a dataset increases. This makes tasks such as numerical integration, clustering, or regression significantly more difficult. For instance, consider evaluating an integral over a multi-dimensional space using Simpson's rule. In one dimension, the computational cost is in the order of $O(n^-4)$. However, for $`d`$ dimensions, the cost becomes $`\O(N^(-4/d))`$, where $`N`$ represents the total number of points evaluated.[<sup>2</sup>](#_enref_2 "Kuo, 2005 #318") This exponential growth in complexity renders calculations infeasible for large dimensions, particularly in high-dimensional settings, especially those involving multimodal health data.

In data science and machine learning, the curse of dimensionality becomes especially important when dealing with digital health data. Electronic health records, genomic data, imaging, and continuous signals from wearables generate vast amounts of high-dimensional data, leading to both opportunities and challenges.[<sup>3</sup>](#_enref_3 "Berisha, 2021 #314") In cancer research, where machine learning algorithms are often used to analyze high-dimensional datasets—such as genomic sequences or high-resolution medical images—the curse of dimensionality presents a serious obstacle.[<sup>4</sup>](#_enref_4 "Crespo Márquez, 2022 #315") These datasets often have more features than samples, which complicates the problem by leaving large portions of the feature space unexplored, leading to blind spots where models are prone to error.

In cancer pathology, high-dimensional image analysis is also crucial. For instance, multispectral imaging in prostate cancer pathology allows the capture of a broad range of spectral data, creating large feature vectors.[<sup>5</sup>](#_enref_5 "Tahir, 2006 #316") However, the high dimensionality of these vectors poses challenges for pattern recognition techniques, often leading to degraded model performance unless appropriately addressed through dimensionality reduction techniques.

Another notable example is IBM’s Watson for Oncology, an AI system trained on a limited dataset of historical patient data to recommend cancer treatments.[<sup>3</sup>](#_enref_3 "Berisha, 2021 #314") Due to the high dimensionality of the data, coupled with the small sample sizes used for training, the model was unable to generalize effectively. The limited training data resulted in poor performance when the model was deployed in real-world clinical environments, particularly when it encountered unseen data points in the blind spots of the feature space. The failure of Watson for Oncology illustrates how high-dimensional datasets can lead to overfitting and poor generalization, ultimately diminishing the effectiveness of AI in clinical settings.

The curse of dimensionality highlights the need for innovative approaches to manage the complexity of high-dimensional data in healthcare. Techniques such as dimensionality reduction, feature selection, and the development of more robust models are essential to overcome the limitations imposed by high-dimensional data.[<sup>6</sup>](#_enref_6 "Sharma, 2015 #317") This enables better generalization and more accurate clinical decision-making.


**References**

<a name="_enref_1"></a>1.	Chandra J. Understanding High Dimensional and Large Data Sets: Some Mathematical Challenges and Opportunities. In: Grossman RL, Kamath C, Kegelmeyer P, Kumar V, Namburu RR, editors. Data Mining for Scientific and Engineering Applications. Boston, MA: Springer US; 2001. p. 23-34.

<a name="_enref_2"></a>2.	Kuo FY, Sloan IH. Lifting the curse of dimensionality. Notices of the AMS. 2005;52(11):1320-8.

<a name="_enref_3"></a>3.	Berisha V, Krantsevich C, Hahn PR, Hahn S, Dasarathy G, Turaga P, et al. Digital medicine and the curse of dimensionality. npj Digital Medicine. 2021;4(1):153.

<a name="_enref_4"></a>4.	Crespo Márquez A. The Curse of Dimensionality. In: Crespo Márquez A, editor. Digital Maintenance Management: Guiding Digital Transformation in Maintenance. Cham: Springer International Publishing; 2022. p. 67-86.

<a name="_enref_5"></a>5.	Tahir MA, Bouridane A. Novel Round-Robin Tabu Search Algorithm for Prostate Cancer Classification and Diagnosis Using Multispectral Imagery. IEEE Transactions on Information Technology in Biomedicine. 2006;10(4):782-93.

<a name="_enref_6"></a>6.	Sharma N, Saroha K, editors. A novel dimensionality reduction method for cancer dataset using PCA and Feature Ranking. 2015 International Conference on Advances in Computing, Communications and Informatics (ICACCI); 2015 10-13 Aug. 2015.


