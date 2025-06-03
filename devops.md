#### 1. The Pipeline Detective
The Prompt:
```
Analyze this CI/CD pipeline error and suggest possible fixes:

[Paste your error logs here]
Context:
- We're using GitHub Actions with a Node.js application
- Tests pass locally but fail in the pipeline
- This started happening after upgrading dependencies yesterday
```

#### 2. The Infrastructure Writer
“I need to explain our complex infrastructure to the new team members,” thought Priya, technical lead at a growing startup. The architecture had evolved organically over three years and documenting it seemed overwhelming.

The Prompt:
```
Convert this infrastructure description into clear, comprehensive documentation with appropriate sections:

[Describe your infrastructure components, connections, and dependencies]
Please include:
1. A high-level architectural overview
2. Key components and their purposes
3. Data flow between services
4. Security considerations
5. Common failure points and mitigations
```

#### 3. The Script Whisperer
The rain pattered against the office windows as Dev hunched over his laptop. He needed to write a shell script to automate a tedious server maintenance task, but shell scripting wasn’t his strong suit.

The Prompt:
```
Create a bash script that:
- Backs up all MySQL databases
- Compresses the backups
- Uploads them to S3
- Deletes backups older than 7 days
- Sends a status email with success/failure details

Include error handling, logging, and comments explaining complex parts. I'm running this on Ubuntu 22.04
```

#### 4. The Monitoring Mastermind
The alerts kept coming, one after another. Elena’s phone buzzed constantly with notifications, most of which weren’t actionable. “There must be a better way to configure our monitoring,” she thought.

The Prompt:
```
Help me optimize these Prometheus alerting rules:

[Paste your current alerting rules]
We're experiencing:
- Too many false positives for CPU spikes
- Missing alerts for actual database connection issues
- Alerts that don't provide enough context for triage
Our environment: Kubernetes cluster with 30 microservices, primarily Go and Java applications, PostgreSQL and Redis for storage.

[Paste your current alerting rules]
We're experiencing:
- Too many false positives for CPU spikes
- Missing alerts for actual database connection issues
- Alerts that don't provide enough context for triage
Our environment: Kubernetes cluster with 30 microservices, primarily Go and Java applications, PostgreSQL and Redis for storage.
```

#### 5. The Terraform Architect
James stood at the whiteboard, sketching out the infrastructure for a new project. The requirements were complex: multi-region deployment, strict security needs, and cost optimization. Translating this into Terraform code would normally take days.

The Prompt:
```
Generate Terraform code for AWS infrastructure with:
- Load-balanced web tier in 2 availability zones
- Auto-scaling application tier
- RDS database with read replicas
- S3 for static assets with CloudFront CDN
- Appropriate security groups and IAM roles
- Tags for all resources for cost allocation

Include documentation comments and follow Terraform best practices for organization and variable usage.
```

#### 6. The Documentation Generator
“We need better runbooks for on-call engineers,” Wei told his team during their retrospective. Three incident responses had taken longer than necessary because procedures weren’t clearly documented.

The Prompt:
```
Create a comprehensive incident response runbook for our MySQL database failures.

Include:
- Initial assessment steps
- Common causes and their specific symptoms
- Step-by-step recovery procedures for each scenario
- Escalation criteria and contact information
- Post-incident analysis template
Make it accessible for engineers with basic database knowledge but who aren't database experts.
```

#### 7. The Security Sentinel
The company Slack channel exploded with messages when news of the latest critical vulnerability hit. Nadia, the security lead, needed to assess exposure across dozens of services quickly.

The Prompt:
```
Analyze this vulnerability (CVE-2023-XXXXX) for our environment:

Vulnerability details:
[Paste details from security advisory]
Our environment:
- 40 microservices running Java 17 and Node.js 18
- Using Spring Boot 2.7.x and Express 4.x
- Containerized with Docker, deployed on Kubernetes
- External-facing APIs behind Cloudflare WAF
Provide:
1. Assessment of our potential exposure
2. Specific services/components likely affected
3. Immediate mitigation steps
4. Long-term remediation plan
```