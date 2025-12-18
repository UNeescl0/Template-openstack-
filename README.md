# Template-openstack-
Ce dépôt contient un template Heat (YAML) qui déploie 3 services OpenStack :  Réseau (Neutron)  Port (Neutron)  Machine virtuelle (Nova)

OpenStack Heat – 3 services

## Description
Ce projet montre un exemple basique d'**Infrastructure as Code** avec **Heat**.

Le template crée :
- Un réseau Neutron
- Un port Neutron
- Une machine virtuelle Nova

## Prérequis
- OpenStack installé et fonctionnel
- Accès CLI OpenStack
- Image `ubuntu` existante
- Flavor `m1.small`
- Keypair `mykey`
