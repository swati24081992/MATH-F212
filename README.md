# APL405: Machine Learning in Mechanics (Winter semester 2024)

![image](https://github.com/coursesAM/APL405W24/assets/109568856/a56eedeb-7cb1-42bc-a1f5-ed8ee1f6a70c)


## Course Info

**Credit:** 3 units (2-0-2) <br> 

**Pre-requisites:** APL101/MTL106/MTL108, COL106 <br>

**Instructors:** [Rajdip Nayek](https://sites.google.com/view/rajdip-nayek/) (rajdipn@am.iitd.ac.in) <br> 

**Class timings:** Tue, Thu & Fri (11:00 to 11:50 AM) at LHC517 <br>

**Practical Session:** Fri (3 PM to 5 PM) at two labs LH503 and LH502 <br> <br>

**Attendance and Marks:** [Link here](https://docs.google.com/spreadsheets/d/1dkHXrfufbpG6P75PFV1eT8Ll7bcTSrFx2Au0paBTgdU/edit?usp=sharing)

**Office hours (TA)**: By email appointment <br> 
**Office hours (Instructor)**: By email appointment (Room B24, Block 4) <br><br>

**Intended audience:** BTech students in Applied Mechanics, Materials, Mechanical and Civil Engineering disciplines.<br>


**NOTE**-For *all course related emails*, please put **APL405** in the subject line <br>

## Table of Contents
- [Course Content](#course-content)
- [Course Structure](#course-structure)
- [Lecture Schedule](#lecture-schedule)
- [Practical Schedule](#practical-schedule)
- [Homework Schedule](#homework-schedule)
- [Course References](#course-references)
- [Grading](#grading)
- [Project](#project)

## Course Content
This is an introductory course to statistical machine learning for students with some background in calculus, linear algebra, and statistics. The course focuses on supervised learning, i.e., classification and regression. The course will cover a range of methods used in machine learning and data science, including:
- Linear regression
- Classification via logistic regression and k-nearest neighbor
- Regression and classification trees
- Bagging and boosting
- Neural networks and deep learning
- Principal component analysis
- k-means clustering

These methods will be studied from various applications throughout the course. The course also covers important practical considerations such as cross-validation, model selection, and the bias-variance trade-off. The course includes theory (e.g., derivations and proofs) and practice (notably the lab and the course project). The practical part will be implemented using Python.

## Course Structure
* Introduction 
* k-NN and Decision Trees 
* Linear Regression and Logistic regression 
* Polynomial regression
* Bias-Variance decomposition
* Loss function vs likelihood-based models
* Regularization
* Parameter optimization
* Three sets: Train, test, validation
* Neural Networks (NN)
* Support vector machine (SVM) 
* Ensemble algorithms
* PCA
* k-means clustering
* EM algorithm

## Lecture Schedule

|Module#| Main Topic | Sub Topics|Lecture Notes (2024)| Extra material |
|:----------:|:------------------------------:|:------------------:|:-----------------:|:-----------:|
|Mod 00| Introduction | | [Lecture 1](Lectures/Lecture1.pdf)  | |
|Mod 01| A Preliminary Approach <br> to Supervised Learning| Background <br> k-Nearest Neighbours <br> Decision Trees | [Lecture 2](Lectures/Lecture2.pdf) <br> [Lecture 3](Lectures/Lecture3.pdf) <br> [Lecture 4](Lectures/Lecture4.pdf)| [AL] Chapter 2|
|Mod 02| Basic Parametric Models | Linear regression <br> Logistic Regression <br> Regularization | [Lecture 5](Lectures/Lecture5.pdf) <br> [Lecture 6](Lectures/Lecture6.pdf) <br> [Lecture 7](Lectures/Lecture7.pdf)| [AL] Chapter 3 |
|Mod 03| Evaluating Performance | Cross-validation <br> Training error-generalization gap <br> Bias-variance decomposition | [Lecture 8](Lectures/Lecture8.pdf) <br> [Lecture 9](Lectures/Lecture9.pdf) <br> [Lecture 10](Lectures/Lecture10.pdf)| [AL] Chapter 4  |
|Mod 04| Learning Parametric Models | Loss functions <br> Parameter Optimization | [Lecture 11](Lectures/Lecture11.pdf) <br>  [Lecture 12](Lectures/Lecture12.pdf)| [AL] Chapter 5, <br> [Lecture 5 by Prof. Mitesh Khapra](http://www.cse.iitm.ac.in/~miteshk/CS6910.html) |
|Mod 05| Neural Networks | Feedforward neural network <br> Backpropagation <br> Convolutional Neural Network | [Lecture 13](Lectures/Lecture13.pdf) <br>  [Lecture 14](Lectures/Lecture14.pdf) <br>  [Lecture 15](Lectures/Lecture15.pdf)| [AL] Section 6.1, <br> [Video](https://www.youtube.com/playlist?list=PLcqHTXprNMIMinq16VTi6cFeTxuEqlqHC), <br> [Lecture 8 by Prof. Mitesh Khapra](http://www.cse.iitm.ac.in/~miteshk/CS6910.html) |
|Mod 06| Kernel Methods | Kernel Ridge Regression <br> Theory of kernels <br> Support Vector Classification | [Lecture 16](Lectures/Lecture16.pdf)  <br>  [Lecture 17](Lectures/Lecture17.pdf) <br>  [Lecture 18](Lectures/Lecture18.pdf)| [AL] Chapter 8, <br> [SN] Sections 5.5, 5.6 |
|Mod 07| Ensemble Methods | Bagging & Random Forests <br> Boosting | [Lecture 19](Lectures/Lecture19.pdf) <br>  [Lecture 20](Lectures/Lecture20.pdf)| [AL] Chapter 7 |
|Mod 09| Generative Models & <br> Unsupervised Learning  | Gaussian mixture models  <br> GMM (with EM) <br> k-means clustering <br> PCA | [Lecture 21](Lectures/Lecture21.pdf)  <br>  [Lecture 22](Lectures/Lecture22.pdf) <br>  [Lecture 23](Lectures/Lecture23.pdf) <br>  [Lecture 24](Lectures/Lecture24.pdf)|  [AL] Sections 10.1 <br> [AL] Sections 10.2, [slides](https://www.cs.toronto.edu/~rgrosse/courses/csc311_f21/lectures/lec11.pdf) <br> |

## Course References
* [AL] Andreas Lindholm et. al., *"Machine Learning: A First Course for Engineers and Scientists"*, Cambridge University Press, 2022 [[free pdf](http://smlbook.org/book/sml-book-draft-latest.pdf)]
* [SN] Soroush Nasiriany et. al., *"A Comprehensive Guide to Machine Learning"*, EECS Berkeley, 2019. [[free pdf](https://snasiriany.me/files/ml-book.pdf)]
* Andriy Burkov, *"The Hundred Page Machine Learning Book"*, 2019 [[free pdf](http://ema.cri-info.cm/wp-content/uploads/2019/07/2019BurkovTheHundred-pageMachineLearning.pdf)].
* Brunton, Steven L., and J. Nathan Kutz. *"Data-driven science and engineering: Machine learning, dynamical systems, and control"*. Cambridge University Press, 2022.

## Practical Schedule
There will be no make-up labs for students who might have missed the labs due to genuine medical reasons. Marks for the missed labs will be adjusted based on the performance of the class on all labs and your performance in the labs you were present.

|Week# | Topics| Practical Questions | Notes | 
|:------:|:---------:|:--------:|:-------:|
| Wk 0 | Probability refresher | [Practical 0](Practicals/Practical_1.pdf) | [Notes](Practicals/Probability_refresher_updated.pdf) |
| Wk 1 | k-Nearest Neighbours  | [Practical 1](https://colab.research.google.com/drive/1VqG7PNyaXpedQc83uB9cTLe-zQYF1Uvy?usp=sharing) | Section |
| Wk 2 | Decision Trees        | [Practical 2](https://colab.research.google.com/drive/1c3L4Hax0hYIo9-vH-6Klpcu5rAcqsNw2?usp=sharing) | [Dataset](Practicals/Datasets/spring_stiffness_classify.h5) | 
| Wk 3 | Linear Regression     | [Practical 3](https://colab.research.google.com/drive/1SSpo6U-yALWmJlRnk787ntphnCLNJdcz?usp=sharing) | |
| Wk 4 | Logistic Regression   | [Practical 4](https://colab.research.google.com/drive/1sdtXpIo4K3kM5rizinDlsEIp2POHWrKF?usp=sharing) | | 
| Wk 5 | Cross-validation & Bias-variance trade-off  | [Practical 5](https://colab.research.google.com/drive/1PFqSdKV2F_lPF7J9CYRZfHLfKz0iuo2Z?usp=sharing) |  | 
| Wk 6 | Neural network in NumPy | [Practical 6](https://colab.research.google.com/drive/1Wvj4fCqLvb-91rb7I2pM3PnpPH6p45ks?usp=sharing) | [Solution](https://colab.research.google.com/drive/1EF14EbXITBoWRzamyjCVs1FxxA9U0F6o?usp=sharing) | 
| Wk 7 | Neural network in PyTorch | [Practical 7](https://colab.research.google.com/drive/1guRmisURiOFNkMG2cUdJGDX_RlDOUtz7?usp=sharing) | [Tutorial of GD with PyTorch gradients](https://mpol-dev.github.io/MPoL/ci-tutorials/PyTorch.html) |
| Wk 8 | SVM | [Practical 8](https://colab.research.google.com/drive/18-t0OXCsH0E2sCtgvEqDmizuGAy5yuZY?usp=sharing) | |
| Wk 9 | Boosting | [Practical 9](https://colab.research.google.com/drive/1T5FhhRLGqVsdAbnVY3R16hYN8qSJkbm2?usp=sharing) | |


## Homework Schedule
Three homeworks will be given

|HW# | Zip file| Writeup | Solutions |
|:------:|:---------:|:--------:|:---------:|
| HW1 |  [Homework zip 1](Homeworks/HW1.zip) | [Homework 1](Homeworks/HW1.pdf) | [Writeup_soln](Homeworks/HW1soln_writeup.pdf)|
| HW2 |  [Homework zip 2](Homeworks/HW2.zip) | [Homework 2](Homeworks/HW2.pdf) | |
| HW3 | [Datafiles](https://drive.google.com/file/d/1a8ZTb2gswnOnEw_IJMuUWsqoUgMgxwte/view?usp=sharing) <br> [Code Template](https://colab.research.google.com/drive/1tuCsaljFLtdzr6AxNK83e6-alNj4wdJP?usp=sharing)|  [Homework 3](Homeworks/HW3.pdf) | |


## Grading  

|Component|Scores| 
|:---|:-----:|
|**Practical Attendance + Exam** | 5 + 10 |
|**Homework**   | 20 |
|**Project**    | 10 |
|**Quiz**       | 10 | 
|**Minor**      | 20 | 
|**Major**      | 25 |
|**Total**      | 100| 

- Students are highly encouraged to attend all classes, but there are no marks on lecture attendance. **You still have to mark your attendance on Timble. If the combined lecture-plus-practical attendance is below 75% of the total, one grade will be lowered.**
- A penalty of 50% of the mark of the respective homework would be deducted if submitted after the deadline. Any submissions two days after the deadline will not be accepted. 

## Exams

|Component| Solution |
|:-----:|:-----:|
|**Minor**   | [Solution](Exams/Minor2024_sol.pdf) | 
|**Quiz**    | [Solution](Exams/quiz_sol.pdf) | 
|**Major**   | [Solution](Exams/Major_soln.pdf) | 


## Project

The course project is described [here](https://drive.google.com/file/d/194L4ay0NFESSbUdUCremyPefMnaSYRTP/view?usp=drive_link)

Datafiles for the course project can be found [here](https://drive.google.com/file/d/1CBLbrkEDRsjtrJnjr_tjZTnBTDtMlk0q/view?usp=sharing)
