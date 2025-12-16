# Création d'un IHM pour une cellule robotisé
Objectif : Création d'un IHM avec EasyBuiler Pro pour un atomate WAGO dans le cadre d'une intégration d'une cellule robotisé.

Chemin du produit pour la cellule : 

<img width="1103" height="614" alt="Screenshot from 2025-12-16 11-50-02" src="https://github.com/user-attachments/assets/c8e8ea9e-dac9-43b1-985c-9963d244e135" />

Dans le but d'une intégration robotisé, l'objectif était de dévellopper un interface homme machine pour les utilisateurs intéragise très facilement avec la cellule :

<img width="669" height="353" alt="Screenshot from 2025-12-16 11-48-37" src="https://github.com/user-attachments/assets/a27e868c-688f-45ff-9ade-45e3c4df8b30" />

Voici l'automate WAGO PFC300, cablé dans l'armoire électrique de la cellule :

<img width="443" height="291" alt="Screenshot from 2025-12-16 11-43-13" src="https://github.com/user-attachments/assets/32fce163-8fa3-457d-97c6-cd0ac6b26e48" />

Sur le logiciel (CODESYS) de l'automate, créer un fichier GVL (variables globles ou locales) :

<img width="378" height="286" alt="Screenshot from 2025-12-16 11-48-11" src="https://github.com/user-attachments/assets/a48e95b5-8d72-45cf-89e8-08e93f5b6ced" />

Sur le logiciel (EasyBuiler Pro) de l'IHM importer le GVL pour pouvoir configurer les actionneurs : 

<img width="589" height="531" alt="Screenshot from 2025-12-16 11-47-26" src="https://github.com/user-attachments/assets/5de737a8-3226-4ad4-a4d6-6596a5f09d62" />

Exemple de variables du GVL : 

<img width="888" height="172" alt="Screenshot from 2025-12-16 11-42-23" src="https://github.com/user-attachments/assets/7829b117-0dc6-4369-84ea-0b30283cbae2" />

Test unitaire de l'IHM : 
Le but était d'activer le mode local / distant.

<img width="1373" height="525" alt="Screenshot from 2025-12-16 11-44-10" src="https://github.com/user-attachments/assets/bef9920a-a8af-4f36-b739-069e44a30813" />

Test d'intégration système :
Le but était de vérifier si l'IHM et l'automate communiquer correctement.

<img width="732" height="236" alt="Screenshot from 2025-12-16 11-45-08" src="https://github.com/user-attachments/assets/333b1b50-4e32-4099-8599-328b1dbb3bfb" />

Test d'intégration de l'IHM : 
Le but était d'intégrer l'IHM dévelloper dans la cellule.

<img width="465" height="681" alt="Screenshot from 2025-12-16 11-46-11" src="https://github.com/user-attachments/assets/bf9cc062-3c53-4e5a-be2e-4ad2ae15df19" />

IHM finale : 
<img width="1337" height="475" alt="Screenshot from 2025-12-16 11-41-52" src="https://github.com/user-attachments/assets/32332705-ad79-4ede-9ee9-f9a54b7bca39" />
<img width="592" height="339" alt="Screenshot from 2025-12-16 11-45-17" src="https://github.com/user-attachments/assets/c679985a-6c63-44d0-87cd-9ac7f9ea4218" />

