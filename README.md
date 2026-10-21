# Dzhuneyt Ahmed

CTO at Provenant · Cloud infrastructure consultant · AWS Community Builder

I design, build and run cloud infrastructure on AWS for companies that need it to be reliable and not expensive. I have shipped production software since 2012, and I went from backend developer to CTO along the way. I still write the code.

[Website](https://dzhuneyt.com) · [LinkedIn](https://www.linkedin.com/in/juneit/) · [Book a 30-minute call](https://calendly.com/dzhun/30min) · [Stack Overflow](https://stackoverflow.com/users/1364793/dzhuneyt)

## How I work

I zoom out to set direction and zoom in to fix the exact line that breaks. Most problems need both, and I switch to whichever level the problem needs at the time.

| Zoomed out | Zoomed in |
| --- | --- |
| Became CTO as Protokol pivoted to building its own product. Now I lead engineering at Provenant, its spin-off. | 8 merged pull requests in AWS CDK, for example a fix for [Lambda `grantInvoke` called twice with different principals](https://github.com/aws/aws-cdk/pull/20174) |
| Architecture that puts cost first: right-sizing, spot capacity, serverless where it pays off | A [Terraform module](https://github.com/Dzhuneyt/terraform-aws-ecs-cluster) that runs ECS on a mix of spot and on-demand EC2 |
| Ran a 12-person agency: technical direction, mentoring, growing the client base | Replaced `microtime()` with [`hrtime()` in Guzzle](https://github.com/guzzle/guzzle/pull/2242) for monotonic, high-resolution timing |

## What I work on

- **AWS architecture:** serverless (Lambda, API Gateway, AppSync, DynamoDB, SQS/SNS), containers (ECS, EKS), and cost reduction.
- **Infrastructure as code:** AWS CDK, Terraform, SST and CloudFormation.
- **Delivery:** CI/CD with GitHub Actions and CodePipeline, OIDC-based deployments, multi-account AWS.
- **Languages:** TypeScript, Go, Python, Java and PHP.

## Experience

| Role | Company | Years |
| --- | --- | --- |
| Solutions Architect → CTO | Protokol → Provenant (spun off from Protokol) | 2021 – now |
| Co-founder, CTO | ScavaSoft, a 12-person software agency in Varna, Bulgaria | 2019 – 2023 |
| Backend developer → Team lead | Docebo. I joined at about 30 people. It listed on NASDAQ in 2020. | 2012 – 2019 |

## Certifications and community

| | Certification | Earned |
| --- | --- | --- |
| <img src="https://images.credly.com/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" width="60" alt="AWS Certified Solutions Architect – Associate badge"> | [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/ed626109-2bc1-4090-b6ec-3cf7d3e65db6/public_url) | 2023 |
| <img src="https://images.credly.com/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/image.png" width="60" alt="AWS Certified Cloud Practitioner badge"> | [AWS Certified Cloud Practitioner](https://www.credly.com/badges/9f04f98c-11a3-420a-a4a1-807a0b9963cc/public_url) | 2022 |

AWS Community Builder since 2022.

## Open source

**[aws/aws-cdk](https://github.com/aws/aws-cdk): 8 merged pull requests**

- [feat(cognito): allow retrieval of UserPoolClient generated client secret](https://github.com/aws/aws-cdk/pull/21262)
- [feat(batch): add default AWS_ACCOUNT and AWS_REGION to Batch container](https://github.com/aws/aws-cdk/pull/21041)
- [fix(lambda): grant invoke twice with different principals](https://github.com/aws/aws-cdk/pull/20174)
- [feat(aws-ec2): enable/disable EC2 "Detailed Monitoring"](https://github.com/aws/aws-cdk/pull/19437)
- [fix(lambda): validate Lambda "functionName" parameter](https://github.com/aws/aws-cdk/pull/17970)
- [fix(aws-appsync): strip unsupported characters from Lambda DataSource](https://github.com/aws/aws-cdk/pull/18765)
- [feat(core): improved Docker bundling performance on macOS](https://github.com/aws/aws-cdk/pull/8766)

**Other merged contributions**

- [composer/composer](https://github.com/composer/composer/pull/7880): `--no-cache` argument for `composer install` and `composer update`
- [guzzle/guzzle](https://github.com/guzzle/guzzle/pull/2242): replace `microtime()` with `hrtime()`
- [yiisoft/yii2](https://github.com/yiisoft/yii2/pull/17009): support for the `u` modifier in regex validators, plus the [Bulgarian translation](https://github.com/yiisoft/yii2/pull/17010)
- [awesome-cdk/cdk-report-codepipeline-status-to-github](https://github.com/awesome-cdk/cdk-report-codepipeline-status-to-github/pull/4): migration to AWS CDK v2, and [npm trusted publishing via OIDC](https://github.com/awesome-cdk/cdk-report-codepipeline-status-to-github/pull/5)
- [RobHofmann/HomeAssistant-GreeClimateComponent](https://github.com/RobHofmann/HomeAssistant-GreeClimateComponent/pull/442): auto-clear a stale encryption key after repeated update failures

## Tools I built

| Project | What it does |
| --- | --- |
| [terraform-aws-ecs-cluster](https://github.com/Dzhuneyt/terraform-aws-ecs-cluster) | Terraform module for an ECS cluster of spot and on-demand EC2 instances |
| [cf-purge](https://github.com/Dzhuneyt/cf-purge) | Deletes CloudFormation stacks that match a pattern |
| [nuke-orphan-buckets](https://github.com/Dzhuneyt/nuke-orphan-buckets) | Deletes S3 buckets that no CloudFormation stack manages |
| [aws-cdk-get-stack-output](https://github.com/Dzhuneyt/aws-cdk-get-stack-output) | Reads output values from deployed AWS CDK stacks |
| [skill-docs2md](https://github.com/Dzhuneyt/skill-docs2md) | AI agent skill that crawls a docs site into one Markdown file, so the agent reads current docs |

## Teaching and writing

- **Udemy:** [Creating a Serverless API that Scales](https://www.udemy.com/course/aws-cdk-serverless-api/). 4,354 students, rated 4.4/5.
- **Blog:** [dzhuneyt.com](https://dzhuneyt.com) covers AWS, CDK, DevOps, security and AI in engineering teams.

---

Open to consulting on AWS architecture, migrations and cloud cost reduction. [Book a call](https://calendly.com/dzhun/30min).
