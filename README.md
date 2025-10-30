# Multi QR - Générateur & Lecteur de QR Code

Application web pour générer et lire des QR Codes avec de nombreuses fonctionnalités.

## ✨ Fonctionnalités

### Générateur de QR Code
- **Multi‑format**
  - URL/Lien de site
  - Texte
  - Configuration Wi‑Fi
  - Contact (vCard)
  - E‑mail
  - Téléphone

- **Personnalisation**
  - Taille du QR Code : 256×256 px
  - Niveau de correction d’erreur : Élevé (30%)
  - Format de sortie : PNG

- **Résultat**
  - Aperçu en direct
  - Téléchargement en image PNG
  - Création d’un nouveau QR en un clic

### Lecteur de QR Code
- **Entrées multiples**
  - Caméra (avant/arrière)
  - Import d’image
  - Glisser‑déposer (desktop)

- **Caméra**
  - Détection de la caméra arrière
  - Aperçu en temps réel
  - 10 FPS

- **Détection intelligente**
  - Lien : ouverture automatique dans un nouvel onglet
  - Wi‑Fi : copie de la configuration
  - Téléphone : appel direct
  - E‑mail : ouverture du client mail
  - Texte : copie dans le presse‑papiers

## 🚀 Technologies
- HTML5
- Tailwind CSS
- JavaScript (Vanilla)
- QRCode.js
- HTML5‑QRCode

## 💻 Utilisation

### Créer un QR Code
1. Sélectionnez l’onglet « Générateur »
2. Choisissez le type de QR Code
3. Renseignez les informations nécessaires
4. Cliquez sur « Générer le QR Code »
5. L’aperçu du QR Code apparaît
6. Cliquez sur « Télécharger » pour enregistrer
7. Cliquez sur « Créer un nouveau QR » pour réinitialiser

### Lire un QR Code
1. Sélectionnez l’onglet « Lecteur »
2. Choisissez une méthode d’entrée :
   - Cliquez sur « Ouvrir la caméra » pour scanner
   - Importez une image
   - Glissez‑déposez un fichier (desktop)
3. Le résultat du scan apparaît automatiquement
4. Utilisez le bouton d’action selon le type
5. Cliquez sur « Copier » pour copier le résultat

## 📱 Design responsive
- Interface responsive pour desktop et mobile
- Optimisations spécifiques par plateforme
- Glisser‑déposer sur desktop
- Bouton d’import dédié sur mobile

## 🎨 UI/UX
- Mode sombre
- Animations fluides
- États de chargement
- Feedback visuel
- Gestion des erreurs
- Boutons d’action contextuels

Application conçue mobile‑first, en mode sombre, pour un usage confortable sur tous les appareils.

## ✨ Points forts

### 1. Générateur multi‑types
- Prend en charge :
  - 🔗 URL
  - 📝 Texte
  - 📶 Wi‑Fi
  - 👤 Contact
  - 📧 E‑mail
  - 📞 Téléphone
- Champs dynamiques selon le type choisi
- Aperçu en temps réel
- Téléchargement en un clic

### 2. Lecteur de QR Code
- 📸 Scan via la caméra du périphérique
- 🖼️ Import d’image QR Code
- 📋 Copie du résultat dans le presse‑papiers
- Affichage clair et lisible

### 3. Expérience utilisateur
- 🌙 Mode sombre exclusif
- 📱 Design mobile‑first
- ✨ Animations fluides
- 💫 Transitions douces
- 🎯 Champs intuitifs

## 🚀 Guide rapide

### Générateur
1. Choisissez le type de QR Code
2. Remplissez les champs selon le type :
   - **URL** : adresse du site
   - **Texte** : contenu libre
   - **Wi‑Fi** : SSID, mot de passe, sécurité
   - **Contact** : nom, téléphone, e‑mail, adresse
   - **E‑mail** : adresse, objet, message
   - **Téléphone** : numéro
3. Cliquez « Générer le QR Code »
4. Téléchargez avec « Télécharger »

### Lecteur
1. Ouvrez l’onglet « Lecteur »
2. Méthodes :
   - « Ouvrir la caméra »
   - « Importer une image de QR »
3. Le résultat s’affiche automatiquement
4. Utilisez « Copier » pour copier

## 🛠️ Pile technique

- **HTML5** – structure
- **Tailwind CSS** – styles
- **JavaScript** – logique
- **QRCode.js** – génération
- **html5‑qrcode** – lecture
- **LocalStorage** – historique local

## 📁 Arborescence

```
multi-qr/
├── index.html      # Point d’entrée de l’appli
├── style.css       # Styles & animations
├── script.js       # Logique JavaScript
└── README.md       # Documentation
```

## 💡 Conseils

1. **Mode hors‑ligne**
   - Fonctionne sans internet
   - Tout se passe dans le navigateur
   - Résultats générés/scannés conservés localement

2. **Thème sombre**
   - Conçu pour faible luminosité
   - Contrastes optimisés

3. **Mobile‑first**
   - Idéal sur smartphone/tablette
   - Responsive sur desktop

4. **Champs dynamiques**
   - S’adaptent au type de QR
   - Placeholders informatifs

## 📝 Points importants

- Autorisez l’accès à la caméra pour le scan
- Assurez‑vous d’une image claire pour l’import
- Téléchargement direct du QR généré
- Historique stocké dans le navigateur (optionnel)

## 🔒 Vie privée & sécurité

- 100% hors‑ligne (offline‑first)
- Aucune donnée envoyée au serveur
- Traitement entièrement local
- Pas besoin d’internet pour les fonctions principales

---

Créé avec ❤️ par Dzarel
