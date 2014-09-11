Useful git hooks
=====

Dependencies: 
  http://jira-python.readthedocs.org/en/latest/
  
Usage:

Configure your git config file with the following attributes:

* jira.url
* jira.username
* jira.password

Don't forget to give the file execution permission

* chmod +x <script>

Features so far
----

* Comment pattern enforcement
* Branch naming convention enforcement
* Tags naming convention enforcement
* Add a comment on JIRA issue after a commit
* Add a comment on JIRA issue after new branch creation
* Add a comment on JIRA issue after branch deletion
