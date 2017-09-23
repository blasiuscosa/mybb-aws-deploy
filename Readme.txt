## MyBB Crossover Assignment Solution

# Objective

This document aims to guide through the solution so that it can be easily assessed.

# Solution files

As required the solution contains the following files and directories:

\Code
\Demo
Design.doc
Deployment.doc
Readme.txt

Below I provide a brief description of these files and directories:
1. Readme.txt
2. Demo: This directory contains the video with demonstration of the solution.
3. Design.doc: Describes in high-level the architecture and design of the solution.
4. Deployment.doc: Covers the details of deployment of the solution in a new brand AWS account if necessary.
5. Code: Scripts used to automate the deployment in AWS.

# Assumptions

* It was assumed that high availability in just one region would be enough for the purpose of this exercise.

# Requirements not covered

1. The management system was not created.

2. It was identified that for the MyBB application should have some files synchronized between the webservers 
(avatars and uploaded files). One way to solve this would be to develop a plugin for MyBB that used S3 for those
files instead local filesystem. Alternatively, it could be used a shared file system. None of this were implemented 
and this identified requirement was not covered.

# Feedback

I was very happy working on this exercise! I think one of the positive points was having the requirements a little abstract. That
provide to candidates to use their creativity to provide solutions that may not have been thought before.

# Contact

You can contact me via blasiuscosa@gmail.com
