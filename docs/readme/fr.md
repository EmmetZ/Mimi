<div align="center">
  <img src="../../src-tauri/icons/128x128@2x.png" width="96" alt="mimi">
  <h1>Mimi</h1>
  <p>Sous-titres et traduction en direct pour l’audio du système ou le microphone sur macOS 13+ (puces Apple et Intel), Windows et Linux x86_64.</p>
  <p>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/github/v/release/yuxino/mimi?style=flat&amp;logo=github&amp;logoColor=white" alt="Dernière version"></a>
    <a href="https://github.com/yuxino/mimi/releases"><img src="https://img.shields.io/github/downloads/yuxino/mimi/total?style=flat&amp;labelColor=a85f82&amp;color=e889b5" alt="Nombre total de téléchargements"></a>
    <a href="https://github.com/yuxino/mimi/actions/workflows/ci.yml?query=branch%3Amain"><img src="https://img.shields.io/github/actions/workflow/status/yuxino/mimi/ci.yml?style=flat&amp;logo=githubactions&amp;logoColor=white&amp;branch=main&amp;event=push&amp;label=CI" alt="État de la CI sur main"></a>
    <a href="../../LICENSE"><img src="https://img.shields.io/github/license/yuxino/mimi?style=flat&amp;logo=opensourceinitiative&amp;logoColor=white" alt="Licence MIT"></a>
  </p>
  <p>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/macOS-13%2B-555?style=flat&amp;logo=apple&amp;logoColor=white" alt="macOS 13+"></a>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/Windows-x64-0078D4?style=flat&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDBoMTF2MTFIMHptMTMgMGgxMXYxMUgxM3pNMCAxM2gxMXYxMUgwem0xMyAwaDExdjExSDEzeiIvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="Windows x64"></a>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/Linux-x86__64-FCC624?style=flat&amp;logo=linux&amp;logoColor=white" alt="Linux"></a>
    <a href="../../android/README.md"><img src="https://img.shields.io/badge/Android-app-3DDC84?style=flat&amp;logo=android&amp;logoColor=white" alt="Android"></a>
  </p>
  <p>
    <a href="../../README_EN.md">English</a> · <a href="../../README.md">简体中文</a> · <a href="zh-TW.md">繁體中文</a> · <a href="ja.md">日本語</a> · <a href="th.md">ภาษาไทย</a> · <a href="ko.md">한국어</a> · <a href="fr.md">Français</a> · <a href="de.md">Deutsch</a>
  </p>
</div>

![Illustration des sous-titres bilingues de Mimi avec un dialogue fictif](../assets/readme-preview.png)

Illustration de l’interface avec un dialogue d’exemple. [Voir les sous-titres et le mode immersif (ancienne interface)](../demos/README.md).

## Lire tout en écoutant

- **Comprendre ce qui passe** : des sous-titres flottants pour les voix des films, diffusions et cours. Affichez les deux langues, la traduction seule ou l’original seul.
- **Choisir la source** : le son de l’ordinateur par défaut ; activez vous-même le microphone ou les deux sources. Sélectionnez une application sous macOS / Windows 11.
- **Adapter l’affichage** : réglez la position, la taille et la couleur. Le mode immersif ne garde que le texte ; la transparence aux clics permet d’utiliser l’application dessous.
- **Enregistrer au besoin** : sur ordinateur, conservez les sous-titres ou le son sélectionné et exportez en TXT / WAV. La sauvegarde et l’enregistrement sont désactivés par défaut.

## Premiers pas

1. **[Téléchargez Mimi](https://github.com/yuxino/mimi/releases/latest)** pour macOS 13+ (puce Apple / Intel), Windows x64 ou Linux x86_64. Sur téléphone, suivez le [guide Android (anglais)](../../android/README.md#start).
2. **Configurez un service** dans Réglages → Modèles et services (Parole et traduction dans les anciennes versions). Choisissez le service et enregistrez ses identifiants. Le [guide de configuration (anglais)](../provider-setup.md#choose) explique les choix et l’obtention d’une clé.
3. **Lancez les sous-titres**. Choisissez la source audio, la langue parlée et la langue cible. Lancez un contenu, activez les sous-titres en direct sur la page Sous-titres et accordez les autorisations audio demandées.

Mimi est gratuit ; les services cloud peuvent être payants. La reconnaissance cloud reçoit l’audio, la traduction distante reçoit le texte reconnu. Le traitement local nécessite des services Apple compatibles ; consultez les conditions dans le guide de configuration.

## Besoin d’aide ?

Le [guide d’utilisation](../usage.fr.md) couvre l’installation, les autorisations, l’affichage et les sessions enregistrées. Si les sous-titres manquent ou si la connexion échoue, consultez les [erreurs de reconnaissance](../usage.fr.md#errors). Si le problème persiste, [signalez-le](https://github.com/yuxino/mimi/issues).

## Contributeurs

Pour participer, consultez le [guide de contribution (anglais/chinois)](../../.github/CONTRIBUTING.md).

Merci à toutes les personnes qui écrivent du code, signalent des problèmes, essaient Mimi ou le font connaître (๑•̀ㅂ•́)و✧

Un grand merci à [@yebuwudong](https://github.com/yebuwudong) pour l’[application Android](https://github.com/yuxino/mimi/pull/37), ainsi qu’à [@LLLin000](https://github.com/LLLin000) pour l’[animation des sous-titres](https://github.com/yuxino/mimi/pull/67) et les [améliorations audio sous Windows](https://github.com/yuxino/mimi/pull/89).

Merci aussi à [@Chtholly000](https://github.com/Chtholly000) pour les améliorations des [sous-titres continus de Gemini et du renouvellement planifié des connexions](https://github.com/yuxino/Mimi/pull/176).

Merci à [@EmmetZ](https://github.com/EmmetZ) d’avoir corrigé [les commandes qui ne suivaient pas la fenêtre de sous-titres sous Wayland](https://github.com/yuxino/Mimi/pull/242).

Merci à [@wangmian0](https://github.com/wangmian0) d’avoir [désactivé le mode de raisonnement de DeepSeek pour la traduction des sous-titres en direct](https://github.com/yuxino/Mimi/pull/270).

<p>
  <a href="https://github.com/yuxino"><img src="../assets/contributors/yuxino.svg" width="64" height="64" alt="@yuxino"></a>
  <a href="https://github.com/LLLin000"><img src="../assets/contributors/LLLin000.svg" width="64" height="64" alt="@LLLin000"></a>
  <a href="https://github.com/yebuwudong"><img src="../assets/contributors/yebuwudong.svg" width="64" height="64" alt="@yebuwudong"></a>
  <a href="https://github.com/Chtholly000"><img src="../assets/contributors/Chtholly000.svg" width="64" height="64" alt="@Chtholly000"></a>
  <a href="https://github.com/inhome"><img src="../assets/contributors/inhome.svg" width="64" height="64" alt="@inhome"></a>
  <a href="https://github.com/EmmetZ"><img src="../assets/contributors/EmmetZ.svg" width="64" height="64" alt="@EmmetZ"></a>
  <a href="https://github.com/wangmian0"><img src="../assets/contributors/wangmian0.svg" width="64" height="64" alt="@wangmian0"></a>
</p>

[Tous les contributeurs](https://github.com/yuxino/mimi/graphs/contributors)

## Communauté

Merci aux membres de [V2EX](https://www.v2ex.com/), [LINUX DO](https://linux.do/), [Appinn](https://meta.appinn.net/), [NodeLoc](https://www.nodeloc.com/), [Solo](https://solo.xin/), [Xinquji](https://xinquji.com/posts/859305) et [Eleduck](https://eleduck.com/) d’avoir essayé Mimi, partagé leurs retours et fait connaître le projet.

[MIT](../../LICENSE) © 2026 yuxino
