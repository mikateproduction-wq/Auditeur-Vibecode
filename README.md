# Auditeur-Vibecode

**Auditeur-Vibecode** est un outil d'analyse statique destiné à évaluer la probabilité qu'une application soit issue du *vibe coding* (code généré par IA). En scannant la structure des répertoires et les fichiers sources (Python, Java, Web...), l'outil calcule un indice de probabilité et fournit un rapport de conformité.

---

## Fonctionnalités

* **Analyse multi-langages** : Prise en charge des fichiers Python, Java, Web (HTML/CSS/JS) et autres langages courants.
* **Détection des motifs IA** : Repérage des commentaires hyper-descriptifs, des structures récurrentes et des tournures typiques des LLM.
* **Score de probabilité** : Calcul d'un indice évaluant la part estimée de code généré automatiquement.
* **Bilan de conformité** : Analyse de la lisibilité, du respect des conventions et de la maintenabilité du projet.

---

## Installation

```bash
git clone [https://github.com/mikateproduction-wq/Auditeur-Vibecode.git](https://github.com/mikateproduction-wq/Auditeur-Vibecode.git)
cd Auditeur-Vibecode
