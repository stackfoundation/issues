# stack.foundation 
## Public Issue Tracker

## Changelog
*Note that the issue numbers (SF-***) reference internal issue numbers.*

### Release 0.0.2-closed-alpha (October 19, 2016)
- SF-599, SF-612: When viewing the source code for a specific file while browsing through an application's repository, switching branches did not change the content of the file to the content within the branch. This is now fixed.
- SF-600, SF-607, SF-609: If an application has compilation errors, they were printed in the logs but the application still continued to load. On compile errors for classes used during application startup, the error is now logged more visibly, and the application will fail to startup.
- SF-604: If an application was deleted and a new application with the same name was created, cloning the application using the Git command line resulted in retrieval of stale application content. This is now fixed.
- SF-603: If the user reaches their application limit, a warning alert was not displayed. This is now shown.
- SF-564: Prevent double submission of forms. Fixed the display of certain field errors on forms.
- SF-613: Improve the notification for the server being down, especially for maintenance
