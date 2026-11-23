# DevOps & Cloud Infrastructure

Ce dépôt regroupe plusieurs travaux pratiques et projets académiques réalisés dans le cadre de ma formation en **Cloud Computing & Cybersécurité à l'Université de Lille (2026)**.

L'objectif est de mettre en pratique différentes technologies et approches DevOps pour concevoir, déployer, automatiser et administrer des infrastructures distribuées.

Les travaux couvrent notamment le provisionnement d'infrastructures, l'automatisation de configurations, la conteneurisation, l'orchestration avec Kubernetes ainsi que la mise en place de services résilients et de mécanismes de réplication de bases de données.

## Technologies utilisées

| Domaine | Technologies |
|---|---|
| Infrastructure Cloud | OpenStack |
| Infrastructure as Code | Terraform / OpenTofu |
| Automatisation | Ansible |
| Conteneurisation | Docker, containerd |
| Orchestration | Kubernetes, Minikube |
| Bases de données | MySQL, PostgreSQL |
| Haute disponibilité | HAProxy, réplication |
| Scripting | Bash, YAML |

## Travaux pratiques

### TP4 — Automatisation et haute disponibilité MySQL
**Outils :** Ansible, MySQL, HAProxy.

Automatisation du déploiement et de la configuration de serveurs MySQL. Mise en place de mécanismes de réplication, de sécurisation et de répartition des connexions avec HAProxy.

[Consulter le rapport](./tp4/rapport.md)

### TP5 — Provisionnement d'infrastructure Cloud
**Outil :** Terraform.

Mise en pratique de l'Infrastructure as Code pour automatiser le provisionnement des ressources d'infrastructure.

[Consulter le rapport](./tp5/README.md)

### TP6 — Déploiement et orchestration Kubernetes
**Outils :** Kubernetes, Minikube, YAML, Ansible.

Découverte et mise en pratique de Kubernetes à travers le déploiement d'applications, la gestion des ressources et l'utilisation de différents objets Kubernetes.

[Consulter le rapport](./tp6/README.md)

### TP7 — Déploiement automatisé d'un cluster Kubernetes
**Outils :** OpenStack, OpenTofu, Ansible, Kubernetes, containerd.

Provisionnement automatisé de machines virtuelles sur OpenStack et déploiement d'un cluster Kubernetes multi-nœuds. Automatisation de la configuration des nœuds, du Control Plane et des Workers.

[Consulter le rapport](./tp7/README.md)

### TP8 — Déploiement PostgreSQL et réplication
**Outils :** Kubernetes, PostgreSQL, YAML, Bash.

Déploiement d'une architecture PostgreSQL composée d'un serveur primaire et de réplicas. Configuration du stockage persistant, des services Kubernetes et des mécanismes de réplication des données.

[Consulter le rapport](./tp8/README.md)

---

## Objectifs et compétences développées

- Automatiser le provisionnement et la configuration d'infrastructures.
- Appliquer les principes de l'Infrastructure as Code (IaC).
- Déployer et administrer des environnements Cloud.
- Mettre en œuvre des architectures distribuées avec Kubernetes.
- Conteneuriser et orchestrer des applications.
- Configurer des bases de données avec réplication.
- Mettre en place des mécanismes de haute disponibilité.
- Structurer et documenter des déploiements reproductibles.

## Organisation du dépôt

```text
devops-infrastructure/
├── README.md
├── tp4/    # Automatisation et haute disponibilité MySQL
├── tp5/    # Provisionnement avec Terraform
├── tp6/    # Déploiements Kubernetes
├── tp7/    # Cluster Kubernetes sur OpenStack
└── tp8/    # PostgreSQL et réplication
```

---

**Auteur :** Jonas Numa  
**Formation :** Master Cybersécurité – Cloud Computing & Cybersécurité  
**Établissement :** Université de Lille  
**Année :** 2026