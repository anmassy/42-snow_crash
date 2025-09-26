# Snow Crash

## Règles du projet

- **Pas de documentation externe** : On doit se débrouiller avec les outils système
- **Pas de brute force** : Chaque niveau a une solution logique
- **Travail individuel** : Pas de collaboration, chacun doit comprendre
- **Documentation obligatoire** : Expliquer chaque étape de résolution
- **Progression linéaire** : Level00 → Level01 → ... → Level14

## Le concept

Snow Crash c'est 15 challenges de sécurité où il faut trouver le flag de chaque level pour passer au suivant. Chaque niveau apprend une technique différente d'exploitation.

## Ce qu'on fait concrètement

- **Reverse engineering** de binaires avec gdb
- **Exploitation** de buffer overflow et format strings  
- **Cryptographie** basique (caesar, base64...)
- **Steganographie** dans des images/fichiers
- **Escalade de privilèges** Unix
- **Analyse** de permissions et processus

## Outils utilisés

```bash
gdb          # debug des binaires
strings      # chercher du texte dans les fichiers
objdump      # désassembler  
hexdump      # voir en hexa
ltrace       # tracer les appels de fonctions
file         # identifier le type de fichier
```

## Ma méthodo

1. **Observer** : `ls -la`, `file`, `strings`
2. **Analyser** : `gdb`, `objdump` si nécessaire  
3. **Exploiter** : buffer overflow, format string, etc.
4. **Documenter** : expliquer la vulnérabilité trouvée

---