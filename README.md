**Mission**
|Evaluating delta debugging on real regression bugs and facilitate further studies on application of delta debugging.|
|:-------------------------------------------------------------------------------------------------------------------|

**Description**
<blockquote>
<a href='http://www.st.cs.uni-saarland.de/dd/'>Delta debugging</a> has long been considered useful for debugging regressions. This project provides implementation and experimental results of applying delta debugging in fifteen <a href='http://code.google.com/p/ddexpr/wiki/Subjects'>real regressions</a> collected from GNU Software. <a href='http://code.google.com/p/ddexpr/downloads/detail?name=manual_results.tar.gz'>Our results</a> showed that two thirds of studied programs’isolated changes were useful in locating faults in terms of efficiency and accuracy. To conduct the experiments and facilitate further studies on application of dd, we have implemented an automated tool which is avaiable <a href='http://code.google.com/p/ddexpr/downloads/detail?name=prototype.tar.gz'>here</a>.<br>
</blockquote>

<img src='http://ddexpr.googlecode.com/files/fig.png' align='center' />


**Support**

[Subjects](http://code.google.com/p/ddexpr/wiki/Subjects) Subjects used in this study.

[AutoGuide](http://code.google.com/p/ddexpr/wiki/AutoGuide)           A Guide to Use Our Prototype (prototype.tar.gz).

[QuickGuide](http://code.google.com/p/ddexpr/wiki/QuickGuide) A Quick Guide to Use
Both prototype.tar.gz and implement.tar.gz.

[Guide](http://code.google.com/p/ddexpr/wiki/Guide)           A Guide to Apply Delta Debugging to Isolate Failure-inducing Changes of Regressions (implement.tar.gz).

**Publication**

The paper _**Towards Automated Debugging in Software Evolution: Evaluating Delta Debugging on Real Regression Bugs from Developers' Perspectives**_, which descibed DDExpr
in detail is accepted by [Journal of Systems and Software(JSS)](http://www.elsevier.com/locate/jss). Here is a suggested bibtex (note the title is too _**long**_ to be place in the following citation :-) ):

```bibtex

@article{jss,
author = {Kai Yu and Mengxiang Lin and Jin Chen and Xiangyu Zhang},
journal = {Journal of Systems and Software},
volume = {85},
issue = {10},
month = {Oct},
year = {2012},
issn = {0164-1212},
pages = {2305--2317},
url = {http://ast.nlsde.buaa.edu.cn/~kaiyu/pub/JSS.pdf},
doi = {http://dx.doi.org/10.1016/j.jss.2011.10.016},
publisher = {Elsevier Science Inc.},
address = {New York, NY, USA},
institution = {State Key Laboratory of Software Development Environment, Beihang University, China},
keywords ={delta debugging; fault localization; automated debugging; regression bugs},
author_url = {http://ast.nlsde.buaa.edu.cn/~kaiyu/},
group_url = {http://ast.nlsde.buaa.edu.cn/},
}
```


**Projects you might be interested in ...**

**[iRegression](http://code.google.com/p/iregression/) A simple and practical tool for debugging software regressions**

**[iLoupe](http://code.google.com/p/iloupe/) A tool locating faults using multiple spectra-specific models**
