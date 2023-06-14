# POPQUORN: the Potato-Prolific dataset for Question- Answering, Offensiveness, text Rewriting and politeness rating with demographic Nuance

POPQUORN is a collaboration effort of [potato](https://github.com/davidjurgens/potato) and [prolific](https://www.prolific.co) to create an open-source dataset with both individual annotations and annotator's backgrounds.
POPQUORN contains 45,000 annotations from 1484 annotators drawing from a US-population representative sample (for age, sex, and race). This GitHub repo contains raw annotations as well as detailed demographic information. POPQUORN is released with the following paper:

>Jiaxin Pei and David Jurgens. [When Do Annotator Demographics Matter? Measuring the Influence of Annotator Demographics with the POPQUORN Dataset.](https://arxiv.org/abs/2306.06826) The 17th Linguistic Annotation Workshop (LAW-XVII) @ACL 2023

## Using the annotation interfaces

All the annotation interfaces are available in [potato project-hub](https://github.com/davidjurgens/potato/tree/master/project-hub)

Install potato-annotation

``` 
pip install potato-annotation
```

#### Offensiveness rating

[yaml
config](https://github.com/davidjurgens/potato/tree/master/project-hub/offensiveness)
\|
[Dataset](https://github.com/Jiaxin-Pei/Potato-Prolific-Dataset/tree/main/dataset/offensiveness)

``` 
[fetch] potato get offensiveness
[launch] potato start offensiveness -p 8000
[Annotate] http://localhost:8000/?PROLIFIC_PID=user
```

#### Question Answering (SQuAD style)

[yaml
config](https://github.com/davidjurgens/potato/tree/master/project-hub/reading_comprehension)
\|
[Dataset](https://github.com/Jiaxin-Pei/Potato-Prolific-Dataset/tree/main/dataset/question_answering)

``` 
[fetch] potato get reading_comprehension
[launch] potato start reading_comprehension -p 8000
[Annotate] http://localhost:8000/?PROLIFIC_PID=user
```

#### Text rewriting

[yaml
config](https://github.com/davidjurgens/potato/tree/master/project-hub/email_rewriting)
\|
[Dataset](https://github.com/Jiaxin-Pei/Potato-Prolific-Dataset/tree/main/dataset/text_rewriting)

``` 
[fetch] potato get text_rewriting
[launch] potato start text_rewriting -p 8000
[Annotate] http://localhost:8000/?PROLIFIC_PID=user
```

#### Politeness rating

[yaml
config](https://github.com/davidjurgens/potato/tree/master/project-hub/politeness_rating)
\|
[Dataset](https://github.com/Jiaxin-Pei/Potato-Prolific-Dataset/tree/main/dataset/politeness_rating)

``` 
[fetch] potato get politeness_rating
[launch] potato start politeness_rating -p 8000
[Annotate] http://localhost:8000/?PROLIFIC_PID=user
```
