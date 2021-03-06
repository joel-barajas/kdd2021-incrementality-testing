# Online Advertising Incrementality Testing And Experimentation: Industry Practical Lessons

Presented at the [KDD 2021](https://www.kdd.org/kdd2021/)

## Authors
  - [Joel Barajas](http://www.linkedin.com/pub/joel-barajas/8/6b7/bb0), [Yahoo Research](https://research.yahoo.com/researchers/jbarajas?fr=crmas), Verizon Media
  - [Narayan Bhamidipati](https://www.linkedin.com/in/narayanb), [Yahoo Research](https://research.yahoo.com/researchers/narayanb?fr=crmas), Verizon Media
  - [James G. Shanahan](https://www.linkedin.com/in/jimis/), Church and Duncan Group Inc., UC Berkeley

## Abstract

Online advertising has historically been approached as user targeting and ad-to-user matching problems within sophisticated optimization algorithms. As the research area and ad tech industry have progressed over the last couple of decades, advertisers have increasingly emphasized the causal effect estimation of their ads (aka incrementality) using controlled experiments (or A/B testing). Even though observational approaches have been derived in marketing science since the 80s including media mix models, the availability of online advertising personalization has enabled the deployment of more rigorous randomized controlled experiments with millions of individuals.

These evolutions in marketing science, online advertising, and the ad tech industry have posed incredible challenges for engineers, data scientists, and marketers alike. With low effect percentage differences (or lift) and often sparse conversion rates, the development of incrementality testing platforms at scale suggests tremendous engineering challenges in the measurement precision and detailed implementation. Similarly, the correct interpretation of results addressing a business goal within the marketing science domain requires significant data science and experimentation research expertise. All these challenges on the ongoing evolution of the online advertising industry and the heterogeneity of its sources (social, paid search, native, programmatic, etc).

In the current tutorial, we propose a practical, grounded view in the incrementality testing landscape, including:
- The business need
- Solutions in the literature
- Design and choices in the development of incrementality testing platform
- The testing cycle, case studies, and recommendations to effective results delivery
- Incrementality testing evolution in the industry

We will provide first-hand lessons on developing and operationalizing such a platform in a major combined DSP and ad network; these are based on running tens of experiments for up to two months each over the last couple of years. 

## Outline and Presentations

1. [slides](presentations/inc_testing_part_1.pdf) The basics: context and challenges
2. [slides](presentations/inc_testing_part_2.pdf) Incrementality Testing: concepts, solutions and literature
3. [slides](presentations/inc_testing_part_3.pdf) From concept to production: platform building, challenges, case studies
4. [slides](presentations/inc_testing_part_4.pdf) Deployment at Scale: test cycle and case studies
5. [slides](presentations/inc_testing_part_5.pdf) Emerging trends: identity challenges, industry trends and solutions

Some of the papers cited in the slides are avaiable at the folder [papers](papers)

The detailed outline of the tutorial is avilabler [here](tutorial_detailed.pdf) as well as the tutorial ACM paper [here](kdd2021_inc_testing_tutorial.pdf).

Feedback welcome!! 
