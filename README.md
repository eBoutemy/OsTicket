# 📋 osTicket Installer pour Debian

Un script Bash simple pour installer et configurer automatiquement [osTicket](https://osticket.com/) sur Debian 11/12.

---

## 🚀 Fonctionnalités
- Installe Apache, MariaDB, PHP et toutes les dépendances nécessaires.
- Télécharge et déploie automatiquement la dernière version stable d'osTicket.
- Configure la base de données MySQL/MariaDB pour osTicket.
- Prépare Apache avec un Virtual Host dédié.
- Rend osTicket prêt à être installé via l'interface Web.

---

## 📂 Installation rapide

```bash
git clone https://github.com/ton-pseudo/osticket-debian-installer.git
cd osticket-debian-installer
chmod +x install_osticket.sh
sudo ./install_osticket.sh
```

⚡ **En quelques minutes, osTicket est prêt à être configuré depuis votre navigateur !**

---

## ⚙️ Configuration par défaut

🔔 **Pensez à modifier les mots de passe dans le script avant exécution pour plus de sécurité !**

---

## 🌐 Accéder à l'installation Web

Après exécution du script, ouvrez votre navigateur et allez sur :

```text
http://<votre-ip-serveur>/
```

Suivez les instructions pour terminer la configuration d'osTicket.

---

## 🛡️ Sécurisation supplémentaire recommandée
- Utiliser `mysql_secure_installation`.
- Configurer HTTPS avec Let's Encrypt (`certbot`).
- Restreindre les accès SSH.
- Régler les permissions après installation (`ost-config.php` en 0644).

---

- [osTicket](https://osticket.com/)
- [Debian](https://www.debian.org/)
