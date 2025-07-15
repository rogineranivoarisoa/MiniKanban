# MiniKanban

Petit projet .NET Core - Test technique "Mini-Kanban"

## 📌 Description

API .NET Core simulant un tableau Kanban simplifié pour la gestion des tâches d'équipe.

- Créer des tâches avec titre, description et utilisateur assigné
- Changer leur statut (ToDo → InProgress → Done)
- Suivi des historiques des changements
- Gestion des utilisateurs

---

## 📌 Technologies utilisées

- ASP.NET Core 8
- Entity Framework Core (InMemory)
- .NET 8

---

## 📌 Instructions pour lancer le projet (Back-end uniquement)

1. **Prérequis :**
   - .NET 8 SDK installé

2. **Cloner le repo :**
   ```bash
   git clone https://github.com/ton-nom-utilisateur/MiniKanban.git
   cd MiniKanban
Restaurer les packages :

dotnet restore

Lance l'API
dotnet run
