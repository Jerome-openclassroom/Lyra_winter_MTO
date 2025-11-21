# Étude de cas : Mistral froid, stratocumulus glacés et goutte froide méditerranéenne  
*Analyse humaine + IA assistée (Lyra) – 21 novembre 2025*

## Mise à jour importante
Cette version intègre explicitement que **Jérôme** a :
- identifié le **jetstream ondulant**,
- repéré l’**ondulation du front polaire**,
- déduit l’**advection de vorticité cyclonique** en altitude,
- détecté l’**abaissement local de la tropopause** → **goutte froide / cut‑off**,
- reconnu l’association **ACCAS + Cb noyés** sur une Méditerranée encore chaude,
- ce que l’IA (Lyra) a confirmé en précisant le rôle des **ondes de Rossby**.

Ce README documente l’ensemble du raisonnement : observation → microphysique → synoptique → dynamique → radiosondage.

---

## 1. Contexte du cas
Observation à Avignon sous mistral fort (~30 kt) avec un ciel d’arrière perturbation présentant des stratocumulus d’aspect inhabituel : lissés, homogènes, légèrement cirriformes. Cette signature visuelle conduit à une hypothèse de nuages glacés laminés, rare pour cette région.

<p align="center">
  <img src="nuages.jpg" alt="Stratocumulus glacés sous mistral – Avignon 2025" width="70%">
</p>


---

## 2. Données et fichiers du dépôt

- `nuages.jpg` – photo d’observation  
- `petit_emagramme.jpg` – radiosondage de Nîmes  
- `pression.jpg` – carte du champ de pression  
- `temsi_france.pdf` – TEMSI France (SFC–FL100)  
- `temsi_euroc.pdf` – TEMSI EUROC (FL150–450)

---

## 3. Méthodologie : humain + IA
### Contribution humaine (Jérôme)
- Observation fine de l’aspect nuageux.
- Hypothèse microphysique (stratocumulus glacés).
- Détection autonome :
  - **Jetstream ondulant**,  
  - **Ondes de Rossby**,  
  - **Advection de vorticité cyclonique**,  
  - **Abaissement de tropopause (FL220)**,  
  - **Goutte froide en altitude**,  
  - **ACCAS + Cb noyés** sur mer chaude.
- Lecture intégrée METAR / TEMSI / synoptique / radiosondage.

### Contribution IA (Lyra)
- Mise en forme scientifique et structuration du raisonnement.
- Clarification pédagogique des processus :  
  ondes de Rossby, PVA (Positive Vorticity Advection), cut‑off, divergence en altitude.
- Harmonisation du récit scientifique.

---

## 4. Résultats synthétiques
### Microphysique
Stratocumulus glacés à basse altitude, sublimation de la fraction liquide, effet de cisaillement et polissage par mistral sec.

### Synoptique
Flux polaire continental, iso 0°C très bas, stratus bas sur Massif central, mistral renforcé par gradient et effet Venturi.

### Dynamique d’altitude
Jet ondulant ~100 kt, ondes de Rossby, advection de vorticité cyclonique, tropopause abaissée → **goutte froide**.  
ACCAS et Cb isolés sur mer chaude = **instabilité méditerranéenne**.

### Validation verticale
Radiosondage : saturation vers 800 hPa (~6000 ft) à –10°C, inversion laminante, vent N en troposphère puis Ouest en stratosphère.

---

## 5. Arborescence du dépôt

```
Lyra_winter_MTO
├── README.md
├── README_en.md 
├── nuages.jpg
├── petit_emagramme.jpg
├── pression.jpg
├── temsi_france.pdf
└── temsi_euroc.pdf
```

---

## 6. Conclusion
Ce cas montre comment une **observation visuelle précise**, associée à une **analyse humaine experte** et à une **IA structurant le raisonnement**, permet de reconstruire un phénomène atmosphérique complet :  
mistral froid → stratocumulus glacés → jet ondulant → advection de vorticité → goutte froide → convection méditerranéenne.
