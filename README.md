## [LearnCpp.com](http://www.learncpp.com/)

My attempt at learnin C++ and gtest unit testing

## Installing [gtest](https://github.com/google/googletest) framework

1. Install `sudo apt-get install libgtest-dev`
2. Compile `gtest` and install
~~~
sudo apt-get install cmake # install cmake
cd /usr/src/gtest
sudo cmake CMakeLists.txt
sudo make
 
# copy or symlink libgtest.a and libgtest_main.a to your /usr/lib folder
sudo cp *.a /usr/lib
~~~
3. Create a function and a test suite - `squareRoot.cpp` and `squareRoot_test.cpp`
4. Tell Cmake to create your tests - `CMakeLists.txt`
5. Run test - `./runTests`

### Helpful links

* https://www.eriksmistad.no/getting-started-with-google-test-on-ubuntu/
* http://ysonggit.github.io/coding/2014/12/19/use-gtest-in-ros-program.html
* https://meekrosoft.wordpress.com/2009/10/04/testing-c-code-with-the-googletest-framework/
* http://www.ibm.com/developerworks/aix/library/au-googletestingframework.html
* http://www.yolinux.com/TUTORIALS/Cpp-GoogleTest.html

