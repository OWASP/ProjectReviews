Title:     OWASP Review List
Created:   2016-01-13 , Enrico Branca  
Edited:    2016-01-13 , Enrico Branca  
Edited:    2016-01-14 , Enrico Branca  


[//]: # (BE SURE THERE ARE NO EMPTY LINES BEFORE 'Title')  
[//]: # (end each line of the metadata with TWO spaces before the newline)  
[//]: # (insert TWO blank lines after the metadata)  
[//]: # (<ADD YOUR TEXT STARTING FROM HERE>)  

## Why a review?

The purpose of this assessment is to determine whether a project meets the minimum criteria for each OWASP project.

See the '[Create a New Project](new_project.md#new_project_requirements)' section to see all the minimum requirements.

An analysis based on Qualitative content audit methodology (Martin & Hannington, 2012), can help us identify the key indicators the content must have in order to be considered of sufficient quality.

For this method, content is rated on the following criteria:

* Credibility

* Originality

* Accuracy

* Accessibility

* Open Source

* Publicly Available

Some criteria that would be consider during the review process for projects to become flagships are:

* Defined

* Repeatable

* Formatting/Branding

* Relevance to the audience (which is the target group?)

* Relevance to the subject (security)

## Manual Review Process

The review process is manually carried out for each project and consists of the following steps:

1. Identify the project

2. Get the 'Compliance Checklist'

3. Answer all questions in the checklist

4. If the project is using a version control system, get all the details

## Compliance Checklist

|     **Compliance Checks**                                   |     **Results**    |
|:------------------------------------------------------------|:------------------:|
|     **General**                                             |                    |
| Does the project have an active project leader ?            |      Yes/No        |
| Is the project free and open and not-for-profit ?           |      Yes/No        |
| Is the project vendor neutral ?                             |      Yes/No        |
|                                                             |                    |
|     **Production**                                          |                    |
| Has the project released something since its creation ?     |      Yes/No        |
| Does the project have any activity in the last 6 months?    |      Yes/No        |
| Does the project have any activity in the last 12 months?   |      Yes/No        |
| Does the project have any activity in the last 24 months?   |      Yes/No        |
|                                                             |                    |
|     **OWASP Wiki**                                          |                    |
| Does the project have a wiki page hosted in OWASP ?         |      Yes/No        |
| Does it has a relevant project summary hosted in OWASP ?    |      Yes/No        |
| Does it has a relevant project roadmap hosted in OWASP ?    |      Yes/No        |
| Does it specify at least one project owner?                 |      Yes/No        |
| Does it specify at least one contact email?                 |      Yes/No        |
| Is the wiki page up to date ?                               |      Yes/No        |
|                                                             |                    |
|     **Content released**                                    |                    |
| Has the project published something since its creation ?    |      Yes/No        |
| At least one update in the last 12 months ?                 |      Yes/No        |
| At least two updates in the last 24 months ?                |      Yes/No        |
|                                                             |                    |
|     **Public Data repository**                              |                    |
| Has a publicly accessible data repository ?                 |      Yes/No        |
| Does the repository contains some data ?                    |      Yes/No        |
| Does the repository contains a license file ?               |      Yes/No        |
| Does the repository contains what has been published ?      |      Yes/No        |
|                                                             |                    |
|     **Source Code repository**                              |                    |
| Has a publicly accessible source code repository ?          |      Yes/No        |
| Does the repository contains some data ?                    |      Yes/No        |
| Does the repository contains a license file ?               |      Yes/No        |
| Does the repository contains what has been published ?      |      Yes/No        |

## Version Control

In case the project is storing data in a version control system, for each data repository used, the reviewer has to collect ALL the following details:

| **Compliance Checks - for Version Control systems** |     **What has to be recorded**                |
|:----------------------------------------------------|:-----------------------------------------------|
| Repository Status ?                                 | Answers: CURRENT, OLD                          |
| Repository has data ?                               | Answers: YES, NO                               |
| Repository has source code ?                        | Answers: YES, NO                               |
| Repository type ?                                   | Answer: technology abbreviated name            |
| Repository main web page ?                          | Answer: valid web URL/URI confirmed reachable  |
| Repository HTTP/HTTPS clone links ?                 | Answer: valid web URL/URI confirmed reachable |
| Repository NATIVE clone links ?                     | Answer: valid web URL/URI confirmed reachable |

Example:
```
Repository_Status|CURRENT
Repository_HasData|YES
Repository_SourceCode|YES
Repository_Type|GIT
Repository_Page|<https://github.com/zaproxy/zaproxy>
Repository_Link|<https://github.com/zaproxy/zaproxy.git>
Repository_Link|git://github.com/zaproxy/zaproxy.git
```

[//]: # (<STOP HERE - do not write anything after this point !!! >)
