# Project Ageratum: Launching an AWS EC2 instance with Jenkins installed

A CloudFormation template to launch an EC2 instance having Jenkins installed.


### Dependencies

* None

### Installing

* Clone the repository.
* Create a S3 bucket and make it public.
* Create the folders - 0040-ageratum/cft
* Upload the YAML template ageratum-stack.yaml to 0040-ageratum/cft
* Create the entire using by using the CloudFormation template ageratum-stack.yaml by providing the required parameters.
* Once the instance is created, open a SSH session and get the initial password by executing 
```
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```
* Login to Jenkins using the URL from the Outputs section  (Key : JenkinsURL) and using the administrator password from the previous step.
* Create a admin user and log in to Jenkins


## Help

Email me at subhamoyb@yahoo.com


## Authors

Contributors names and contact info

Subhamay Bhattacharyya  - [subhamoyb@yahoo.com](https://subhamay.blog)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under Subhamay Bhattacharyya. All Rights Reserved.

## Acknowledgments

Inspiration, code snippets, etc.
* [Rajdeep Saha] (https://www.linkedin.com/in/rajdeep-sa-at-aws/)
* [Stephane Maarek](https://www.linkedin.com/in/stephanemaarek/)
* [Neal Davis](https://www.linkedin.com/in/nealkdavis/)
* [Adrian Cantrill](https://www.linkedin.com/in/adriancantrill/)
