# Types of version control systems.

## There are a lot of different version control systems out there like:
- Subversion (SVN)
- Perforce
- AWS Code Commit
- Mercurial
- Git (Which is the most popular)
------------------
## V.C. systems are in 2 types:
### Centralized: (CVCS)
- we have one server (where the code base repo is located and full history of versions) and client(s).
- clients has only the latest version and always need to it to local device, and push any updates.
- The server is the center.
- Examples of CVCS are `Subversion (SVN)`
### Distributed: (DVCS)
- Here every client is acting as a server, same as centralized but each  client will have a full history of versions of the code base.
### Advantages and Disadvantages of each:
- CVCS is a bit slower because you need to connect to the server for any action or viewing history, but it gives more access control and easier to lear.
- DVCS is faster and allows you to work offline, you need to connect only with pulling or pushing.
- Examples of DVCS are `Mercurial and Git`