## Pourquoi ce changement ?
<!-- Le problème résolu, ou le besoin couvert. Lien vers le ticket si applicable. -->

## Ce qui change
-
-

## Comment le vérifier
```bash
./mvnw test


# Chaque regle associe un motif de fichiers a des relecteurs OBLIGATOIRES.
# La DERNIERE regle qui correspond l'emporte.

# Par defaut, toute l'equipe
* Frostvide

# Le code metier exige une relecture
/src/main/java/ Frostvide

# Les fichiers d'infrastructure et de CI
/.github/workflows/ Frostvide
/pom.xml Frostvide
