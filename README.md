## Hi! I'm Soufiyane 👋

```hcl
resource "github_repository" "about_me" {
  name        = "soufiyane"
  description = "Cloud Engineer | AI Enthusiast"
}

resource "info" "soufiyane" {
  name    = "Soufiyane AIT MOULAY"
  location = "Marrakech, Morocco"

  certifications = [
    "AWS Certified Cloud Practitioner",
    "AWS Certified Solutions Architect",
    "AWS Certified Developer",
    "HashiCorp Certified: Terraform"
  ]

  skills = [
    "AWS Cloud Computing",
    "Serverless Architectures",
    "AI Integration",
    "Infrastructure as Code (IaC): Terraform, CloudFormation, SAM"
  ]

  current_role = "System and Cloud Engineer"
  education = [
    "Double Master's in Artificial Intelligence - Université Côte d’Azur, Nice",
    "Engineer’s Degree in Computer Science - EMSI, Marrakech",
  ]

  currently_learning = "Oracle Cloud Infrastructure (OCI)"
}
