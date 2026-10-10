# 🎬 Catalogue de mes codes — laurentvoanhofficiel-jpg

Tous mes logiciels web actuels, avec l'URL de chaque fichier et ce qu'il fait.
Chaque fichier HTML est autonome : ouvrez-le dans un navigateur, collez vos clés API (Agnès AI, Mistral…) et lancez la génération.

Mon compte GitHub : [laurentvoanhofficiel-jpg](https://github.com/laurentvoanhofficiel-jpg)

---

## 📁 Sommaire des dépôts

| Dépôt | Contenu |
| --- | --- |
| [Voanh-Agnes-film-maker](https://github.com/laurentvoanhofficiel-jpg/Voanh-Agnes-film-maker) | CINÉ-GENESIS — studio de films IA étape par étape (version de référence, avec README complet) |
| [Agnes-ai-film-maker-Universal-one-page-HTML-4-all](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-film-maker-Universal-one-page-HTML-4-all) | Version « une seule page HTML » de CINÉ-GENESIS, universelle |
| [redesigned-potato](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato) | Collection de 41 outils HTML autonomes : JT par IA, studios de films, plan-séquence, générateurs d'images… |
| [Code-a-reparer](https://github.com/laurentvoanhofficiel-jpg/Code-a-reparer) | Codes en cours de développement (bugs en fin de chaîne, mais bonnes pistes et débouts fonctionnels) |
| [laurentvoanhofficiel-jpg](https://github.com/laurentvoanhofficiel-jpg/laurentvoanhofficiel-jpg) | Dépôt de profil (vide pour l'instant) |

---

## 🎥 1. Voanh-Agnes-film-maker — CINÉ-GENESIS (version de référence)

Créer un court-métrage complet généré par IA, étape par étape : clés API → genre → synopsis → personnages (visages cohérents) → scènes (décors, dialogues) → plans → vidéos. Gère plusieurs clés API avec répartition automatique des requêtes.

- [README.md](https://github.com/laurentvoanhofficiel-jpg/Voanh-Agnes-film-maker/blob/main/README.md) — Documentation complète du studio CINÉ-GENESIS : principe, installation assistée par IA, exemples d'utilisation, reconversion pour d'autres usages, déploiement.
- [index.html](https://github.com/laurentvoanhofficiel-jpg/Voanh-Agnes-film-maker/blob/main/index.html) — Le studio CINÉ-GENESIS complet en un seul fichier : pipeline en 7 étapes (clés, genre, synopsis, personnages, scènes, plans, vidéos), sessions persistantes (IndexedDB), lecteur final avec sous-titres.

## 🌍 2. Agnes-ai-film-maker-Universal-one-page-HTML-4-all — CINÉ-GENESIS (une page, pour tous)

- [deepseek_html_20261010_d59eb0.html](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-film-maker-Universal-one-page-HTML-4-all/blob/main/deepseek_html_20261010_d59eb0.html) — Version « universelle » du studio de films IA CINÉ-GENESIS : un seul fichier HTML à ouvrir n'importe où, assistant guidé en 7 étapes pour créer un film de A à Z avec l'API Agnès (multi-clés, planificateur de requêtes, journal technique intégré).

## 🛠️ 3. redesigned-potato — 41 outils HTML autonomes

Collection d'outils web (une page = un logiciel) pour créer des vidéos, des films et des images par IA, principalement via l'API Agnès AI. Les studios persistants utilisent IndexedDB (sessions, vidéothèque, styles favoris).

| Fichier | Ce qu'il fait |
| --- | --- |
| [NewsReel_Studio_v2 (3).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/NewsReel_Studio_v2%20(3).html) | Générateur de journal télévisé (JT) : à partir de sujets d'actualité (Google News RSS), produit un JT complet avec chroniqueur plateau, reporters et figurants, sketches comiques, choix du réalisateur (Wes Anderson, Kubrick…), palettes de couleurs, images puis vidéos hook. |
| [appforge.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/appforge.html) | APPFORGE, générateur d'applications IA : décrivez l'application souhaitée en une phrase, l'IA fabrique le formulaire et la chaîne de génération (texte, image, vidéo), prête à servir immédiatement. Supporte clés Agnès et Mistral. |
| [deepseek_html_20260925_fdc9e9 (6) (5).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260925_fdc9e9%20(6)%20(5).html) | Dessin Animé IA : studio de dessin animé, transforme une idée en séquence animée image par image. |
| [deepseek_html_20260928_a49b89 (3).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260928_a49b89%20(3).html) | MoneyPrinterTurbo · Agnès : machine à vidéos automatiques (script, images, voix) à partir d'un sujet. |
| [deepseek_html_20260930_a237a0 (3).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260930_a237a0%20(3).html) | Kata Studio — Cinéma Généré : scénario, découpage en plans, images puis film. |
| [deepseek_html_20260930_c27961 (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260930_c27961%20(1).html) | Kata Studio — variante : génération complète d'un court-métrage IA, du scénario au film. |
| [deepseek_html_20260930_ddbba8 (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260930_ddbba8%20(2).html) | Kata Studio — Le Moine Shaolin : instance dédiée prête à générer ce court-métrage précis. |
| [deepseek_html_20260930_edff6d.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260930_edff6d.html) | Kata Studio — autre variante de génération de films par IA. |
| [deepseek_html_20261001_4955e8 (2) (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261001_4955e8%20(2)%20(2).html) | NewsReel Studio — Le JT : création d'un journal télévisé complet généré par IA. |
| [deepseek_html_20261001_4955e8 (3) (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261001_4955e8%20(3)%20(2).html) | Copie strictement identique du fichier précédent. |
| [deepseek_html_20261001_f4d029 (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261001_f4d029%20(1).html) | NewsReel Studio — L'actualité en film : transforme l'actualité en film / reportage vidéo IA. |
| [deepseek_html_20261006_367208 (1) (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261006_367208%20(1)%20(2).html) | ViMax-Agnès Studio : génération d'images et vidéos via l'API Agnès, orientée production maximale. |
| [deepseek_html_20261006_618dc3 (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261006_618dc3%20(2).html) | Style Studio : analyse d'une image, transfert de son style, puis génération d'une vidéo (chaîne Analyse + Transfert + Vidéo). |
| [deepseek_html_20261007_68b448 (10) (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261007_68b448%20(10)%20(1).html) | Cinéma Studio — JT cinématographique : journal télévisé réalisé comme un vrai film (plans ciné, mise en scène, narrateur IA). |
| [deepseek_html_20261007_68b448 (10) (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261007_68b448%20(10)%20(2).html) | Copie strictement identique du fichier précédent. |
| [deepseek_html_20261007_68b448 (7) (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261007_68b448%20(7)%20(2).html) | Cinéma Studio v7 : itération antérieure du JT cinématographique. |
| [deepseek_html_20261007_d9219c (2) (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261007_d9219c%20(2)%20(2).html) | Cinéma Studio — News × Réalisateurs × Style : JT cinématographique croisant actualité, signature de réalisateurs et style visuel. |
| [deepseek_html_20261008_267dcc.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_267dcc.html) | Studio Plan-Séquence : génère un plan-séquence continu de 4 minutes, un seul plan sans coupes, écrit et mis en scène par IA. |
| [deepseek_html_20261008_623f87.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_623f87.html) | Plan-Séquence — Studio : autre version du studio de plan-séquence IA. |
| [deepseek_html_20261008_68b448 (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_68b448%20(1).html) | Cinéma Studio v1 : première itération du JT cinématographique. |
| [deepseek_html_20261008_7846d2.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_7846d2.html) | Plan-Séquence — Studio : variante du studio de plan-séquence IA. |
| [deepseek_html_20261008_c87882.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_c87882.html) | Studio Plan-Séquence v15 : génération d'un long plan unique scénarisé. |
| [deepseek_html_20261008_e00c27 (2) (1) (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_e00c27%20(2)%20(1)%20(1).html) | VISUAL.JOURNAL : briefs d'actualité pilotés par images de référence. |
| [deepseek_html_20261008_e5910a.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_e5910a.html) | Journal Visuel : JT dont le discours éditorial est piloté par l'image. |
| [deepseek_html_20261008_eb4c02.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_eb4c02.html) | Plan-Séquence v26 : version 26 du générateur de plan-séquence IA. |
| [deepseek_html_20261008_f10acd.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_f10acd.html) | Studio d'Auteur : créateur de films IA où l'utilisateur est traité comme un auteur de cinéma, du concept au film final. |
| [deepseek_html_20261008_faf9ac.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_faf9ac.html) | VISUAL.JOURNAL — Chœur intellectuel : JT humaniste où plusieurs voix s'expriment en chœur sur l'actualité, piloté par images. |
| [deepseek_html_20261008_faf9ac (1) (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_faf9ac%20(1)%20(2).html) | Copie strictement identique du fichier précédent. |
| [deepseek_html_20261009_0a2943 (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_0a2943%20(1).html) | Studio Portrait 9:16 : studio story-first au format vertical, base multi-références, analyse IA puis génération d'un univers. |
| [deepseek_html_20261009_1e97ca (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_1e97ca%20(1).html) | Ciné Studio : pipeline complet — votre photo → analyse IA → questionnaire de vision → scénario et découpage → images des plans → film. |
| [deepseek_html_20261009_23906d (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_23906d%20(1).html) | Copy Studio : reproduit une image de référence en 3 lots de 10 copies, fidélité maximale. |
| [deepseek_html_20261009_299879 (1) (1).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_299879%20(1)%20(1).html) | Studio complet : image de référence → analyse et images en un clic → styles favoris → film. Sessions et vidéothèque persistantes (IndexedDB). |
| [deepseek_html_20261009_299879 (2).html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_299879%20(2).html) | Copie strictement identique du fichier précédent. |
| [deepseek_html_20261009_5e4e22.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_5e4e22.html) | Studio — 21 propositions : image de référence → analyse IA → 21 propositions d'images → vidéo parlante finale. |
| [deepseek_html_20261009_6558de.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_6558de.html) | Studio — Film collectif : image → analyse → 21 images + 20 styles additionnels → film collectif des images sélectionnées. |
| [deepseek_html_20261009_7c63e1.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_7c63e1.html) | Studio — Sessions & styles : un clic — analyse vision, reconstructions prompt-only, 19 styles + complémentaire, tout en parallèle. |
| [deepseek_html_20261009_9918ac.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_9918ac.html) | Studio — 40 images par bloc : une photo puis des blocs créatifs de 40 images (catégories personnages et décors générées sans la photo). |
| [deepseek_html_20261009_c1cb28.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_c1cb28.html) | Scene Studio : générateur de scènes complètes (décor, ambiance, action) à partir de descriptions. |
| [deepseek_html_20261009_f81bff.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_f81bff.html) | Studio — Blocs infinis : une photo + blocs créatifs illimités de 40 images, styles favoris et persistance locale. |
| [plan-sequence-v23.html](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/plan-sequence-v23.html) | Plan-Séquence v23 : scénarisation et rendu d'un plan unique continu. |
| [readme.md](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/readme.md) / [readme-redesigned-potato.md](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/readme-redesigned-potato.md) | README du dépôt : sommaire des 41 logiciels, tableau détaillé et catégories (deux copies identiques). |

Catégories rapides : JT / actualité (NewsReel, Cinéma Studio, VISUAL.JOURNAL, Journal Visuel) · Films et scénarios (Kata Studio, Ciné Studio, Studio d'Auteur, Dessin Animé IA) · Plans uniques (Plan-Séquence v15/v23/v26) · Images et styles (Style Studio, Copy Studio, Studio variantes) · Divers (APPFORGE, MoneyPrinterTurbo, ViMax-Agnès, Scene Studio).

## 🔧 4. Code-a-reparer — travaux en cours

Codes qui ne marchent pas encore complètement : le début fonctionne bien et de grandes options utiles sont déjà en place, mais des bugs subsistent souvent vers la fin de la chaîne. Bonnes pistes à reprendre.

- [cine-genesis-studio (3).html](https://github.com/laurentvoanhofficiel-jpg/Code-a-reparer/blob/main/cine-genesis-studio%20(3).html) — Itération en développement du studio CINÉ-GENESIS (films IA en 7 étapes) : les premières étapes (clés, genre, synopsis, personnages) sont opérationnelles, la fin du pipeline est à corriger.
- [deepseek_html_20261010_28d9b3.html](https://github.com/laurentvoanhofficiel-jpg/Code-a-reparer/blob/main/deepseek_html_20261010_28d9b3.html) — Autre itération de Ciné-Genesis Studio, même principe : à réparer, base réutilisable.

## 👤 5. laurentvoanhofficiel-jpg/laurentvoanhofficiel-jpg

Dépôt de profil GitHub, actuellement vide. Ajoutez-y un README.md pour présenter votre profil et vos projets.