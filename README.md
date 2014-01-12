jenkins_test
============

Test repository to test jenkins push behaviour after builds.

The idea is to commit into a local repository. Have Jenkins build the project and if the build succeeds the changes
should be committed github.

Ok i now have two references HEAD and master o_O

* 12.01.2014 new test
** had to run git config remote.github_repo.url "<github url>" in a shell script