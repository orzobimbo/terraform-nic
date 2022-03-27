# terraform-nic

## aws
13/03/2022 - file numero: 01
- [reference-official](#reference-official)
- [reference](#reference)
- [void](#void)
- [void](#void)
- [void](#void)
- [void](#void)
- [void](#void)
- [void](#void)
---
### reference-official

---
### reference

---
### note

---
### iam
https://youtu.be/7xngnjfIlK4?t=1341
settare utente IAM per utilizzare Terraform:
- nella sezione `IAM`
- dalla sidebar cliccare su `Gestione degli accessi` > `Gruppo di utenti`
- cliccare sul bottone `Crea gruppo`

Assegnare i seguenti ruoli:
- AmazonRDSFullAccess
- AmazonEC2FullAccess
- IAMFullAccess
- AmazonS3FullAccess
- AmazonDynamoDBFullAccess
- AmazonRoute53FullAccess

---
### installare-aws-cli
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

Per installare la cli di aws eseguire:
```
msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi
```

Per controllare se la cli è installata:
```
aws --version
```

la CLI l'ho installata nel percorso:
```
D:\Programmi\Amazon\AWSCLIV2
```


---
### login-to-aws
eseguire:
```
aws configure
```

...e fornire: 
- `AWS Access Key ID`:
- `AWS Secret Access Key`:
- `Default region name [None]`: eu-west-1 e premere invio
- `Default output format [None]`: premere invio

Per ottenere la `AWS Access Key ID` e `AWS Secret Access Key`:
https://console.aws.amazon.com/iamv2/home?#/users
- nella sezione `IAM`
- dalla sidebar cliccare su `Gestione degli accessi` > `utenti`
- cliccare su un utente a scelta
- cliccare sul tab `Credenziali di sicurezza`
- cliccare sul bottone `Creare chiave di accesso`
- copiare il valore nel campo `ID chiave di accesso`
- copiare il valore nel campo `Chiave di accesso segreta`


Vengono generati i file:
- config
- credentials

Io li ho generati nel percorso: `C:\Users\User\.aws`

---
### aws_instance
EC2
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance
```
```
---
### aws_vpc
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc
```
```
---
### void
```
```
---
### void
```
```
---
### void
```
```

---
### [TORNA-SU](#aws)
