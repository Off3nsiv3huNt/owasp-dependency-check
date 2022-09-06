OWASP dependency-check is an open source solution to the OWASP Top 10 2021 entry: A06:2021 – Vulnerable and Outdated Components. Dependency-check can currently be used to scan software to identify the use of known vulnerable components. For a full list of supported languages/technologies please see the File Type Analyzer page). Note that some of the analyzers are experimental and may produce more false positive and false negative rates. To use the experimental analyzers they must be specifically enabled via the appropriate experimental configuration.

The problem with using known vulnerable components was covered in a paper by Jeff Williams and Arshan Dabirsiaghi titled, “The Unfortunate Reality of Insecure Libraries” (registration required). The gist of the paper is that we as a development community include third party libraries in our applications that contain well known published vulnerabilities (such as those at the National Vulnerability Database).


https://github.com/jeremylong/DependencyCheck
https://hub.docker.com/r/owasp/dependency-check
