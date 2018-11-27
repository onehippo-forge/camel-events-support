[![Build Status](https://travis-ci.org/bloomreach-forge/camel-events-support.svg?branch=develop)](https://travis-ci.org/bloomreach-forge/camel-events-support)

# Apache Camel - Hippo Events Support

Apache Camel - Hippo Events Support provides: 
- A **hippoevent:** Apache Camel component
- A Camel Repository Scheduler Job component which can invoke a Camel Endpoint URI
- Utility classes to help integration between Hippo CMS/Repository and Apache Camel.

# Documentation 

Documentation is available at [bloomreach-forge.github.io/camel-events-support](https://bloomreach-forge.github.io/camel-events-support)

The documentation is generated by this command from the master branch:

 > mvn clean site:site -Pgithub.pages 
 
The output is in the ```/docs``` directory; push it and GitHub Pages will serve the site automatically. 

For rendering documentation on non-master branches, use the normal site command so the output will be in the ```/target``` 
and therefore ignored by Git.

 > mvn clean site:site