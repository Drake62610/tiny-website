+++
title = "Drake deviens enfin célèbre"
description = "Vive Le monde des rappeurs"
author = "Florian MATTE"
date = "2021-19-04"
tags = ["famous","youtube"]
[[images]]
  src = "https://cdn.discordapp.com/attachments/178532977901305857/832286661743738930/Screenshot_20210415_180919.jpg"
  alt = "Le début de la célébrité"
  stretch = "stretchH"
+++

Merci Daviyas
<!--more--->
La fonction [`emojify`] (https://gohugo.io/functions/emojify/) peut être appelée directement dans les modèles ou [Inline Shortcodes] (https://gohugo.io/templates/shortcode-templates/#inline- codes courts).

Pour activer globalement emoji, définissez `enableEmoji` sur` true` dans la [configuration] de votre site (https://gohugo.io/getting-started/configuration/), puis vous pourrez taper des codes abrégés emoji directement dans les fichiers de contenu; par exemple.


<p> <span class = "nowrap"> <span class = "emojify"> 🙈 </span> <code>: see_no_evil: </code> </span> <span class = "nowrap"> <span class = "emojify"> 🙉 </span> <code>: hear_no_evil: </code> </span> <span class = "nowrap"> <span class = "emojify"> </span> <code>: speak_no_evil: </code> </span> </p>
<br>

Le [aide-mémoire Emoji] (http://www.emoji-cheat-sheet.com/) est une référence utile pour les codes abrégés emoji.

***

** N.B.: ** Les étapes ci-dessus permettent d'activer des caractères emoji standard Unicode dans Hugo. Toutefois, le rendu de ces glyphes dépend du navigateur et de la plate-forme. Pour dénommer les émoticônes, vous pouvez utiliser une police emoji tierce ou une pile de polices. par exemple.

{{< highlight html >}}
.emoji {
font-family: Apple Color Emoji, Interface utilisateur Segoe Emoji, NotoColorEmoji, Symbole Segoe UI, Android Emoji, EmojiSymbols;
}
{{< /highlight >}}

{{< css.inline >}}
<style>
.emojify {
font-family: Apple Color Emoji, Interface utilisateur Segoe Emoji, NotoColorEmoji, Symbole Segoe UI, Android Emoji, EmojiSymbols;
taille de la police: 2rem;
alignement vertical: milieu;
}
Écran @média et (largeur maximale: 650px) {
    .nowrap {
bloc de visualisation;
marge: 25px 0;
}
}
</ style>
{{< /css.inline >}}
