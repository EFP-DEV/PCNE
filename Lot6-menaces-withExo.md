# Menaces virtuelles

## Ingénierie sociale & usurpation

### 1. **Phishing**

* **Description** : Tentatives d'usurpation via email ou SMS.
* **Bonne habitude** : Toujours vérifier l’expéditeur et ne pas cliquer sans réflexion.
* **Mauvaise habitude** : Cliquer sur des liens suspects.
* **Solutions** : Antispam, anti-phishing (Google Safe Browsing).
* **Impact** : Financier, réputationnel. — **Criticité** : 4/5
* **Cible** : Employés, comptabilité.
* **Exercices pédagogiques** :
  * [Quizz interactif : Email légitime ou phishing ?](https://www.guardey.com/fr/anti-phishing-games/)
  * [Quizz Email](https://www.ftc.gov/business-guidance/small-businesses/cybersecurity/quiz/phishing)
  * [Quizz Tech Support Scam](https://www.ftc.gov/business-guidance/small-businesses/cybersecurity/quiz/tech-support-scam)
  * Démo : Analyse en direct d’un email (entête, lien, pièce jointe).

### 2. **Usurpation de compte**

* **Description** : Prise de contrôle d’un compte via mot de passe volé ou deviné.
* **Bonne habitude** : Utiliser 2FA, mots de passe uniques.
* **Mauvaise habitude** : Réutiliser les mots de passe.
* **Solutions** : Gestionnaire de mots de passe, 2FA obligatoire. [BitWarden](https://bitwarden.com/)
* **Impact** : Financier, opérationnel. — **Criticité** : 4/5
* **Cible** : Employés, IT.
* **Exercices** :
  * Atelier : création de mots de passe robustes.
  * Mini-jeu : identifier le mot de passe le plus faible. [Tester](https://www.security.org/how-secure-is-my-password/)
  * Simulation : activer la 2FA sur un service courant. 

### 3. **Business Email Compromise (BEC)**

* **Description** : Fraude par usurpation d’identité d’un dirigeant pour détourner des fonds.
* **Bonne habitude** : Vérifier les demandes par un second canal.
* **Mauvaise habitude** : Répondre sans vérification.
* **Solutions** : DMARC, SPF, authentification de domaine.
* **Impact** : Financier, juridique. — **Criticité** : 5/5
* **Cible** : Direction, comptabilité.
* **Exercices** :
  * Cas pratique : repérer les signaux faibles.
  * Jeu d’enquête : retracer un faux email.
  * Démonstration : mise en place SPF/DMARC.

### 4. **Partage non sécurisé de documents**

* **Description** : Envoi de fichiers sensibles via des moyens non sécurisés.
* **Bonne habitude** : Lien avec expiration et mot de passe.
* **Mauvaise habitude** : Partage sans restriction.
* **Solutions** : Outils sécurisés (Tresorit, Dropbox Pro).
* **Impact** : Réputationnel, juridique. — **Criticité** : 3/5
* **Cible** : Employés, RH, commerciaux.
* **Exercices** :
  * Démo : créer un lien sécurisé.
  * Quizz : repérer les erreurs de partage.
  * Atelier : sécuriser un dossier cloud.
  * [Partage de documents via email et OneDrive - Exercices corrigés](https://www.exocours.com/exercices/Microsoft+Word/Partage+documents+email+OneDrive+Exercices+corrig%C3%A9s/1161)

---

## Logiciels malveillants & infections

### 1. **Malwares**

* **Description** : Logiciels conçus pour endommager ou infiltrer un système.
* **Bonne habitude** : Mise à jour régulière, vigilance.
* **Mauvaise habitude** : Téléchargement de logiciels crackés.
* **Solutions** : Antivirus, sandboxing, pare-feu.
* **Impact** : Opérationnel. — **Criticité** : 4/5
* **Exercices** :
  * Jeu : identifier les fichiers ou sites à risque.
  * Démonstration : malware en sandbox.
  * Quizz : réactions face à une alerte antivirus.

### 2. **Ransomwares**

* **Description** : Logiciels qui chiffrent les fichiers et exigent une rançon.
* **Bonne habitude** : Sauvegardes hors-ligne régulières.
* **Mauvaise habitude** : Ouvrir des fichiers suspects.
* **Solutions** : Sauvegarde auto, détection comportementale.
* **Impact** : Financier, opérationnel. — **Criticité** : 5/5
* **Exercices** :
  * Quizz ransomware [Quizz EN](https://www.ftc.gov/business-guidance/small-businesses/cybersecurity/quiz/ransomware)
  * Démo : impact sur fichiers non sauvegardés.
  * Exercice : configurer une sauvegarde hors-ligne.

### 3. **Spywares / Keyloggers**

* **Description** : Logiciels espions collectant des données à l’insu de l’utilisateur.
* **Bonne habitude** : Installer des logiciels vérifiés.
* **Mauvaise habitude** : Ignorer les permissions.
* **Solutions** : Antispyware, comptes limités.
* **Impact** : Financier, réputationnel. — **Criticité** : 4/5
* **Exercices** :
  * Atelier : permissions abusives.
  * Quizz : comportements typiques d’un spyware.
  * Démo : capture de frappe par keylogger simulé.

### 4. **Adwares malveillants**

* **Description** : Publicités non sollicitées installées avec des programmes.
* **Bonne habitude** : Privilégier le logiciel open-source.
* **Mauvaise habitude** : Extensions douteuses.
* **Solutions** : Bloqueurs pub, pare-feux DNS.
* **Impact** : Opérationnel. — **Criticité** : 2/5
* **Exercices** :
  * Jeu : repérer les faux boutons de téléchargement.
  * Quizz : extension sécurisée ou douteuse ?
  * Exercice : nettoyage de navigateur.

### 5. **Fausse mise à jour logicielle**

* **Description** : Faux messages de mise à jour menant à l'installation de malwares.
* **Bonne habitude** : Téléchargement via site officiel.
* **Mauvaise habitude** : Chercher des versions modifiées.
* **Solutions** : Signature numérique, MDM.
* **Impact** : Sécurité, opérationnel. — **Criticité** : 3/5
* **Exercices** :
  * Démo : site officiel vs. site frauduleux.
  * Vérification : hash ou signature numérique.
  * Quizz : réflexes à adopter.

---

## Failles techniques & piratage réseau

### 1. **Fuite via applications tierces**

* **Description** : Données exposées par des applications connectées (OAuth, API).
* **Bonne habitude** : Contrôle des autorisations.
* **Mauvaise habitude** : Connexion à la volée.
* **Solutions** : Audit API, sécurité Microsoft/Google.
* **Impact** : Juridique, réputationnel. — **Criticité** : 4/5
* **Exercices** :
  * Audit des apps Google/Microsoft.
  * Jeu : permissions excessives ?
  * Simulation : fuite via API.

### 2. **Malveillance interne**

* **Description** : Actes malveillants commis par un employé ou un prestataire ayant accès.
* **Bonne habitude** : Révocation rapide des accès.
* **Mauvaise habitude** : Laisser des comptes actifs.
* **Solutions** : Gestion des droits, journaux d’accès.
* **Impact** : Juridique, réputationnel. — **Criticité** : 5/5
* **Exercices** :
  * Étude de cas : incident interne.
  * Jeu de rôle : départ à risque.
  * Checklist : désactivation d’accès.

---

## Menaces physiques
[Quizz EN]([https://www.ftc.gov/business-guidance/small-businesses/cybersecurity/quiz](https://www.ftc.gov/business-guidance/small-businesses/cybersecurity/quiz/physical-security))

### Accès non autorisé & espionnage

#### 1. **Poste non verrouillé**

* **Description** : Ordinateur laissé accessible sans surveillance.
* **Bonne habitude** : Verrouillage systématique.
* **Mauvaise habitude** : Session ouverte.
* **Solutions** : Verrouillage auto, biométrie.
* **Impact** : Réputationnel, opérationnel. — **Criticité** : 3/5
* **Exercices** :
  * Jeu : "Capture the flag" au bureau.
  * Quizz : combien de secondes suffisent ?
  * Paramétrer un verrouillage auto.

#### 2. **Shoulder surfing**

* **Description** : Espionnage visuel sur écran.
* **Bonne habitude** : Utiliser un filtre de confidentialité.
* **Mauvaise habitude** : Exposer ses infos sans précaution.
* **Solutions** : Filtres, positionnement écran.
* **Impact** : Fuite d'information. — **Criticité** : 3/5
* **Exercices** :
  * Démo : effet d’un filtre.
  * Jeu : position idéale ?
  * Quizz : placement d’écran.

#### 3. **Keylogger matériel**

* **Description** : Dispositif USB interceptant les frappes clavier.
* **Bonne habitude** : Inspection physique régulière.
* **Mauvaise habitude** : Ports accessibles.
* **Solutions** : Boîtiers sécurisés, détection de connectique.
* **Impact** : Fuite d’identifiants. — **Criticité** : 4/5
* **Exercices** :
  * Démo : keylogger USB simulé.
  * Jeu : repérer l’intrus USB.
  * Exercice : inspection physique.

#### 4. **Accès tiers non encadré**

* **Description** : Accès d’un prestataire sans supervision ni limitation.
* **Bonne habitude** : Charte de confidentialité.
* **Mauvaise habitude** : Accès libre.
* **Solutions** : Comptes invités, segmentation réseau.
* **Impact** : Fuite de données, compromission système. — **Criticité** : 4/5
* **Exercices** :
  * Rédiger une clause de confidentialité.
  * Simulation : accès prestataire.
  * Jeu : identifier les failles.
  * [Quizz Vendor Sec](https://www.ftc.gov/business-guidance/small-businesses/cybersecurity/quiz/vendor-security)

---

## Supports et périphériques

### 1. **Objets connectés non sécurisés**

* **Description** : Appareils IoT mal configurés exposant le réseau interne.
* **Bonne habitude** : Changer les mots de passe par défaut.
* **Mauvaise habitude** : Garder les identifiants par défaut.
* **Solutions** : Scan réseau, segmentation.
* **Impact** : Sécurité du réseau. — **Criticité** : 3/5
* **Exercices** :
  * Quizz : objets à risque.
  * Changer un mot de passe IoT.
  * Jeu : sécuriser avec budget limité.

### 2. **Supports non chiffrés**

* **Description** : Clés USB ou disques durs contenant des données sensibles non protégées.
* **Bonne habitude** : Toujours chiffrer.
* **Mauvaise habitude** : Stocker des données sensibles sans protection.
* **Solutions** : VeraCrypt, chiffrement matériel.
* **Impact** : Fuite de données. — **Criticité** : 4/5
* **Exercices** :
  * Démo : accès à une clé non chiffrée.
  * Atelier : chiffrer une clé USB.
  * Quizz : bonnes pratiques.

### 3. **Maintenance non encadrée**

* **Description** : Interventions techniques sans contrôle ni restriction d’accès.
* **Bonne habitude** : Compte invité avec droits limités et journalisation.
* **Mauvaise habitude** : Accès administrateur sans traçabilité.
* **Solutions** : Compte invité, logs, partition dédiée.
* **Impact** : Sécurité, confidentialité. — **Criticité** : 3/5
* **Exercices** :
  * Simulation : audit d’un technicien.
  * Exercice : création d’un compte invité.
  * Jeu : bonnes pratiques de maintenance.

### 4. **Documents papier sensibles**

* **Description** : Documents confidentiels visibles ou non sécurisés.
* **Bonne habitude** : Ranger sous clé.
* **Mauvaise habitude** : Laisser traîner les papiers sensibles.
* **Solutions** : Armoires verrouillées, destructeurs de documents.
* **Impact** : Réputationnel, conformité (RGPD). — **Criticité** : 3/5
* **Exercices** :
  * Quizz visuel : fuites potentielles.
  * Atelier : espace RGPD-compliant.
  * Jeu de rôle : rangement rapide.

---

## Pannes & imprévus

### 1. **Vol de matériel**

* **Description** : Disparition d’un poste de travail ou d’un appareil mobile.
* **Bonne habitude** : Chiffrer, localiser.
* **Mauvaise habitude** : Aucun verrouillage ni traçabilité.
* **Solutions** : BitLocker, FileVault, géolocalisation.
* **Impact** : Fuite de données, perte opérationnelle. — **Criticité** : 4/5
* **Exercices** :
  * Activer chiffrement/localisation.
  * Cas pratique : vol.
  * Quizz : erreurs de configuration.

### 2. **Conférences et coworking**

* **Description** : Travail sur réseau public ou en environnement partagé.
* **Bonne habitude** : VPN, écran de confidentialité, Bluetooth désactivé.
* **Mauvaise habitude** : Se connecter sans précaution.
* **Solutions** : VPN, filtre écran, désactiver Bluetooth.
* **Impact** : Fuite d’information, intrusion. — **Criticité** : 3/5
* **Exercices** :
  * Jeu : sécuriser un poste nomade.
  * Démo : écoute réseau publique.
  * Atelier : configurer un VPN.

### 3. **Pas de verrouillage automatique**

* **Description** : Écran inactif non protégé après un délai.
* **Bonne habitude** : Configurer un délai court de verrouillage.
* **Mauvaise habitude** : Laisser actif par défaut.
* **Solutions** : Verrouillage automatique par GPO ou MDM.
* **Impact** : Accès non autorisé. — **Criticité** : 3/5
* **Exercices** :
  * Quizz : délai idéal ?
  * Paramétrer l’écran de verrouillage.
  * Démo : intrusion sur poste inactif.

### 4. **Poste public non protégé**

* **Description** : Utilisation de postes en libre accès sans précaution.
* **Bonne habitude** : Naviguer en privé et se déconnecter.
* **Mauvaise habitude** : Laisser des sessions ouvertes.
* **Solutions** : Session éphémère, navigateur sécurisé.
* **Impact** : Vol de données personnelles. — **Criticité** : 3/5
* **Exercices** :
  * Simulation : traces sur PC partagé.
  * Quizz : services à éviter.
  * Exercice : navigation privée + déconnexion.

### 5. **Panne sans PCA**

* **Description** : Interruption d’activité sans plan de continuité.
* **Bonne habitude** : Anticiper avec un PCA simple.
* **Mauvaise habitude** : Dépendre d’un seul support local.
* **Solutions** : Cloud, PCA, NAS.
* **Impact** : Perte d’activité. — **Criticité** : 4/5
* **Exercices** :
  * Atelier : créer un PCA de base.
  * Jeu : reconstituer les étapes de reprise.
  * Démo : restauration depuis sauvegarde.



---

# Resources



## 🔹 Phase 1 – Pré-formation (E-learning)

| Activité                                          | Sites utiles                                                                                                                                                                                                                                                                                                                                                                        |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Test de positionnement**                        | [https://www.cybermalveillance.gouv.fr](https://www.cybermalveillance.gouv.fr) – auto-évaluation sécurité / quiz<br>[https://haveibeenpwned.com](https://haveibeenpwned.com) – test d’exposition de comptes                                                                                                                                                                         |
| **Risques : phishing, usurpation, escroqueries**  | [https://www.phishing-initiative.fr](https://www.phishing-initiative.fr) – signalement et exemples<br>[https://www.secnumacademie.gouv.fr](https://www.secnumacademie.gouv.fr) – MOOC ANSSI : modules introductifs gratuits<br>[https://www.cybermalveillance.gouv.fr/tous-nos-contenus/bonnes-pratiques](https://www.cybermalveillance.gouv.fr/tous-nos-contenus/bonnes-pratiques) |
| **Bonnes pratiques (mots de passe, cloud, etc.)** | [https://bitwarden.com](https://bitwarden.com) – gestionnaire open-source<br>[https://security.org/how-secure-is-my-password](https://security.org/how-secure-is-my-password) – test de robustesse<br>[https://ssd.eff.org](https://ssd.eff.org) – Electronic Frontier Foundation (EFF) : guides pratiques                                                                          |
| **Obligations légales : RGPD**                    | [https://www.cnil.fr](https://www.cnil.fr) – ressources pédagogiques<br>[https://gdpr.eu](https://gdpr.eu) – version synthétique du RGPD en anglais<br>[https://www.educnum.fr](https://www.educnum.fr) – kits pour éducateurs                                                                                                                                                      |

---

## 🔹 Phase 2 – Présentiel

| Activité                                               | Sites utiles                                                                                                                                                                                                                                                    |
| ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Quiz & jeu de rôle (mail piège)**                    | [https://www.phishingbox.com](https://www.phishingbox.com) (en démo)<br>[https://tryhackme.com/room/phishing](https://tryhackme.com/room/phishing) – salle de simulation pour découvrir les pièges                                                              |
| **Atelier pratique : mot de passe, gestionnaire, 2FA** | [https://bitwarden.com](https://bitwarden.com)<br>[https://2fa.directory](https://2fa.directory) – liste des sites compatibles 2FA<br>[https://authy.com](https://authy.com) – alternative à Google Authenticator                                               |
| **Charte de bonnes pratiques**                         | [https://www.cybermalveillance.gouv.fr/charte-informatique](https://www.cybermalveillance.gouv.fr/charte-informatique)<br>[https://www.ssi.gouv.fr/uploads/2016/07/NP\_Charte\_admin\_SSI.pdf](https://www.ssi.gouv.fr/uploads/2016/07/NP_Charte_admin_SSI.pdf) |
| **Évaluation finale (incident fictif)**                | [https://www.root-me.org](https://www.root-me.org) – scénarios pour débutants<br>[https://www.hackthebox.com](https://www.hackthebox.com) – pour profils plus techniques                                                                                        |

---

## 🔹 Phase 3 – Post-formation

| Activité                          | Sites utiles                                                                                                                                                                                                                                                                                    |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Vidéo/podcast sur les fraudes** | [https://www.futura-sciences.com/tech/podcasts/](https://www.futura-sciences.com/tech/podcasts/) – podcasts vulgarisation<br>[https://www.scamwatch.gov.au/](https://www.scamwatch.gov.au/) – études de cas internationales                                                                     |
| **Simulation d’attaque**          | [https://cyberrange.org](https://cyberrange.org) – environnement de simulation (pro niveau)<br>[https://www.ouestnumerique.fr/cybersurvie](https://www.ouestnumerique.fr/cybersurvie) – kit simplifié pour TPE/PME                                                                              |
| **Routine mensuelle**             | [https://www.cybermalveillance.gouv.fr/checklists](https://www.cybermalveillance.gouv.fr/checklists)<br>[https://www.cisco.com/c/fr\_fr/products/security/cybersecurity-month.html](https://www.cisco.com/c/fr_fr/products/security/cybersecurity-month.html) – routines thématiques mensuelles |

--- Autres

[Sur la piste du hacker](https://cyber.forge.apps.education.fr/cyber-enquete/)
[Escape Game AC Normandie](https://view.genially.com/66474a537609460014772eec)
[Cyber Enquete](https://scape.enepe.fr/cyber-enquete.html)
[Cyber3000](https://scape.enepe.fr/cyber3000.html)
