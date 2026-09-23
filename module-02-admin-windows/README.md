
# Module 2 — Administration Windows
## Objectifs
- Administrer un poste ou un serveur Windows
- Gérer les utilisateurs et les groupes locaux
- Utiliser les outils d’administration Windows
- Découvrir les commandes PowerShell utiles
## Outils Windows
| Outil | Utilité |
|---|---|
| Gestionnaire des tâches | Consulter les processus et les performances |
| Gestion de l’ordinateur | Administrer les utilisateurs, disques et services |
| Observateur d’événements | Consulter les journaux système et les erreurs |
| PowerShell | Automatiser et administrer Windows en ligne de commande |
| Windows Admin Center | Administrer des serveurs depuis une interface Web |
## Utilisateurs et groupes locaux
Un utilisateur possède un compte pour se connecter à Windows. Un groupe permet d’attr
Exemples de groupes locaux :
- `Administrateurs` : droits élevés sur le poste
- `Utilisateurs` : droits standards
- `Utilisateurs du Bureau à distance` : autorisation de connexion à distance
## Commandes PowerShell
```powershell
Get-ComputerInfo
Get-LocalUser
Get-LocalGroup
5. Exemple — Module 2 : Administration Windows
Get-Service
Get-Process
```
| Commande | Rôle |
|---|---|
| `Get-ComputerInfo` | Affiche des informations sur le poste |
| `Get-LocalUser` | Liste les utilisateurs locaux |
| `Get-LocalGroup` | Liste les groupes locaux |
| `Get-Service` | Liste les services Windows |
| `Get-Process` | Liste les processus en cours d’exécution |
## Exemple réalisé en TP
Nous avons vérifié les comptes locaux du poste avec la commande :
```powershell
Get-LocalUser
```
