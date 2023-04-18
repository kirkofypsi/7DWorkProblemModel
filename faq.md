# Frequently asked questions

- [What is Culturama?](#what-is-culturama)
- [How can Culturama improve work cultures?](#how-can-culturama-improve-work-cultures)
- [Where does Culturama data come from?](#where-does-culturama-data-come-from)
- [Is the Culturama employee opinion dataset static?](#is-the-culturama-employee-opinion-dataset-static)
- [Will the Culturama employee opinion dataset be public?](#will-the-culturama-employee-opinion-dataset-be-public)
- [Do you gather any additional information on the authors of opinions?](#do-you-gather-any-additional-information-on-the-authors-of-opinions)
- [What does the intensity of a workplace problem mean?](#what-does-the-intensity-of-a-workplace-problem-mean)
- [How is the intensity of a workplace problem calculated?](#how-is-the-intensity-of-a-workplace-problem-calculated)
- [Why focus on workplace issues and ignore the positive?](#why-focus-on-workplace-issues-and-ignore-the-positive)
- [Why are fake positive reviews a problem, while fake negative reviews are not?](#why-are-fake-positive-reviews-a-problem-while-fake-negative-reviews-are-not)
- [Why are only large companies included in Culturama?](#why-are-only-large-companies-included-in-culturama)
- [How can Culturama identify 130 distinct types of workplace issues?](#how-can-culturama-identify-130-distinct-types-of-workplace-issues)

## What is Culturama?

Culturama is **a first-of-its-kind, free-to-use work culture analytics**, covering 1,500 major companies and drawing insights from 5 million employee opinions. It utilizes GPT technology, popularized by ChatGPT, to analyze public employee comments about companies.

## What makes Culturama unique?

Culturama differentiates itself from other work culture analytics services in several key ways:

 - **Scope of analysis**: Culturama covers a wide range of 1,500 major companies and gathers insights from 5 million employee opinions, providing a comprehensive view of work culture across various industries.
 - **Exclusion of fake positive reviews**: To maintain the reliability of the analysis, Culturama excludes positive employee feedback due to the difficulty in verifying its authenticity. This approach helps to focus on the absence of workplace problems as a measure of work culture quality rather than the presence of praise.
- **Focus on tangible workplace problems**: Unlike other services that use abstract concepts to describe work environments like ***Agility***, ***Performance***, or ***Execution***, Culturama identifies 130 common, practical workplace issues like ***Blame game***, ***Tight deadlines***, ***Late or incorrect pay***, and ***Uncaring managers*** that employees and employers can easily understand and address.
 - **Continuous study with quarterly updates**: Culturama is not a one-time report but a continuous study that provides updated information every quarter, ensuring that the insights remain relevant and accurate.
 - **Publicly available and free**: Culturama is a free-to-use platform, making work culture analytics accessible to a broader audience, including employees, employers, and researchers.

## How can Culturama improve work cultures?

Enhancing workplace cultures depends on one critical condition - companies must genuinely prioritize improvement rather than merely paying lip service. To accomplish this, we need to encourage competition between companies based on the quality of their workplace cultures. This, in turn, necessitates objective, quantitative measures of work cultures that are both reliable and publicly accessible. Culturama aims to address this current lack of publicly available cultural indicators.

## Where does Culturama data come from?

First, it's essential to clarify what Culturama is not. Culturama is not a panel research study, meaning we haven't recruited a panel of respondents representative of the target population and collected data on workplace issues through questionnaires or interviews.

Culturama data is sourced from internet monitoring, an approach that has significantly grown in popularity in recent years due to advances in data processing capabilities and analysis quality. For instance, massive internet scans have resulted in extensive datasets used to train AI models like OpenAI's ChatGPT and Stability AI's Stable Diffusion. One major advantage of internet monitoring over panel research is the sheer volume of data available, often several orders of magnitude larger. In the case of Culturama, data is gathered from all publicly available online sources, such as social media platforms, blogs, forums, and review websites. 

Culturama's focus is not on general opinions about companies but specifically on employee accounts of workplace cultures. Furthermore, for the reasons explained below, we aimed to limit our scope to opinions that are not entirely positive and include at least one drawback of a given culture. To filter the relevant content, we developed a highly accurate GPT-based classifier capable of detecting opinions meeting these criteria.

Since we don't want to publish outdated data on work cultures, we exclude opinions that were published more than 4 years ago. Naturally, we also need to be able to identify the specific company each opinion refers to.

In summary, Culturama data consists of opinions that:

 - represent employee perspectives on workplace cultures,
 - mention **at least one issue of a work culture**, i.e., are not 100% positive,
 - relate to the workplace cultures of the selected 1500 global organizations,
 - were published **no earlier than 4 years ago**.

## Is the Culturama employee opinion dataset static?

No, Culturama constantly scans the internet for employee opinions on companies. Data updates occur at least once per quarter, ensuring the information presented remains up-to-date and relevant. It's important to note that Culturama utilizes a 4-year moving window, so as updates occur, older opinions that may no longer be relevant are removed from the dataset.

## Will the Culturama employee opinion dataset be public?

We do not have plans to publish our dataset. Our primary goal is to offer an aggregated overview of workplace cultures that can assist organizations in identifying areas for improvement and enable job seekers to make data-driven decisions. By releasing our dataset, we would inadvertently draw attention to individual opinions, which is not our intention. Although all opinions collected by us are publicly accessible, compiling them in one place and making them searchable could potentially cause issues for those who expressed them.

## Do you gather any additional information on the authors of opinions?

We only store the content of the opinion and the date it was created. We do not retain any personal information such as names or addresses. Additionally, we do not gather any demographic data such as age, gender, employment location, or income level.

## What does the intensity of a workplace problem mean?

Intensity indicates how frequently employees report a particular workplace problem. The higher the intensity of a problem, the more prevalent it is within an organization. Problem intensity is derived from problem frequency and is **measured on a scale from 0 to 100**.

It is essential to emphasize that, contrary to the natural interpretation where higher values are perceived as better, problem intensity works the other way around. **An intensity of 0** is an excellent score, signifying a complete absence of evidence that a problem exists in a company. Conversely, **an intensity of 100** indicates that the problem is very commonly mentioned by employees.

## How is the intensity of a workplace problem calculated?

Culturama identifies 130 distinct types of workplace problems. In a single opinion, an employee may raise multiple workplace concerns, potentially even listing several dozen of them. However, in practice, it is most common for an individual opinion to mention 1-3 problems. Please note that, due to the constraints we placed on our dataset, an opinion must contain at least one mention of a workplace issue.

**The frequency of a workplace issue refers to the percentage of opinions that include this specific problem out of all opinions**. In 99% of cases, the frequency is less than **15%**. This is not surprising, as it would be unusual for a single issue to appear in a significant portion of a large number of unprompted, independent opinions. Therefore, to make our data more interpretable, we remove outliers by capping all frequencies above 15% at 15%.

**Intensity measure comes from linearly rescaling the range from [0%, 15%] to [0, 100]**.

In summary:

 - **An intensity of 100** indicates that the workplace issue was mentioned in **15% or more of the opinions**.
 - **An intensity of 0** signifies that **no opinions mentioned the specific workplace issue**.

## Why focus on workplace issues and ignore the positive?

It's no secret that companies often try to enhance their reputation as employers by posting fake positive reviews online. This practice has been widely reported by reputable media outlets such as [The Wall Street Journal](https://www.wsj.com/articles/companies-manipulate-glassdoor-by-inflating-rankings-and-pressuring-employees-11548171977) and can be easily identified through statistical analysis. One common indicator of manipulation is when a negative review is always followed by a series of excessively positive reviews, seemingly intended to offset the negative impact.

It's important to acknowledge that companies typically do not hire external PR agencies to create false positive reviews. Instead, they employ more subtle tactics, which can be perceived as legitimate by the individuals involved. One such approach is when a manager sends an email to a group of employees, requesting them to post a positive review, with a message along the lines of, "After all, we're not as bad as they say we are online." Often, the recipients of these requests are members of the recruitment department, who have a vested interest in posting fabricated reviews, as it increases their chances of attracting potential candidates.

In summary, Culturama excludes positive employee feedback due to the difficulty in verifying its authenticity. Although many positive comments are genuine, a significant number are either influenced by employers or entirely fabricated. In our opinion, **the only reliable measure of work culture quality is the absence of workplace problem reports, rather than the presence of praise**.

## Why are fake positive reviews a problem, while fake negative reviews are not?

While it's possible for a company to post fake negative reviews in order to harm a competitor's reputation, it's important to understand that engaging in such behavior can result in serious legal consequences. Spreading false information with the intention of damaging another business can provide grounds for a defamation lawsuit.

Because of this, it's unlikely that falsifying negative reviews would happen as frequently as falsifying positive ones. Encouraging an employee to write an excessively positive review of their own company simply involves setting aside personal opinions temporarily, whereas fabricating negative statements about a company they have no affiliation with is a completely different matter.

Additionally, every company has dozens, if not hundreds, of competitors in the job market. To improve their own standing, a company would have to produce fake negative reviews for all of their competitors, which would be a monumental task.

Therefore, it's clear that the unethical method of choice for enhancing one's reputation is by posting fake positive reviews rather than publishing fake negative reviews about competitors.

## Why are only large companies included in Culturama?

Regrettably, for small and some medium-sized companies, particularly those with 500 employees or fewer, there is usually insufficient publicly available information to make statistically significant conclusions about their work culture.

Nonetheless, this does not imply that we cannot expand the current selection of 1500 companies in Culturama. There are undoubtedly numerous large companies not yet featured in Culturama that have ample public information on their work cultures. Our goal is to continue broadening the range of analyzed companies in the near future.

## How can Culturama identify 130 distinct types of workplace issues?

Culturama employs a custom fine-tuned model based on the state of art LLM ([large language model](https://en.wikipedia.org/wiki/Large_language_model)). [Fine-tuning](https://en.wikipedia.org/wiki/Fine-tuning_(machine_learning)) involves further training of a pre-trained model on new data to enhance its performance for a particular task. In our scenario, the task is detecting workplace issues from our taxonomy within employee feedback, and the new data consists of a substantial collection of manually annotated employee opinions.

To test the prediction quality, we used [k-fold cross-validation](https://en.wikipedia.org/wiki/Cross-validation_(statistics)#k-fold_cross-validation), a widely recognized evaluation method that ensures robustness and accuracy. By doing so, we achieved an impressive [F1-score](https://en.wikipedia.org/wiki/F-score) of **0.93**, demonstrating the model's effectiveness in identifying various workplace problems.


