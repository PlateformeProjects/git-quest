# 📋 SOLUTION POUR LE FORMATEUR

## Étapes de résolution :

### 1. Premier fragment
```bash
git log --oneline
# Le message "Vieux souvenir - Fragment: GIT" contient le premier indice
```

### 2. Découverte de l'île secrète  
```bash
git branch -a
# Révèle l'existence de la branche "ile-secrete"
git checkout ile-secrete
cat indices/fragment2.txt  # Contient: _QUEST
```

### 3. Fusion et trésor final
```bash
git checkout main
git merge ile-secrete
# Après résolution du conflit :
cat indices/tresor.txt  # Révèle: _2024
```

### Code final : **GIT_QUEST_2024**
