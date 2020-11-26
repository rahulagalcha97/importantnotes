# importantnotes

--> For installing the gitleaks 

https://computingforgeeks.com/gitleaks-audit-git-repos-for-secrets/      

--> Creating Dynamic Azure Service Principals for Terraform with HashiCorp vault

https://blog.nico-schiering.de/creating-dynamic-azure-service-principals-for-terraform-with-hashicorp-vault/

--> Defect Dojo ( Management app: can take reports from tools like gitleaks,zap,burp and analyze)

Integrations: https://defectdojo.readthedocs.io/en/latest/integrations.html

curl --location --request POST 'http://52.14.220.159:8080/api/v2/import-scan/' --header 'Authorization: Token 301fec2b582e884436617f35a5cdf9e1930a999a' --form 'engagement=6' --form 'verified=true' --form 'active=true' --form 'scan_type=Gitleaks Scan' --form 'file=@/var/lib/jenkins/gitscan1.json
'
