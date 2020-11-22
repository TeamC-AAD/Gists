
## Problem Statement

In this following selection , we have applied Genetic algorithm in the field of machine Learning. Given a set of feaures <i>n</i> and given the condition that we must selection <i>m</i> features from these <i>n</i> features such that the linear regression prediction of the test set using these features result in the least possible mean squared errors. The details of the datasets and the Libraries (non-trivial) used are follows:

- <b>Dataset Used</b> : <a href="http://archive.ics.uci.edu/ml/datasets/communities+and+crime"> Communities and Crime Dataset, UCI </a>
- <b>Libraries Used</b> : Pandas, Scikit-Learn

## Approach

We used Genetic Algorithms to solve this problem. The walkthrough of our code has been provided below:

<b>Step 1</b>: Import the libraries

//Embed f16
<div id="f1"></div>

<b>Step 2</b>: Preprocess the data

//Embed f15,f14,f13
<div id="f2"></div>
<div id="f3"></div>
<div id="f4"></div>

<b>Step 3</b>: Define fitnesss function. The fitness function for a given set of chromosomes is defined as follows:

<img src="http://www.sciweavers.org/upload/Tex2Img_1605900223/render.png">
<img src="http://www.sciweavers.org/upload/Tex2Img_1605900540/render.png">

//Embed f12
<div id="f5"></div>
 
<b>Step 4</b>: Run using our Library! The results after a few convergences in generations have been shown below:

// Embed f11
<div id="f6"></div>

```bash
Iter Number: 14
Best individual: [64. 73. 90. 84. 74. 21. 67. 35. 40. 24. 81. 69. 26. 55. 25. 68. 57. 59.
 47. 87. 38. 82.  0. 44. 76. 33. 92. 32. 13. 52. 79. 78. 85.  9. 72. 20.
 66. 49. 22. 65. 62.  7.  4. 89. 96. 17. 11. 15.  2. 93.]
Best fitness: 734.5108830937046
```
