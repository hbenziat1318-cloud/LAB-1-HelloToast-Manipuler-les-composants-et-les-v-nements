# TP HelloToast - Application Android

##  Description
Application Android simple développée en Java permettant d'afficher des messages Toast et d'incrémenter un compteur.

##  Objectifs du TP
- Découverte du développement Android avec Java
- Manipulation des composants d'interface (TextView, Button)
- Gestion des événements utilisateur (clics)
- Utilisation des messages Toast
- Mise à jour dynamique de l'interface

##  Technologies utilisées
- **Langage** : Java
- **SDK Android** : API 24 (Android 7.0 Nougat) minimum
- **IDE** : Android Studio
- **Gradle** : Groovy DSL

##  Structure du projet
```
HelloToastFinal/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/hellotoastfinal/
│   │   │   └── MainActivity.java
│   │   ├── res/layout/
│   │   │   └── activity_main.xml
│   │   └── AndroidManifest.xml
│   └── build.gradle
└── build.gradle
```

##  Fonctionnalités implémentées

###  Fonctionnalité 1 : Message Toast
- **Bouton** : "Afficher un message"
- **Action** : Affiche un message temporaire "Bonjour Toast !"
- **Technique** : `Toast.makeText().show()`

###  Fonctionnalité 2 : Compteur incrémental
- **Bouton** : "Incrémenter le compteur"
- **Action** : Augmente la valeur affichée de +1 à chaque clic
- **Technique** : `setText()` sur TextView

##  Installation et exécution

### Prérequis
- Android Studio installé
- SDK Android API 24+
- Émulateur Android ou appareil physique

### Étapes de lancement
1. **Ouvrir le projet** dans Android Studio
2. **Synchroniser** Gradle : `File → Sync Project with Gradle Files`
3. **Choisir la cible** : Émulateur ou appareil connecté
4. **Lancer l'application** : Bouton  Run

## Démonstration

### Interface utilisateur
```
[Afficher un message] 
[Incrémenter le compteur]
```

## Encadrement & Auteur
**Encadré par**:Mr.LACHGAR mohammmed
<br>
**Réalisée par**:BENZIAT hana

