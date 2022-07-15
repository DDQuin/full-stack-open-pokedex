Java - When it comes to linting checkstyle can be used to lint java code and can be used with maven, the testing
and building can also be done with maven with a single command run from the commandline that takes care of everything.
Junit for testing and maven compiler for building. GitHub Actions can use maven to create
a workflow to test and build with maven which simplifys everything. Azure devops can be used to set up CI/CD, GitLab Ci, Buddy etc.
Cloud devlepment is better for 6 people as the application is going to be released soon so there needs to be a quick and easy setup
by using GitHub Actions for example rather than having to set everthing in a self hosted enviroment which
could be difficult and cause extra bugs/hassle. It also depends on the complexity of the application
which isn't given but if it was a really complex application then self hosted would fare better so that
more specific testing/checks could be performed as opposed to a cloud enviroment.