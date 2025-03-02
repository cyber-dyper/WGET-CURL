# 🌐 **WGET-CURL**

## 🧠 **Apprends à télécharger en ligne de commande !**  

Bienvenue dans ce guide pratique sur **wget** et **curl**, deux outils incontournables pour télécharger des fichiers directement depuis le terminal.  

Ce guide t'expliquera pourquoi utiliser **wget** sous **Linux** et **curl** sous **Windows** et **macOS**, avec des exemples concrets pour chaque scénario !  

---

## 📚 **Table des Matières**

- [😅 Qu'est-ce que wget et curl ?](#-qu'est-ce-que-wget-et-curl-)
- [🚀 Pourquoi utiliser wget sur Linux et curl sur Windows/macOS ?](#-pourquoi-utiliser-wget-sur-linux-et-curl-sur-windowsmacos-)
- [🔍 Vérifier si wget ou curl est installé](#-vérifier-si-wget-ou-curl-est-installé)
- [💡 Scénarios pratiques d'utilisation](#-scénarios-pratiques-dutilisation)
  - [📡 Scénario 1 : Télécharger un fichier sur Linux avec wget](#-scénario-1--télécharger-un-fichier-sur-linux-avec-wget)
  - [📡 Scénario 2 : Télécharger un fichier sur Windows/macOS avec curl](#-scénario-2--télécharger-un-fichier-sur-windowsmacos-avec-curl)
  - [📡 Scénario 3 : Télécharger plusieurs fichiers avec wget](#-scénario-3--télécharger-plusieurs-fichiers-avec-wget)
  - [📡 Scénario 4 : Tester une connexion HTTP avec curl](#-scénario-4--tester-une-connexion-http-avec-curl)
- [📚 Ressources Utiles](#-ressources-utiles)

---

## 😅 **Qu'est-ce que wget et curl ?**  

### 📦 **wget (Linux)**  

- **wget** (*"web get"*) est un outil en ligne de commande pour **Linux** qui permet de télécharger des fichiers via les protocoles **HTTP**, **HTTPS** et **FTP**.  
- Idéal pour :  
  - 📥 **Télécharger des fichiers volumineux**.  
  - 🌐 **Récupérer des sites web entiers**.  
  - 🔄 **Automatiser des téléchargements répétitifs** dans des scripts appelés "**Bash**".

---

### 🌐 **curl (Windows/macOS)**  

- **curl** (*"client URL"*) est un outil intégré à **Windows 10+** et **macOS**, offrant une large gamme de fonctionnalités.  
- En plus du téléchargement de fichiers, **curl** permet de :  
  - 📨 **Envoyer des requêtes API**.  
  - 💬 **Tester des connexions réseau**.  
  - 🔀 **Utiliser différents protocoles** comme **SFTP**, **SMTP**, **IMAP**, etc.

---

## 🚀 **Pourquoi utiliser wget sur Linux et curl sur Windows/macOS ?**  

### 🐧 **Avantages de wget sur Linux**  

- 📂 **Téléchargement de sites web entiers** pour consultation hors ligne :  

```code
wget -r https://example.com
```
- 🛠️ Utilisation dans les scripts Bash pour automatiser des tâches serveur.
- 🔄 Téléchargement en série à partir d'un fichier de liens :
```bash
wget -i liste_de_liens.txt
```
### 🪟🍏 Avantages de curl sur Windows et macOS
- ✅ curl est déjà installé sur Windows 10+ et macOS, aucune installation nécessaire.
- 🌐 Parfait pour les requêtes API REST, notamment pour envoyer des données POST :
```bash
curl -X POST -d "param1=value1" https://example.com/api
```
- 💻 Utile pour tester les connexions réseau et vérifier les réponses HTTP :
```bash
curl -I https://example.com
```
## 🔍 Vérifier si wget ou curl est installé

`wget --version` ou `curl --version`


Si une version s'affiche, c'est tout bon ! 😊

## 💡 Scénarios pratiques d'utilisation

### 📡 Scénario 1 : Télécharger un fichier sur Linux avec wget
```bash
wget -O fichier.zip https://example.com/fichier.zip
```
📥 Cas d'utilisation : Automatiser le téléchargement de mises à jour logicielles sur un serveur Linux.

### 📡 Scénario 2 : Télécharger un fichier sur Windows/macOS avec curl
```bash
curl -o fichier.zip https://example.com/fichier.zip
```
📥 Cas d'utilisation : Installer un utilitaire en ligne ou télécharger un script de configuration.

### 📡 Scénario 3 : Télécharger plusieurs fichiers avec wget
```bash
wget -i liste_de_liens.txt
```
📥 Cas d'utilisation : Automatiser le téléchargement de plusieurs images ou fichiers texte depuis une liste de liens.

### 📡 Scénario 4 : Tester une connexion HTTP avec curl
```bash
curl -I https://example.com
```
📥 Cas d'utilisation : Vérifier rapidement si un site web répond correctement avec un statut HTTP 200 OK.

## 📚 **Ressources Utiles**

Si tu veux te renseigner davantage sur les commandes wget et curl, je te laisse visiter leur site officiel en anglais.

- 🌍 [Site officiel de wget](https://www.gnu.org/software/wget/)  
- 🌐 [Site officiel de curl](https://curl.se)

Continue ton apprentissage et visite mes autres dépôts 👇 !

- 📁 [GNU-LINUX - Détails sur les distributions](https://github.com/cyber-dyper/GNU-LINUX)  
- 💻 [VIRTUAL-LAB - Crée ton laboratoire virtuel](https://github.com/cyber-dyper/VIRTUAL-LAB)  


___
✨ Amuse-toi bien avec tes téléchargements en ligne de commande ! 🚀😊
