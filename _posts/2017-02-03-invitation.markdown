---
layout: post
title:  "Invitation"
date:   2017-01-28 17:18:59 +0100
permalink: /invitation.html
featured: none
categories: invitation
---
Inscrivez-vous ici pour faire partie des premiers à bénéficier du service exceptionnel de **HappyChauffeur**

<form action="https://formspree.io/d@labacar.com"
      method="POST">
    Nom <input type="text" name="name">
    Prénom <input type="text" name="prenom">
    Téléphone <input type="text" name="phone">
    Email <input type="email" name="_replyto">
    Code parrain <em>Si vous n'avez pas de code parrain, laissez ce champ vide</em><input type="text" name="code"> 

    Nombre de véhicules <input type="text" name="nbre">
    <input type="hidden" name="_next" value="{{ site.baseurl }}/merci.html" />
    <input type="submit" value="Envoyer">
</form>