# Towards Learning Convolutions from Scratch

This readme file is an outcome of the [CENG501 (Spring 2021)](http://kovan.ceng.metu.edu.tr/~sinan/DL/) project for reproducing a paper without an implementation. See [CENG501 (Spring 2021) Project List](https://github.com/sinankalkan/CENG501-Spring2021) for a complete list of all paper reproduction projects.

# 1. Introduction

In this paper, they investigated minimum description length as a guiding principle and show that in some settings, it can indeed be indicative of the performance of architectures. To find architectures with small description length, they proposed B-lasso, a simple variant of lasso algorithm that, when applied on fully-connected networks for image classification tasks, learns architectures with local connections and achieves state-of-the-art accuracies for training fully-connected nets on CIFAR-10 (85.19%), CIFAR-100 (59.56%) and SVHN (94.07%) bridging the gap between fully-connected and convolutional nets.

## 1.1. Paper summary

They introduced shallow (s-conv) and deep (d-conv) all-convolutional networks with desirable properties for studying convolutions. Through systematic experiments on s-conv and d-conv and their locally connected and fully-connected counterparts, they made several observations about the role of depth, local connectivity and weight sharing.

They looked at Minimum Description Length (MDL) as a guiding principle to what architectures generalize better.

Inspired by MDL, they proposed a training algorithm B-lasso , a variant of lasso with a more aggressive soft-thresholding to find architectures with few parameters and hence, a small description length. 

Summarize the paper, the method & its contributions in relation with the existing literature. 

# 2. The method and my interpretation

## 2.1. The original method

Explain the original method.

## 2.2. My interpretation 

Explain the parts that were not clearly explained in the original paper and how you interpreted them.

# 3. Experiments and results

## 3.1. Experimental setup

Describe the setup of the original paper and whether you changed any settings.

## 3.2. Running the code

Explain your code & directory structure and how other people can run it.

## 3.3. Results

Present your results and compare them to the original paper. Please number your figures & tables as if this is a paper.

# 4. Conclusion

Discuss the paper in relation to the results in the paper and your results.

# 5. References

Provide your references here.

# Contact

Provide your names & email addresses and any other info with which people can contact you.
