# Introduction #
Ce projet a pour objectif de contenir les sources du ou des Gadgets (Widget) [Wikipen](http://fr.wikipen.org).

Le gadget Wikipen peut s'afficher :
  * sur [iGoogle](http://www.google.fr/ig?hl=fr)
  * ou bien sur [votre page web](http://gmodules.com/ig/creator?synd=open&url=http%3A//wikipen-gadgets.googlecode.com/svn/wikipen.xml) ([exemple](http://boly38.free.fr))

Le principe est assez simple :
  * Récupérer le nom d'un texte grâce à la page "un texte au hasard"
  * Récupérer le contenu du texte (directement depuis [wikipen (fr)](http://fr.wikipen.org) ou [wikipen (en)](http://en.wikipen.org) suivant les préférences)
  * Afficher dans le gadget le titre et le contenu récupéré

L'image de Wikipen affichée en haut du gadget permet par un simple clic de relancer ce processus.

[![](http://wikipen-gadgets.googlecode.com/svn/wikipenwidget.png)](http://fusion.google.com/add?moduleurl=http%3A//wikipen-gadgets.googlecode.com/svn/wikipen.xml)

# Details #

## Utiliser le gadget ##

_Ce gadge est référencé dans le [dictionnaire de gadgets de Google](http://www.google.com/ig/directory?q=wikipen&source=gapi)_

### Utiliser sur iGoogle ###
Pour **ajouter le gadget Wikipen** :
[![](http://buttons.googlesyndication.com/fusion/add.gif)](http://fusion.google.com/add?moduleurl=http%3A//wikipen-gadgets.googlecode.com/svn/wikipen.xml)

Sinon rendez-vous sur [iGoogle](http://www.google.fr/ig?hl=fr)
  * aller sur [Ajouter des modules](http://www.google.fr/ig/directory?hl=fr&root=/ig&igtab=Outils+&dpos=top)
  * cliquer sur "Ajouter une URL"
  * entrer le texte suivant et valider : http://wikipen-gadgets.googlecode.com/svn/wikipen.xml

### Utiliser sur votre site web ###
  * Allez sur [cette page](http://gmodules.com/ig/creator?synd=open&url=http%3A//wikipen-gadgets.googlecode.com/svn/wikipen.xml)
  * Faites les modifications sur la forme (couleur, bordure, taille, ..)
  * Cliquez sur "Obtenir le code"
  * Copiez le code qui apparaît en dessous et collez le dans votre page Web.


<a href='Hidden comment: 
===Aperçu===
<wiki:gadget url="http://wikipen-gadgets.googlecode.com/svn/wikipen.xml?toto=test5" height="200" border="1" />

'></a>

## Participer aux évolutions ##
  * Rendez-vous sur l'onglet "Issues"

> Pour mémoire :
  * [envoi d'un gadget](http://www.google.com/ig/submit)
  * Test du gadget : utiliser le gadget de test.

### Evolution du 2/10/2009 ###
  * Ajout d'un fix : suite à un problème avec Google Analytics et modification de la gestion des preferences (langue fr/en).

### Evolution du 28/04/2009 ###
  * Suite à la migration de Wikipen, le gadget n'affichait plus aucun texte. Ce problème a été corrigé.

### Evolution du 29/07/2008 ###
_pour mettre à jour votre gadget, pensez à vider le cache de votre navigateur, supprimer le gadget et le réintroduire à nouveau par la méthode d'ajout d'URL (cf. ci-dessus)_

  * Suite au passage en UTF-8 des gadgets d'iGoogle. Ce gadget ne fonctionnait plus correctement (affichage d'erreurs et/ou de caractères bizaroïdes..). Ce problème a été résolu. Grand Merci à Gabriel Wicke pour [ses sources JavaScript en Copyleft de "wiki2html(str)"](http://en.wikipedia.org/wiki/User:Sverdrup/Wikipreview.html)...
  * Ajout de la possibilité de cliquer sur un lien interne pour rechargement du texte concerné dans le widget même (_vous avez toujours la possibilité de vous rendre sur l'original en cliquant sur le titre du texte_).
> > BUG : Pour cette fonction, il demeure malheureusement un soucis avec les titres comportant une apostrophe..


### Participer aux développements ###
  * Merci d'en faire la demande (bvandeputte at gmail dot com)