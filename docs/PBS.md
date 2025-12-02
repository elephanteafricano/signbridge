# Product Breakdown Structure (PBS) – SignBridge

## 1. Traduction LSF → Français
### 1.1 Capture & Entrées
- Flux caméra
- Vidéos importées

### 1.2 Analyse Visuelle
- Détection des mains / bras
- Pose estimation
- Extraction du mouvement

### 1.3 Interprétation & Classification
- Reconnaissance du signe
- Interprétation séquentielle

### 1.4 Production
- Génération texte
- Synthèse vocale (TTS)

---

## 2. Traduction Français → LSF
### 2.1 Entrées
- Texte
- Audio → Speech-to-Text

### 2.2 Analyse linguistique
- Parsing de la phrase
- Mapping vers signes

### 2.3 Génération
- Séquençage des gestes
- Synchronisation mouvement / rythme

### 2.4 Avatar
- Animation 3D des signes
- Expression faciale et posture

---

## 3. Mode Apprentissage
### 3.1 Dictionnaire
- Liste des signes
- Vidéos / animations
- Explications

### 3.2 Leçons
- Parcours d’apprentissage
- Exercices
- Validation

### 3.3 Correcteur par Caméra
- Capture du signe
- Analyse du geste
- Feedback et scoring

---

## 4. Front-end
### 4.1 Interface Traduction
- Module LSF → FR
- Module FR → LSF

### 4.2 Interface Apprentissage
- Leçons
- Dictionnaire
- Historique progression

### 4.3 Espace Utilisateur
- Profil
- Sauvegarde progression
- Paramètres

---

## 5. Backend / API
### 5.1 Authentification
- Comptes utilisateurs
- Permissions

### 5.2 API Traduction
- Appels aux modèles IA
- Gestion des flux vidéo / audio

### 5.3 API Apprentissage
- Stockage progression
- Gestion des leçons

### 5.4 Dictionnaire
- Base de données des signes

---

## 6. Modèles IA
### 6.1 Données
- Dataset LSF
- Préprocessing

### 6.2 Vision
- Pose estimation
- Classification gestes

### 6.3 Génération Avatar
- Paramétrage mouvements
- Animation automatique

### 6.4 Pipeline ML
- Entraînement
- Tests
- Versionning des modèles

---

## 7. Outils Projet
### 7.1 Documentation
### 7.2 Présentation / Pitch / Promo
### 7.3 Organisation GitHub
