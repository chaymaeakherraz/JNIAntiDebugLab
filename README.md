# JNIAntiDebugLab

## Description
Ce laboratoire Android montre comment utiliser JNI et le NDK pour intégrer du code C++ dans une application Android et ajouter une couche simple de détection anti-debug.

L’application :
- charge une bibliothèque native avec JNI ;
- exécute des fonctions C++ ;
- détecte un environnement suspect ;
- affiche le résultat dans l’interface Android.

---

## Technologies utilisées
- Android Studio
- Java
- C++
- JNI
- Android NDK
- CMake
- Logcat

---

## Fonctionnalités
- Communication Java ↔ C++
- Méthode native `helloFromJNI()`
- Calcul factoriel en C++
- Méthode native `isDebugDetected()`
- Affichage de l’état de sécurité
- Logs natifs dans Logcat

---

## Structure du projet

```text
app/
 └── src/main/
     ├── cpp/
     │   ├── CMakeLists.txt
     │   └── native-lib.cpp
     ├── java/com/example/jniantidebuglab/
     │   └── MainActivity.java
     ├── res/layout/
     │   └── activity_main.xml
     └── AndroidManifest.xml
```
## Compilation et exécution
Ouvrir le projet dans Android Studio
Installer NDK + CMake + LLDB depuis SDK Manager
Synchroniser le projet Gradle
Build → Rebuild Project
Lancer l’application



https://github.com/user-attachments/assets/88fb597d-052e-49b9-bf66-ff5a96efc49f




