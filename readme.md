

# 👋 Laurent Vo Anh — AI Creative Tools Collection

Bienvenue sur mon profil GitHub ! Je suis **Laurent Vo Anh**, créateur d'outils web autonomes (fichiers HTML uniques) dédiés à la **génération d'images et de vidéos par intelligence artificielle**, avec un focus sur l'API **Agnès AI** et l'intégration avec **Google Flow / Veo 3.1**.

Tous mes outils sont des **fichiers HTML autonomes** : pas d'installation, pas de build, pas de serveur. Vous ouvrez le fichier dans un navigateur, vous entrez votre clé API, et l'application fonctionne.

> ⚠️ **Note** : Les liens ci-dessous pointent vers la branche `main`. Si un lien renvoie une 404, remplacez `main` par `master` dans l'URL, ou naviguez directement depuis la page du dépôt.

---

## 📑 Table des matières

- [🎬 Studios de cinéma & vidéo IA](#-studios-de-cinéma--vidéo-ia)
- [🖼️ Labs de stylisation d'images](#️-labs-de-stylisation-dimages)
- [📰 Actualités RSS → Visuel](#-actualités-rss--visuel)
- [🎭 Portraits & sosies](#-portraits--sosies)
- [📖 Analyse biblique IA](#-analyse-biblique-ia)
- [🛠️ Outils divers & prototypes](#️-outils-divers--prototypes)
- [🔧 Notes techniques](#-notes-techniques)

---

## 🎬 Studios de cinéma & vidéo IA

### 📁 [Voanh-Agnes-film-maker](https://github.com/laurentvoanhofficiel-jpg/Voanh-Agnes-film-maker)

**CINÉ-GENESIS** — Le studio complet de création de films IA en un seul fichier HTML.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1 (référence)** | `index.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Voanh-Agnes-film-maker/blob/main/index.html) | Studio guidé en **7 étapes** pour produire un court-métrage de A à Z |

**Ce que fait le code :**
L'application vous guide à travers un pipeline complet de production cinématographique :
1. **Clés API** — Saisie et validation des clés (Agnès AI, Google Flow)
2. **Genre** — Choix du genre (thriller, science-fiction, drame, etc.)
3. **Synopsis** — Génération assistée du synopsis par l'IA
4. **Personnages** — Création des fiches personnages (nom, apparence, traits)
5. **Scènes** — Découpage en scènes avec descriptions
6. **Plans** — Génération des prompts de plans (image clé + mouvement caméra)
7. **Vidéos** — Génération des vidéos via Google Flow / Veo 3.1

**Mini mode d'emploi :**
1. Téléchargez `index.html` et ouvrez-le dans Chrome ou Edge.
2. Entrez votre clé API Agnès AI (et éventuellement votre clé Google Flow).
3. Suivez les 7 onglets dans l'ordre. Chaque étape valide la précédente.
4. À la fin, exportez le storyboard complet ou lancez la génération vidéo.

**Résultat :** Un **court-métrage complet** (synopsis + personnages + scènes + plans + vidéos), exportable en JSON ou directement lisible dans le studio.

---

### 📁 [Agnes-ai-film-maker-Universal-one-page-HTML-4-all](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-film-maker-Universal-one-page-HTML-4-all)

Version **universelle** du studio CINÉ-GENESIS, pensée pour être un fichier HTML unique à ouvrir n'importe où.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1 (universelle)** | `deepseek_html_20261010_d59eb0.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-film-maker-Universal-one-page-HTML-4-all/blob/main/deepseek_html_20261010_d59eb0.html) | Studio CINÉ-GENESIS universel, assistant guidé en 7 étapes |

**Ce que fait le code :** Identique à CINÉ-GENESIS, mais **sans dépendances externes** — tout est inline (CSS, JS, prompts). Idéal pour partager le fichier par email ou clé USB.

**Mini mode d'emploi :** Ouvrez le fichier → entrez la clé API → suivez les 7 étapes.

**Résultat :** Un film IA complet, généré entièrement depuis un seul fichier HTML.

---

### 📁 [Ai-Movie-maker-tools](https://github.com/laurentvoanhofficiel-jpg/Ai-Movie-maker-tools)

Deux applications pour générer des **images clés** (first frames) à utiliser comme point de départ dans Google Flow pour Veo 3.1.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1 — Hyperreal** | `deepseek_html_20261014_0c6fb6.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Ai-Movie-maker-tools/blob/main/deepseek_html_20261014_0c6fb6.html) | **Hyperreal Photo Lab** — transforme des images de référence en série de photos hyperréalistes |
| **v1 — Multi-Style** | `deepseek_html_20261014_b9b777.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Ai-Movie-maker-tools/blob/main/deepseek_html_20261014_b9b777.html) | **Multi-Style Lab** — transforme une image dans 21 styles (Ghibli, Pixar, cyberpunk, etc.) |

**Ce que fait Hyperreal Photo Lab :**
Prend une ou plusieurs images de référence et génère une série de photographies hyperréalistes cohérentes (même sujet, même éclairage, variations de pose/cadrage). Utilise des agents conçus dynamiquement par l'IA Agnès.

**Ce que fait Multi-Style Lab :**
Prend une image source et la décline dans **21 styles visuels** prédéfinis (Ghibli, Pixar, cyberpunk, aquarelle, noir et blanc, etc.), avec un onglet personnalisé pour créer son propre style.

**Mini mode d'emploi :**
1. Ouvrez le fichier, entrez la clé API Agnès.
2. Uploadez une image de référence.
3. Choisissez le style (ou le nombre de variantes hyperréalistes).
4. Cliquez sur « Générer ».

**Résultat :** Des **images clés haute qualité** prêtes à être importées dans Google Flow pour lancer la génération vidéo Veo 3.1.

---

### 📁 [redesigned-potato](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato)

Le plus grand dépôt : une **collection d'outils HTML autonomes** pour créer vidéos, films et images par IA.

#### 🎥 NewsReel Studio (JT par IA)
| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v2 (référence)** | `NewsReel_Studio_v2 (3).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/NewsReel_Studio_v2%20(3).html) | Générateur de journal télévisé (JT) complet |
| **v1 — Le JT** | `deepseek_html_20261001_4955e8 (2) (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261001_4955e8%20(2)%20(2).html) | Version initiale du JT par IA |
| **v1 — copie** | `deepseek_html_20261001_4955e8 (3) (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261001_4955e8%20(3)%20(2).html) | Copie de la version initiale |
| **v1 — L'actualité en film** | `deepseek_html_20261001_f4d029 (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261001_f4d029%20(1).html) | Variante « actualité en film » |

**Ce que fait NewsReel Studio :** Génère un **journal télévisé complet** : intro, présentateur, sujets, transitions, habillage graphique — à partir d'un texte d'actualité saisi ou d'un flux RSS.

**Résultat :** Un JT complet, exportable en vidéo ou en HTML.

#### 🎬 Kata Studio (Cinéma généré)
| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1 — Cinéma Généré** | `deepseek_html_20260930_a237a0 (3).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260930_a237a0%20(3).html) | Génération complète d'un court-métrage IA |
| **v1 — Cinéma Généré (variante)** | `deepseek_html_20260930_c27961 (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260930_c27961%20(1).html) | Variante de Kata Studio |
| **v1 — Le Moine Shaolin** | `deepseek_html_20260930_ddbba8 (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260930_ddbba8%20(2).html) | Studio thématique « Le Moine Shaolin » |
| **v1 — Cinéma Généré (autre)** | `deepseek_html_20260930_edff6d.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260930_edff6d.html) | Autre variante de Kata Studio |

**Ce que fait Kata Studio :** Génère un **court-métrage IA** complet : scénario, découpage en plans, images puis film. Chaque variante est pré-configurée avec un univers thématique.

**Résultat :** Un film court généré de A à Z.

#### 🎥 Cinéma Studio (JT cinématographique)
| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1 — JT cinématographique** | `deepseek_html_20261007_68b448 (10) (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261007_68b448%20(10)%20(1).html) | JT au format cinématographique |
| **v1 — copie** | `deepseek_html_20261007_68b448 (10) (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261007_68b448%20(10)%20(2).html) | Copie de la version cinéma |
| **v7** | `deepseek_html_20261007_68b448 (7) (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261007_68b448%20(7)%20(2).html) | Version 7 du JT cinématographique |
| **v1 — News × Réalisateurs × Style** | `deepseek_html_20261007_d9219c (2) (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261007_d9219c%20(2)%20(2).html) | JT combinant actualités, réalisateurs et styles |

**Ce que fait Cinéma Studio :** Produit des **journaux télévisés au format cinématographique** (cadrage, lumière, montage).

**Résultat :** Un JT avec une esthétique de cinéma.

#### 🎬 Studio Plan-Séquence
| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261008_267dcc.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_267dcc.html) | Studio de plan-séquence |
| **v1 — autre** | `deepseek_html_20261008_623f87.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_623f87.html) | Autre version du studio plan-séquence |
| **v1 — encore** | `deepseek_html_20261008_7846d2.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_7846d2.html) | Encore une variante |
| **v15** | `deepseek_html_20261008_c87882.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_c87882.html) | Version 15 |
| **v26** | `deepseek_html_20261008_eb4c02.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_eb4c02.html) | Version 26 |
| **v23** | `plan-sequence-v23.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/plan-sequence-v23.html) | Version 23 |

**Ce que fait Studio Plan-Séquence :** Un studio dédié à la création de **plans-séquences** (scènes filmées en un seul plan continu) assistée par IA.

**Résultat :** Des plans-séquences générés et assemblés.

#### 🎨 Autres studios et générateurs
| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `appforge.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/appforge.html) | **APPFORGE** — génère des applications web à partir d'une description |
| **v1** | `deepseek_html_20260925_fdc9e9 (6) (5).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260925_fdc9e9%20(6)%20(5).html) | **Dessin Animé IA** — studio de dessin animé |
| **v1** | `deepseek_html_20260928_a49b89 (3).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20260928_a49b89%20(3).html) | **MoneyPrinterTurbo · Agnès** — génération de vidéos monétisables |
| **v1** | `deepseek_html_20261006_367208 (1) (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261006_367208%20(1)%20(2).html) | **ViMax-Agnès Studio** — studio de création vidéo |
| **v1** | `deepseek_html_20261006_618dc3 (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261006_618dc3%20(2).html) | **Style Studio** — applique des styles visuels |
| **v1** | `deepseek_html_20261008_e00c27 (2) (1) (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_e00c27%20(2)%20(1)%20(1).html) | **VISUAL.JOURNAL** |
| **v1** | `deepseek_html_20261008_e5910a.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_e5910a.html) | **Journal Visuel** |
| **v1** | `deepseek_html_20261008_f10acd.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_f10acd.html) | **Studio d'Auteur** |
| **v1** | `deepseek_html_20261008_faf9ac.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_faf9ac.html) | **VISUAL.JOURNAL — Chœur intellectuel** |
| **v1 — copie** | `deepseek_html_20261008_faf9ac (1) (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261008_faf9ac%20(1)%20(2).html) | Copie de VISUAL.JOURNAL — Chœur intellectuel |
| **v1** | `deepseek_html_20261009_0a2943 (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_0a2943%20(1).html) | **Studio Portrait 9:16** |
| **v1** | `deepseek_html_20261009_1e97ca (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_1e97ca%20(1).html) | **Ciné Studio** |
| **v1** | `deepseek_html_20261009_23906d (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_23906d%20(1).html) | **Copy Studio** |
| **v1** | `deepseek_html_20261009_299879 (1) (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_299879%20(1)%20(1).html) | Studio avec sessions, IndexedDB, film |
| **v1 — copie** | `deepseek_html_20261009_299879 (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_299879%20(2).html) | Copie du studio IndexedDB |
| **v1** | `deepseek_html_20261009_5e4e22.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_5e4e22.html) | Studio — 21 propositions |
| **v1** | `deepseek_html_20261009_6558de.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_6558de.html) | Studio — Film collectif |
| **v1** | `deepseek_html_20261009_7c63e1.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_7c63e1.html) | Studio — Sessions & styles |
| **v1** | `deepseek_html_20261009_9918ac.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_9918ac.html) | Studio — 40 images par bloc |
| **v1** | `deepseek_html_20261009_c1cb28.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_c1cb28.html) | **Scene Studio** |
| **v1** | `deepseek_html_20261009_f81bff.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/redesigned-potato/blob/main/deepseek_html_20261009_f81bff.html) | Studio — Blocs infinis |

**Mini mode d'emploi (commun à tous les outils de `redesigned-potato`) :**
1. Ouvrez le fichier HTML dans Chrome/Edge.
2. Entrez votre clé API Agnès AI.
3. Remplissez le formulaire (texte, image, ou scénario selon l'outil).
4. Cliquez sur « Générer » et suivez la progression.

**Résultat :** Selon l'outil : un JT, une app web, un dessin animé, une vidéo monétisable, ou une série de plans stylisés.

---

### 📁 [Agnes-ai-story-bord-maker-for-Google-flow-](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-story-bord-maker-for-Google-flow-)

Créateur de **storyboards** avec prompts prêts pour Google Flow et autres générateurs vidéo.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261016_a0d94e.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-story-bord-maker-for-Google-flow-/blob/main/deepseek_html_20261016_a0d94e.html) | Version 1 du storyboard maker |
| **v2** | `deepseek_html_20261016_daf53f.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-story-bord-maker-for-Google-flow-/blob/main/deepseek_html_20261016_daf53f.html) | Version 2 |
| **v3** | `deepseek_html_20261016_daf53f (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-story-bord-maker-for-Google-flow-/blob/main/deepseek_html_20261016_daf53f%20(2).html) | Version 3 |
| **v4 (récente)** | `deepseek_html_20261016_daf53f (2) (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-story-bord-maker-for-Google-flow-/blob/main/deepseek_html_20261016_daf53f%20(2)%20(1).html) | Version la plus récente |

**Ce que fait le code :**
Prend un synopsis ou un script, et génère un **storyboard visuel** : chaque plan est décrit (cadrage, mouvement, lumière) et accompagné d'un **prompt optimisé pour Google Flow** (Veo 3.1) ou un autre générateur (Runway, Pika, etc.).

**Mini mode d'emploi :**
1. Ouvrez la version la plus récente (`daf53f (2) (1)`).
2. Entrez la clé API.
3. Collez votre synopsis.
4. Choisissez le générateur cible (Google Flow, Runway, Pika…).
5. Exportez le storyboard (JSON ou copier-coller des prompts).

**Résultat :** Un **storyboard complet** avec prompts prêts à l'emploi pour générer chaque plan vidéo.

---

## 🖼️ Labs de stylisation d'images

### 📁 [Moebius-style-by-agnes-ai](https://github.com/laurentvoanhofficiel-jpg/Moebius-style-by-agnes-ai)

Application de transformation de photos dans le style du dessinateur **Moebius** (Jean Giraud).

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261017_81ffe7.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Moebius-style-by-agnes-ai/blob/main/deepseek_html_20261017_81ffe7.html) | Version 1 |
| **v2** | `deepseek_html_20261017_f164e5.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Moebius-style-by-agnes-ai/blob/main/deepseek_html_20261017_f164e5.html) | Version 2 |

**Ce que fait le code :**
Analyse une photo source (portrait, paysage, scène) et la retranscrit dans le **style Moebius** : lignes fines, aplats de couleurs désaturées, ambiance science-fiction poétique, désert de « L'Incal » ou « Arzach ».

**Mini mode d'emploi :**
1. Ouvrez le fichier, entrez la clé API.
2. Uploadez une photo.
3. Ajustez l'intensité du style (curseur).
4. Cliquez sur « Générer ».

**Résultat :** Une **image stylisée Moebius**, prête à être utilisée comme concept art ou image clé.

---

### 📁 [Egon-schieles-by-agnes-ai-model](https://github.com/laurentvoanhofficiel-jpg/Egon-schieles-by-agnes-ai-model)

Labs pour générer des portraits et scènes stylisés par **Egon Schiele**.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v2** | `deepseek_html_20261016_a8841e.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Egon-schieles-by-agnes-ai-model/blob/main/deepseek_html_20261016_a8841e.html) | 20 concepts viennois, analyse du visage seul |
| **v3 (récente)** | `deepseek_html_20261017_fc5c42 (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Egon-schieles-by-agnes-ai-model/blob/main/deepseek_html_20261017_fc5c42%20(1).html) | 40 œuvres pré-chargées, analyse visage + habits + décor |

**Ce que fait la Version 2 :**
Analyse le **visage** d'une photo et le retranscrit dans le style d'Egon Schiele (traits anguleux, couleurs expressionnistes, poses contorsionnées), avec 20 concepts viennois (café, atelier, rue…).

**Ce que fait la Version 3 :**
Étend l'analyse au **visage + habits + décor**, propose **40 œuvres de Schiele pré-chargées** comme références, et impose la **palette de couleurs** de l'artiste.

**Mini mode d'emploi :**
1. Ouvrez la version 3 (`fc5c42 (1)`).
2. Entrez la clé API.
3. Uploadez une photo.
4. Choisissez une œuvre de référence (parmi les 40).
5. Cliquez sur « Générer ».

**Résultat :** Un **portrait expressionniste** dans le style Schiele, avec décor et palette cohérents.

---

### 📁 [Portrait-by-voanh-agnes-ai-pic-2-bulk-pic](https://github.com/laurentvoanhofficiel-jpg/Portrait-by-voanh-agnes-ai-pic-2-bulk-pic)

Labs pour générer une multitude de **portraits stylisés** à partir d'une seule image.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v2 (Multi-Style)** | `deepseek_html_20261016_35be39.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Portrait-by-voanh-agnes-ai-pic-2-bulk-pic/blob/main/deepseek_html_20261016_35be39.html) | **Visual.Studio — Multi-Style Lab v2** — 39 presets + onglet personnalisé |
| **v3.1 (Monetize)** | `deepseek_html_20261016_4d5942.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Portrait-by-voanh-agnes-ai-pic-2-bulk-pic/blob/main/deepseek_html_20261016_4d5942.html) | **Visual.Studio — Monetize Lab v3.1** — styles orientés monétisation |
| **v1 (Consciousness)** | `deepseek_html_20261016_500ec2.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Portrait-by-voanh-agnes-ai-pic-2-bulk-pic/blob/main/deepseek_html_20261016_500ec2.html) | **Visual.Studio — Consciousness Lab** — styles abstraits / « conscients » |
| **v1 (Wes Anderson)** | `deepseek_html_20261016_8a5ad9.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Portrait-by-voanh-agnes-ai-pic-2-bulk-pic/blob/main/deepseek_html_20261016_8a5ad9.html) | **Visual.Studio — Wes Anderson Lab** — esthétique Wes Anderson |
| **v1 (Director)** | `deepseek_html_20261016_f31b63.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Portrait-by-voanh-agnes-ai-pic-2-bulk-pic/blob/main/deepseek_html_20261016_f31b63.html) | **Visual.Studio — Director Lab** — mise en scène cinématographique |

**Ce que fait Multi-Style Lab v2 :**
Prend une photo de portrait et la décline en **39 styles** prédéfinis (peinture, cinéma, illustration, etc.) + un onglet pour créer son propre style. Génération en **bulk** (plusieurs variantes d'un coup).

**Ce que fait Monetize Lab v3.1 :**
Variante avec des styles **optimisés pour la monétisation** (visuels accrocheurs, esthétiques tendance).

**Ce que fait Consciousness Lab :**
Exploration de styles **abstraits ou « conscients »** (formes organiques, textures oniriques).

**Ce que fait Wes Anderson Lab :**
Presets inspirés de l'esthétique **Wes Anderson** (symétrie, palettes pastel, cadrages frontaux).

**Ce que fait Director Lab :**
Styles de **mise en scène cinématographique** (éclairage, profondeur de champ, ambiance de film).

**Mini mode d'emploi :**
1. Ouvrez le lab souhaité.
2. Entrez la clé API.
3. Uploadez un portrait.
4. Sélectionnez un ou plusieurs presets.
5. Lancez la génération en bulk.

**Résultat :** Une **série de portraits stylisés** (une par preset), exportables en ZIP.

---

### 📁 [Agn-s-ai-art-maker-4-pic-to-bulk](https://github.com/laurentvoanhofficiel-jpg/Agn-s-ai-art-maker-4-pic-to-bulk)

Transforme plusieurs photos en style **Moebius** et génère des images en masse.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261017_079d2b.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agn-s-ai-art-maker-4-pic-to-bulk/blob/main/deepseek_html_20261017_079d2b.html) | Version 1 |
| **v2** | `deepseek_html_20261017_0fa7f2 (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agn-s-ai-art-maker-4-pic-to-bulk/blob/main/deepseek_html_20261017_0fa7f2%20(1).html) | Version 2 |
| **v3** | `deepseek_html_20261017_56536e.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agn-s-ai-art-maker-4-pic-to-bulk/blob/main/deepseek_html_20261017_56536e.html) | Version 3 |
| **v4 (récente)** | `deepseek_html_20261017_84ad6a.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agn-s-ai-art-maker-4-pic-to-bulk/blob/main/deepseek_html_20261017_84ad6a.html) | Version 4 (la plus récente) |

**Ce que fait le code :** Prend **4 photos** en entrée et génère une **série d'images** dans le style Moebius, en bulk.

**Mini mode d'emploi :** Ouvrez la version 4 → entrez la clé API → uploadez 4 photos → lancez la génération.

**Résultat :** Un **lot d'images stylisées Moebius** à partir de 4 photos sources.

---

## 📰 Actualités RSS → Visuel

### 📁 [Agnes-ai-news-RSS-2-diaporama-](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-news-RSS-2-diaporama-)

Transforme des actualités RSS en **diaporama visuel**.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v9.1 (corrigée)** | `visual-journal-v9.1-corrige.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agnes-ai-news-RSS-2-diaporama-/blob/main/visual-journal-v9.1-corrige.html) | Outil de transformation RSS → diaporama |

**Ce que fait le code :**
Récupère un flux RSS, extrait les articles, génère pour chacun une **image illustrative** (via Agnès AI) et assemble le tout en **diaporama** (style journal télévisé ou magazine).

**Mini mode d'emploi :**
1. Ouvrez le fichier, entrez la clé API.
2. Collez l'URL d'un flux RSS.
3. Choisissez le style visuel (journal, magazine, cinéma).
4. Lancez la génération.

**Résultat :** Un **diaporama visuel** des actualités, exportable en vidéo ou en HTML.

---

### 📁 [RSS-News-by-artist-on-agnes-ai-model](https://github.com/laurentvoanhofficiel-jpg/RSS-News-by-artist-on-agnes-ai-model)

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261016_2f5f92.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/RSS-News-by-artist-on-agnes-ai-model/blob/main/deepseek_html_20261016_2f5f92.html) | Génération d'actualités par un « artiste » IA |

**Ce que fait le code :** Transforme des actualités RSS en contenu **stylisé par un artiste** (le style est défini par l'utilisateur ou par un preset).

**Mini mode d'emploi :** Ouvrez → clé API → URL RSS → choisir le style d'artiste → générer.

**Résultat :** Des **actualités illustrées** dans un style artistique.

---

### 📁 [RSS-News-to-Egon-schiele-art](https://github.com/laurentvoanhofficiel-jpg/RSS-News-to-Egon-schiele-art)

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261016_23dd02.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/RSS-News-to-Egon-schiele-art/blob/main/deepseek_html_20261016_23dd02.html) | Convertit des actualités RSS en créations style Egon Schiele |

**Ce que fait le code :** Prend un flux RSS et génère pour chaque article une **illustration dans le style d'Egon Schiele**.

**Mini mode d'emploi :** Ouvrez → clé API → URL RSS → générer.

**Résultat :** Un **flux d'actualités illustré** en style Schiele.

---

## 🎭 Portraits & sosies

### 📁 [Mes-faux-sosies-avec-agnes-ai](https://github.com/laurentvoanhofficiel-jpg/Mes-faux-sosies-avec-agnes-ai)

Application ludique pour créer une liste de **sosies** ou trouver le « sosie parfait » à partir d'une image.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261016_523557 (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Mes-faux-sosies-avec-agnes-ai/blob/main/deepseek_html_20261016_523557%20(1).html) | Version 1 |
| **v2** | `deepseek_html_20261016_cb131d.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Mes-faux-sosies-avec-agnes-ai/blob/main/deepseek_html_20261016_cb131d.html) | Version 2 |

**Ce que fait le code :** Analyse une photo de visage, identifie les **traits saillants**, et génère une liste de **sosies célèbres** ou de **variantes** du visage. Peut aussi générer des « faux sosies » (versions imaginaires).

**Mini mode d'emploi :** Ouvrez la version 2 → clé API → uploadez une photo → cliquer sur « Trouver mes sosies ».

**Résultat :** Une **galerie de sosies** (réels ou imaginaires) avec scores de ressemblance.

---

### 📁 [Just-me-myself-and-I-agnes-ai-one-picture-make-320-variants](https://github.com/laurentvoanhofficiel-jpg/Just-me-myself-and-I-agnes-ai-one-picture-make-320-variants)

**Ce que fait le dépôt :** (Dépôt actuellement vide, mais le nom indique la fonction.) Générer **320 variantes** à partir d'une seule image.

**Mini mode d'emploi :** (À venir — le code n'est pas encore publié.)

**Résultat attendu :** 320 variantes d'une même image source.

---

### 📁 [Laurent-Vo-Anh-top-model-pressbook-by-ai](https://github.com/laurentvoanhofficiel-jpg/Laurent-Vo-Anh-top-model-pressbook-by-ai)

Créer un **pressbook de top model** en analysant des photos via l'IA Agnès.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261014_47741b.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Laurent-Vo-Anh-top-model-pressbook-by-ai/blob/main/deepseek_html_20261014_47741b.html) | Version 1 |
| **v2** | `deepseek_html_20261014_8a875b.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Laurent-Vo-Anh-top-model-pressbook-by-ai/blob/main/deepseek_html_20261014_8a875b.html) | Version 2 |
| **v3** | `deepseek_html_20261014_d31ed2.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Laurent-Vo-Anh-top-model-pressbook-by-ai/blob/main/deepseek_html_20261014_d31ed2.html) | Version 3 |
| **v4** | `deepseek_html_20261014_d858dd.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Laurent-Vo-Anh-top-model-pressbook-by-ai/blob/main/deepseek_html_20261014_d858dd.html) | Version 4 |
| **v5** | `deepseek_html_20261014_d858dd (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Laurent-Vo-Anh-top-model-pressbook-by-ai/blob/main/deepseek_html_20261014_d858dd%20(1).html) | Version 5 |
| **v6 (récente)** | `deepseek_html_20261014_d858dd (2).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Laurent-Vo-Anh-top-model-pressbook-by-ai/blob/main/deepseek_html_20261014_d858dd%20(2).html) | Version 6 (la plus récente) |

**Ce que fait le code :** Analyse des photos d'un modèle (visage, corps, style) et génère un **pressbook professionnel** : bio, mensurations, photos retouchées, prompts pour Google Flow afin de créer des vidéos de défilé.

**Mini mode d'emploi :** Ouvrez la version la plus récente → clé API → uploadez les photos → générer le pressbook → exporter en PDF/HTML.

**Résultat :** Un **pressbook de top model** complet (bio + photos + prompts vidéo).

---

## 📖 Analyse biblique IA

### 📁 [Agn-s-g.od-motor](https://github.com/laurentvoanhofficiel-jpg/Agn-s-g.od-motor)

Projet **Genesis·Decoder** — moteur d'analyse de l'Ancien Testament assisté par IA.

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v3** | `deepseek_html_20261013_2e6d6d.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agn-s-g.od-motor/blob/main/deepseek_html_20261013_2e6d6d.html) | Validation E=mc² + analyse des jours 1 à 7 de la Genèse |
| **v4** | `deepseek_html_20261013_a30293.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agn-s-g.od-motor/blob/main/deepseek_html_20261013_a30293.html) | 39 livres de l'Ancien Testament + 15 « angles d'attaque » |
| **v5 (récente)** | `deepseek_html_20261014_783e95.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Agn-s-g.od-motor/blob/main/deepseek_html_20261014_783e95.html) | Moteur auto-évolutif (l'IA établit sa propre méthodologie) |

**Ce que fait la Version 3 :**
Gère les clés API, valide une démonstration scientifique (**E=mc²**) pour prouver la fiabilité du modèle, puis analyse les **jours 1 à 7 de la Genèse** avec un système de notation et de **détection d'hallucinations**.

**Ce que fait la Version 4 :**
Étend l'analyse aux **39 livres de l'Ancien Testament** et introduit **15 « angles d'attaque »** (lenses) pour examiner chaque verset sous différents angles (historique, littéraire, théologique, etc.).

**Ce que fait la Version 5 :**
Moteur **auto-évolutif** : l'IA doit d'abord **établir et valider sa propre méthodologie** avant de procéder à l'analyse complète.

**Mini mode d'emploi :**
1. Ouvrez la version souhaitée.
2. Entrez la clé API.
3. Laissez la validation scientifique se faire (E=mc²).
4. Choisissez les livres / versets à analyser.
5. Lancez l'analyse et lisez le rapport.

**Résultat :** Un **rapport d'analyse** verset par verset, avec scores, détection d'hallucinations et angles d'analyse.

---

## 🛠️ Outils divers & prototypes

### 📁 [Ofa](https://github.com/laurentvoanhofficiel-jpg/Ofa)

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v1** | `deepseek_html_20261017_0fa7f2 (1).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Ofa/blob/main/deepseek_html_20261017_0fa7f2%20(1).html) | Outil non documenté (à compléter) |

**Ce que fait le code :** Aucune description détaillée n'est fournie dans le dépôt. À documenter.

---

### 📁 [Code-a-reparer](https://github.com/laurentvoanhofficiel-jpg/Code-a-reparer)

Prototypes en cours de développement (bugs en fin de chaîne, mais début fonctionnel).

| Version | Fichier | Lien | Description |
|---|---|---|---|
| **v3** | `cine-genesis-studio (3).html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Code-a-reparer/blob/main/cine-genesis-studio%20(3).html) | Version expérimentale du studio de films |
| **v1** | `deepseek_html_20261010_28d9b3.html` | [Ouvrir](https://github.com/laurentvoanhofficiel-jpg/Code-a-reparer/blob/main/deepseek_html_20261010_28d9b3.html) | Prototype d'outil |

**Ce que fait le code :** Ce sont des **brouillons** — utiles comme pistes de développement, mais pas prêts pour la production.

---

### 📁 [Correction-de-tous-les-codes-de-Laurent-vo-anh-par-l-intelligence-artificielle-Maia](https://github.com/laurentvoanhofficiel-jpg/Correction-de-tous-les-codes-de-Laurent-vo-anh-par-l-intelligence-artificielle-Maia)

Ce dépôt ne contient pas de nouveaux outils, mais des **versions corrigées** des fichiers HTML des autres dépôts, organisées par dépôt d'origine. Il inclut également des fichiers `.diff` pour visualiser les changements.

**Mini mode d'emploi :** Naviguez dans le dossier du dépôt d'origine pour trouver la version corrigée.

**Résultat :** Des **versions stables** des outils, avec corrections de bugs.

---

### 📁 [laurentvoanhofficiel-jpg](https://github.com/laurentvoanhofficiel-jpg/laurentvoanhofficiel-jpg)

Dépôt de profil — sert de **catalogue** listant les autres dépôts et leurs fonctions. Ne contient pas de fichiers HTML exécutables.

---

## 🔧 Notes techniques

### Prérequis
- Un navigateur moderne (**Chrome** ou **Edge** recommandés — Firefox peut poser des problèmes avec certaines API).
- Une **clé API Agnès AI** (et éventuellement une clé Google Flow pour les outils vidéo).
- Une connexion Internet (les appels API se font en direct).

### Installation
Aucune installation ! Chaque outil est un **fichier HTML autonome** :
1. Téléchargez le fichier `.html` depuis GitHub (bouton « Raw » → « Enregistrer sous »).
2. Ouvrez-le dans votre navigateur.
3. Entrez votre clé API.

### Sécurité des clés API
- Les clés API sont stockées **localement** dans le navigateur (`localStorage`).
- Elles ne sont **jamais envoyées** à un serveur tiers autre que l'API Agnès AI.
- Pour les effacer : videz le cache/localStorage de votre navigateur.

### Structure des dépôts
- Chaque dépôt = un outil ou une famille d'outils.
- Les fichiers sont nommés `deepseek_html_<date>_<hash>.html` (nom généré automatiquement).
- Les versions successives sont conservées (v1, v2, v3…) pour permettre le rollback.

### Branches
- La branche par défaut est `main`. Si un lien renvoie une 404, essayez `master`.

---

## 📜 Licence

Ces outils sont fournis **tels quels**, à des fins créatives et éducatives. Vous êtes libre de les utiliser, modifier et partager. Une attribution est appréciée mais non obligatoire.

---

## 📬 Contact

- **GitHub** : [@laurentvoanhofficiel-jpg](https://github.com/laurentvoanhofficiel-jpg)
- **Agnès AI** : [API Agnès AI](https://agnes.ai) *(lien à vérifier)*

---
