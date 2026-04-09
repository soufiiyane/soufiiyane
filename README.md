## Hi! I'm Soufiyane 👋

```hcl
resource "github_repository" "about_me" {
  name        = "soufiyane"
  description = "DevOps & Cloud Engineer | AI Enthusiast"
}

resource "info" "soufiyane" {
  name    = "Soufiyane AIT MOULAY"
  location = "Marrakech, Morocco"

certifications = [
  "AWS Certified Cloud Practitioner",
  "AWS Certified Solutions Architect – Associate",
  "AWS Certified Developer – Associate",
  "HashiCorp Certified: Terraform Associate",
  "Google Cloud Associate Cloud Engineer",
  "Kubernetes and Cloud Native Associate (KCNA)",
  "Kubernetes and Cloud Native Security Associate (KCSA)",
  "Certified Kubernetes Application Developer (CKAD)",
  "Certified Kubernetes Administrator (CKA)",
  "Certified Kubernetes Security Specialist (CKS)",
]

  skills = [
    "AWS Cloud Computing",
    "Kubernetes"
    "Serverless Architectures",
    "AI Integration",
    "Infrastructure as Code (IaC): Terraform, CloudFormation, SAM"
  ]

  current_role = "DevOps & Cloud Engineer"
  education = [
    "Engineer’s Degree in Computer Science - EMSI, Marrakech",
  ]
}
