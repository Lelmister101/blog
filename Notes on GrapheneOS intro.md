# Notes on GrapheneOS
This is a new blog series that I'm creating about the privacy and security enhancements in GrapheneOS. This series intends to provide third party sources on GrapheneOS's work, as well as a bit of code analysis. It also attempts to be well sourced and relatively neutral. I will also attempt to show which mitigations result in what impact on usage, in order to let users determine if and how the added security is worth it. Statements from the project will be given in order to give their rationale on implementing the feature, but most of the sources will be non-GrapheneOS or will be code commits.
Enhancements to be covered:
- [Exec spawning](https://github.com/Lelmister101/blog/blob/main/Notes%20on%20GrapheneOS:%20Exec%20spawning.md)
- Kernel hardening (the linux-hardened project)
- hardened_malloc
- Sandboxed Google Play Services

The rest of the features may also be covered, but focus is given to these features due to the many misconceptions about their effect on security and how they are valuable.

Note: This blog mainly focuses on security at the moment, but GrapheneOS is also a privacy focused project, adding many features such as the network/sensors permissions, as well as MAC randomization.
