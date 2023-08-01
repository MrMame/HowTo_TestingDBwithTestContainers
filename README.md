# How to setup test database using Testcontainer
This example code was taken from the official Testcontainer webiste.
It will show on how easy it is to get a docker test db running.

[Testcontainer Getting started](https://testcontainers.com/guides/getting-started-with-testcontainers-for-java/)




# Appendix
## Fixing Problem : Could not find a valid Docker environment.
This error can be due to missing user permissions of the active user. Docker needs to Start/Stop Container 
with sudo permissions. Since it cannot be prompt for sudo passwort during runtime it's necessary to
add the active user to the docker user-group.

https://stackoverflow.com/questions/61108655/test-container-test-cases-are-failing-due-to-could-not-find-a-valid-docker-envi

