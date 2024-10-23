<p>
In the assignment section of this  Blackboard dropbox include a link to your github and answer the following questions:<br/>
According to the book, what is Big O for this algorithm?<br/>
Big O is O(N*M).<br/>
Did your calculations of elapsedTime align with what the book said about Big O for this brute-force string matching algorithm?<br/>
So it seems my calculations for elapsedTime have more noise than signal. As an example running the method match(‘elmo’,’mo’); a bunch of times prior to checking for the best case changed from thousands of nano seconds to hundreds of nano seconds. Apparently this might be due to warming up the jvm. So as for if it aligns with O(N*M) kind of in that it doesn’t take a lot of time and there isn’t much variance. It is definitely not lining up with an exponential.<br/>
Describe what you think the purpose of the exercise is?<br/>
Maybe as a demonstration of why execution times might not be the best comparison tool since in some cases the minute difference are insignificant. Which is why with Big O they drop constants and non dominant terms.<br/>
Is this enough to calculate a best- and worst-case scenario?<br/>
Not at all, in many cases the best case could be worse than the worst case.<br/>
</p>
