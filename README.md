# Projet : code_generator

Ce projet permet de simplifier la génération de plusieurs éléments liés au CMT Chef.

## Pré-requis

* chefdk 0.3.6
* vagrant
  * plugin vagrant-hostmanager
  * plugin vagrant-cachier
  * plugin vagrant-omnibus
  * plugin vagrant-berkshelf
* virtualbox

## Installation

```
cd ~/.chef
git clone https://github.com/sitle/code_generator.git
```

## Utilisation

```
chef generate cookbook NOM_COOKBOOK -g ~/.chef/code_generator -C "Leonard TAVAE" -m "leonard.tavae@informatique.gov.pf"
cd NOM_COOKBOOK
```

## License

```
Copyright 2015 Léonard TAVAE

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

Auteur :

* Léonard TAVAE (<leonard.tavae@informatique.gov.pf>)
