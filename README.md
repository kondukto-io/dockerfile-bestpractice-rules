# dockerfile-bestpractices-rules

This repository contains a list of semgrep rules that can be used to enforce some security and best practices in dockerfiles.
The best practices that we followed are:
- Enforcing a “custom” distroless image.
- Using rootless containers.
- Effective user control (user must be the “app” user).
- Checking the health-check instructions.
- Using a multistage build.

Shifting tests and evaluations left in the CI/CD pipeline is a key aspect of DevSecOps. And adopting a secure by default approach 
will improve organizations' security posture dramatically.

You can find a detailed explanation of the rules in the following [link](https://kondukto.io/blog/docker-security-best-practices-with-semgrep).

*Feel free to reach us for your questions and comments.*
