# Drafts
Ideas for implementing democratic software development.

# Index
1. What would a democratic software development look like?
2. The Network
3. The System of Versioning and Implementing

# What would a democratic software development look like?
To build a social network democratically is just a less general version
of another idea.
Which is to develop software and only implementing it if the changes win an election.
Thus I want to develop a Software Versioning and Implementing System, that would make it
possible to push changes to a decentralised network. 
This network would then hold an election among a set of users
and implement it as the official version, if the elections is won.
And if the software is a server of some kind, the network would also run it.

# The Network
I would use IPFS as a database for the network.
Each node would download the recent version of that data base,
which is  referenced by a single point of reference, a point of trust,
the supervisor.
This supervisor can either be a simple server, run by somebody, you can trust.
Or it is run by a Smart Contract on a Blockchain.

# The System of Versioning and Implementing
The thing we need to build is the system running on the
nodes of the network supervisor.
I call this System, the System of Versioning and Implementing.
This System has to do these things:
1. Provide Source Code and means to build and execute the program
2. Build the Source Code
3. Execute Source Code
4. Version Source Code
5. Hold elections

# How to build the System
I would use Git as the Versioning System
and manager of the repository.
The System would publish the most up to date
version on IPFS and reference the right hash on
IPNS.
It would also have to hold elections
and accept changes for such elections.
This System would thus have these parts:
1. A Git Repository, published on IPFS
2. A Database of Users
3. A Database of Elections 
4. The ability to hold Elections.
