# 🔎 Google X-Ray Search for Recruiters

> A practical Google X-Ray Search playbook for US IT recruiting, technical sourcing, passive candidate discovery, public resume discovery, GitHub sourcing, portfolio research, and targeted talent mapping.

Google X-Ray Search combines:

```text
GOOGLE SEARCH
+
SEARCH OPERATORS
+
BOOLEAN LOGIC
+
TARGET DOMAIN
+
RECRUITING KEYWORDS
=
X-RAY SOURCING

| Section | Topic                           |
| ------- | ------------------------------- |
| 1       | What Is Google X-Ray Search?    |
| 2       | Why Recruiters Use Google X-Ray |
| 3       | X-Ray vs Boolean                |
| 4       | Google Search Fundamentals      |
| 5       | Exact Phrase Search             |
| 6       | `site:`                         |
| 7       | `-` Exclusions                  |
| 8       | `filetype:`                     |
| 9       | `intitle:`                      |
| 10      | `inurl:`                        |
| 11      | `intext:`                       |
| 12      | Date Operators                  |
| 13      | Search Term Stacking            |
| 14      | LinkedIn X-Ray                  |
| 15      | GitHub X-Ray                    |
| 16      | Resume X-Ray                    |
| 17      | Portfolio X-Ray                 |
| 18      | Technical Community X-Ray       |
| 19      | Company X-Ray                   |
| 20      | Location X-Ray                  |
| 21      | Title Clusters                  |
| 22      | Technology Clusters             |
| 23      | Advanced Search Architecture    |
| 24      | Broad Search                    |
| 25      | Narrow Search                   |
| 26      | Search Troubleshooting          |
| 27      | US IT Recruiting Examples       |
| 28      | Multi-Source Sourcing           |
| 29      | Search Validation               |
| 30      | Ethical Sourcing                |
| 31      | Google X-Ray Cheat Sheet        |
| 32      | Final Framework                 |


1. What Is Google X-Ray Search?
Google X-Ray Search is a sourcing technique where Google is used to discover publicly indexed information from a targeted website, domain, or source.

The basic structure is:
site:target-domain.com keywords

Example:
site:linkedin.com/in/ "Java Developer" "Spring Boot"

Conceptually:
GOOGLE
  +
TARGET WEBSITE
  +
SEARCH TERMS
  =
X-RAY SEARCH

2. Why Recruiters Use Google X-Ray

Google X-Ray can help recruiters discover:

Public professional profiles
Public resumes
Public CVs
Public portfolios
Public GitHub pages
Public technical profiles
Public conference pages
Public professional websites
Public technical articles
Publicly indexed career information

It can be especially useful when:
Internal platform search
        ↓
does not provide enough discovery

The recruiter can try:
Google
+
Boolean
+
site:
+
professional keywords

3. What X-Ray Search Is Not
X-Ray Search does not mean:
Bypassing authentication
Accessing private profiles
Circumventing access controls
Obtaining passwords
Accessing restricted databases
Extracting private information
Breaking website security
Accessing information that is not publicly available

This repository focuses on legitimate discovery of public professional information.


4. X-Ray vs Boolean Search
These concepts work together but are different.

Boolean
Controls the logical relationship between search terms.

Example:
("Java Developer" OR "Java Engineer")
AND
"Spring Boot"
AND
AWS


X-Ray
Targets a particular source.

Example:
site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
"Spring Boot"
AWS

Therefore:
BOOLEAN
=
SEARCH LOGIC


X-RAY
=
SOURCE TARGETING

Combined:
X-RAY
+
BOOLEAN
=
TARGETED WEB SOURCING


5. Google Search Fundamentals
Google evaluates search terms, pages, links, site relationships, and other signals to produce results.
Google notes that search results may include related terms rather than requiring an exact match for every term entered.

Therefore:
SEARCH QUERY
≠
EXACT DATABASE FILTER

A recruiter should expect:
Related terms
Variations
Search ranking differences
Missing pages
Indexed pages
Stale pages
Different results over time
This is why search results must be reviewed rather than blindly trusted.


6. Exact Phrase Search
Use quotation marks when a phrase should be treated as an exact phrase.

Example:
"Java Developer"

Another:
"Spring Boot"

Another:
"Machine Learning Engineer"

Recruiting example:
"Senior Java Developer" "Spring Boot"

Google's official search guidance documents quotation marks for exact matches.


7. The site: Operator
The site: operator restricts results to a particular website or domain.

Basic structure:
site:domain.com keyword

Example:
site:linkedin.com/in/ "Java Developer"

GitHub:
site:github.com "Python" "FastAPI"

Portfolio:
site:example.com "Software Engineer"

Resume:
site:example.com filetype:pdf "Java Developer"


Google currently documents site: as a way to search within a specific site or domain.

8. site: Syntax

Correct:
site:linkedin.com/in/ "Java Developer"
Avoid inserting a space between the operator and its value:

site: linkedin.com/in/
Google specifically notes that there should not be a space between the operator and search term.


9. LinkedIn X-Ray Search
A common recruiter pattern is:
site:linkedin.com/in/

Example:
site:linkedin.com/in/ "Java Developer"

Add technology:
site:linkedin.com/in/
"Java Developer"
"Spring Boot"

Add location:
site:linkedin.com/in/
"Java Developer"
"Spring Boot"
Michigan

Add title alternatives:
site:linkedin.com/in/
("Java Developer" OR "Java Engineer" OR "Backend Engineer")
"Spring Boot"
Michigan
10. LinkedIn X-Ray Architecture

Use:
TARGET
+
TITLE
+
CORE SKILL
+
LOCATION
+
OPTIONAL SIGNAL

Example:
site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
"Spring Boot"
(AWS OR Azure)
Michigan
11. LinkedIn X-Ray — Senior Java
site:linkedin.com/in/
("Senior Java Developer"
OR "Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer")
"Spring Boot"
Microservices
(AWS OR Azure)
Michigan
12. LinkedIn X-Ray — Python
site:linkedin.com/in/
("Python Developer"
OR "Python Engineer"
OR "Backend Engineer")
Python
(Django OR Flask OR FastAPI)
(AWS OR Azure OR GCP)
Texas


13. LinkedIn X-Ray — React
site:linkedin.com/in/
("React Developer"
OR "React Engineer"
OR "Frontend Engineer"
OR "UI Engineer")
(React OR ReactJS OR "React.js")
(TypeScript OR JavaScript)
Florida
14. LinkedIn X-Ray — DevOps
site:linkedin.com/in/
("DevOps Engineer"
OR "Platform Engineer"
OR "Cloud Engineer"
OR "Site Reliability Engineer"
OR SRE)
(AWS OR Azure OR GCP)
(Kubernetes OR K8s)
(Terraform OR "Infrastructure as Code")
15. LinkedIn X-Ray — QA Automation
site:linkedin.com/in/
("QA Automation Engineer"
OR "Automation Engineer"
OR SDET
OR "Test Automation Engineer")
(Selenium OR Cypress OR Playwright)
(Java OR Python OR JavaScript OR TypeScript)


16. LinkedIn X-Ray — Data Engineer
site:linkedin.com/in/
("Data Engineer"
OR "Senior Data Engineer"
OR "Data Platform Engineer")
(Python OR PySpark)
SQL
(Spark OR PySpark)
(AWS OR Azure OR GCP)
17. LinkedIn X-Ray — AI / GenAI
site:linkedin.com/in/
("AI Engineer"
OR "Machine Learning Engineer"
OR "ML Engineer"
OR "Generative AI Engineer"
OR "GenAI Engineer")
Python
(LLM OR "Large Language Model")
(RAG OR "Retrieval Augmented Generation")
18. LinkedIn X-Ray — Cybersecurity
site:linkedin.com/in/
("Cybersecurity Engineer"
OR "Security Engineer"
OR "Information Security Engineer")
(Vulnerability OR "Vulnerability Management")
(SIEM OR SOC)
19. LinkedIn X-Ray — Automotive
site:linkedin.com/in/
("Software Engineer"
OR "Java Developer"
OR "Python Developer")
(Automotive OR Mobility)
Michigan


20. LinkedIn X-Ray — Target Company
A recruiter can combine a company term with technical requirements.

Example:
site:linkedin.com/in/
"Java Developer"
"Spring Boot"
"Ford"

However:

"Ford"

appearing on a page does not automatically establish current employment.
Always validate the professional context.


21. The - Exclusion Operator

Google documents the minus sign as a way to exclude a word from search results.

Example:

Java Developer -Android

Another:

"Java Developer" -training

Another:

"Data Scientist" -course

Use exclusions only when they solve a real search problem.


22. Targeted Exclusions

Example:
site:linkedin.com/in/
"Java Developer"
"Spring Boot"
-Android

Possible use:
Reduce Android-related noise
Do not create enormous exclusion lists.

Bad:
-JavaScript
-Android
-Junior
-Intern
-Student
-Trainer
-Teacher
-Course
-Certification

A broad exclusion list can remove legitimate candidates.


23. filetype: Operator
Google documents filetype: for searching for particular document types.

Example:
filetype:pdf "Java Developer"

Resume example:
filetype:pdf "Senior Java Developer" "Spring Boot"

Technical document:
filetype:pdf "AWS" Terraform

Presentation:
filetype:ppt "Machine Learning"
Document searches should always be evaluated for:

Age
Authenticity
Relevance
Ownership
Currentness
24. Resume X-Ray

A basic resume search:
filetype:pdf
"Java Developer"
"Spring Boot"
AWS

Location:
filetype:pdf
"Java Developer"
"Spring Boot"
Michigan

Title variation:
filetype:pdf
("Java Developer" OR "Java Engineer")
"Spring Boot"
Michigan
25. Resume + LinkedIn X-Ray
site:linkedin.com/in/
"resume"
"Java Developer"
"Spring Boot"

Another:
site:linkedin.com/in/
("CV" OR "Resume")
"Python Developer"
AWS

The presence of words such as resume or CV is a search signal, not proof that the page contains a current resume.


26. intitle: Operator
intitle: can target words or phrases appearing in page titles where supported.

Example:
intitle:"Java Developer"

Combined:

intitle:"Java Developer"
"Spring Boot"

With a domain:

site:example.com
intitle:"Software Engineer"

Use it when the page title itself is a useful discovery signal.

27. inurl: Operator

inurl: can target terms appearing in URLs where supported.

Example:

inurl:resume "Java Developer"

Another:

inurl:portfolio React

Another:

inurl:developer Python

Use it to exploit meaningful URL structures.

28. intext: Operator

intext: can be useful when you want to target words within page text where supported.

Example:

intext:"Java Developer"

Another:

intext:"Spring Boot" AWS

Another:

intext:"Machine Learning Engineer"

Operator behavior can vary, so test the query rather than assuming perfect field-level filtering.

29. Combining Operators

The real power of Google X-Ray comes from combining operators.

Example:

site:linkedin.com/in/
intitle:"Software Engineer"
"Java"
"Spring Boot"
Michigan

Another:

site:github.com
inurl:users
Python
FastAPI

Another:

filetype:pdf
"Java Developer"
"Spring Boot"
Michigan
30. Operator Architecture

Think of a Google X-Ray query as:

SOURCE
+
STRUCTURE
+
CONTENT
+
CONTEXT
+
EXCLUSIONS

Example:

SOURCE
site:linkedin.com/in/


STRUCTURE
intitle:"Java Engineer"


CONTENT
"Spring Boot" Microservices


CONTEXT
Michigan


EXCLUSION
-Android
31. Search Term Stacking

Search term stacking means intentionally combining multiple relevant terms.

Example:

"Java Developer"
"Spring Boot"
Microservices
Kafka
AWS
Michigan

Do not assume every term must be mandatory.

The search engine determines how terms influence result retrieval and ranking.

32. Title Stacking

Example:

("Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer")

This allows multiple professional title variations.

33. Technology Stacking

Example:

(Java
AND
"Spring Boot"
AND
Microservices
AND
Kafka)

This targets a technical combination.

34. Cloud Stacking

Example:

(AWS OR Azure OR GCP)

More specific:

(AWS OR "Amazon Web Services")

Use broader cloud alternatives only when the requirement permits them.

35. Location Stacking

Example:

(Detroit OR Michigan OR MI)

Another:

(Dallas OR "Dallas, TX" OR Texas OR TX)

Another:

(Atlanta OR Georgia OR GA)

Location expansion should reflect the actual recruiting market.

36. Domain Stacking

Automotive:

(Automotive OR Mobility)

Banking:

(Banking OR "Financial Services" OR FinTech)

Manufacturing:

(Manufacturing OR Industrial)

Healthcare:

(Healthcare OR HealthTech)
37. Google X-Ray Search Formula

Use:

site:TARGET
(TITLE VARIATIONS)
(CORE SKILLS)
(LOCATION)
(OPTIONAL DOMAIN)
-EXCLUSIONS

Example:

site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
("Spring Boot" OR Spring)
Microservices
(AWS OR Azure)
(Michigan OR MI)
-Android
38. Broad Google X-Ray

When candidate supply is low:

site:linkedin.com/in/
("Java Developer" OR "Java Engineer" OR "Backend Engineer")
Java
Michigan

Do not add every skill immediately.

39. Balanced Google X-Ray
site:linkedin.com/in/
("Java Developer" OR "Java Engineer" OR "Backend Engineer")
Java
"Spring Boot"
Microservices
Michigan

This is often a useful starting point for technical sourcing.

40. Narrow Google X-Ray
site:linkedin.com/in/
("Senior Java Developer" OR "Java Engineer")
Java
"Spring Boot"
Microservices
Kafka
AWS
Michigan

Use a narrow query when the initial result set contains too much noise.

41. Search Broadening Ladder

If results are too limited:

LEVEL 1
Exact title
      ↓
LEVEL 2
Title variations
      ↓
LEVEL 3
Technology variations
      ↓
LEVEL 4
Location variations
      ↓
LEVEL 5
Remove secondary requirements
      ↓
LEVEL 6
Change source
42. Search Narrowing Ladder

If results are too broad:

LEVEL 1
Add core technology
      ↓
LEVEL 2
Add framework
      ↓
LEVEL 3
Add architecture
      ↓
LEVEL 4
Add location
      ↓
LEVEL 5
Add domain
      ↓
LEVEL 6
Add targeted exclusions
43. GitHub X-Ray

GitHub can provide technical discovery signals.

Basic:

site:github.com "Java" "Spring Boot"

Python:

site:github.com Python FastAPI

React:

site:github.com React TypeScript

Kubernetes:

site:github.com Kubernetes Terraform

AI:

site:github.com Python LLM RAG
44. GitHub Profile Discovery

A recruiter can experiment with public profile-oriented searches.

Example:

site:github.com
"Java Developer"

Another:

site:github.com
"Python Developer"

Another:

site:github.com
"Machine Learning Engineer"

Do not assume the search result represents current employment or job availability.

45. GitHub Repository Discovery

Example:

site:github.com
"Spring Boot"
"Microservices"

Another:

site:github.com
React
TypeScript

Another:

site:github.com
Terraform
Kubernetes
AWS

Repository discovery can identify technical ecosystems and potential contributors.

46. GitHub + Location

Location information may be less consistently represented on GitHub.

Example:

site:github.com
"Java"
"Michigan"

Treat location matches as a discovery signal requiring validation.

47. Portfolio X-Ray

Personal websites can be discovered using:

"Java Developer"
"portfolio"
"Spring Boot"

Or:

inurl:portfolio
"React Developer"

Another:

inurl:resume
"Software Engineer"
Python
48. Technical Community X-Ray

Public technical communities can contain useful professional signals.

Example:

site:stackoverflow.com
"Java"
"Spring Boot"

Another:

site:dev.to
"Python"
"FastAPI"

Another:

site:medium.com
"Machine Learning Engineer"

These are discovery sources, not employment databases.

49. Company Website X-Ray

Example:

site:company.com
"Software Engineer"

Another:

site:company.com
"Java"
"Developer"

This can be useful for public employee directories, speaker pages, engineering blogs, team pages, or other professional content where such pages are publicly indexed.

50. Company Talent Mapping

Use:

site:linkedin.com/in/
"Company Name"
"Java"
"Spring Boot"

Then compare with:

site:linkedin.com/in/
"Competitor Company"
"Java"
"Spring Boot"

This can support competitor talent mapping.

Remember:

Company keyword
≠
Confirmed current employment
51. Location X-Ray

Example:

site:linkedin.com/in/
"Java Developer"
Detroit

Broader:

site:linkedin.com/in/
"Java Developer"
(Detroit OR Michigan OR MI)

Metro-focused:

site:linkedin.com/in/
"Java Developer"
("Metro Detroit" OR Detroit OR Michigan)
52. Remote Candidate Search

Example:

site:linkedin.com/in/
"Java Developer"
Remote
"Spring Boot"

Another:

site:linkedin.com/in/
"Software Engineer"
"Remote"
AWS

Do not interpret the presence of Remote as proof of current work authorization, availability, or willingness to work remotely.

53. Contract Candidate Search

Potential discovery terms:

"Contract"
"Consultant"
"Consulting"
"Contractor"

Example:

site:linkedin.com/in/
"Java Developer"
"Contract"
"Spring Boot"

These terms are signals, not proof of current contract status.

54. Certification Search

Example:

site:linkedin.com/in/
"AWS Certified"
"Java Developer"

Another:

site:linkedin.com/in/
"Azure Certified"
"Cloud Engineer"

Another:

site:linkedin.com/in/
"PMP"
"Project Manager"

Certification information should be validated through appropriate professional screening.

55. Education Search

Example:

site:linkedin.com/in/
"Computer Science"
"Java Developer"
Michigan

Use education terms carefully.

Do not use public search techniques to infer sensitive personal characteristics.

56. Advanced Search Architecture

A mature Google X-Ray search may contain:

TARGET SOURCE
+
TITLE CLUSTER
+
CORE TECHNOLOGY
+
SECONDARY TECHNOLOGY
+
DOMAIN
+
LOCATION
-
NOISE

Example:

site:linkedin.com/in/
("Senior Java Developer"
OR "Java Engineer"
OR "Backend Engineer")
(Java)
("Spring Boot" OR Spring)
Microservices
(AWS OR Azure)
(Automotive OR Mobility)
(Michigan OR MI)
-Android
57. Multi-Source X-Ray Strategy

Do not rely on only one source.

Use:

LINKEDIN
   ↓
GITHUB
   ↓
RESUMES
   ↓
PORTFOLIOS
   ↓
TECHNICAL COMMUNITIES
   ↓
COMPANY PAGES

Different sources expose different professional signals.

58. Source Selection Matrix
Source	Useful Signals
LinkedIn	Career / title / professional profile
GitHub	Code / repositories / technical activity
Resume	Career history / skills
Portfolio	Projects / professional presentation
Stack Overflow	Technical participation
Dev.to	Technical writing
Medium	Technical content
Company Website	Public team / engineering information
Conference Pages	Speaking / technical expertise
Public Communities	Technical interests
59. Discovery vs Validation

Google X-Ray is primarily a discovery mechanism.

DISCOVERY
    ↓
SEARCH RESULT
    ↓
PROFILE / DOCUMENT
    ↓
VALIDATION
    ↓
RECRUITER SCREEN

Do not treat:

Google result
=
verified candidate
60. Public Resume Validation

A public resume may be:

Old
Duplicated
Archived
Incomplete
Incorrect
No longer current

Check:

Publication / update signals
Employment dates
Current profile
Technical consistency
Candidate-provided information
61. Search Result Validation

For each promising result ask:

[ ] Is this the correct person?
[ ] Is this the correct professional field?
[ ] Is the information relevant?
[ ] Is the information current enough?
[ ] Is the source credible?
[ ] Does the technical evidence align?
[ ] Does the candidate actually fit the requirement?
62. Zero Results

If Google returns little or nothing:

Step 1

Remove secondary technologies.

Step 2

Expand title variations.

Step 3

Expand location terms.

Step 4

Remove unnecessary exclusions.

Step 5

Change the target source.

Step 6

Try a simpler query.

Example:

site:linkedin.com/in/
"Java Developer"
Michigan

instead of:

site:linkedin.com/in/
"Senior Java Developer"
"Spring Boot"
Microservices
Kafka
AWS
Terraform
Michigan
Automotive
-Android
63. Too Many Results

Add specificity.

Start:

site:linkedin.com/in/
Java

Then:

site:linkedin.com/in/
"Java Developer"
"Spring Boot"

Then:

site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
"Spring Boot"
Microservices
Michigan
64. Wrong Candidates

Identify the source of noise.

Example:

Java

may return:

Java Developer
Java Trainer
Java Instructor
Android Developer
JavaScript Developer

Add context:

"Java Developer"
"Spring Boot"

or use a justified exclusion:

"Java Developer"
"Spring Boot"
-Android
65. Search Iteration

Use:

BUILD
 ↓
SEARCH
 ↓
REVIEW
 ↓
IDENTIFY NOISE
 ↓
MODIFY
 ↓
SEARCH AGAIN
 ↓
VALIDATE

Do not assume the first query is the final query.

66. One-Change-at-a-Time Rule

When optimizing a query:

Change TITLE
→ test


Change TECHNOLOGY
→ test


Change LOCATION
→ test


Add EXCLUSION
→ test

Avoid changing everything simultaneously.

This makes search behavior easier to understand.

67. Example — Senior Java Developer

Requirement:

Senior Java Developer
Detroit, MI


Java
Spring Boot
Microservices
AWS
Kafka
Broad
site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
Java
Michigan
Balanced
site:linkedin.com/in/
("Senior Java Developer"
OR "Java Developer"
OR "Java Engineer"
OR "Backend Engineer")
"Spring Boot"
Microservices
Michigan
Narrow
site:linkedin.com/in/
("Senior Java Developer"
OR "Java Engineer")
Java
"Spring Boot"
Microservices
Kafka
AWS
(Detroit OR Michigan OR MI)
68. Example — Python Full Stack
site:linkedin.com/in/
("Python Developer"
OR "Python Full Stack Developer"
OR "Full Stack Engineer")
Python
(Django OR FastAPI)
(React OR ReactJS)
(AWS OR Azure)
Michigan
69. Example — React Developer
site:linkedin.com/in/
("React Developer"
OR "React Engineer"
OR "Frontend Engineer")
(React OR ReactJS OR "React.js")
(TypeScript OR JavaScript)
(HTML OR CSS)
Philadelphia
70. Example — QA Lead
site:linkedin.com/in/
("QA Lead"
OR "Test Lead"
OR "QA Automation Lead"
OR "Quality Engineering Lead")
(Selenium OR Cypress OR Playwright)
(API OR "API Testing")
(Azure OR AWS)
71. Example — DevOps Engineer
site:linkedin.com/in/
("DevOps Engineer"
OR "Platform Engineer"
OR SRE
OR "Site Reliability Engineer")
(Kubernetes OR K8s)
(Terraform OR "Infrastructure as Code")
(AWS OR Azure OR GCP)
72. Example — GenAI Engineer
site:linkedin.com/in/
("Generative AI Engineer"
OR "GenAI Engineer"
OR "AI Engineer"
OR "Machine Learning Engineer")
Python
(LLM OR "Large Language Model")
(RAG OR "Retrieval Augmented Generation")
(LangChain OR LangGraph)
73. Example — Security Architect
site:linkedin.com/in/
("Security Architect"
OR "Cybersecurity Architect"
OR "Security Engineer")
("Cloud Security"
OR "Application Security"
OR "GenAI Security")
(AWS OR Azure)
74. Example — Automotive AI
site:linkedin.com/in/
("AI Engineer"
OR "Machine Learning Engineer"
OR "Software Engineer")
(Automotive OR Mobility)
(Python OR C++ OR Java)
(AI OR "Machine Learning")
Michigan
75. Example — Electrical Engineering
site:linkedin.com/in/
("Electrical Engineer"
OR "Power Systems Engineer"
OR "Transmission Line Engineer")
("PLS-CADD"
OR "Transmission Line")
("Power Systems" OR Electrical)
Georgia
76. Example — MES Specialist
site:linkedin.com/in/
("MES Specialist"
OR "MES Engineer"
OR "Manufacturing Execution System")
(MES OR "Manufacturing Execution")
(Manufacturing OR Automotive)
Kentucky
77. Example — ServiceNow
site:linkedin.com/in/
("ServiceNow Developer"
OR "ServiceNow Engineer"
OR "ServiceNow Consultant")
ServiceNow
(ITSM OR "IT Service Management")
78. Example — Salesforce
site:linkedin.com/in/
("Salesforce Developer"
OR "Salesforce Engineer"
OR "Salesforce Technical Consultant")
Salesforce
(Apex OR Lightning)
79. Example — SAP
site:linkedin.com/in/
("SAP Consultant"
OR "SAP Developer"
OR "SAP Technical Consultant")
SAP
("S/4HANA" OR "S4 HANA")
80. Google X-Ray Cheat Sheet
Exact phrase
"Java Developer"
Specific site
site:linkedin.com/in/
Exclusion
-JavaScript
PDF
filetype:pdf
Title
intitle:"Java Developer"
URL
inurl:resume
Page text
intext:"Spring Boot"
Date
after:2025-01-01
before:2026-01-01

Google's current official documentation lists before: and after: for date-based filtering.

81. Operator Combination Cheat Sheet
LinkedIn
site:linkedin.com/in/
"Java Developer"
"Spring Boot"
GitHub
site:github.com
Java
"Spring Boot"
PDF
filetype:pdf
"Java Developer"
AWS
Portfolio
inurl:portfolio
"Software Engineer"
Resume
inurl:resume
"Java Developer"
Page title
intitle:"Software Engineer"
Page content
intext:"Spring Boot"
Exclusion
Java -Android
82. Google Search Operator Rules
Rule 1

Do not place a space after the operator.

Correct:

site:linkedin.com

Incorrect:

site: linkedin.com

Google explicitly documents this syntax requirement.

Rule 2

Use quotes for important phrases.

Rule 3

Use site: to target a source.

Rule 4

Use - only for justified exclusions.

Rule 5

Use filetype: for document discovery.

Rule 6

Test advanced operators before building a large search around them.

Rule 7

Treat search results as discovery signals.

Rule 8

Validate candidate information independently.

83. Google X-Ray Search Quality Checklist
[ ] Target source is defined
[ ] Search objective is clear
[ ] Title cluster is relevant
[ ] Core technology is defined
[ ] Technology alternatives are accurate
[ ] Location terms are appropriate
[ ] Domain terms are justified
[ ] Exclusions are justified
[ ] Query is readable
[ ] Query is not unnecessarily restrictive
[ ] Query is not unnecessarily broad
[ ] Results have been reviewed
[ ] False positives have been identified
[ ] Search has been optimized
[ ] Candidate information will be validated
84. Google X-Ray Search Workflow
JOB DESCRIPTION
      ↓
REQUIREMENT EXTRACTION
      ↓
TITLE CLUSTER
      ↓
TECHNOLOGY CLUSTER
      ↓
LOCATION CLUSTER
      ↓
DOMAIN
      ↓
TARGET SOURCE
      ↓
GOOGLE X-RAY
      ↓
SEARCH RESULTS
      ↓
RESULT REVIEW
      ↓
QUERY OPTIMIZATION
      ↓
CANDIDATE DISCOVERY
      ↓
VALIDATION
      ↓
RECRUITER SCREEN
85. Multi-Source Recruiter Workflow
                 JOB
                  │
                  ▼
             REQUIREMENTS
                  │
                  ▼
            BOOLEAN LOGIC
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
    LINKEDIN    GITHUB    RESUMES
        │         │         │
        └─────────┼─────────┘
                  ▼
             PORTFOLIOS
                  │
                  ▼
        TECHNICAL COMMUNITIES
                  │
                  ▼
             VALIDATION
                  │
                  ▼
               SCREEN
86. Ethical X-Ray Sourcing

Google X-Ray should be used for professional sourcing.

Appropriate examples:

Public professional profiles
Public resumes
Public portfolios
Public GitHub repositories
Public technical articles
Public conference profiles
Public company pages

Avoid:

Private-account discovery
Password discovery
Authentication bypass
Restricted database access
Sensitive personal information gathering
Doxxing
Harassment
Stalking
87. Important Candidate Data Boundary

The objective is:

PROFESSIONAL DISCOVERY

Not:

PRIVATE PERSON INVESTIGATION

Focus searches on:

Skills
Experience
Projects
Professional titles
Public technical work
Professional affiliations
Public career information
88. Search Result ≠ Candidate

A Google result is only a discovery signal.

GOOGLE RESULT
      ↓
POTENTIAL PROFESSIONAL
      ↓
VALIDATION
      ↓
SCREENING
      ↓
CANDIDATE

Do not skip validation.

89. Search Result ≠ Current Employment

A public page may contain outdated information.

Therefore:

Company Name
≠
Confirmed Current Employer

and:

Job Title
≠
Confirmed Current Role

and:

Technology Mention
≠
Professional Experience

Context matters.

90. Search Result ≠ Availability

A public profile cannot establish:

Candidate availability
Notice period
Job-search status
Interest in your opportunity
Compensation expectations
Work authorization

These require appropriate recruiting conversations and verification processes.

91. Search Result ≠ Skill Validation

A keyword appearing on a page does not automatically establish:

Years of experience
Proficiency
Production experience
Recent usage
Professional ownership

Use search to discover candidates.

Use screening to evaluate them.

92. Search Optimization Loop
             BUILD
               │
               ▼
             SEARCH
               │
               ▼
            REVIEW
               │
       ┌───────┴────────┐
       ▼                ▼
    TOO FEW          TOO MANY
       │                │
       ▼                ▼
    BROADEN            NARROW
       │                │
       └───────┬────────┘
               ▼
             SEARCH
               │
               ▼
           VALIDATE
93. The 5-Layer Google X-Ray Model
LAYER 1
SOURCE
site:


LAYER 2
ROLE
Title cluster


LAYER 3
TECHNOLOGY
Skill cluster


LAYER 4
CONTEXT
Location / domain / company


LAYER 5
NOISE CONTROL
Exclusions

Example:

site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
"Spring Boot"
Microservices
(Michigan OR MI)
-Android
94. The Recruiter Search Formula

Remember:

GOOGLE X-RAY
=
TARGET SOURCE
+
TITLE
+
CORE SKILLS
+
CONTEXT
+
OPTIONAL SIGNALS
-
NOISE

Where:

TARGET SOURCE
=
Where should the information exist?


TITLE
=
Who are you looking for?


CORE SKILLS
=
What must they know?


CONTEXT
=
What makes the candidate relevant?


OPTIONAL SIGNALS
=
What can improve discovery?


NOISE
=
What should be excluded?
95. Final Google X-Ray Framework
                 REQUISITION
                     │
                     ▼
             EXTRACT REQUIREMENTS
                     │
                     ▼
                BUILD BOOLEAN
                     │
                     ▼
               SELECT SOURCE
                     │
        ┌────────────┼────────────┐
        ▼            ▼            ▼
     LINKEDIN      GITHUB       RESUME
        │            │            │
        └────────────┼────────────┘
                     ▼
                BUILD X-RAY
                     │
                     ▼
                  SEARCH
                     │
              ┌──────┴──────┐
              ▼             ▼
           TOO FEW       TOO MANY
              │             │
              ▼             ▼
           EXPAND          NARROW
              │             │
              └──────┬──────┘
                     ▼
                  SEARCH
                     │
                     ▼
                REVIEW RESULTS
                     │
                     ▼
                 VALIDATE
                     │
                     ▼
                 SCREEN
96. Golden Rules
Rule 1

Start with the sourcing objective.

Rule 2

Choose the right source.

Rule 3

Use site: to target a source when appropriate.

Rule 4

Use quotation marks for important phrases.

Rule 5

Use Boolean groups for genuine alternatives.

Rule 6

Use - exclusions only when justified.

Rule 7

Do not make every JD keyword mandatory.

Rule 8

Broaden when candidate supply is low.

Rule 9

Narrow when noise is high.

Rule 10

Use multiple sources.

Rule 11

Validate public information.

Rule 12

Keep professional sourcing separate from private information gathering.

97. Final Cheat Sheet
┌──────────────────────────────────────────────┐
│          GOOGLE X-RAY CHEAT SHEET            │
├──────────────────────────────────────────────┤
│ Exact phrase     "Java Developer"            │
│ Site             site:linkedin.com/in/       │
│ Exclude          -Android                    │
│ File type        filetype:pdf                │
│ Title            intitle:"Developer"         │
│ URL              inurl:resume                │
│ Page text        intext:"Spring Boot"        │
│ After date       after:2025-01-01            │
│ Before date      before:2026-01-01           │
├──────────────────────────────────────────────┤
│ TITLE + SKILLS + LOCATION + SOURCE           │
└──────────────────────────────────────────────┘
98. One Master Example

For a Senior Java Developer requirement:

site:linkedin.com/in/
("Senior Java Developer"
OR "Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer")
AND
Java
AND
("Spring Boot" OR Spring)
AND
(Microservices OR "Micro Services")
AND
(AWS OR "Amazon Web Services")
AND
(Kafka OR "Apache Kafka")
AND
(Detroit OR Michigan OR MI)
-Android

This query should be treated as a starting point, not a permanent universal search string.

99. The X-Ray Mindset

The most important principle is:

Do not search for a candidate. Search for the public professional evidence that can lead you to the candidate.

That evidence can exist across:

LinkedIn
GitHub
Resumes
Portfolios
Technical Communities
Company Pages
Conference Pages
Professional Websites
Public Technical Work

The recruiter connects those signals into a structured sourcing workflow.

100. Module Summary

Google X-Ray Search combines:

GOOGLE
+
BOOLEAN
+
OPERATORS
+
TARGET SOURCES
+
RECRUITER INTENT

A strong recruiter can:

DECOMPOSE A JD
      ↓
BUILD BOOLEAN
      ↓
SELECT SOURCE
      ↓
BUILD X-RAY
      ↓
SEARCH
      ↓
REVIEW
      ↓
OPTIMIZE
      ↓
DISCOVER
      ↓
VALIDATE

The goal is not the longest query.

The goal is:

RIGHT SOURCE
+
RIGHT TERMS
+
RIGHT LOGIC
+
RIGHT ITERATION
=
BETTER DISCOVERY
🔗 Previous Module

➡️ 02 — Boolean Search

🔗 Next Module

➡️ 04 — Bing X-Ray Search

The next module will cover Bing-specific sourcing techniques, search behavior, operators, recruiter workflows, LinkedIn discovery, GitHub discovery, resume searches, and practical US IT recruiting examples.

📌 Repository Navigation
X-Ray-Search-Master/
│
├── README.md
│
├── 01-Fundamentals/
│   └── README.md
│
├── 02-Boolean-Search/
│   └── README.md
│
├── 03-Google-X-Ray/
│   └── README.md
│
├── 04-Bing-X-Ray/
│   └── README.md
│
└── ...

Last Verified: 2026-08-14

Verification Note: Google Search syntax and result behavior can change. Google's official documentation currently confirms operators such as site:, quotation marks, -, filetype:, before:, and after:. Test search behavior before treating any operator or query pattern as guaranteed.



### After pasting


Click **Preview**.


You should see:


```text
🔎 Google X-Ray Search for Recruiters

at the top instead of:

There is no content to preview.

If the preview looks correct, commit it with:

Build Google X-Ray Search module

Then your repository will be:

X-Ray-Search-Master/
├── README.md                  ✅
├── 01-Fundamentals/
│   └── README.md              ✅
├── 02-Boolean-Search/
│   └── README.md              ✅
├── 03-Google-X-Ray/
│   └── README.md              🔨 NOW
├── CONTRIBUTING.md
└── LICENSE

Do not create 04-Bing-X-Ray yet. First commit this Google module and send me the screenshot, and we'll continue one module at a time.
