# gradle-travis-sample

This is a coding exercise, you'll be working in IntelliJ with git, GitHub and Travis CI.

Read and follow the instructions carefully. The exercise is marked as follows:

10 marks - Correct domain modelling - classes, interfaces, abstract classes, function signatures
5 marks - Code quality - code compiles, good naming, whitespace, use of streams where appropriate
5 marks - Project structure - code and tests in the right place, good unit test coverage
5 marks - Code in GitHub
5 marks - Travis builds & runs tests successfully

This exercise will take THREE HOURS and is OPEN BOOK - you may use your notes, previous code, the slides, and the internet. You must understand & be able to explain your solution.

#
1. Fork & Clone
Fork and clone the git repository at https://github.com/turntabl/gradle-travis-sample 

#
2. Travis integration
Enable a Travis CI build for your repository. Check that the sample code builds and the unit tests pass

#
3. Test the build locally
Test that the code builds and the test runs by running
$ gradle test
in your project repo.

#
4. IntelliJ
Open the gradle project in IntelliJ. 
Open > build.gradle > Open as Project

#
5. Build and run the tests
Open test/java/turntabl/io/NumbersTest and run the unit tests by clicking the green arrows. You should see the test result in the console window.

#
6. The exercise
Turntabl has a number of clients who pay us to write code for them. We want to keep a register of clients so we can contact them.

There are two types of Client: Corporate and Private. Every client has a name, an ID, and a Service Level.

The Service Level is either Gold, Platinum, or Premium.

A Corporate Client has an Account Manager.
A Private Client is just a person.

Turntabl wants to get the Contact Name of a Client. In the case of a Corporate Client, that's the name of the Account Manager. In the case of a Private Client, that's the Client's name.

The Client Register should be initialised with a collection of both Corporate and Private Clients.

Model this scenario appropriately. Ensure you have appropriate tests for your model.

#
7. Using the Register
Extend your register to accommodate the following requirements.

*I would like to get a list of the Contact Names of all the Gold clients.

*I would like to get a Client's name by their ID. This should take into account the fact that there may be no Client with that ID.

*I would like a Count of all clients at every Service Level. For example, there may be 5 Gold clients, 6 Platinum clients, and 2 Premium clients.

#
8. Handing in your work
Make sure you push your code to GitHub regularly, and that your code builds and your tests pass in Travis.

Feel free to remove the Numbers sample code.

Fill out the sections below with your GitHub repo and Travis project details.
