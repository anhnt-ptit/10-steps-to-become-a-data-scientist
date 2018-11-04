
<img src="http://s9.picofile.com/file/8338833934/DS.png"/>
 <a id="0"></a> <br>
 
 # 10 Steps to Become a Data Scientist
 
 <div align="center">quite practical and far from any theoretical concepts</div>

#  Introduction
If you Read and Follow **Job Ads** to hire a machine learning expert or a data scientist, you find that some skills you should have to get the job.
In this Kernel, I want to review **10 skills** that are essentials to get the job

In fact, this kernel is a reference for **ten other kernels**, which you can learn with them,  all of the skills that you need.
# 1-Python
for Reading this section **please** fork and upvote  this kernel:

[numpy-pandas-matplotlib-seaborn-scikit-learn](https://www.kaggle.com/mjbahmani/numpy-pandas-matplotlib-seaborn-scikit-learn)
# 1-1 Why you sdould use python?

As **machine learning engineer** I would like to compare 4 machine learning programming languages(tools). Let's take this a bit deeper. Since most of us are concerned with ML and analysis being a big part of why we are using these programs. I want to list a few advantages and disadvantages of each for who want to start learning them as a data scientist.


##1-1-1 R

R is a language and environment for statistical computing and graphics. It is a GNU project which is similar to the S language and environment which was developed at Bell Laboratories (formerly AT&amp;T, now Lucent Technologies) by **John Chambers** and colleagues. **R** can be considered as a different implementation of S. There are some important differences, but much code written for S runs unaltered under R.


###1-1-1-1 Advantages of R 


* End To End development to execution (some brokers packages allows execution, IB)
* Rapid development speed (60% fewer lines vs python, ~500% less than C)
* A large number of Open Source Packages
* Mature quantitative trading packages( quantstrat, quantmod, performanceanalyitics, xts)
* Largest Community
* Can integrate into C++/C with rcpp

### 1-1-1-2 Disadvantages of R 

* Slow vs Python especially in iterative loops and non vectorized functions
* Worse plotting than Matlab and difficult to implement interactive charts
* Limited capabilities in creating stand-alone applications

----------------------------------------------

## 1-1-2 Python

Python is an interpreted high-level programming language for general-purpose programming. Created by Guido van Rossum and first released in 1991, Python has a design philosophy that emphasizes code readability, notably using significant whitespace. It provides constructs that enable clear programming on both small and large scales.

### 1-1-2-1Advantages

* End To End development to execution (some brokers packages allows execution, IB)
* Open source packages( Pandas, Numpy, scipy) 
* Trading Packages(zipline, pybacktest, pyalgotrade)
* best for general programming and application development
* can be a "glue" language to connect R, C++, and others (python)
* Fastest general speed especially in iterative loops

### 1-1-2-2 Disadvantages

* immature packages especially trading packages
* some packages are not compatible with others or contain overlap
* smaller community than R in finance
* More code required for same operations vs R or Matlab
* Silent errors that can take a very long time to track down (even with visual debuggers / IDE)

----------------------------------------------------

## 1-1-3 MATLAB

**MATLAB (matrix laboratory)** is a multi-paradigm numerical computing environment. A proprietary programming language developed by MathWorks, MATLAB allows matrix manipulations, plotting of functions and data, implementation of algorithms, a creation of user interfaces, and interfacing with programs written in other languages, including C, C++, C#, Java, Fortran, and Python.

Although MATLAB is intended primarily for numerical computing, an optional toolbox uses the MuPAD symbolic engine, allowing access to symbolic computing abilities. An additional package, Simulink, adds graphical multi-domain simulation and model-based design for dynamic and embedded systems.

### 1-1-3-1 Advantages

Fastest mathematical and computational platform especially vectorized operations/ linear matrix algebra 
Commercial level packages for all fields of mathematics and trading
Very short scripts considering the high integration of all packages
Best visualization of plots and interactive charts
Well tested and supported due to it being a commercial product
Easy to manage multithreaded support and garbage collection
Best debugger

### 1-1-3-2 Disadvantages

Can not execute - must be translated into another language
Expensive ~1000 per license and 50+ per additional individual package
Can not integrate well with other languages
Hard to detect biases in trading systems (it was built for math and engineering simulations) so extensive testing may be required. EG. look ahead bias
Worst performance for iterative loops
Can not develop stand-alone applications at all.

## 1-1-4 Octave

Octave is sort of the GNU answer to the commercial language MATLAB. That is, it is a scripting matrix language, and has a syntax that is about 95% compatible with MATLAB. It's a language designed by engineers, and thus is heavily loaded with routines commonly used by engineers. It has many of the same time series analysis routines, statistics routines, file commands, and plotting commands of the MATLAB language.

### 1-1-4-1 Advantages

First of all, there is no robust Octave compiler available and this is not really necessary either since the software can be installed free of charge.
Looking at the language element the two packages are identical except for some particularities like nested functions. Octave is under constant active development and every deviation from the Matlab syntax is treated as a bug or at least an issue to be resolved.
There are also plenty of toolboxes available for octave and as long as a program does not require graphical output there is a good chance that it runs under Octave just like under Matlab without considerable modification.
Graphics capabilities are clearly an advantage of Matlab. The latest versions include a GUI designer on top of excellent visualization features.
Octave uses either GNU Plot or JHandles as graphics packages, where the latter is somehow closer to what Matlab provides. However, there are no Octave equivalents to a GUI designer and the visualization mechanisms are somehow limited and not Matlab compatible.
The same holds for an integrated development environment. There is a project called QTOctave but it is still at an early stage.
Looking at the collaborate efforts taking place around the Octave community it is likely that this software will soon provide better and possibly even compatible graphics and GUI capabilities and it is well worth a look before buying Matlab.

### 1-1-4-2 Disadvantages

it just a free open source of MATLAB and don't bring us anything new


![compare1][1]
![compare2][2]



to sum up, there are several tools for data scientist and machine learning engineer in the below chart you can see which one is more popular than others.
![compare1][3]
**[reference][4]**


  [1]: https://media.licdn.com/dms/image/C4E12AQHC8vSsbqji1A/article-inline_image-shrink_1500_2232/0?e=1543449600&amp;v=beta&amp;t=lUVejbr2Lwdz9hZuYmVY3upQB2B4ZIjJsP6eiwvrW0A
  [2]: https://media.licdn.com/dms/image/C4E12AQEH61x6adp36A/article-inline_image-shrink_1000_1488/0?e=1543449600&amp;v=beta&amp;t=EJdx7dx7UMFnOpc5QndIulg9GI2Fd1NyAouEM6s945Q
  [3]: https://media.licdn.com/dms/image/C4D12AQGPCHd41RDuzg/article-inline_image-shrink_1000_1488/0?e=1543449600&amp;v=beta&amp;t=aksgcN2r_TRkBKgaxYbLh-rZHsMa8xqXiBm-oravz-k
  [4]: https://www.linkedin.com/pulse/r-vs-python-matlab-octave-mohamadjavad-mj-bahmani/
  
  [Download paper](https://github.com/mjbahmani/Machine-Learning-Workflow-with-Python/blob/master/Ebooks/R%20vs%20Python%20vs%20MATLAB%20%20vs%20Octave.pdf)
<a id="11"></a> <br>
# 2-Python Packages
* Numpy
* Pandas
* Matplotlib
* Seaborn

<img src="http://s8.picofile.com/file/8338227868/packages.png">

for Reading this section **please** fork and upvote  this kernel:



[numpy-pandas-matplotlib-seaborn-scikit-learn](https://www.kaggle.com/mjbahmani/numpy-pandas-matplotlib-seaborn-scikit-learn)

<a id="44"></a> <br>
## 2-4 SKlearn

<img src="http://scikit-learn.org/stable/_static/scikit-learn-logo-small.png">

for Reading this section **please** fork and upvote  this kernel:

[A-Journey-with-scikit-learn](https://www.kaggle.com/mjbahmani/a-journey-with-scikit-learn)
<a id="45"></a> <br>
##  3- Mathematics and Linear Algebra

<img src=" https://s3.amazonaws.com/www.mathnasium.com/upload/824/images/algebra.jpg " height="300" width="300">

for Reading this section **please** fork and upvote  this kernel:

[Linear Algebra in 60 Minutes](https://www.kaggle.com/mjbahmani/linear-algebra-in-60-minutes)
