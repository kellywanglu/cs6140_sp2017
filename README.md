# CS 6140: Machine Learning

**Time and Location:** Thursdays from 6:00 pm to 9:00 pm in Forsyth Building 129

**Instructor**: [Lu Wang](http://www.ccs.neu.edu/home/luwang/), Office 448 WVH

**Staff and Office Hours**: 

* Prof. Lu Wang, Thursdays from 4:30pm to 5:30pm, or by appointment, 448 WVH
* Rui Dong (TA, email: dongrui@ccs.neu.edu), Tuesdays from 4pm to 5pm, 466B WVH

**Discussion Forum**: [Piazza](http://piazza.com/northeastern/spring2017/cs614002/home), sign up at [piazza.com/northeastern/spring2017/cs614002](http://piazza.com/northeastern/spring2017/cs614002)

_______
## Important Announcement
* [1/1/2017] We will have a quiz with 22 simple questions, 20 of them as True or False questions (relevant to probability, statistics, and linear algebra) in the first class (1/12/2017). This quiz will be graded, but will not be counted in your final score if you’re enrolled in CS6140. The purpose of this quiz is to indicate the expected background of students. 80% of the questions should be easy to answer. If you find yourself struggling with this quiz, it’s possible that you need to catch up on the background or it may be preferable to take one or two preliminary courses. For students previously do not take any algorithm course (CS 5800 or CS 7800, see Prerequisites), an 80% or above is required to enroll in this course.

_______
## Course Description

#### Content
* Regression: linear regression, logistic regression
* Dimensionality Reduction: Principal Component Analysis (PCA), Independent Component Analysis (ICA), Linear Discriminant Analysis
* Probabilistic Models: Naive Bayes, maximum likelihood estimation, bayesian inference
* Statistical Learning Theory: VC dimension
* Kernels: Support Vector Machines (SVMs), kernel tricks, duality
* Sequential Models and Structural Models: Hidden Markov Model (HMM), Conditional Random Fields (CRFs)
* Clustering: spectral clustering, hierachical clustering
* Latent Variable Models: K-means, mixture models, expectation-maximization (EM) algorithms, Latent Dirichlet Allocation (LDA), representation learning
* Deep Learning: feedforward neural network, restricted Boltzmann machine, autoencoders, recurrent neural network, convolutional neural network
* Reinforcement Learning: Markov decision processes, Q-learning
* and others, including advanced topics for machine learning in natural language processing and text analysis

#### Textbooks and Reference
* Main Textbooks
 * Kevin Murphy, "Machine Learning - a Probabilistic Perspective", MIT Press, 2012.
 * Christopher M. Bishop, "Pattern Recognition and Machine Learning", Springer, 2006.

* Other Reference: 
 * Tom Mitchell, "Machine Learning", McGraw Hill, 1997.
 
#### Prerequisites
This course is designed for graduate students majoring in computer science, applied math, and other related areas. Students who take this course are expected to be able to write code in some programming languages (e.g. Python, Java, C/C++) proficiently, and finish courses in algorithms (CS 5800 or CS 7800), multivariable calculus, probability, statistics, and linear algebra.

_______
## Grading
Each assignment or report, both electronic copy and hard copy, is due at the beginning of class on the corresponding due date. Hard copies are submitted in class. Assignment or report turned in late will be charged 10 points (out of 100 points) off for each late day (i.e. 24 hours). Each student has a budget of 5 days throughout the semester before a late penalty is applied. You may want to use it wisely, e.g. save for emergencies. 

Grades will be determined based on three assignments, ten in-class tests, one course project, one open-book exam, and participation:

* Assignments (30%): three assignments, each of 10%
* Quiz (10%): ten quick in-class tests, each of 1%
* Project (27%): team of 2 to 3 students, proposal (2%), reports (10%+10%), final presentation (5%)
* Exam (30%): open-book
* Participation (3%): classes, Piazza
 
_______
## Schedule
#### Jan 12
* Topic: Introduction, basic concepts, K-nearest neighbors, linear regression, ridge regression
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec1.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec1_6pp.pdf)
* Reading: Murphy CH1, CH2, CH7 (sections covered in the lecture)
* TODO: start thinking about projects and looking for teammates

#### Jan 19
* Topic: Logistic Regression, Decision Tree, Generative Models (Naive Bayes)
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec2.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec2_6pp.pdf)
* Reading: 
* TODO: assignment 1 is released [[pdf]](material_cs6140_sp17/cs6140sp17-assignment1.pdf) [[dataset(.zip)]](material_cs6140_sp17/a1_datasets.zip)

#### Jan 26
* Topic: Perceptron, Support Vector Machines, Kernels, Statistical Learning Theory
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec4.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec4_6pp.pdf)
* Project proposal report due

#### Feb 2
* Topic: Deep Learning
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec5.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec5_6pp.pdf)

#### Feb 9
* Topic: Deep Learning
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec6.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec6_6pp.pdf)
* Assignment 1 due
* TODO: assignment 2 is released [[pdf]](material_cs6140_sp17/cs6140sp17-assignment2.pdf) [[dataset(.zip)]](material_cs6140_sp17/a2_datasets.tar.gz)



#### Feb 16
* Topic: Bayesian Statistics and Frequentist Statistics
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec3.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec3_6pp.pdf)


#### Feb 23
* Topic: Dimensionality Reduction
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec7.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec7_6pp.pdf)


#### Mar 2
* Topic: Clustering
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec8.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec8_6pp.pdf)
* Assignment 2 due
* TODO: assignment 3 is released [[pdf]](material_cs6140_sp17/cs6140sp16-assignment3.pdf) [[dataset(.zip)]](material_cs6140_sp17/a3_datasets.zip)


#### Mar 9 (No Class: Spring Break)



#### Mar 16
* Topic: Structured Output Prediction
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec9.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec9_6pp.pdf)
* Project progress report due


#### Mar 23
* Topic: Mixture Models and Expectation Maximization
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec10.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec10_6pp.pdf)

  
#### Mar 30
* Topic: Reinforcement Learning
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec11.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec11_6pp.pdf)
* Assignment 3 due


#### Apr 6
* Topic: Representation Learning
* Slides: [[Download]](slides_cs6140_sp17/cs6140_lec12.pdf) [[6pp version]](slides_cs6140_sp17/cs6140_lec12_6pp.pdf)
* Exam guideline: [[Download]](slides_cs6140_sp17/exam_guideline.pdf)


#### Apr 13
* Topic: Course Project Presentation



#### Apr 20
* Topic: Exam
* Project final report due

_______
## Academic Integrity 
This course follows the [Northeastern University Academic Integrity Policy](http://www.northeastern.edu/osccr/academic-integrity-policy/). All students in this course are expected to abide by the Academic Integrity Policy. Any work submitted by a student in this course for academic credit should be the student's own work. Collaborations are allowed only if explicitly permitted. Violations of the rules (e.g. cheating, fabrication, plagiarism) will be reported.



 

