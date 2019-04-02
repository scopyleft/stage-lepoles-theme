# Maquillage

Un thème Jekyll pour publier des contributions issues de l'éco-système [Daktary](http://daktary.com).

## Utiliser le thème

### Contexte

J'ai des ressources *markdown* hébergées dans un *dépôt Github* et je souhaite les présenter au reste du monde en réduisant le bruit visuel.

Par exemple, je pourrais avoir un compte *github* : **mezig**  
Et un dépôt : **crenshaw** qui contiendrait plein de fiches très inspirantes sur [l'intersectionnalité](https://fr.wikipedia.org/wiki/Intersectionnalit%C3%A9).     

### Construire rapidement un site avec le thème maquillage

Créer un fichier *_config.yml* en insérant la ligne : 
```yaml
remote_theme: daktary-team/maquillage
```

Pour que mon site soit accessible en ligne, je dois activer *github-pages*.

Dans settings :

![](https://guides.github.com/features/pages/repo-settings.png)

Je sélectionne la branche *master* et je clique sur *save*

![](https://guides.github.com/features/pages/launch-theme-chooser.png)

En reprennant l'exemple proposé, après quelques secondes, mes contributions deviennent consultables à l'adresse : [mezig.github.io/crenshaw]()

### Pour fignoler un peu

Je peux rajouter la personalisation des *erreurs 404* en ajoutant un fichier *404.html* avec à l'intérieur :

```markdown
---
permalink: /404.html
layout: 404
---
```

## FAQ

**Pourquoi c'est sur Github et pas sur une plateforme libre ?**

On a commencé là en se disant que ce serait facile à migrer. Bientôt on passera sur gitlab.com.

**Pourquoi je dois faire des trucs techniques comme créer des fichiers *yaml* ?**

Avec [coup de pinceau](https://github.com/daktary-team/coup-de-pinceau) ça se passera en un clic. On y travaille tranquillement.

**Et si je galère, je fais comment ?**

Plein de solutions s'offrent à toi, parmi lesquelles :
- on pourrait organiser un walkingdev.com
- tu peux contacter [Stéphane](mailto:stephane.langlois@scopyleft.fr)
- on pourrait programmer une exploration collective un peu comme un devopensud.fr

**Et la suite, c'est quoi ?

on utilise la [grainerie](https://github.com/daktary-team/maquillage/projects/1) pour prioriser nos idées.

## Quelques explications sur le "projet"

### À quoi on aspire ?

Présenter convenablement des ressources *markdown* en renseignant un fichier de configuration minimaliste.

### Qui seraient intéressé·e·s ?
- Pour les utilisat·eur·rice·s de multibao.
- Pour les petit·e·s blogueu·r·se·s.
- Pour les collectifs sensibles aux pratiques collaboratives.

### Pour quoi faire ?
- Pour associer mes contributions à ma personne ou à mon collectif.
- Pour montrer à mes proches la facilité de mise en œuvre d'une gestion de documentation collaborative.
- Pour me débarrasser de mon ancien outil sans trop sacrifier la présentation.

### Ce serait une expérience réussie, si...
- Si après avoir installé le produit, Bénédicte décide de remplir les métas de 50% de [ses fiches](https://github.com/bndct-lmbrt/mes-recettes/tree/master/recettes) 
- Si cinq contribut·eur·rice·s décident d'accepter des [PR](https://github.com/bndct-lmbrt/mes-recettes/pull/3) pour installer la solution.
- Si on utilise ce thème pour [coup-de-pinceau](https://github.com/daktary-team/coup-de-pinceau)

## Pour aller plus loin techniquement

Pour tester ce thème en local, lancer `bundle exec jekyll serve` dans un terminal.

### Installation dans un site Jekyll

Pour utiliser ce thème dans un site utilisant *Jekyll*, vous pouvez ajouter cette ligne dans votre fichier `Gemfile`:

```ruby
gem "maquillage"
```

Et ajouter la ligne suivante `_config.yml`:

```yaml
theme: maquillage
```

Puis exécuter :

```bash
bundle
```

Ou bien, installer par vous même :

```bash
gem install maquillage
```

### License

[CC0-1.0](./LICENCE)
