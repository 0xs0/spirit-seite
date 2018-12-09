---
layout: page
current: Forschungsgruppe
title: Forschungsgruppe
navigation: true
cover: 'assets/images/Forschungsgruppe/10_groß.jpg'
class: page-template
subclass: 'post page'
navigation_weight: 1
---

Die Forschungsgruppe SPiRIT – Sciene Projects in Radio and Information Technology ist eine interdisziplinäre Einrichtung des Instituts für Management und des Instituts für Elektrotechnik der Hochschule Magdeburg-Stendal. Sie wurde im Sommer 2012 von Michael Herzog und Olaf Friedewald als ThinkTank und Projektschmiede gegründet.

Im Mittelpunkt stehen derzeit innovative Lösungen im Bereich von Radio Frequency Identification (RFID), SocialMedia und Webtechnologien, sowie Prozess- und Content Engineering. Außerdem werden Forschungsvorhaben zum Lehren und Lernen mit Digitalen Medien umgesetzt.

Die Arbeit der Forschungsgruppe SPiRIT stützt sich hauptsächlich auf drittmittelgeförderte Projekte in Zusammenarbeit mit Unternehmen und anderen Forschungseinrichtungen. Sie fördert die interdisziplinäre Arbeit junger WissenschaftlerInnen und motivierter Studierender, etwa mit der exzellenten Betreuung von Forschungs- und Entwicklungsprojekten.

Die erfahrenen Teammitglieder engagieren sich besonders in der projektorientierten Lehre. Sie vermitteln auch die Grundlagen ihrer jeweiligen Arbeitsgebiete, häufig auch in anderen Fachdiziplinen.

Das Team lädt regelmäßig zu Kolloquien und anderen Veranstaltungen ein, zu der interessierte Studierende, Wissenschaftler und Unternehmer herzlich eingeladen sind!

{% for author in site.data.authors %}
 {% if author[1].title %}
  {{ author[1].title }}
 {% endif %}
  
 {% if author[1].name %}
  {{ author[1].name }}
 {% endif %}
  
 {% if author[1].projekt %}
  {{ author[1].projekt }}
 {% endif %}

 {% if author[1].url_full %}
  {{ author[1].url_full }}
 {% endif %}

 {% if author[1].email %}
  {{ author[1].email }}
 {% endif %}

 {% if author[1].picture %}
  <img src="/{{ author[1].picture }}">
 {% endif %}
{% endfor %}
