# Introduction

In the 21st century, work is still a miserable experience despite all the technological advances. Gallup reports show that only around one fifth of today's global workforce is actively engaged [[1]](https://github.com/kirkofypsi/7DWorkProblemModel/blob/main/README.md#references) and that employee engagement has not significantly improved over the last decade. As job satisfaction is strongly correlated with mental health, dissatisfaction with work may partially explain the recent raise of psychological issues among working adults. __The Institute for a Better Workplace__ believes this issue must be taken seriously because it has severe implications for the economy and society and such a dysfunctional work system cannot be maintained in a long term.

We believe that lowered work satisfaction largely stems from the fact that modern companies are able to successfully employ marketing to create a favorable but largely untrue image of themselves. This in turn prevents the general public from realizing weaknesses of organizations and creates an opportunity for companies to ignore bad practices negatively impacting their employees well-being. Our aim is to open the black box of companies and to provide a neutral point of view on the working world. In order to do that, however, we had to first create an exhaustive catalogue of the most common work problems. Without it, it would be extremely difficult to objectively compare different companies by their work climate and to offer to the general public a uniform, digestible, and easy-to-understand view of what is happening at different work places. 

# Catalogue of work problems

Work-related health risks have been since long studied by the science.  Initially, those studies were almost completely limited to physical work hazards but in the recent decades, the focus has shifted towards mental and social factors and how they affect workers' well-being.  In scientific literature, they are usually referred to as psychosocial stressors or hazards. We decided instead to use a simpler term - __work problem__ as we want to also cover those work characteristics that prevents employees from achieving self actualization and full satisfaction from work, even if they are not negatively affecting employees' mental health. Therefore for us the term __work problem__ means any source of employees' frustration, stress, or dissatisfaction in the workplace.

Unfortunately, there is an absence in the scientific literature of a reference taxonomy cataloguing all factors leading to dissatisfaction in the workplace, even if we limit ourselves only to psychosocial stressors and physical hazards. Numerous attempts were made, most notably the ones described in [[2],[3]](https://github.com/kirkofypsi/7DWorkProblemModel/blob/main/README.md#references) comprising of 53 and 44 categories respectively, however, in our opinion they are not covering all relevant dissatisfaction factors and were not derived from analysis of really large datasets of employees opinions (1M+).

Given that absence,  the __Institute for a Better Workplace__ decided to create own taxonomy, which we believe to be the most exhaustive one (currently comprising of 130 categories) and the only one tested on large enough dataset of employees opinions. The taxonomy was derived from more than two million opinions about workplace experiences reported by the employees of over 300 global organizations and its creation was possible thanks to the support of machine learning and NLP techniques that allowed us to discover hidden relationships between the contents of millions of employees reports. Two million opinions is an equivalent of 250 average-sized books so it is not surprising that traditional, manual approaches to building taxonomies were not applicable in this case.

# 7D Work Problem Model™

The resulting taxonomy called the __7D Work Problem Model™__ recognizes at the most granular level 130 different work problems which is enough to classify more than 75% of our dataset of employees' opinions. One option that we rejected was to build a taxonomy by grouping work problems into categories representing super-problems. We decided instead to cluster work problems around __work satisfaction factors__ that are most negatively affected by them. For example, the occurrence of a work problem "No freedom to speak one's mind"  negatively impacts employees satisfaction of being able to work for a company that supports open-minded exchange of ideas. We call this satisfaction factor "Openness" and thus the aforementioned problem was assigned to it along with the two other problems "Lack of transparency" and "Aversion to risk or changes". Finally, work satisfaction factors were subsequently grouped into __work satisfaction dimensions__ representing crucial concepts from the areas of management and systems organization.

<br/>

*Summary of 7D Work Problem Model™ taxonomy levels*

| Level (from the top)  |      Level name      |  Description  | Cardinality |
|-----------------------|---------------------:|--------------:|------------:| 
|  1|  __Work satisfaction dimension__ |  high-level components of work satisfaction in the organization representing crucial concepts from the areas of management and systems organization | 7 |
|  2|  __Work satisfaction factor__   | low-level components of work satisfaction in the organization; work problems negatively affect work satisfaction factors | 39  |
|  3| __Work problem__ | any source of frustration, stress, or dissatisfaction for the employees in their workplace | 130 |

*Exemplary fragment of 7D Work Problem Model™ structure*

* __Opportunities__  &nbsp;  &nbsp;  &nbsp;  <-- *Work satisfaction dimension*
    * __Career growth__  &nbsp;  &nbsp;  &nbsp; <-- *Work satisfaction factor*
       * Poor career growth  &nbsp;  &nbsp;  &nbsp; <-- *Work problem*
       * Difficulties in internal transfers  &nbsp;  &nbsp;  &nbsp; <-- *Work problem*
       * Undefined career paths  &nbsp;  &nbsp;  &nbsp; <-- *Work problem*
       * Outsiders favored over insiders  &nbsp;  &nbsp;  &nbsp; <-- *Work problem*

<br/>

The __7D Work Problem Model™__ does not represent a static taxonomy. It will be thoroughly reviewed every few months and possibly modified to reflect new developments in research or changes in the world of work.

__The Institute for a Better Workplace__ decided to open-source work problem taxonomy in order to make it available to researchers and companies interested in the topic. It is our hope that this taxonomy will be used to improve work environments and the well-being of employees around the world.
<br/>
<br/>
# Explore [ 7D Work Problem Model™](taxonomy.md)
<br/>
<br/>

### References

[1] https://www.gallup.com/workplace/352949/employee-engagement-holds-steady-first-half-2021.aspx

[2] Jean-Luc Kop, Virginie Althaus, Nadja Formet, Vincent Grosjean, Systematic comparative content analysis of 17 psychosocial work environment questionnaires using a new taxonomy, International Journal of Occupational and Environmental Health, April 2016

[3]  Hamidrezaa Mokarami, Stefano Toderi, Reclassification of the work-related stress questionnaires scales based on the work system model: A scoping review and qualitative study, Work, April 2019
