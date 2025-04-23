# How to contribute

MariaDB Server has a vibrant community contributing in a wide range of areas. There are many valuable ways you can contribute to MariaDB.

## 1. Contributing code
--- 

### 1.1 Do you have an idea for a new feature to code? First write the specs into Jira!
----
**Use case:** You have a new idea for a feature, and you want to code it as part of MariaDB.

We strongly encourage you to create an MDEV with a feature specification in [Jira](https://jira.mariadb.org) before writing code and submitting a Pull Request. Your intent should be crystal clear.

This way, we can give you specification level feedback about whether we think the feature belongs in MariaDB, including feedback on the specs, syntax, naming, functionality, compatibility, maintenance burden, and architecture.

Should you be daring enough to send a PR without having got specification level feedback, we will still first look at the specs, only then at the code. Hence, we need you to be specific about the intent of your code. We cannot review code if you don’t say what you’re shooting for!

### 1.2 Do you want to code a feature with an existing MDEV? Sanity check the basics!
----
**Use case:** You want a new feature that is already specified in [Jira](https://jira.mariadb.org), and want to implement it.

We encourage you to verify that the MDEV is in the “Approved for Development" aka "Confirmed” status.

If the MDEV is not yet approved for development, and if you are still interested in developing the feature, please communicate with us using Jira comments, with the goal to make the MDEV specific and clear enough to be moved to the “Approved for Development” status. 

### 1.3 Do you want to fix a bug? Sanity check the basics!
----
**Use case:** You have found a bug in MariaDB, and think you can fix it.

We encourage you to apply your judgement that the bug has a discrete fix. If the bug has an MDEV and fixing it does not touch many different areas of code, it’s probably OK to submit an MDEV. If the bug doesn’t yet have an MDEV, we encourage you to first submit one to [Jira](https://jira.mariadb.org) – as that is how we track the bugs.

### 1.4 Do you want to show what you’re made of? Pick an MDEV that is fun and doable!
----
**Use case:** You want to spread your wings and prove yourself to future employers and/or customers.

We encourage you to browse around our MDEVs which are labelled “[Beginner friendly](https://jira.mariadb.org/browse/MDEV-15736?jql=resolution%20%3D%20Unresolved%20AND%20labels%20%3D%20beginner-friendly%20ORDER%20BY%20updated%20DESC)”. We also encourage you to use AI assistance by asking Cursor to help you with coding the MDEV. You can prompt it for help pointing to the URL of the MDEV; the suggestions are surprisingly insightful.

### 1.5 Practical steps
----

Once you are ready to get coding: 

1. Fork and fetch the code from [mariadb/server](https://github.com/mariadb/server)
2. Compile it
3. Test it 
4. Write a patch
5. Submit a pull request
6. Make sure tests pass [buildbot](https://buildbot.mariadb.org/#/)
7. Wait for feedback and merge

See [Getting Started for Developers](https://mariadb.org/getting-started-for-developers) for further details.


## 2. Other ways to contribute to MariaDB
---

### 2.1 Help document MariaDB
----
-   Contribute towards [documenting MariaDB Server](https://mariadb.com/kb/en/meta/writing-editing-library-articles/) and its ecosystem by adding new content or improving existing content.
-   [Translate](https://mariadb.com/kb/en/meta/translating-library-articles/)  existing documentation.

### 2.2 Help develop MariaDB
----
-   [Report bugs in Jira](https://jira.mariadb.org/)
-   Test development versions
-   [MariaDB KB: Getting Started for Developers](https://mariadb.org/getting-started-for-developers)
-   Help with code quality control
-   Participate in packaging for different Linux distributions
-   Coding standards for the main source code can be found in [CODING_STANDARDS.md](CODING_STANDARDS.md).

### 2.3 Attend or host a MariaDB event or conference
----
-   [Events and Conferences page](https://mariadb.org/events/)
-   [MariaDB Server Community on meetup.com](https://www.meetup.com/pro/anna-widenius/)

### 2.4 Sponsor or donate to MariaDB Foundation
----
You’re very welcome to support MariaDB Server as an individual, or talk your company into joining the Foundation as a sponsoring member. See the  [Sponsor page](https://mariadb.org/donate/).

## 3. Contribution support
---

### 3.1 Where to find fellow community members
----
-   [MariaDB Zulip Chat](https://mariadb.zulipchat.com/)
-   [MariaDB issue tracker on Jira](https://jira.mariadb.org)
-   Mailing lists
	-   [maria-developers mailing list](http://launchpad.net/~maria-developers)
	-   [maria-discuss mailing list](http://launchpad.net/~maria-discuss)
	-   [maria-docs mailing list](http://launchpad.net/~maria-docs)
-   [/r/mariadb on reddit](https://www.reddit.com/r/mariadb/)
-   and other [social media](https://mariadb.com/kb/en/mariadb/social-media/).

### 3.2 Participate in Live QA for beginner contributors
----
MariaDB has a dedicated time each week when we answer new contributor questions live on Zulip. From 8:00 to 10:00 UTC on Mondays, and 10:00 to 12:00 UTC on Thursdays, anyone can ask any questions they’d like, and a live developer will be available to assist. New contributors can ask questions any time, but we will provide immediate feedback during that interval.


## 4. Additional resources
----
 - [MariaDB Foundation ](https://mariadb.org/)
 - [Knowledge Base](https://mariadb.com/kb/en/)
