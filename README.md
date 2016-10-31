# stack.foundation 
## Public Issue Tracker

## Changelog
*Note that the issue numbers (SF-***) reference internal issue numbers.*

### Release 0.0.3-closed-alpha (October 28, 2016)
- SF-637: An updated stack.foundation JDBC driver was released that can be used by Java applications running on stack.foundation that require database connectivity.
- SF-627, SF-644, SF-614, SF-601: Git history (file structure, and commit messages) was not being displayed correctly when browsing through Git repositories on the stack.foundation site - this was especially the case following changes being pushed after an application was running. Changes were made to address these issues.
- SF-625: Java code that used generics did not display properly when viewing Java source files on the stack.foundation site. This is now fixed.
- SF-577, SF-630: Some minor fixes were made to make the progress monitoring on the database screens more reliably show progress.
- SF-626, SF-632: A new Spring Boot JPA seed project was added that demonstrates connectivity to databases from Java applications running on stack.foundation.
- SF-594, SF-622, SF-633, SF-640: Updates were made to the getting started guide, especially to include a discussion on connecting to a database from a Java application running on stack.foundation.
- SF-638: An error is now shown when an attempt is made to add a named database that already exists.

### Release 0.0.2-closed-alpha (October 19, 2016)
- SF-599, SF-612: When viewing the source code for a specific file while browsing through an application's repository, switching branches did not change the content of the file to the content within the branch. This is now fixed.
- SF-600, SF-607, SF-609: If an application has compilation errors, they were printed in the logs but the application still continued to load. On compile errors for classes used during application startup, the error is now logged more visibly, and the application will fail to startup.
- SF-604: If an application was deleted and a new application with the same name was created, cloning the application using the Git command line resulted in retrieval of stale application content. This is now fixed.
- SF-603: If the user reaches their application limit, a warning alert was not displayed. This is now shown.
- SF-564: Prevent double submission of forms. Fixed the display of certain field errors on forms.
- SF-613: Improve the notification for the server being down, especially for maintenance
