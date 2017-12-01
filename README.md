# Piwam

[![Codeship Status for piwam/piwam](https://app.codeship.com/projects/f5efc150-b8bf-0135-344c-064e0f24fac0/status?branch=master)](https://app.codeship.com/projects/259073)
[![Maintainability](https://api.codeclimate.com/v1/badges/158bcda181e7748a5657/maintainability)](https://codeclimate.com/github/piwam/piwam/maintainability)
[![Coveralls](https://img.shields.io/coveralls/piwam/piwam/master.svg)](https://coveralls.io/r/piwam/piwam)

**P**iwam **I**s a **W**onderful **A**ssociation **M**anager.


### Qu'est-ce que c'est ?

Cette application est un portage du projet [Piwam](https://code.google.com/p/piwam), qui est un
excellent gestionnaire d'association dont le développement a malheureusement été abandonné par
son créateur. L'application a donc été entièrement ré-écrite en [Ruby on Rails](http://rubyonrails.org).

![Screenshot de l'application](http://piwam.org/images/screenshot.png)

### Que puis-je gérer avec Piwam ?

Piwam vous permet de gérer les activités d'une association ainsi que d'éditer divers rapports comptables :

- membres
- cotisations
- recettes / dépenses
- activités


### Installation

```
bundle install
rake db:setup
rails s
```

Requiert Ruby 2.4 ou supérieur et MySQL.
