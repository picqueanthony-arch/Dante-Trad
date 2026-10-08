# Dante Trad

**Live translated subtitles over any video — everything runs on your phone.**
A module of [Dante OS](https://github.com/picqueanthony-arch/Dante-OS).

*Français plus bas.*

## What it does

- A small subtitle bubble over any video: the YouTube app, Firefox, any app that lets Android capture its sound.
- **Whisper** (OpenAI's speech recognition) runs on the phone and hears the real speech, with punctuation. A **Google ML Kit offline translator** then translates it into your language.
- Translate **to** 18 languages: English, French, Spanish, German, Italian, Portuguese, Russian, Ukrainian, Polish, Dutch, Turkish, Arabic, Hindi, Japanese, Korean, Chinese, Indonesian, Vietnamese.
- Videos in 17 languages, or "Auto" (picking the video's language is more reliable).
- About 1 to 4 seconds behind the speech. Drag the bubble anywhere (one spot for portrait, one for landscape); tap it to see the original sentence; long-press to put it back at the bottom.
- **Nothing leaves your phone.** The Internet is only used once, to download the models: Whisper small (about 375 MB from HuggingFace), then about 30 MB per translation language.

## Requirements

- Android 14 or newer, 64-bit (arm64) phone. No root needed.
- About 500 MB of free storage.
- Android asks your permission to capture each time you start a translation: that's normal.

## Install

1. Download `Dante-Trad-1.0.0.apk` from [Releases](https://github.com/picqueanthony-arch/Dante-Trad/releases) and check its SHA-256.
2. Open Dante Trad, download the Whisper model (step 1), allow the permissions (step 2), choose the languages, then "Start translating".
3. On OnePlus phones, the "Phone manager" may show "Risks detected" after install, because the app captures sound and is not from the Play Store: tap "Ignore".

## Firefox extensions

- **Fullscreen for Dante OS**: real fullscreen on any page (no address bar, menus or status bar), keeps Dark Reader's dark mode. Waiting for Mozilla's review on [addons.mozilla.org](https://addons.mozilla.org/firefox/addon/fullscreen-for-dante-os/); until then, the signed file is in Releases.
- **Dante Trad for Dante OS**: a tab to start or stop Dante Trad without leaving the video. Signed by Mozilla, file in Releases.
- To install a file in Firefox for Android: Settings → About Firefox → tap the logo 5 times → back → "Install extension from file".
- With **uBlock Origin**, this gives a clean YouTube in Firefox: no ads, real fullscreen, live subtitles. (A DNS filter, Dante OS's included, cannot block YouTube ads: they come from the same servers as the videos.)

## Limits

- The translation is good but not perfect: it is an offline translator, not a human.
- Protected apps (Netflix and co.) block audio capture, and Dante Trad respects that.

## Credits and licenses

Whisper (OpenAI, MIT) · sherpa-onnx (k2-fsa, Apache 2.0) · ONNX Runtime (Microsoft, MIT) · Silero VAD (MIT) · Google ML Kit translation (Google terms).
Dante Trad itself: all rights reserved. AI-assisted development, directed, tested and verified by its author.

---

# Dante Trad (français)

**Des sous-titres traduits en direct sur n'importe quelle vidéo, entièrement sur le téléphone.**
Un module de [Dante OS](https://github.com/picqueanthony-arch/Dante-OS).

- Une bulle de sous-titres par-dessus n'importe quelle vidéo : l'app YouTube, Firefox, toute app qui laisse Android capter son son.
- **Whisper** reconnaît la voix sur le téléphone, avec la ponctuation, puis un **traducteur hors ligne de Google (ML Kit)** traduit dans ta langue (18 langues au choix).
- Vidéos dans 17 langues, ou « Auto » (choisir la langue de la vidéo est plus fiable).
- Environ 1 à 4 secondes de retard. Glisse la bulle où tu veux (une place debout, une couché), touche-la pour la phrase d'origine, appui long pour la remettre en bas.
- **Rien ne quitte le téléphone.** Internet ne sert qu'une fois, pour les modèles : Whisper small (environ 375 Mo), puis environ 30 Mo par langue.
- Android 14 ou plus récent, 64 bits, sans root, environ 500 Mo libres. Android demande l'autorisation de capturer à chaque démarrage : c'est normal.
- Sur OnePlus, le gestionnaire du téléphone peut afficher « Risques détectés » après l'installation : appuie sur « Ignorer ».

**Extensions Firefox :** « Fullscreen for Dante OS » (vrai plein écran, garde le mode sombre de Dark Reader ; en attente de validation par Mozilla, le fichier signé est dans Releases) et « Dante Trad for Dante OS » (un onglet pour lancer ou arrêter Dante Trad). Installation depuis un fichier dans Firefox Android : Paramètres → À propos de Firefox → toucher le logo 5 fois → retour → « Installer une extension depuis un fichier ». Avec **uBlock Origin**, ça donne un YouTube propre : sans pubs, en vrai plein écran, avec les sous-titres traduits. (Un filtre DNS, celui de Dante OS compris, ne peut pas bloquer les pubs YouTube : elles viennent des mêmes serveurs que les vidéos.)

**Limites :** la traduction est bonne mais pas parfaite ; les apps protégées (Netflix…) bloquent la capture, et Dante Trad le respecte.

**Crédits :** Whisper (OpenAI, MIT) · sherpa-onnx (k2-fsa, Apache 2.0) · ONNX Runtime (MIT) · Silero VAD (MIT) · traduction ML Kit de Google (conditions de Google). Dante Trad : tous droits réservés. Développement assisté par IA, dirigé, testé et vérifié par son auteur.
