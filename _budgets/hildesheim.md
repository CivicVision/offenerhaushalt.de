---
title: Stadt Hildesheim
slug: hildesheim
tagline: "Ergebnishaushalt 2015."
source:  Stadt Hildesheim
data_url: http://db.offenerhaushalt.de/api/3/datasets/hildesheim_eh_2015n/serve/2015-ergebnishaushalt-nachtrag.txt
state: NI
level: kommune
dataset: hildesheim_eh_2015n
default: produkte

filters:
  # - field: 'jahr'
  #   name: 'Jahr'
  #   default: '2015'
  - field: 'ea'
    name: 'Ertrag/Aufwand'
    default: 'Aufwand'

hierarchies:
    produkte:
        name: Produkte
        drilldowns:
            - produktebene
            - produktbereich
            - produktgruppe
            - produkt
---