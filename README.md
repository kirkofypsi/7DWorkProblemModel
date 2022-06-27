# 7D Work Problem Model™

## Introduction

In the 21st century, work is still a miserable experience despite all the technological advances. Gallup reports that
only around one-fifth of today's global workforce is
engaged [[1]](https://github.com/kirkofypsi/7DWorkProblemModel/blob/main/README.md#references) and that employee
engagement has not significantly improved over the last decade. As job satisfaction strongly correlates with mental
health, dissatisfaction with work may partially explain the recent rise of psychological issues among working
adults [[2]](https://github.com/kirkofypsi/7DWorkProblemModel/blob/main/README.md#references).
__The Institute for a Better Workplace__ believes the engagement issue must be addressed as it has severe
economical and societal implications [[3]](https://github.com/kirkofypsi/7DWorkProblemModel/blob/main/README.md#references)
and such a dysfunctional work system cannot be maintained in a long term.

We believe that the decrease in work satisfaction largely stems from the fact that modern companies misdirect their efforts
by focusing on creating favorable but largely untrue images of themselves instead of addressing the actual issues. This in turn prevents the public
from realizing the weaknesses of organizations and creates the opportunity for companies to ignore bad practices
impacting their employees' well-being. Our aim is to tear down the walls erected by companies and to provide a neutral point of 
view of the work world. To lay the groundwork for that we created an exhaustive catalog of the most common work
problems. We are introducing it to objectively compare different companies' work climates and to offer
a uniform, digestible, and easy-to-understand view of what is happening
at different work places.

## Catalogue of work problems

Work-related health risks have been studied by scientists for decades. Initially, those studies were almost completely
limited to physical work hazards but in recent decades, the focus has shifted towards mental and social factors and
how they affect workers' well-being. In scientific literature, they are usually referred to as *psychosocial stressors* or
*hazards*. We decided to use a simpler term – __work problem__ as we want to also shed light on organizational characteristics
that prevent employees from achieving self-actualization and satisfaction from work, even if they are not
negatively affecting employees' mental health. Therefore, for us, the term __work problem__ represents any source of employees'
frustration, stress, or dissatisfaction in the workplace.

Unfortunately, there is an absence in the scientific literature of a reference taxonomy cataloging all factors leading
to dissatisfaction in the workplace, even if we limit ourselves only to psychosocial stressors and physical hazards.
Numerous attempts were made, most notably the ones described
in [[4],[5]](https://github.com/kirkofypsi/7DWorkProblemModel/blob/main/README.md#references) comprising 53 and 44
categories, respectively. Notwithstanding, in our opinion, they fail to cover all relevant dissatisfaction factors and were not
derived from analysis of really large datasets of employees opinions.

Given that absence, the __Institute for a Better Workplace__ decided to create its own taxonomy, which we believe to be the
most exhaustive one (currently comprising 130 categories) and the only one that has been tested on a large dataset of
employees' opinions. The taxonomy was derived from __millions of opinions__ about workplace experiences
reported by the employees of __hundreds of global organizations__ and its creation was possible thanks to the support of machine
learning and NLP techniques that allowed us to discover hidden relationships between the contents of employees' reports.
One million opinions is the equivalent of 200 average-sized books, so it is not surprising that traditional, manual
approaches to building taxonomies could not be applied in this case.

## 7D Work Problem Model™

The resulting taxonomy, called the __7D Work Problem Model™__, recognizes at the most granular level 130 different work
problems which suffice to classify more than 88% of our dataset of employees' opinions. One option that we rejected
was to build a taxonomy by grouping work problems into categories representing super-problems. We decided instead to
cluster work problems around __work satisfaction factors__ that are most negatively affected by them. For example, an
occurrence of a work problem "No freedom to speak one's mind" negatively impacts the aspect of
working at a company that supports the open-minded exchange of ideas. We call this satisfaction factor "Openness" and thus
the aforementioned problem is assigned to it along with the two other problems "Lack of transparency" and "Aversion
to risk or changes". Finally, work satisfaction factors were subsequently grouped into __work satisfaction dimensions__
representing crucial concepts from the areas of management and systems organization.

*Summary of 7D Work Problem Model™ taxonomy levels*

| Level (from the top)  |      Level name      |  Description  | Size |
|-----------------------|---------------------:|--------------:|-----:| 
|  1|  __Work satisfaction dimension__ |  high-level components of work satisfaction in the organization representing crucial concepts from the areas of management and systems organization | 7 |
|  2|  __Work satisfaction factor__   | low-level components of work satisfaction in the organization; work problems negatively affect work satisfaction factors | 39 |
|  3| __Work problem__ | any source of frustration, stress, or dissatisfaction for the employees in their workplace | 130 |

*An exempt from the 7D Work Problem Model™ structure:*

* __Opportunities__  &nbsp; &nbsp; &nbsp;  <-- *Work satisfaction dimension*
    * __Career growth__  &nbsp; &nbsp; &nbsp; <-- *Work satisfaction factor*
        * Poor career growth &nbsp; &nbsp; &nbsp; <-- *Work problem*
        * Difficulties in internal transfers &nbsp; &nbsp; &nbsp; <-- *Work problem*
        * Undefined career paths &nbsp; &nbsp; &nbsp; <-- *Work problem*
        * Outsiders favored over insiders &nbsp; &nbsp; &nbsp; <-- *Work problem*

The __7D Work Problem Model™__ does not represent a static taxonomy. It will be thoroughly reviewed every few  months and 
possibly modified to reflect new developments in research or changes in the world of work.

__The Institute for a Better Workplace__ decided to open-source work problem taxonomy in order to make it available to
researchers and companies interested in the topic. We hope that this taxonomy will be used to improve work
environments and the well-being of employees around the world.

## How can the 7D Work Problem Model™ be used?

The 7D Work Problem Model™ is a tool for conducting research in the field of work satisfaction as it comes with an
automated classifier that can be used to quickly and unbiasedly identify relevant work problems without the need for
expert review or manual tagging. Therefore, given a large enough dataset of employees' opinions
we can use it to:

* analyze work problems' distribution across different functions/locations/departments
* track how the number of work problems changes over time in a specific organization
* measure how satisfied employees from a given organization are comparing to the average for that industry
* compare the satisfaction of employees between different organizations.

Moreover, the analysis of new opinions is done in a matter of minutes and in a way that guarantees to all respondents
both a lack of bias and full anonymity which constitutes a significant improvement over traditional, manual solutions.

## Our reports

In the coming months, the __Institute for a Better Workplace__ will publish numerous reports on work problems in
different organizations. Our findings are based on the analysis of millions of employee opinions from
hundreds of global organizations across various industries.

Here is list of reports that have been published thus far:
* [The most characteristic work problems per industry](reports/industry_report_22_09_21.md) - __September 2021__
* [The most characteristic work problems per industry](reports/industry_report_22_12_21.md) - __December 2021__
* [The most characteristic work problems per industry](reports/industry_report_26_01_22.md) - __January 2022__
* [The most characteristic work problems per industry](reports/industry_report_28_06_22.md) - __June 2022__

<br/>
<br/>

## Explore [ 7D Work Problem Model™](taxonomy.md)

<br/>

## References

[1] Jim Harter, [U.S. Employee Engagement Holds Steady in First Half of 2021](https://www.gallup.com/workplace/352949/employee-engagement-holds-steady-first-half-2021.aspx),
Gallup, July 2021

[2] [2021 State of Mental Health in America Report](https://mhanational.org/issues/state-mental-health-america),
Mental Health America, September 2020

[3] Allan Schweyer, [The Economics of Engagement](https://www.enterpriseengagement.org/articles/content/8288917/the-economics-of-engagement/),
Human Capital Institute, June 2009

[4] Jean-Luc Kop, Virginie Althaus, Nadja Formet, Vincent Grosjean, [Systematic comparative content analysis of 17
psychosocial work environment questionnaires using a new taxonomy](https://www.researchgate.net/publication/304707060_Systematic_comparative_content_analysis_of_17_psychosocial_work_environment_questionnaires_using_a_new_taxonomy),
International Journal of Occupational and Environmental Health, April 2016

[5]  Hamidrezaa Mokarami, Stefano Toderi, [Reclassification of the work-related stress questionnaires scales based on the
work system model: A scoping review and qualitative study](https://www.researchgate.net/publication/337758774_Work_xx_20xx_x-xx_Reclassification_of_the_work-related_stress_questionnaires_scales_based_on_the_work_system_model_A_scoping_review_and_qualitative_study),
Work, April 2019

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-YVBM7MM6EQ"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-YVBM7MM6EQ');
</script>
