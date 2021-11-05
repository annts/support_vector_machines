# support_vector_machines
Back to basics overview of support vector machines. Trying to bridge the gap between theory and practice by covering both.

This repo contains 4 main notebooks to articulate the mathematical concepts of support vecto machines

### 01_SVM_Foundational_Maths
Purpose of the notebook is to demonstrate mathematical intuition behind SVM. The intent is to first work out the underlying maths by hand and then replicate it via python libraries. This will help to crystalise the understanding of anyone who is using packages to solve these problems.


### 02_Effect_Of_C_Regularization

Purpose of the notebook is to demonstrate the soft constraint that can be incorporated into support vector machines when the classes to be predicted are not linearly separable. It tends to be used in most real world scenarios as the classes are not linearly separable.

First, we will formulate the constraint and update the objective to allow some wiggle room while determining the hyperplane. Then, we will find the solution through optimisation. Then, we will develop intuitions on how the algorithm performs using the maths basics developed so far in 01_SVM_Foundational_Maths notebook. Then, we will derive hinge loss and view the support vector machine through empirical risk minimisation framework. In the final section, we will use code to demonstrate out all the concepts developed in the notebook.

### 03_Unbalanced_classes_sample_weight
Purpose of the notebook is to deep dive into the impact of setting class weights in an SVM algorithm. This is typically used when classes are imbalanced


### 04_linear_svc_multiclass_classification
Purpose of the notebook is to deep dive into multiclass classification of SVM. Different variants of SVM handle multi class classification differently. For example, SVM with linear kernel does one vs. one classification under the hood. LineasrSVC does one vs. rest classification. Aim is to visualise one vs. one  and one vs. rest algorithms in the 3D space.