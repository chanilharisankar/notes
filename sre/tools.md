# Helpful tools

1. TDD for Infrastructure
    * [inspec](https://www.inspec.io/docs/)
    * awspec
    * pytest + boto
    * AWS CDK for AWS CloudFormation
    * Terratest for Terraform
    * [DOJO for testing docker containers](https://github.com/kudulab/dojo#docker-compose-driver)
    * [ServerSpec for testing docker containers](https://github.com/moritzheiber/playing-port-authority) - [video](https://www.youtube.com/watch?v=B4yvo-O4AL4)
    * [moto](https://github.com/spulec/moto)
      * library that allows you to easily mock out tests based on AWS infrastructure
    * [shellcheck](https://github.com/koalaman/shellcheck)
      * GPLv3 tool that gives warnings and suggestions for bash/sh shell 
    * [Therapist](https://github.com/rehandalal/therapist)
      * A lint suite runner with Git-aware capabilities and a smart pre-commit hook
    * [taskcat](https://github.com/aws-quickstart/taskcat)
      * TaskCat is a python framework for validation of Cloudformation templates
    * [bats](https://github.com/sstephenson/bats)
      * TAP-compliant testing framework for Bash
    * [tflint](https://github.com/terraform-linters/tflint)
      * terraform lint
    * [localstack](https://github.com/localstack/localstack)
      * Develop and test your cloud & Serverless apps offline
    * [yamllint](https://github.com/adrienverge/yamllint)
      * A linter for YAML files
    * [Molecule](https://molecule.readthedocs.io/en/stable/)
      * development and testing of Ansible roles
    * [chart-resting](https://github.com/helm/chart-testing) 
      * testing helm chart 

2. command-line tool to inject secrets as environment variables
   * [summon](https://cyberark.github.io/summon)
3. detect file changes when they're working on code 
    * [entr](https://www.systutorials.com/docs/linux/man/1-entr/)
4. network debug tools
    * dig
    * Ngrep
5. code analysis tool 
    * [codescene](https://codescene.io/)
