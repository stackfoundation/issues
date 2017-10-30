# stack.foundation 
## Public Issue Tracker
File issues on this repository for the Sandbox CLI.

## Changelog
Issues prefixed INTERNAL are internal issue numbers used by the StackFoundation team.

### Version 0.1.2 (Alpha) - October 30, 2017
- Issue #3: Updated the example in the calling generated workflows section of the docs
- Issue #2: Fix in wrappers for Linux & macOS to set the correct `rwxr-xr-x` permissions on the bootstrap to be called
- Issue #2: Fix to correctly show the Kubernetes dashboard URL in the `sbox status` command on Linux & macOS
- INTERNAL-1303: Fix to properly fail workflows when steps fail, unless otherwise requested
- INTERNAL-1303: Fix to properly cleanup pods and services on step failure
- INTERNAL-1308: Fix elevated execution of VirtualBox install on Windows
- INTERNAL-1314: Allow caching of workflow steps, if desired, using `cache` property
- INTERNAL-1314: Update website docs to document caching of steps
