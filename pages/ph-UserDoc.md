# Documentation utilisateurs

Présentation de quelques outils pour la mise en ligne d'une documentation.

<BarBottom  title="Charlie Cohen">
  <Item text="Linzell">
    <carbon:logo-github />
  </Item>
</BarBottom>

<!--
Objectifs :
- Comprendre les besoins
- Voir ce qu'il existe
- Voir les outils disponibles
- Préparer la mise en place
-->

---
layout: intro
---

## Les besoins ?

<br />
<br />

<div class="grid grid-cols-2 gap-x-4">
<div>
• Une documentation simple a éditer par l'équipe
<br />
<v-click>
• Qui passe par les processus de validation
</v-click>
<br />
<v-click>
• La possibilité de partager la documentation avec les utilisateurs par internet
</v-click>
<br />
<v-click>
• Une gestion par "versions" de la documentation
</v-click>

</div>
<div class="relative flex justify-center">
    <img src="/assets/images/markdown.png" class="absolute top--40">
    <img v-click="1" src="/assets/images/gitlab.png" class="absolute top--40">
    <img v-click="2" src="/assets/images/vitepress.png" class="absolute top--40">
    <img v-click="3" src="/assets/images/versions.png" class="absolute top--40">
</div>
</div>

<!--
- Simple :
• Utilisation du Markdown
• Possibilité de rajouter un éditeur et des comptes
• Possibilité de rajouter des images
• Possibilité de rajouter des liens
- Validation :
• Toutes modifications doivent être validées par un administrateur avant de pouvoir être publiées
• Utilisation de GitLab pour la gestion des versions
• Déploiement automatique quand cycle de validation est terminé
- Partage :
• Possibilité de partager la documentation avec les utilisateurs par internet
• Possibilité de le connecter avec le site Wordpress existant
• Possibilité de renvoyer depuis l'application Phealing vers la documentation
- Versions :
• Possibilité de créer des versions de la documentation
• Possibilité de renvoyer les utilisateurs vers leurs versions en cours
-->

---
layout: image-x
image: '/assets/images/docusaurus.svg'
---

# Docusaurus

La solution de documentation la plus populaire et la plus facile à utiliser

<ul>
<v-click>
<li><span class="text-sm">
    ✅ Couvre toutes les fonctionnalités de base pour nos besoins
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ✅ Trés facile à utiliser et à personnaliser
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ✅ Déployable sur n'importe quel serveur
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ✅ Open-source (MIT - Facebook)
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ⚠️ React
</span></li>
</v-click>
</ul>

<!--
Notes :
- C'est la solution la plus populaire
- Je l'ai utilisé sur de nombreux projets
- Ce lance en 5 minutes, déploiement compris sur Github/Vercel/Netlify
- Pas encore testé sur AWS de déployer la chose, mais pas de raisons
- Les peluches sont beaucoup trop mignonnes
- Possibilité d'y adjoindre des "pages", comme des tutoriels ou des guides, mais à voir la pertinence avec Wordpress
- Respectera les standards de SEO et nos cycles de validations facilement
-->

---
layout: image-x
image: '/assets/images/vitepress-logo-large.svg'
---

# VitePress

L'alternative sous VueJS

<ul>
<v-click>
<li><span class="text-sm">
    ✅ Couvre toutes les fonctionnalités de base pour nos besoins <strong>avec des plugins</strong>
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ✅ Trés facile à utiliser et à personnaliser
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ✅ Déployable sur n'importe quel serveur
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ✅ Open-source (MIT - VueJS)
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ⚠️ Pas vraiment autonome
</span></li>
</v-click>
<v-click>
<li><span class="text-sm">
    ⚠️ Moins à jours
</span></li>
</v-click>
</ul>

<!--
Notes :
- C'est plus une solution "doc tech" que de documentation
- Moins autonome de base, mais des plugins plus ou moins à jours existent pour améliorer la situation
- A le gros avantage de nous permettre de re-utiliser nos composants VueJS pour construire des pages plus complexes
- Risque de prendre plus de temps à développer que d'autres solutions
-->

---
layout: quote
position: center
---

# "Le plus simple n'est pas toujours le meilleur"
Qui va gagner le match ?

Plusieurs questions à se poser avant de décider

<!--
Questions :
- Echelle de temps avant release de la documentation. Avant le départ de Xavier ? De Salome ?
- Va t'on vraiment re-utiliser nos composants VueJS pour construire des pages plus complexes ?
- Besoin de passer par Gitlab/Github, donc qui va review la chose ? Est-ce qui est souhaitable ?
-->

---
layout: center
class: "text-center"
---

# Quelques ressources

[Docusaurus](https://docusaurus.io/)
<br />
[VitePress](https://vitepress.dev/) / [Plugin Versioning](https://vvp.imb11.dev/)

<br />
<br />

<div class="flex justify-center">
    <img src="/assets/images/qrCode.png" style="width: 200px;">
</div>

<BarBottom  title="Charlie Cohen">
  <Item text="Linzell">
    <carbon:logo-github />
  </Item>
</BarBottom>
