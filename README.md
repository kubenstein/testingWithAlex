#testingWithAlex

##Summary
testingWithAlex is a bash script wrapping [parallel_test](https://github.com/grosser/parallel_tests) commands. To bring some fun, whenever your tests fail or pass, Alex, MacOS buildin voice synthesizer, will let you know about final verdict.

##Setup
* open script and change name
* make script executable: `chmod +x testingWithAlex`
* ( optionally you can copy script to some preloaded location like /bin/ )
* run script inside folder with your rails app

##Supported systems
* MacOS

##Making unsupported systems supported
If you want to run this script on any other unix-based system, you have to change `say` function to any other function you want to handle verdict of your tests. 

##References
[parallel_test](https://github.com/grosser/parallel_tests)