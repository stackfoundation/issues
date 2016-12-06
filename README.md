# stack.foundation 
## Public Issue Tracker

## Changelog
*Note that the issue numbers (SF-***) reference internal issue numbers.*

### Release 0.0.6-closed-alpha (December 6, 2016)
- SF-733: Fixed several minor issues with the loading bar, and confirmation modals on the site
- SF-548, SF-468, SF-734, SF-736: Fixed several errors that prevented npm install, and npm postinstall from running properly for Node.js applications

### Release 0.0.5-closed-alpha (November 21, 2016)
- SF-687: Fixed the validation on some fields in our forms
- SF-691: Improved the feedback shown while the databases tab is loading
- SF-697: The position of alert messages in mobile views has been improved
- SF-700, SF-704, SF-716: We guard against form resubmission more robustly
- SF-712: Recognize and use Docker for Mac in client machine
- SF-713, SF-714, SF-728: The documentation has been broken into sections, and several additions and updates were made to the content
- SF-725: Feedback shown when errors occur while loading in the databases has been improved

### Release 0.0.4-closed-alpha (November 7, 2016)
- SF-554, SF-646, SF-682: Loading spinners were added to provide better feedback in certain areas.
- SF-543, SF-647: The maintenance of a logged-in user's session has been improved. In addition, expired sessions are handled better.
- SF-575, SF-654: A bug prevented private applications from being cloned by their owner - this is now fixed.
- SF-560, SF-674: Application logs now show colors if present in the log output.
- SF-566, SF-676, SF-677: The logging during application startup has been improved - logging improvements were made specifically around Maven dependency resolution for Java applications, and npm resolution for Node.js applications.
- SF-685: Some minor design changes were made to the site.
- SF-687, SF-688: Minor fixes were made to the validation of forms on the site.

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
