# 🧠 Action unifiée de Kaluza–Dirac–Einstein  
**Auteur : Bastien Baranoff**  
**Licence : [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)**  

---

## 📘 Présentation
Ce dépôt regroupe l’ensemble des travaux de recherche sur la **théorie unifiée de Kaluza–Dirac–Einstein**,  
ainsi que les développements connexes autour de la **non-localité**, de la **rétro-propagation du gradient**  
et de la **charte des énergies**.

L’objectif : proposer une géométrie unique du champ \( \mathcal{A}_\mu \)  
reliant les quatre interactions fondamentales par un même formalisme de connexion.

---

## 🧩 Structure du dépôt

| Fichier | Description |
|----------|-------------|
| `action_unifie_kaluza.Rmd` | Base du formalisme unifié Kaluza–Dirac–Einstein |
| `kaluza_einstein.Rmd` | Dérivation géométrique de la connexion et de la métrique |
| `gravite_quantifie_et_non_localite.Rmd` | Cohérence quantique et invariance de la gravité |
| `superposition_mort_vivant_bell.Rmd` | Interprétation des inégalités de Bell |
| `tryptique_non_localite.Rmd` | EPR, ER=EPR et causalité symétrique |
| `interferences_trou_de_ver.Rmd` | Onde auto-interférente via un trou de ver |
| `ondes_gravitationnelles_et_mq.Rmd` | Couplage entre gravité et mécanique quantique |
| `densite_coherence.Rmd` | Densité spectrale et cohérence d’état |
| `matrice_Operateurs.Rmd` | Formulation matricielle et opérateurs de champ |
| `retropropagation_gradient.Rmd` | Rétro-causalité constructive et gradient d’erreur |
| `charte_energies.Rmd` | Charte de principes physiques et éthiques |
| `bastien_public.asc` | Clé publique GPG de signature |
| `legalcode.txt` | Licence Creative Commons BY-NC-SA 4.0 |
| `Dolores_Unified_Action.pdf` | Version complète du papier (PDF final signé) |

---


## Compilation directe
```bash
Rscript -e 'bookdown::render_book("action_unifie_kaluza.Rmd", "bookdown::pdf_book")'
```

