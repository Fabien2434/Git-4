# Git/GitHub 4 : Branche et flow

# 🚀 Challenge Git : Création et Fusion d'une Branche

## 📌 Étapes suivies

### 1️⃣ Création du dépôt sur GitHub  
- **Nom du dépôt** : `website-flow`  
- **Option cochée** : ✅ Initialisation avec un `README.md`  

### 2️⃣ Clonage du dépôt en local  
```bash
git clone https://github.com/mon-utilisateur/website-flow.git
cd website-flow
3️⃣ Création et passage sur une nouvelle branche cheese
bash
Copier
Modifier
git checkout -b cheese
4️⃣ Modification du fichier README.md
Ajout du contenu suivant :

markdown
Copier
Modifier
## 🧀 Mes fromages préférés pour une pizza

- Mozzarella
- Gorgonzola
- Parmesan
- Cheddar
- Emmental
5️⃣ Validation et envoi des modifications
bash
Copier
Modifier
git add README.md
git commit -m "Ajout de mes fromages préférés pour une pizza 🍕"
git push origin cheese
6️⃣ Création d'une Pull Request et fusion avec main
Sur GitHub, une Pull Request a été ouverte depuis cheese vers main.
Une fois la fusion effectuée, la branche cheese est supprimée.
7️⃣ Suppression de la branche cheese
bash
Copier
Modifier
git branch -d cheese
git push origin --delete cheese

Remplace **`mon-utilisateur`** par ton pseudo GitHub avant de partager ! 
