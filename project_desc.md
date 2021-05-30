# PROJET FINAL: Testimonials (..ou tout autre nom qui claque)

## 1. Présentation
**Que fait notre application?**
* Testimonials permet à une entreprise de receuillir facilement un témoignage vidéo auprès de ses clients

**Mais encore?**
* Testimonials envoie un mail à la personne dont on souhaite receuillir le témoignage. Ce mail contient un lien qui une fois cliqué, redirige l'utilisateur vers une page où il peut enregistrer son témoignage.
Un peu comme ça :

![record_video](https://support.dreamseedo.org/hc/article_attachments/115009850608/DSD-Record-Video-Web-Participant.png)
* Une fois validé, le témoignage est directement renvoyé à l'entreprise qui peut par la suite le publier ou non. 

**Quelle valeur apporte Testimonials?**
* Receuillir des témoignages de clients est compliqué pour les entreprises, et encore plus pour les témoignages vidéos, qui demandent d'enregistrer et d'_*envoyer*_ la vidéo.\
En simplifiant ce process (il suffit d'un clic pour enregistrer et envoyer sa vidéo) Testimonials augmente (grandement on espère..) le pourcentage de témoignage récupérés.\
Les entreprises clientes obtiennent plus de témoignages, plus facilement et sont mieux armés pour nourrir leur landing page.

* Les témoignages de clients sont devenu un outil incontournable du web marketing et augmentent significativement les ventes selon [Stategic Factory](https://strategicfactory.com/2017/06/take-it-from-me-why-testimonials-are-so-effective/) :
>Using customer testimonials on a business site regularly leads to an increase in revenue of 62% because testimonials placed on sales pages generate 34% more conversions.

* Les témoignages sous format vidéo sont de plus en plus populaires et facilement enregistrable notament via les smartphones.

## 2. Parcours utilisateur
La landing page de l'application présente le service (message principal : avec nous vous pouvez récupérer des témoignages vidéos simplement en partageant un lien). On peut aussi s'inscrire ou se connecter depuis cette page.

Un utilisateur connecté a accés à son profil d'où il peut :
* générer un lien à envoyer au clients dont il souhaite récupérer le témoignage.
* télécharger les vidéos receuillies
* _{intégrer les vidéos receuillies a son site web ?}_


## 3. Concrètement et techniquement
Dans cette partie, tu pourras décrire l'aspect technique du projet.

On va avoir besoin d'une techno pour enregistrer le flux vidéo.
 - On pense à [Media recorder](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder).
 - [la page mdn de l'api](https://developer.mozilla.org/en-US/docs/Web/API/MediaStream_Recording_API)
 - [un post google devellopeurs](https://developers.google.com/web/updates/2016/01/mediarecorder)
 - [Plus de détails sur comment fonctionne l'api](https://whatwebcando.today/recording.html)
 - [Un tuto media recorder](https://www.twilio.com/blog/mediastream-recording-api)

### 3.1. Base de données
Comment tu vois la base de données de l'application ?

### 3.2. Front
Quels sont les composants dont vous aurez besoin ? Aurez-vous besoin d'un peu de front dynamique avec JavaScript pour la faire fonctionner ? 

### 3.3. Backend
De quoi avez-vous besoin pour le backend ? Quelles sont les APIs en back que vous allez brancher et utiliser ?

### 3.4. Mes besoins techniques
Balance ici tes compétences, puis tes besoins pour les 3-4 personnes restantes.

## 4. La version minimaliste mais fonctionnelle qu'il faut avoir livré la première semaine
Nous allons vous demander de livrer une version minimaliste mais fonctionnelle à la fin de la première semaine. Décris ce que vous voulez avoir fait à la fin de la première semaine. Pense minimaliste, fonctionnel, efficace. Comment avec le moins de code possible vous arrivez à donner une version fonctionnelle de l'application. 

Ceci s'appelle le MVP, pour Minimum Viable Product. Voici un exemple de MVP pour un site que tu connais bien, celui de THP : les gens peuvent s'enregistrer sur le site, puis s'inscrire à une session. S'ils s'inscrivent, ils ont accès à tout le cursus qui est hébergé sur la plateforme. Nous nous occuperons à la main d'envoyer des emails pour annoncer le début de la session et nous ferons les groupes à la main. Spoiler : THP a commencé comme ceci ;)

## 5. La version que l'on présentera aux jury
La deuxième semaine vous allez ajouter des fonctionnalités pour améliorer l'expérience utilisateurs de votre application. Quelles fonctionnalités tu aimerais bien ajouter ?

## 6. Notre mentor
Qui est ton mentor ?