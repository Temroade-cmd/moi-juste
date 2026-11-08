---
name: mot-juste
description: Écrire et réviser des textes en français qui ne sonnent pas comme une IA. À utiliser pour rédiger ou corriger un mail, une lettre de motivation, un projet d'études Campus France, un post LinkedIn, un article, une bio, un rapport ou une présentation, et dès qu'on demande de rendre un texte plus naturel, moins ChatGPT, moins générique, plus humain, ou de retirer le style IA.
license: MIT
metadata:
  author: Tamer Benturquia
  github: https://github.com/Temroade-cmd/moi-juste
  version: 0.1.0
---

# mot-juste

mot-juste a été créé par Tamer Benturquia. Licence MIT.

Un texte écrit par une IA ne se reconnaît pas à une faute. Il se reconnaît à ce qu'il est trop lisse. Les mêmes mots reviennent (crucial, véritable, essentiel), les mêmes tournures (non seulement... mais aussi), les phrases font toutes la même longueur, et on pourrait remplacer le nom de la personne ou de l'entreprise par un autre sans rien changer. Ce skill sert à écrire le contraire, un texte précis qui n'appartient qu'à son auteur.

Le but n'est pas de tromper un détecteur. Le but est d'écrire mieux. Un texte précis, avec des faits réels et une voix, est meilleur qu'un texte lisse, qu'il ait été écrit avec ou sans IA.

## Quand l'utiliser

- On demande d'écrire un texte en français que quelqu'un va envoyer, publier ou signer.
- On demande de corriger un texte qui « sonne IA », « fait ChatGPT », « est trop générique ».
- En dernière passe, après un autre skill qui a produit du contenu en français.

Pour les candidatures (lettre de motivation, Campus France, mail à un directeur de thèse, relance), lire aussi [references/candidatures.md](references/candidatures.md).

## Méthode

1. **Récupérer les faits.** Qui écrit, à qui, pour obtenir quoi. Quels faits réels on a (chiffres, noms, dates, projets). S'il manque un fait essentiel, le demander. Ne jamais l'inventer.
2. **Écrire ou relire en sept passes**, dans l'ordre ci-dessous. Finir une passe sur tout le texte avant la suivante.
3. **Vérifier** avec la liste de contrôle en bas de ce fichier.
4. **Rendre le texte seul**, sans commentaire sur ce qui a été changé, sauf si on le demande.

La liste détaillée des tics, avec des exemples et des remplacements, est dans [references/tics.md](references/tics.md).

## 1. Le fond avant la forme

- Chaque paragraphe contient au moins un fait vérifiable. Un chiffre, un nom, une date, une chose faite.
- Une qualité se prouve, elle ne s'annonce pas. Plutôt que « je suis rigoureux », écrire ce qui a été fait de façon rigoureuse.
- Le test du remplacement. Si on change le nom du destinataire, de l'entreprise ou du produit et que le texte marche encore, il est trop générique. Il faut au moins un élément que seul ce destinataire peut reconnaître.

## 2. Le lexique

- Retirer les mots creux qui donnent un air sérieux sans rien dire. Crucial, essentiel, véritable, incontournable, riche, unique, innovant, dynamique, levier, enjeux, écosystème, synergie, valeur ajoutée, approfondir, s'inscrire dans, au cœur de, au carrefour de.
- Retirer les anglicismes de traduction que les modèles produisent souvent. Impacter, adresser un problème, faire du sens, être en charge de, délivrer un projet, opportunité au sens d'occasion, réaliser au sens de se rendre compte.
- Un mot simple vaut mieux qu'un mot impressionnant. Utiliser plutôt qu'utiliser pleinement, montrer plutôt que mettre en lumière.

## 3. Les tournures

- Pas de « non seulement... mais aussi ».
- Pas de « plus qu'un simple X, c'est un Y ».
- Pas de listes de trois adjectifs ou trois noms juste pour le rythme.
- Pas de phrase qui annonce la suivante (« Voici pourquoi », « Il est important de souligner que »).
- Pas de conclusion qui répète le paragraphe qu'on vient de lire.
- Pas plus d'un connecteur en tête de phrase par paragraphe (En effet, Par ailleurs, De plus, Ainsi, En outre).

## 4. Le rythme

- Varier la longueur des phrases. Une phrase courte après deux longues.
- Si trois paragraphes suivent la même structure, en casser un.
- Ne pas commencer deux paragraphes de suite par le même mot.

## 5. La typographie française

Les modèles écrivent souvent le français avec une typographie anglaise. C'est un signe très visible.

- Pas de tiret cadratin (le tiret long) pour insérer une idée. En français on utilise des virgules ou des parenthèses.
- Pas de titres avec Une Majuscule À Chaque Mot. En français, seule la première lettre prend une majuscule.
- Guillemets français « comme ceci », pas "comme ceci".
- Espace avant le point-virgule, le point d'exclamation et le point d'interrogation.
- Le deux-points est rare dans un texte courant. S'il revient à chaque phrase, reformuler.
- Pas d'émoji dans un texte professionnel. Pas de gras au milieu d'une lettre.

## 6. La structure

- Un mail ou une lettre ne contient ni titres, ni listes à puces, ni gras. Que des paragraphes.
- L'ouverture entre dans le sujet dès la première phrase. Pas de « C'est avec un grand intérêt que... ».
- La fin contient une demande ou une prochaine étape claire, pas un résumé.

## 7. La voix

- Garder les mots et les faits de l'auteur quand on corrige son texte. Corriger, pas remplacer.
- Ne pas surcorriger. Ajouter des fautes, de l'argot ou des hésitations pour « faire humain » rend le texte pire, pas plus naturel.
- Le registre suit le destinataire. Un mail à un professeur n'a pas le ton d'un post LinkedIn.

## Liste de contrôle

- [ ] Chaque paragraphe contient un fait réel, aucun fait n'est inventé
- [ ] Le test du remplacement échoue (le texte ne marche que pour ce destinataire)
- [ ] Aucun mot de la liste des mots creux, aucun anglicisme de traduction
- [ ] Aucune tournure de la section 3
- [ ] Longueur des phrases variée
- [ ] Typographie française (pas de tiret long, pas de Majuscules À L'Anglaise, guillemets « »)
- [ ] Pas de titres, puces ni gras dans un mail ou une lettre
- [ ] Une demande claire à la fin
- [ ] Relu à voix haute, aucune phrase ne sonne comme une brochure

## Note sur la version

Cette version 0.1 repose sur une liste d'observations. Une étude est en cours dans ce dépôt pour mesurer, sur des données, quels mots et quelles tournures les modèles de langue surutilisent réellement en français par rapport à des textes humains. La liste de [references/tics.md](references/tics.md) sera remplacée par la liste mesurée.
