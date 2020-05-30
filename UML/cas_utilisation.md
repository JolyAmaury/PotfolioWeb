# UML
## Cas d'utilisations
### CAS N°1
__Nom :__ Choix du domaine recruteur  
__Acteur :__ *Recruteur*  
__Description :__ Un recruteur peut choisir le domaine dans lequel il souhaite recruter le propriétaire pour avoir des infos particulières  
__Date :__ 29/05/2020 (1ère)  
__Pré-condition :__ L’utilisateur s’est identifié comme recruteur (`CAS N°5`)  
__Démarrage :__ L’utilsateur s’est identifié comme étant recruteur.
#### __Description__
##### __Le scénario nominal__
- - -
1. Le __système__ affiche un élément proposant le choix entre differents domaines selectionable par le recruteur
2. L’*utilsateur* séléctionne un des choix proposés
3. Le __système__ lui retourne les informations les plus importantes.
- - -
##### __Les scénarii alternatif__
- - -
2.a L’*utilsateur* demande un retour au choix entre utilisateur et recruteur  
Le __système__ retourne au `CAS N°5`
- - -
__Fin :__ Scénario nominale : à l'étape 2.  
__Post-condition :__ Le domaine du recruteur est définit
#### __Complements__
...
* * * *
* * * *
### CAS N°2
__Nom :__ Vue des détails d'une compétence   
__Acteur :__ *Utilisateur*  
__Description :__ Un utilisateur peut approfondir une connaissance de manière a voir les sous-compétences et les projets réalisés en rapport avec ses compétences  
__Date :__ 29/05/2020 (1ère)  
__Pré-condition :__ Aucune  
__Démarrage :__ L’*utilisateur* à cliqué sur une compétence 
#### __Description__
##### __Le scénario nominal__
- - -
1. Le __système__ affiche la liste des compétences
2. L’*utilsateur* séléctionne une compétence particulière
3. Le __système__ lui retourne sous forme d’arborescence les sous compétences/projets qui en découle
4. L’*utilsateur* séléctionne une sous-compétence
5. Le __système__ lui retourne les sous-compétences/projets qui en découle (Retour à l’`étape 3`)
- - -
##### __Les scénarii alternatif__
- - -
2.a L'*utilisateur* choisi une compétence ne possédant aucune sous-compétence/projet  
Le __système__ ne fait rien.

4.a L’*utilisateur* choisi une autre compétence  
Le __système__ cache la compétence précédente et affiche celle nouvellement choisis (Retour à l'`étape 3`).  
4.b L'*utilisateur* choisi une competence/sous-compétence/projet mais elle ne contient pas de sous-compétences/projets (voire l'`étape 2.a`)
4.c L'*utilisateur* chosis de quitter les détails des compétences  
- - -
__Fin :__ Scénario nominal : à l'étape 4 sur décision de l'utilisateur.  
__Post-condition :__ Aucune
#### __Complements__
...
* * * *
* * * *
### CAS N°3
__Nom :__ Exportation d'un CV  
__Acteur :__ *Utilisateur*  
__Description :__ Un *utilisateur* peut télécharger un CV dans une bibliothèque mis a disposition et regroupant les différents CV en fonction du poste  
__Date :__ 29/05/2020 (1ère)  
__Pré-condition :__ Aucune  
__Démarrage :__ L'*utilisateur* a choisis et sélectionné son CV  
#### __Description__
##### __Le scénario nominal__
- - -
1. L'*utilisateur* choisis d'exporter un CV  
2. Le __système__ propose de choisir un domaine  
3. L'*utilisateur* sélectionne un domaine  
4. Le __système__ lance le téléchargement du CV  
- - -
##### __Les scénarii alternatif__
- - -
3.a L'*utilisateur* décide de ne pas choisir de domaine  
Le __système__ affiche la page d'accueil
- - -
__Fin :__ Scénario nominale : à l'étape 3 sur action de l'utilisateur ou à l'étape 4.  
__Post-condition :__ Un fichier PDF est téléchargé sur le navigateur de l'utilisateur.  
#### __Complements__
...
* * * *
* * * *
### CAS N°4
__Nom :__ Redirection sur les infos de contacts / réseaux sociaux  
__Acteur :__ *Utilisateur*  
__Description :__ Un *utilisateur* peut accéder aux réseaux sociaux ou au info de contacts de l’utilsateur.  
__Date :__ 29/05/2020 (1ère)  
__Pré-condition :__ Aucune  
__Démarrage :__ L’*utilisateur* à demandé une redirection sur une platforme de contact  
#### __Description__
##### __Le scénario nominal__
- - -
1. L'*utilisateur* sélectionne un moyen de contact
2. Le __systeme__ le redirige vers le moyen de contact demandé
- - -
##### __Les scénarii alternatif__
- - -
...
- - -
__Fin :__ Scénario nominale : à l'étape 2.  
__Post-condition :__ Une redirection à été faite du coté dur client.
#### __Complements__
...
* * * *
* * * *
### CAS N°5
__Nom :__ Choix d'une vistite "recruteur" ou "utilisateur"  
__Acteur :__ *Utilisateur*  
__Description :__ Un *utilisateur* peut choisir d'être considéré comme un utilisateur ou un recruteur  
__Date :__ 29/05/2020 (1ère)  
__Pré-condition :__ Aucune
__Démarrage :__ L'*utilisateur* se connecte sur le site
#### __Description__
##### __Le scénario nominal__
- - -
1. Le __système__ affiche un élément proposant le choix entre le statut de recruteur ou d'utilisateur
2. L'*utilisateur* choisis d'être considérer comme recruteur ou non
- - -
##### __Les scénarii alternatif__
- - -
...
- - -
__Fin :__ Scénario nominale : à l'étape 2  
__Post-condition :__ L'*utilisateur* est considéré comme recruteur ou non
#### __Complements__
...
* * * *
* * * *
### CAS N°6
__Nom :__ Choix du mode sombre
__Acteur :__ *Utilisateur*  
__Description :__ Un utilisateur peut choisir un thème sombre ou claire  
__Date :__ 29/05/2020 (1ère)  
__Pré-condition :__ L’utilisateur s’est identifié comme recruteur (`CAS N°5`)
#### __Description__
##### __Le scénario nominal__
- - -
1. Le __système__ affiche un élément proposant le choix entre differents domaines selectionable par le recruteur
2. L’*utilsateur* séléctionne un des choix proposés
3. Le __système__ lui retourne les informations les plus importantes.
- - -
##### __Les scénarii alternatif__
- - -
...
- - -
__Fin :__ Scénario nominale : à l'étape 2 sur décision de l'utilisateur.  
__Post-condition :__ Le thème du site est changé
#### __Complements__
...
* * * *
* * * *
