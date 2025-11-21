::rules
Le chatbot doit aider l'élève à identifier des mots-clés dans un document.
Les boutons déclenchent une navigation entre les sections définies dans ::state.
::

::bot
# Coach mots-clés – document de religion

Je suis ton coach pour t’aider à repérer les mots-clés importants du document que tu étudies.

L’objectif est de trouver 7 mots-clés en lien avec la religion et les pratiques religieuses.

Choisis ce que tu veux faire :

- [Je veux comprendre ce qu’est un mot-clé](QuEstCeQuUnMotCle)
- [Je veux des indices pour repérer les mots-clés du document](Indices)
- [Je veux directement la liste des mots-clés attendus](Correction)
- [Terminer la discussion](Fin)
::

::state

# QuEstCeQuUnMotCle
Un mot-clé est un mot important du texte :

- il résume une idée essentielle du document ;
- il pourrait servir à un titre ;
- il revient souvent ou il est significatif.

Dans ton activité, ils concernent la religion, les croyances et les lieux de culte.

- [Donne-moi des indices](Indices)
- [Terminer](Fin)

# Indices
Voici des conseils pour repérer les mots-clés :

- Repère les mots qui parlent des êtres supérieurs vénérés.
- Cherche les pratiques religieuses (gestes, cérémonies…).
- Observe les mots liés aux textes religieux.
- Regarde comment on nomme une divinité.
- Note les lieux de réunion des croyants.

- [Indices plus précis](IndicesDetail)
- [Voir la correction](Correction)
- [Terminer](Fin)

# IndicesDetail
Voici sept indices, chacun correspond à un mot-clé attendu :

1. Êtres supérieurs vénérés au pluriel.
2. Élément qui représente une idée ou une croyance.
3. Être supérieur unique (majuscule).
4. Pratiques religieuses / cérémonies.
5. Texte ou acte d’écrire, lié au religieux.
6. Appellation d’une divinité ou figure religieuse.
7. Lieux où les croyants se réunissent.

- [Je veux la correction](Correction)
- [Terminer](Fin)

# Correction
Voici les mots-clés attendus :

- dieux  
- symbole  
- Dieu  
- culte  
- écriture  
- nom  
- églises  

- [Terminer](Fin)

# Fin
Merci pour ton travail. Tu peux maintenant compléter l’activité dans l'application.
::
