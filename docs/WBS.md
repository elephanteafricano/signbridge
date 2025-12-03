# Work Breakdown Structure (WBS) – SignBridge

## 1. Traduction LSF → Français

### 1.1 Acquisition & Prétraitement
- Capture caméra (webcam / mobile)
- Gestion des vidéos importées
- Normalisation du flux
- Extraction des keypoints (mains / visage / posture)

### 1.2 Reconnaissance des signes
- Classification des signes statiques
- Détection des transitions entre signes
- Reconnaissance séquentielle
- Filtrage des prédictions / réduction du bruit

### 1.3 Traduction en Français
- Interprétation linguistique
- Génération du texte final
- Gestion ponctuation / structure
- Synthèse vocale (optionnelle)

---

## 2. Traduction Français → LSF

### 2.1 Entrées utilisateur
- Texte écrit
- Reconnaissance vocale (Speech-to-Text)
- Nettoyage et segmentation du texte

### 2.2 Analyse linguistique & mapping LSF
- Parsing linguistique
- Détection des concepts importants
- Conversion en gloss LSF
- Application de règles simples de grammaire LSF

### 2.3 Génération de séquences
- Découpage en signes successifs
- Gestion du rythme / pauses
- Fluidification des transitions
- Export de la séquence vers l’avatar

---

## 3. Avatar LSF (Animation du modèle)

### 3.1 Conception du modèle
- Choix 2D / 3D
- Design mains / visage
- Style graphique

### 3.2 Rigging
- Rig des mains
- Rig du visage
- Rig du corps
- Systèmes IK/FK

### 3.3 Animations
- Création ou capture des signes
- Transitions entre animations
- Synchronisation avec le rythme

### 3.4 Intégration & rendu
- Rendu temps réel
- API d’animation
- Intégration front-end

---

## 4. Mode Apprentissage

### 4.1 Dictionnaire LSF
- Liste de signes
- Vidéos / animations de référence
- Recherche et filtres
- Explications du gloss

### 4.2 Leçons
- Parcours d’apprentissage
- Exercices progressifs
- Déblocage des niveaux
- Suivi de progression

### 4.3 Correcteur visuel
- Capture du signe utilisateur
- Analyse du geste
- Comparaison avec le signe attendu
- Feedback visuel et scoring

---

## 5. Front-end

### 5.1 Interfaces Traduction
- UI LSF → FR
- UI FR → LSF
- Visualisation caméra
- Affichage de l’avatar

### 5.2 Interfaces Apprentissage
- Dictionnaire
- Leçons
- Exercices interactifs
- Vue progression

### 5.3 Interfaces Utilisateur
- Profil utilisateur (optionnel)
- Paramètres
- Accessibilité & ergonomie

### 5.4 Intégration API
- API traduction
- API avatar
- API apprentissage

---

## 6. Backend / API

### 6.1 Architecture serveur
- Structure des endpoints
- Gestion flux vidéo/audio
- Sécurité de base

### 6.2 Services Traduction
- API vision
- API texte → gloss
- API gloss → séquence avatar

### 6.3 Services Apprentissage
- Gestion progression
- Gestion leçons / exercices
- Gestion dictionnaire

### 6.4 Stockage
- Base signes
- Base utilisateurs (optionnel)
- Stockage vidéos / animations

---

## 7. IA / Data

### 7.1 Dataset
- Collecte vidéos LSF
- Annotation
- Nettoyage
- Organisation train / val / test

### 7.2 Entraînement des modèles
- Modèle vision
- Modèle séquence
- Modèle traduction
- Modèle synchronisation avatar

### 7.3 Tests & évaluation
- Précision / recall
- Benchmarks internes
- Améliorations itératives

### 7.4 Pipeline ML
- Versionning des modèles
- Scripts d’entraînement
- Documentation ML

---

## 8. Outils & Documentation

### 8.1 Documentation
- Architecture
- API
- Conventions d’équipe

### 8.2 Communication & Promotion
- Pitch
- Slides
- GitHub Pages

### 8.3 Organisation interne
- Gestion Git
- Planning / tickets
- Suivi des risques

---

# High-level Description des Fonctions

### Traduction LSF → Français
Analyse vidéo, détection des gestes, interprétation, génération texte et audio.

### Traduction Français → LSF
Analyse texte/voix, mapping linguistique, animation avatar 3D.

### Mode Apprentissage
Dictionnaire, leçons, correcteur utilisant la caméra.

### Front-end
Interfaces traduction, apprentissage, utilisateur.

### Backend
API, auth, progression, dictionnaire.

### IA / Data
Datasets LSF, entraînement modèles, pipeline ML.

### Outils
Doc, planning, promo.
