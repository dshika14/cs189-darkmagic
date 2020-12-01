# Team DarkMagic - Final Project T (Week 6 - Clustering, Topic 25 - K-Means)

### Description of Learning Objectives

1. **Understand the K-Means Algorithm and how to implement it.** In this project, we guide the students through an implementation of the K-Means algorithm. This exercise is intended to help students understand the inner workings of the K-Means algorithm. Students will have a chance to explore the performance of the algorithm on a real-world dataset.

2. **Utilize the scikit-learn package implementation of K-Means.** From insights gathered in our Early Project T interviews, many undergraduate ML interns use the package implementations of various ML algorithms as a black box, instead of writing their own implementation. For this reason, we have students read through the documentation of the scikit-learn K-means function and use it as a sanity check for their own implementation of K-means.

3. **Perform data exploration on a real-world dataset to justify the clustering approach.** We provide students with a high-dimensionality dataset. In this project, students explore the dataset by visualizing it across different combinations of features. This exercise helps motivate the use of dimensionality reduction techniques in combination with K-means.

4. **Understand the value of using PCA for dimensionality reduction in conjunction with K-means.** Through this project, students will understand that often times K-means alone will not lead to a reasonable clustering. In the Week 3, Topic 12 Project, students will gain exposure to PCA for dimensionality reduction. This project will help students build on their understanding of PCA to project the data into a space that is more clusterable for the K-means algorithm.

5. **Experience tuning k (the number of clusters) for K-means.** In our Early Project T, many interviewed students expressed that hyperparameter tuning is a valuable skill in the industry-setting, but something that they lacked experience with. In this project, we have students identify an appropriate choice for k based on grid search.

6. **Understand how the kernel trick can be applied to K-means.** In the Week 4, Topic 15 project, students will gain exposure to the kernel trick, common kernels like the polynomial, RBF, and Laplacian kernels, and the Gram matrix. We believe that this is a great opportunity for students to connect the K-means algorithm to their earlier work with kernels! In this way, students can cement their earlier understanding of kernelization and how it can be applied to other machine learning algorithms.

7. **Understand limitations of the K-means algorithms and why they arise.** In the note, we give students exposure to some of the shortcomings of the K-means algorithm. In the project, we demo for students instances when the output produced by K-means is not the ideal clustering. We ask students to explore these scenarios and justify why the K-means algorithm leads to these outputs. It is important for students to understand these limitations of the algorithm to apply it in real-world projects.

8. **Explore how K-means can be altered to fix the failure cases above.** After students understand the limitations of the K-means algorithm from the previous learning objective, we explore how we can slightly alter our use of the K-means algorithm to improve performance in these cases. Some of these techniques include random restarts and feature lifting in conjunction with PCA.

9. **Experience working with domain knowledge.** In our Early Project T, we found that industry ML can often times ask interns to work with domain experts or acquire some domain knowledge. We give students exposure to this concept by having them work with a Polymers dataset. We fully expect that some of the features may be unfamiliar to students. We give a basic description for some features, but for others we expect students to do some quick research to familiarize themselves with the dataset! This process is likely to be helpful if they are working with domain knowledge in future ML projects.

10. **Experience reading research papers and translating them to implementations.** In our Early Project T, some interviewees expressed that an integral part of their work involved reading relevant research papers and creating implementations based on them. We give students access to a paper that discusses Weighted Kernel K-means. They will have to read a section of the paper in order to complete a portion of this project. This learning objective will very likely serve useful for industry ML internships.

11. **Experience reading existing code and creating bug fixes.** Based on our findings from Early Project T, sometimes interns worked with existing code that contained bugs or a partial implementation. We give students an implementation of kernelized K-means and ask them to fix the bugs based on their understanding of the research paper (learning objective 10). This skill will likely be helpful for students in an internship-setting.

### How to Navigate the Repository
The workflow of a typical student is as follows: 
1. Look at the [slides] for an overview of K-Means
2. Open the [folder] and start on [project_part_1] where they will create a working K-Means implemention end-to-end in the context of a real industry situation. If they need any clarifications on the theory or more details, they can reference the [notes] as needed. 
3. After completing [project part 1], they will move on to [project part 2] where they will explore the bounds and limitations of K-Means and how they can prevent certain issues from arising. 
4. Once they have finished the coding portion, they will take the [quiz] to check their overall understanding of K-Means.
5. Students can check their solutions using the notebooks found in [folder]

