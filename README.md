# OpenStack Heat – 3 services

## Description
Ce projet montre un exemple basique d'Infrastructure as Code avec OpenStack Heat.

Le template crée :
- Un réseau Neutron
- Un port Neutron
- Une machine virtuelle Nova

## Prérequis
- OpenStack installé et fonctionnel
- Accès à la CLI OpenStack
- Image nommée `ubuntu`
- Flavor `m1.small`
- Keypair `mykey`

## Déploiement
```bash
openstack stack create -t template.yaml stack_demo
