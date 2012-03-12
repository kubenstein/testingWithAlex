#testingWithAlex

##Summary
testingWithAlex is bash script wrapping [parallel_test](https://github.com/grosser/parallel_tests) commands. To bring some fun, results of testing is said by Alex - MacOS buildin voice synthesizer.

##Setup
* open script and change name
* make script executable: `chmod +x testingWithAlex`
* ( optionally you can copy script to some preloaded paths like /bin/ )
* run script inside folder with your rails app

##Supported systems
* MacOS

##Making unsupported systems supported
If you want to run this script on any other unix-based system, you have to change `say` function to any function you want to handle verdict of your tests. 


##References
[parallel_test](https://github.com/grosser/parallel_tests)