# AB-test
A simple code to understand and perform AB-test on your product
When a new feature is about to add to your product (specially your web page or application) you can make AB test tp make sure the new feature is beneficial for you.
You want to know if there are significant evidance that your feature is better to be added into your product.

AB test works based on Null/Alternative hypotesis testing. 
The original product (control here) works better is your Null hypothesis and your new feature (experiment) works better is your Alternative hypothesis.
So if the null hypothesis wins means the difference between the two products should be at least 0.

In this code we see if that's the case and we cannot reject the null hypothesis or not.

The implementation is based on bootstraping technique to build 10000 samples from your data set.
