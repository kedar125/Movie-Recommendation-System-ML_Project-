#Movie Recommendation using Machine Learning

Movie recommendation using Machine Learning Mini Project Submitted in fulfillment of the Course On Machine Learning In Python By Kedar Kharde, Shreyas Udupa, Kunal Kotkar, Sanket Jangale Under the guidance of GURVANSH SINGH, MTech

ABSTRACT
Movie recommendation is an engine that filters movies and suggests them to the user based on their past viewing experiences. This engine has gained more popularity due to the impact of various OTT platforms like Netflix, Prime Video, Hotstar, etc. We have used 3 different algorithms to make our model and execute the engine. First is K-Means clustering, which makes clusters of the movie based on Rating and popularity. Second is the KNN algorithm, which takes the Genre as input, and it displays the nearest neighbors pertaining to the same Genre. Lastly, we have used the SVM algorithm to train our model and give the list of the movies according to the Genre given as input. Based on the execution of the models according to the algorithms as mentioned above, we can concur that the KNN model is more suited than the SVM model to execute the recommendation system.

 

INTRODUCTION 
A recommendation engine is a type of information filtering system that predicts the preferences of the user. It makes a suggestion based on those preferences. Nowadays, the use of recommendation systems has increased manifold as most of the online platforms depend on this system to engage their users. Ecommerce sites like Amazon, Flipkart, Alibaba, and various other indigenous businesses use this system to suggest items based on their previous purchases and their search history. E.g., if a user wants to buy a new phone, the application recommends phones as well as the accessories associated with the search. OTT platforms like Netflix, Amazon Prime Video, Hotstar, etc. use this to suggest movies and tv shows based on previous movies viewed. If the user is using the platform for the first time, then the platform asks for the genres which the user prefers and then displays the associated movies and TV shows. Music apps like Apple Music, Spotify also use this to suggest songs based on the user's past song preferences. Each of the big companies have their own patented recommendation algorithm, which makes their application unique and attractive. People are so used to these apps, that the level of expectation has increased manifold. New users get disinterested by a new app if they don't find the recommendations according to their preferences. So all the new app developers are concentrating more on the development of their recommendation system.

SOFTWARES 
We have mainly used Python and its vast array of libraries to assist us in the making of this project.  Python is a general-purpose interpreted, interactive, object-oriented, and high-level,[1] interpreted, interactive, and object-oriented scripting language. Python has a highly readable design. It uses English keywords frequently, whereas other languages use punctuation, and it has fewer syntactic constructions than other languages. Python is a must for students and working professionals to become a great Software Engineer,[1] especially when they are working in the Web Development Domain. Following are essential characteristics of Python Programming − ⦁ It supports functional and structured programming methods as well as OOP. ⦁ It can be used as a scripting language or can be compiled to byte-code for building large applications. ⦁ It provides very high-level dynamic data types and supports dynamic type checking. ⦁ It supports automatic garbage collection. ⦁ It can be easily integrated with C, C++, COM, ActiveX, CORBA, and Java.[1]  Here are a few essential reasons as to why Python is popular: ⦁ Python has a vast collection of libraries. ⦁ Python is known as the beginner's level programming language because of its simplicity and easiness.[2] ⦁ From developing to deploying and maintaining, Python wants its developers to be more productive.[3] ⦁ Portability is another reason for the vast popularity of Python. ⦁ Python's programming syntax is simple to learn and is of high level compared to C, Java, and C++.[3] Jupyter Notebook - The Jupyter Notebook is an open-source web application that allows us to create and share documents that contain live code, equations, visualizations, and narrative text.[4] Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.[4] The code is written and implemented in both Jupyter Interactive Notebook and IDLE. We have implemented the GUI (Tkinter ) part in IDLE. Tkinter-The Tkinter module ("Tk interface") is the standard Python interface to the Tk GUI toolkit from Scriptics. Both Tk and Tkinter are available on most Unix platforms, as well as on Windows and Macintosh systems.[5] Starting with the 8.0 release, Tk offers native look and feel on all platforms. It is a standard Python interface to the Tk GUI toolkit shipped with Python. Python with Tkinter is the fastest and easiest way to create the GUI applications.[6] The several Python modules provide the public interface. The most crucial interface module is the Tkinter module itself.  The Tkinter module only exports widget classes and associated constants, so you can safely use the from-in form in most cases. 

ALGORITHMS 
K-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. [7] ⦁ It is popular for cluster analysis in data mining. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem. [7] ⦁ k-means clustering is rather easy to apply to even large data sets, mainly when using heuristics such as⦁ Lloyd's algorithm. [7] ⦁ It has been successfully used in⦁ market segmentation,⦁ computer vision, and⦁ astronomy, among many other domains. It often is used as a preprocessing step for other algorithms[7] ⦁ SVM Algorithm-The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space(N — the number of features) that distinctly classify the data points.[8] ⦁ Our objective is to find a plane that has the maximum margin, i.e., the maximum distance between data points of both classes. [8] ⦁ Two main concepts are used in SVM: ⦁ Hyperplanes- They are decision boundaries that help classify the data points. Data points falling on either side of the hyperplane can be attributed to different classes. [8] ⦁ Support vectors are data points that are closer to the hyperplane and influence the position and orientation of the hyperplane. Using these support vectors, we maximize the margin of the classifier. [8] ⦁ KNN (K-Nearest Neighbors)- The KNN algorithm is a robust and versatile classifier that is often used as a benchmark for more complex classifiers such as Artificial Neural [9] Networks (ANN) and Support Vector Machines (SVM).  ⦁ The KNN classifier is also a non-parametric and lazy learning algorithm. ⦁ KNN is a non-parametric learning algorithm because it doesn't assume anything about the underlying data. ⦁ Lazy learning means that the algorithm makes no generalizations. This means that there is little training involved when using this method. Because of this, all of the training data is also used in testing when using KNN[10] ⦁ KNN falls in the supervised learning family of algorithms. In KNN, there are a few hyper-parameters that we need to tune to get an optimal result. The distance metric is one of the important ones through which we calculate the distance between the data points.[11] ⦁ KNN runs a formula to compute the distance between each data point and the test data. It then finds the probability of these points being similar to the test data and classifies it based on which points share the highest probabilities.[10] ⦁ A small value for K provides the most flexible fit, which will have low bias but high variance.[11] Larger values of K will have smoother decision boundaries, which[12] means lower variance but increased bias.[11]

LIBRARIES 
⦁ Pandas - pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with structured (tabular, multidimensional, potentially heterogeneous) and time-series data both easy and intuitive.[13] It aims to be the fundamental high-level building block for doing practical, real-world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible[14] open-source data analysis/manipulation tool available in any language. ⦁ Numpy - NumPy is a python library used for working with arrays. It also has functions for working in the domain of linear algebra, Fourier transform, and matrices. ⦁ Matplotlib - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shell, web application servers, and various graphical user interface toolkits.[15] ⦁ SKLearn - Scikit-learn is a free machine learning library for Python. It features various algorithms like support vector machine, random forests, and k-neighbors, and it also supports Python numerical and scientific libraries like NumPy and SciPy. ⦁ Import_ipynb - Used to display output of imported ".ipynb" files in Jupyter. ⦁ Columnar - It is a library for creating columnar output strings using data as input. ⦁ columnar() Arguments: ⦁ Data: ⦁ An iterable of iterables, typically a list of lists of strings where each string occupies its cell in the table. ⦁ headers=None ⦁ A list of strings, one for each column in data, which will be displayed as the table headers. If left as None, this will produce a table that does not have a header row.no_borders=False ⦁ Accepts a boolean value that specifies whether or not to display the borders between rows and columns. Passing True will hide all the borders and convert the headers to all caps for a more minimalistic look.[16]

MATHEMATICS 
In the SVM algorithm, we are mainly passing the Kernel parameter to SVC. There are three types of kernel- ⦁ Linear: ⦁ It is mostly used when data are linearly related. ⦁ Equation is:

Linear kernel equation ⦁ Rbf Kernel (Radial basis function): ⦁ It is a general-purpose kernel; used when there is no prior knowledge about the data. ⦁ Equation is:

Gaussian radial basis function (RBF) ⦁ Polynomial Kernel: ⦁ It is popular in image processing. ⦁ Equation is:

Polynomial kernel equation ⦁ where d is the degree of the polynomial.\

Euclidean distance: When implementing KNN, the first step is to transform data points into feature vectors, or their numerical value. The algorithm then works by finding the distance between the mathematical values of these points. The most common way to find this distance is the Euclidean distance, as shown below.[8] Minkowski distance: Euclidean distance can be generalized using the Minkowski norm, also known as the p norm. The formula for Minkowski distance is:

D(x, y) = (Σd|xd – yd|^p)^(1/p)

Here we can see that the formula differs from the formula of Euclidean distance as we can see that instead of squaring the difference, we have raised the difference to the power of p and have also taken the p root of the difference. Now the most significant advantage of using such a distance metric is that we can change the value of p to get different types of distance metrics.

⦁ p = 2 ⦁ If we take the value of p as 2, then we get the Euclidean distance. ⦁ p = 1 ⦁ If we set p to 1, then we get a distance function known as the Manhattan distance.[11]

INFERENCE In K-Means Cluster, data is fit into a variable, and k-means was performed on it using the factors like "Number of Votes" and "Ratings." The Result shows the movies divided into 4 categories as "Best," "Good," "Average," and "Worst." Naturally, very few movies deserved the "Best" category, and the majority of the movies belonged to either "Average" or "Worst" category. As Genres contain multiple classes, it is not easily separable, i.e., the basic SVM uses linear hyperplanes to separate classes, and if we provide a different kernel (Non-linear kernel), then it will change the shape of the decision manifold that must be used. Although KNN gives better results, but SVM is more trusted and is considered as a real-time classifier. For example, If we have a fixed data, then KNN may perform better, but if we have to build a prediction model and have to test it on real-time samples which were not previously available with the given dataset with whom we did the training, then SVM will perform better because it has right learning approach. As in our dataset, there are no new movies to predict, and mostly in static data, KNN performs better.

CONCLUSION The popularity and effectiveness of the Movie Recommendation System has been on the rise since the launch of various entertainment services. These services rely heavily on this system to retain its users. Based on the models that we have trained, we can concur that the KNN model is more accurate and faster in predicting the appropriate movies than the rest of the models. Therefore based on the above inference, we can conclude that the KNN model is more accurate at predicting the movies than the SVM model.
