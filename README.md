# EV Station Monitor

Petit projet pour suivre l'état de bornes de recharge électrique, déployé sur AWS.

Fait dans le cadre de ma candidature pour l'alternance Cloud chez Schneider Electric.

## Ce que j'ai utilisé

- **AWS S3** pour héberger le site
- **Terraform** pour créer l'infra en code
- **GitHub Actions** pour déployer automatiquement à chaque push

## Comment ça marche

Je push du code → GitHub Actions se déclenche → il envoie les fichiers sur S3 → le site est mis à jour.

## Lancer l'infra

```bash
cd terraform
terraform init
terraform apply
```
