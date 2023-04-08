# Frequently asked questions

- [What is Culturama?](#what-is-culturama)
- [How can Culturama improve work cultures?](#how-can-culturama-improve-work-cultures)
- [Where does Culturama data come from?](#where-does-culturama-data-come-from)
- [Is the Culturama employee opinion dataset static?](#is-the-culturama-employee-opinion-dataset-static)
- [Will the Culturama employee opinion dataset be public?](#will-the-culturama-employee-opinion-dataset-be-public)

## What is Culturama?

Culturama is **a first-of-its-kind work culture analytics**, covering 1,500 major companies and drawing insights from 5 million employee opinions. It utilizes GPT technology, popularized by ChatGPT, to analyze public employee comments about companies.

Unlike one-time paper studies, Culturama is a continuous study with quarterly updates, ensuring the information always stays relevant.

What truly sets Culturama apart from traditional studies is its approach to discussing work cultures. While many rely on abstract concepts like ***Agility***, ***Performance***, or ***Execution*** to describe work environments, Culturama focuses on 130 common workplace problems that employees and employers can easily understand. These issues include the ***Blame game***, ***Tight deadlines***, ***Late or incorrect pay***, and ***Uncaring managers***. This practical approach enables users to draw meaningful conclusions and take action to address these challenges in the workplace.

## How can Culturama improve work cultures?

Enhancing workplace cultures depends on one critical condition - companies must genuinely prioritize improvement rather than merely paying lip service. To accomplish this, we need to encourage competition between companies based on the quality of their workplace cultures. This, in turn, necessitates objective, quantitative measures of work cultures that are both reliable and publicly accessible. Culturama aims to address this current lack of publicly available cultural indicators.

## Where does Culturama data come from?

First, it's essential to clarify what Culturama is not. Culturama is not a panel research study, meaning we haven't recruited a panel of respondents representative of the target population and collected data on workplace issues through questionnaires or interviews.

Culturama data is sourced from internet monitoring, an approach that has significantly grown in popularity in recent years due to advances in data processing capabilities and analysis quality. For instance, massive internet scans have resulted in extensive datasets used to train AI models like OpenAI's ChatGPT and Stability AI's Stable Diffusion. One major advantage of internet monitoring over panel research is the sheer volume of data available, often several orders of magnitude larger. In the case of Culturama, data is gathered from all publicly available online sources, such as social media platforms, blogs, forums, and review websites. 

Culturama's focus is not on general opinions about companies but specifically on employee accounts of workplace cultures. Furthermore, for the reasons explained below, we aimed to limit our scope to opinions that are not entirely positive and include at least one drawback of a given culture. To filter the relevant content, we developed a highly accurate GPT-based classifier capable of detecting opinions meeting these criteria.

Since we don't want to publish outdated data on work cultures, we exclude opinions that were published more than 4 years ago. Naturally, we also need to be able to identify the specific company each opinion refers to.

In summary, Culturama data consists of opinions that:

 - represent employee perspectives on workplace cultures,
 - mention at least one drawback of a work culture, i.e., are not 100% positive,
 - relate to the workplace cultures of the selected 1500 global organizations,
 - were published no earlier than 4 years ago.

## Is the Culturama employee opinion dataset static?

No, Culturama constantly scans the internet for employee opinions on companies. Data updates occur at least once per quarter, ensuring the information presented remains up-to-date and relevant. It's important to note that Culturama utilizes a 4-year moving window, so as updates occur, older opinions that may no longer be relevant are removed from the dataset.

## Will the Culturama employee opinion dataset be public?

We do not have plans to publish our dataset. Our primary goal is to offer an aggregated overview of workplace cultures that can assist organizations in identifying areas for improvement and enable job seekers to make data-driven decisions. By releasing our dataset, we would inadvertently draw attention to individual opinions, which is not our intention. Although all opinions collected by us are publicly accessible, compiling them in one place and making them searchable could potentially cause issues for those who expressed them.

## Do you gather any additional information on the authors of opinions?

We only store the content of the opinion and the date it was created. We do not retain any personal information such as names or addresses. Additionally, we do not gather any demographic data such as age, gender, employment location, or income level.
