# biophysique-tp1-lysozyme
TP1 biophysique : structure experimentale du lysozyme (1HEW)
# TP1 – Structure expérimentale de la lysozyme (PDB 1HEW)

TP de biophysique (M2) : analyse d'une structure de protéine obtenue par diffraction des rayons X, avec UCSF ChimeraX.

## Contexte

- *Protéine* : lysozyme de blanc d'œuf de poule (Gallus gallus), 129 résidus, chaîne A
- *Entrée PDB* : [1HEW](https://www.rcsb.org/structure/1HEW)
- *Méthode* : diffraction des rayons X, résolution 1,75 Å
- *Ligand* : tri-N-acétylchitotriose (3 NAG, chaîne B), à occupation partielle
- *Logiciel* : UCSF ChimeraX

## Contenu du dépôt

| Fichier | Description |
|---|---|
| `Figure1.png` | Extrémités N et C, hélice (25-35), feuillet (42-46), boucle (65-75) |
| `Figure2.png` | Pont disulfure Cys 6 – Cys 127 |
| `Figure3.png` | Sucre dans la fente, liaisons hydrogène et contact non polaire |
| `TP1-session.cxs` | Session ChimeraX (à ouvrir avec `open TP1-session.cxs`) |

## Principales mesures

- Ponts disulfures : Cys 6 – Cys 127 (2,086 Å), Cys 30 – Cys 115 (2,081 Å), Cys 64 – Cys 80, Cys 76 – Cys 94
- Liaison hydrogène du squelette : Val 29 N → Leu 25 O (3,12 Å)
- Liaisons hydrogène protéine–sucre : Asn 59 N → NAG 1 O7 (2,841 Å) ; NAG 1 N2 → Ala 107 O (2,799 Å)
- Contact non polaire : Trp 108 CD1 ··· NAG 1 C8 (3,597 Å)

## Référence

Cheetham, Artymiuk et Phillips, J. Mol. Biol. 224, 613–628 (1992), DOI 10.1016/0022-2836(92)90548-X.
