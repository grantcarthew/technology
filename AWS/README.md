# Amazon Web Services

## AWS Resources

* [AWS Documentation](https://docs.aws.amazon.com/index.html)
* [AWS Management Console](https://console.aws.amazon.com/)
* [AWS News Blog](https://aws.amazon.com/blogs/aws/)
* [What's New with AWS](https://aws.amazon.com/new/)
* [AWS Application Architecture](https://aws.amazon.com/architecture/)
* [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/)
* [10-Minute Tutorials](https://aws.amazon.com/getting-started/tutorials/)
* [Awesome AWS (GitHub)](https://github.com/donnemartin/awesome-aws)

## Content

* [News Articles](News.md)
* [Videos](#videos)
* [Training Resources](#training-resources) - Links to educational resources.
* [Tools](#aws-tools) - Supporting tools and code resources.
* [Tagging Resources](#tagging-resources)
* [Security](#security)
* [Hands-on](/AWS/Hands-on)
* [Services](Services)

## Videos

* 2013-11-14: [A Day in the Life of a Billion Packets (CPN401) | AWS re:Invent 2013](https://www.youtube.com/watch?v=Zd5hsL-JNY4) - VPC Creation and Function.
* 2012-12-03: [AWS re: Invent ENT 205 - Drinking Our Own Champagne](https://www.youtube.com/watch?v=f45Uo5rw6YY)

## Training Resources

* [AWS Training and Certification](https://aws.amazon.com/training/)
* [AWS Training Dashboard](https://www.aws.training/)
* [AWS Architecture Centre](https://aws.amazon.com/architecture/)
* [AWS Certification](https://aws.amazon.com/certification/)
* [Qwiklabs](https://aws.qwiklabs.com/)
* [AWS This is My Architecture](https://aws.amazon.com/this-is-my-architecture/)
* [AWS FAQs](https://aws.amazon.com/faqs/)
* [Amazon's Machine Learning University is making its online courses available to the public](https://www.amazon.science/latest-news/machine-learning-course-free-online-from-amazon-machine-learning-university)

### Exam Resources

* [Whizlabs](https://www.whizlabs.com/) ([StackSocial - Whizlabs Lifetime Membership](https://stacksocial.com/sales/whizlabs-lifetime-membership))
* [Tutorials Dojo](https://tutorialsdojo.com/)
* [Varun Karthik: Advanced Architect Certification Notes](https://github.com/vforvarun/AWS-SA-PRO-PREP)

## Automation

* [troposphere](https://github.com/cloudtools/troposphere) - library to create AWS CloudFormation descriptions
* [The Serverless Application Framework](https://www.serverless.com/)
* [Pulumi](https://www.pulumi.com/) - Modern Infrastructure as Code for Developers and Infrastructure Teams
* [Amplify CLI](https://docs.amplify.aws/cli) - Unified toolchain to create, integrate, and manage the AWS cloud services for your app
* [InGraph](https://github.com/lifadev/archive_ingraph) - Declarative Infrastructure Graph DSL for AWS CloudFormation
* [CDK for Terraform](https://www.hashicorp.com/blog/cdk-for-terraform-enabling-python-and-typescript-support)
* [Terraform](https://www.terraform.io/) - Write infrastructure as code using declarative configuration files
* [Former2](https://former2.com) ([GitHub](https://github.com/iann0036/former2)) - Generate IaC outputs from your existing resources within your AWS account.

### AWS CloudFormation Resources

* [AWS CloudFormation](https://aws.amazon.com/cloudformation/)
* [AWS CloudFormation Documentation](https://docs.aws.amazon.com/cloudformation/index.html)
* [Getting Started](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/GettingStarted.Walkthrough.html)
* [AWS CloudFormation Templates](https://aws.amazon.com/cloudformation/aws-cloudformation-templates/)
* [AWS Quick Starts](https://aws.amazon.com/quickstart/)
* [AWS Labs GitHub Organization](https://github.com/awslabs)
* [Creating a stack from existing resources](https://docs.amazonaws.cn/en_us/AWSCloudFormation/latest/UserGuide/resource-import-new-stack.html)

## Tools

* [AWS Control Tower](https://aws.amazon.com/controltower/)
  * [Control Tower Workshops](https://controltower.aws-management.tools/)

### Command Line Interface

* [What is the AWS Command Line Interface?](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)
* [Install the CLI](https://aws.amazon.com/cli/)

To configure access:

```sh

$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-west-2
Default output format [None]: ENTER

```

### Web Tools

* [Edge Location Speed Test](http://s3-accelerate-speedtest.s3-accelerate.amazonaws.com/en/accelerate-speed-comparsion.html?region=ap-southeast-2)
* Browser Extensions:
  * [AWS Console Recorder](https://github.com/iann0036/AWSConsoleRecorder)
  * [AWS Extend Switch Roles](https://github.com/tilfin/aws-extend-switch-roles)

### Third-Party Tools

* [Cloudcraft: Draw AWS Diagrams](https://cloudcraft.co/)
* [Dome9: Cloud Infrastructure Security, AWS Security Monitoring](https://dome9.com/)
* [Spotinst: Cloud Workload Automation](https://spotinst.com/)
* [Cloud Conformity](https://www.cloudconformity.com/)
* [RBAC Management Pipeline](https://github.com/mechanicalpete/rbac-management-pipeline)
* [LocalStack](https://github.com/localstack/localstack) - A fully functional local AWS cloud stack.

### Automation Tools

* [Terraform](https://www.terraform.io/)
* [Pulumi](https://www.pulumi.com/)
* [CDK](https://aws.amazon.com/cdk/)
* [Architect](https://arc.codes/docs/en/guides/get-started/quickstart)

## Tagging Resources

* [AWS Resource Groups](https://docs.aws.amazon.com/ARG/index.html)
* [Tagging Your Amazon EC2 Resources](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Using_Tags.html)

## Security

* [AWS Security Services](https://aws.amazon.com/products/security/)
* [OWASP Top Ten](https://owasp.org/www-project-top-ten/)
* [AWS Network Firewall](https://aws.amazon.com/blogs/aws/aws-network-firewall-new-managed-firewall-service-in-vpc/)
* [AWS WAF](https://aws.amazon.com/waf/):
  * [AWS WAF Tutorials - Preconfigured Rules & Tutorials](https://aws.amazon.com/waf/preconfiguredrules/)
  * [How do I block common attacks with AWS WAF?](https://aws.amazon.com/premiumsupport/knowledge-center/waf-block-common-attacks/)
  * [AWS WAF Security Automation with CloudFormation](https://docs.aws.amazon.com/solutions/latest/aws-waf-security-automations/template.html)
* [AWS Shield](https://aws.amazon.com/shield/):
  * [AWS Shield Threat LandscapeReport Q1 2020](https://aws-shield-tlr.s3.amazonaws.com/2020-Q1_AWS_Shield_TLR.pdf)
  
### Third Party Security Services

* [ModSecurity](https://www.modsecurity.org/) ([GitHub](https://github.com/SpiderLabs/ModSecurity)) - Open Source WAF
* [Let's Encrypt](https://letsencrypt.org/)
  * [Standing on Our Own Two Feet](https://letsencrypt.org/2020/11/06/own-two-feet.html)

## DevOps

* [Whitepaper: Blue/Green Deployments on AWS](https://d1.awsstatic.com/whitepapers/AWS_Blue_Green_Deployments.pdf)