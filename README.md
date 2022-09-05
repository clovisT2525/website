
Projects
---
if you hire me as a  Sr. DevOps Engineer in your company. you want me to
implement DevOpsLifecycle in your company. You asked me to implement
this lifecycle as fast as possible. And you are a product-based company, yours 
product is available on this GitHub link.
https://github.com/clovisT2525/website.git
Following are the specifications of the lifecycle:

1. Install the necessary software on the machines using a configuration management tool.

2. Git Workflow has to be implemented

3.Code Build should automatically be triggered once commit is made to
master branch or develop branch.

If commit is made to master branch, test and push to prod
If commit is made to develop branch, just test the product, do not push to prod

4.The Code should be containerized with the help of a Dockerfile. The
Dockerfile should bebuilt every time there is a push to Git-Hub. Use the
following pre-built container for your application:
clovisT2525/webapp
The code should reside in '/var/www/html'

5.The above tasks should be defined in a Jenkins Pipeline, with the
following jobs:

Job1 : build
---
Job2: test
---
Job3 : prod
---

