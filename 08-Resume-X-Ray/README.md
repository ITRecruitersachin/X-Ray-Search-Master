# 🔎 Resume X-Ray Search for Recruiters

> A practical Resume X-Ray Search playbook for US IT recruiting, technical sourcing, passive candidate discovery, public resume research, technical talent mapping, and search-engine-based candidate discovery.

Resume X-Ray Search is the practice of using search engines, Boolean logic, file-type targeting, domain targeting, technical keywords, job titles, locations, and resume-specific terminology to discover publicly indexed professional resumes.

The objective is not to collect random resumes.

The objective is to discover **relevant professional profiles that traditional recruiting searches may miss**, evaluate the available public signals, and move qualified candidates into a structured sourcing workflow.

---

## 🎯 What This Module Covers

This module covers:

- Resume X-Ray fundamentals
- Public resume discovery
- `filetype:pdf`
- Resume-specific search terms
- Job title targeting
- Technology targeting
- Location targeting
- Experience targeting
- Education targeting
- Industry targeting
- Boolean resume searches
- Google resume searches
- Bing resume searches
- DuckDuckGo resume searches
- Resume repository discovery
- Portfolio + resume correlation
- GitHub + resume correlation
- LinkedIn + resume correlation
- Technical resume discovery
- ATS-style resume terminology
- Candidate qualification signals
- Search precision
- Search recall
- False-positive reduction
- Duplicate-resume detection
- Search iteration
- Recruiter sourcing workflows
- Advanced resume X-Ray frameworks
- US IT recruiting examples

---

# 📚 Learning Path

```text
RESUME X-RAY
     │
     ▼
UNDERSTAND SEARCH ENGINES
     │
     ▼
IDENTIFY RESUME SIGNALS
     │
     ▼
BUILD BOOLEAN
     │
     ▼
ADD FILE TYPE
     │
     ▼
ADD TARGET TECHNOLOGY
     │
     ▼
ADD JOB TITLE
     │
     ▼
ADD LOCATION
     │
     ▼
RUN SEARCH
     │
     ▼
EVALUATE RESULTS
     │
     ▼
REFINE QUERY
     │
     ▼
VALIDATE CANDIDATE
     │
     ▼
SOURCE / OUTREACH


1. What Is Resume X-Ray Search?

Resume X-Ray Search uses an external search engine to discover publicly indexed resume documents.

A recruiter can combine:

Boolean logic
Search operators
File-type filters
Resume terminology
Job titles
Technologies
Locations
Education terms
Industry terms
Experience terminology

to narrow a large search universe into a smaller group of potentially relevant professional documents.

A basic concept is:

SEARCH ENGINE
+
BOOLEAN LOGIC
+
RESUME SIGNALS
+
TECHNOLOGY
+
JOB TITLE
+
LOCATION
+
FILE TYPE
=
RESUME X-RAY SEARCH
2. Why Resume X-Ray Search Matters

Traditional recruiter sourcing often begins with:

ATS
LinkedIn
Job boards
Resume databases
Vendor databases

Resume X-Ray Search adds another discovery layer.

It can help uncover:

Public resumes
Personal resumes
Technical portfolios
University career documents
Professional profiles
Publicly indexed PDF documents
Developer portfolios
Technical community profiles
Career documents hosted on public domains

The key advantage is additional discovery surface area.

3. The Resume X-Ray Mindset

A weak sourcing approach asks:

"Where can I find resumes?"

A stronger approach asks:

"Where is the professional signal indexed?"

That distinction changes the search strategy.

A resume may contain:

Name
Job Title
Technology
Location
Employer
Education
Certifications
Projects
Experience
Industry
Contact information
Portfolio
GitHub
LinkedIn
Professional Summary

The recruiter can use those signals to construct increasingly precise searches.

4. Core Resume X-Ray Formula

A basic resume X-Ray query can be represented as:

"JOB TITLE"
TECHNOLOGY
LOCATION
filetype:pdf

Example:

"Java Developer" "Spring Boot" "Michigan" filetype:pdf

Another example:

"React Developer" "JavaScript" "Texas" filetype:pdf

Another:

"Data Engineer" Python AWS Chicago filetype:pdf

The exact wording of resumes varies, so the recruiter should test multiple query structures.

5. Resume X-Ray Search Anatomy

A search can be decomposed into several components.

┌──────────────────────┐
│ TARGET JOB TITLE     │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ CORE TECHNOLOGY      │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ SUPPORTING SKILLS    │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ LOCATION             │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ RESUME SIGNAL        │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ FILE TYPE            │
└──────────────────────┘
6. The Most Important Resume Operator
filetype:pdf

One of the most useful resume discovery operators is:

filetype:pdf

Example:

"Java Developer" "Spring Boot" filetype:pdf

This asks the search engine to prioritize PDF documents.

PDF is common for:

Resumes
CVs
Professional profiles
Career documents
Candidate portfolios

However:

filetype:pdf does not mean every result is a resume.

The recruiter must still evaluate the document.

7. Other Useful File Types

Depending on the search engine and indexing behavior, recruiters may test:

filetype:pdf
filetype:doc
filetype:docx

Examples:

"Software Engineer" Python filetype:pdf
"QA Engineer" Selenium filetype:doc
"DevOps Engineer" AWS filetype:docx

PDF will often be the strongest starting point for public resume research.

8. Resume-Specific Keywords

A resume may contain words such as:

resume
cv
curriculum vitae
professional summary
experience
employment
education
skills
technical skills
certifications
career
profile
objective
projects

These terms can help increase resume relevance.

Example:

"Java Developer" "Spring Boot" resume filetype:pdf

Example:

"Data Engineer" Python "technical skills" filetype:pdf

Example:

"DevOps Engineer" AWS experience filetype:pdf
9. Resume Signal vs Resume Keyword

A recruiter should distinguish between:

Resume keyword
resume
CV
experience
education
skills

and:

Resume signal
Professional Experience
Technical Skills
Education
Certifications
Projects
Work History
Professional Summary

A strong search can combine both.

10. Job Title Targeting

Job titles should be treated as a search family rather than one exact phrase.

For example:

"Java Developer"
"Java Software Engineer"
"Java Engineer"
"Backend Java Developer"
"Senior Java Developer"
"Java Backend Engineer"

A Boolean title group can be:

("Java Developer" OR
 "Java Software Engineer" OR
 "Java Engineer" OR
 "Backend Java Developer" OR
 "Java Backend Engineer")

Then add:

filetype:pdf
11. Technology Targeting

Technology terms are often stronger than job titles because candidates may use different titles while describing similar technical work.

Example:

Java
Spring Boot
Microservices
REST
AWS
Docker
Kubernetes
SQL

Search:

Java "Spring Boot" Microservices filetype:pdf

More specific:

Java "Spring Boot" Microservices AWS Docker filetype:pdf
12. Technology Synonyms

Technology names may appear in different forms.

JavaScript
JavaScript
JS
ECMAScript
React
React
React.js
ReactJS
Node
Node
Node.js
NodeJS
Kubernetes
Kubernetes
K8s
Amazon Web Services
AWS
Amazon Web Services

A recruiter can create a synonym group:

(React OR "React.js" OR ReactJS)
13. Location Targeting

Location can dramatically improve precision.

Example:

"Java Developer" Michigan filetype:pdf

More targeted:

"Java Developer" Detroit Michigan filetype:pdf

Alternative:

"Java Developer" "Detroit, MI" filetype:pdf

Additional geographic variants may include:

Detroit
Detroit, MI
Detroit Michigan
Metro Detroit
Southeast Michigan
14. Location Synonym Strategy

A recruiter should consider:

CITY
+
STATE
+
STATE ABBREVIATION
+
METRO AREA
+
NEARBY MARKET

Example:

("Detroit" OR
 "Detroit, MI" OR
 "Detroit Michigan" OR
 "Metro Detroit")
15. Experience Targeting

Experience terminology can be useful:

senior
lead
principal
architect
manager
director
5+ years
7+ years
10+ years

Example:

"Senior Java Developer" "Spring Boot" filetype:pdf

Another:

Java "7+ years" "Spring Boot" filetype:pdf

However, experience statements are inconsistent across resumes.

Therefore:

Do not make experience wording mandatory unless necessary.

16. Education Targeting

Education terms may help when a requirement is specific.

Example:

"Computer Science" Java filetype:pdf

Example:

"Master of Science" Java "Spring Boot" filetype:pdf

Example:

"MS Computer Science" Python AWS filetype:pdf

Use education filters carefully because excessive education constraints can remove qualified candidates.

17. Certification Targeting

Certifications can provide useful search signals.

Examples:

"AWS Certified"
"PMP"
"CKA"
"Azure Certified"
"Salesforce Certified"
"CISSP"

Example:

"DevOps Engineer" "AWS Certified" filetype:pdf
18. Industry Targeting

Technology alone may produce too many results.

Add industry terms when necessary.

Examples:

Automotive
Banking
Healthcare
Insurance
Manufacturing
Retail
FinTech
Telecommunications
Government

Example:

"Java Developer" "Spring Boot" Automotive filetype:pdf
19. Employer Targeting

Company names can narrow the candidate universe.

Example:

"Java Developer" "General Motors" filetype:pdf

Example:

"Software Engineer" Ford AWS filetype:pdf

Example:

"Java Developer" "Bank of America" filetype:pdf

Use employer targeting when previous-company experience matters.

20. Resume Search Layers

A useful model is:

LAYER 1
JOB TITLE


LAYER 2
CORE TECHNOLOGY


LAYER 3
SUPPORTING TECHNOLOGY


LAYER 4
LOCATION


LAYER 5
INDUSTRY


LAYER 6
EMPLOYER


LAYER 7
RESUME SIGNAL


LAYER 8
FILE TYPE

Do not necessarily use every layer in every search.

21. Precision vs Recall

Recruiter search is an optimization problem.

Precision

How many search results are actually relevant?

Recall

How much of the relevant candidate universe did the search discover?

Conceptually:

HIGH PRECISION
=
FEWER
BUT MORE RELEVANT RESULTS
HIGH RECALL
=
MORE
POTENTIALLY RELEVANT RESULTS

A strong recruiter knows when to optimize each.

22. Search Too Broad

Example:

Java filetype:pdf

Potential problem:

Too many unrelated results

Improve it:

"Java Developer" "Spring Boot" filetype:pdf

Improve further:

"Java Developer" "Spring Boot" Microservices Michigan filetype:pdf
23. Search Too Narrow

Example:

"Senior Java Developer" "Spring Boot" "Microservices" "AWS" "Kubernetes" "Detroit, MI" "8 years" filetype:pdf

This may produce very few results.

Solution:

Remove one or more constraints.

"Java Developer" "Spring Boot" Microservices Detroit filetype:pdf

Then evaluate the results.

24. The Search Refinement Loop

Use:

SEARCH
  ↓
REVIEW
  ↓
IDENTIFY NOISE
  ↓
REMOVE NOISE
  ↓
IDENTIFY MISSING RESULTS
  ↓
ADD ALTERNATIVE TERMS
  ↓
SEARCH AGAIN

Never assume the first query is the final query.

25. Google Resume X-Ray

Google-style search:

"Java Developer" "Spring Boot" filetype:pdf

Location:

"Java Developer" "Spring Boot" Michigan filetype:pdf

Resume signal:

"Java Developer" "Spring Boot" resume filetype:pdf

Multiple technologies:

"Java Developer" "Spring Boot" Microservices AWS filetype:pdf
26. Google site: Targeting

The site: operator can target a domain.

Example:

site:example.com "Java Developer" filetype:pdf

This is useful when you already know a domain where professional documents may be publicly indexed.

General structure:

site:DOMAIN "JOB TITLE" TECHNOLOGY filetype:pdf
27. Google intitle: Targeting

The intitle: operator can target words appearing in page titles.

Example:

intitle:resume "Java Developer" filetype:pdf

Another:

intitle:CV "Software Engineer" Python filetype:pdf

Search-engine behavior can vary, so test queries rather than assuming perfect filtering.

28. Google inurl: Targeting

The inurl: operator can target terms in URLs.

Example:

inurl:resume "Java Developer" filetype:pdf

Another:

inurl:cv "Software Engineer" Python

Potential URL signals:

resume
cv
candidate
profile
portfolio
career
29. Google Exact Phrase

Use quotation marks for an exact phrase.

Example:

"Senior Java Developer"

Without quotes:

Senior Java Developer

With quotes:

"Senior Java Developer"

Quotation marks can improve precision when the phrase is meaningful.

30. Boolean OR

Use OR for alternatives.

Example:

("Java Developer" OR "Java Engineer")

Technology alternatives:

(React OR "React.js" OR ReactJS)

Cloud alternatives:

(AWS OR "Amazon Web Services")
31. Boolean AND

AND conceptually means the results should contain multiple concepts.

Example:

Java AND "Spring Boot"

However, search engines may already treat spaces as implicit AND-like matching.

Therefore, recruiters should focus on meaningful query construction rather than adding AND everywhere.

32. Exclusion

Use exclusions to reduce irrelevant results.

Example:

"Java Developer" "Spring Boot" filetype:pdf -jobs

Potential exclusions:

-jobs
-course
-training
-tutorial
-example

Use exclusions carefully.

33. Resume X-Ray with Job Titles
("Java Developer" OR
 "Java Engineer" OR
 "Java Software Engineer")
"Spring Boot"
filetype:pdf
34. Resume X-Ray with Frontend Skills
("React Developer" OR
 "Frontend Developer" OR
 "UI Developer")
(React OR "React.js" OR ReactJS)
JavaScript
filetype:pdf
35. Resume X-Ray with Full Stack Skills
("Full Stack Developer" OR
 "Full Stack Engineer")
(React OR Angular)
(Node OR "Node.js")
JavaScript
filetype:pdf
36. Resume X-Ray with Python
("Python Developer" OR
 "Python Engineer" OR
 "Software Engineer")
Python
(Django OR Flask OR FastAPI)
filetype:pdf
37. Resume X-Ray with Data Engineering
("Data Engineer" OR
 "Big Data Engineer")
Python
(Spark OR PySpark)
(AWS OR Azure OR GCP)
filetype:pdf
38. Resume X-Ray with DevOps
("DevOps Engineer" OR
 "Cloud DevOps Engineer")
(AWS OR Azure OR GCP)
(Docker OR Kubernetes)
(Terraform OR Jenkins)
filetype:pdf
39. Resume X-Ray with QA
("QA Engineer" OR
 "Test Engineer" OR
 "SDET" OR
 "Automation Engineer")
(Selenium OR Cypress OR Playwright)
Java
filetype:pdf
40. Resume X-Ray with Cybersecurity
("Security Engineer" OR
 "Cybersecurity Engineer" OR
 "Security Analyst")
(SIEM OR SOC OR Splunk)
filetype:pdf
41. Resume X-Ray with Cloud
("Cloud Engineer" OR
 "Cloud Architect")
(AWS OR Azure OR GCP)
Terraform
Kubernetes
filetype:pdf
42. Resume X-Ray with AI / ML
("Machine Learning Engineer" OR
 "ML Engineer" OR
 "AI Engineer")
(Python)
(TensorFlow OR PyTorch)
filetype:pdf
43. Resume X-Ray with GenAI
("AI Engineer" OR
 "Generative AI Engineer" OR
 "ML Engineer")
(Python)
(LLM OR "Large Language Model" OR RAG)
filetype:pdf
44. Resume X-Ray with LLM / RAG
("AI Engineer" OR
 "Machine Learning Engineer")
(LLM OR RAG OR "Retrieval Augmented Generation")
Python
filetype:pdf
45. Resume X-Ray with Location
"Java Developer"
"Spring Boot"
"Detroit"
filetype:pdf

Alternative:

"Java Developer"
"Spring Boot"
("Detroit" OR "Michigan" OR "MI")
filetype:pdf
46. Resume X-Ray for Remote Candidates

Remote terminology can include:

remote
distributed
work from home
WFH
remote team

Example:

"Software Engineer"
Python
remote
filetype:pdf

Do not assume that the presence of the word remote proves current work authorization or current availability.

47. Resume X-Ray for Senior Candidates
("Senior Software Engineer" OR
 "Senior Developer" OR
 "Lead Developer")
Java
"Spring Boot"
filetype:pdf
48. Resume X-Ray for Architects
("Software Architect" OR
 "Solutions Architect" OR
 "Technical Architect")
Java
AWS
Microservices
filetype:pdf
49. Resume X-Ray for Managers
("Engineering Manager" OR
 "Software Engineering Manager" OR
 "Development Manager")
Java
AWS
filetype:pdf
50. Resume X-Ray for Consultants
("Technical Consultant" OR
 "Software Consultant" OR
 "IT Consultant")
Java
AWS
filetype:pdf
51. Resume Repository Discovery

Public resumes may appear on:

Personal websites
Portfolio websites
University domains
Professional organizations
Community websites
Public document repositories
Developer websites
Career resources

The recruiter can investigate these surfaces without assuming that every document represents an active job seeker.

52. University Domain Searches

University domains can contain career documents, portfolios, project pages, and professional information.

Generic structure:

site:.edu "Java Developer" filetype:pdf

Another:

site:.edu "Computer Science" "Software Engineer" filetype:pdf

These searches may produce student or alumni material.

Always validate the candidate's current professional status independently.

53. Portfolio + Resume Search

Example:

"Java Developer"
portfolio
filetype:pdf

Another:

"Software Engineer"
GitHub
filetype:pdf

The objective is to find additional professional signals.

54. GitHub + Resume Correlation

A resume may mention:

GitHub
Git
open source
repositories
projects

Search:

"Software Engineer" GitHub Python filetype:pdf

After finding a resume, inspect any publicly referenced GitHub profile or project.

Do not assume the GitHub account belongs to the candidate without reasonable evidence.

55. LinkedIn + Resume Correlation

A public resume may contain:

LinkedIn
linkedin.com
LinkedIn profile

Search engines may index public LinkedIn pages separately.

A recruiter can use the resume and public professional profile as separate verification signals.

56. Candidate Signal Correlation

Think in terms of:

RESUME
  +
LINKEDIN
  +
GITHUB
  +
PORTFOLIO
  +
TECHNICAL PROJECTS
  +
EMPLOYMENT HISTORY
=
CANDIDATE SIGNAL MAP

The objective is not to collect data unnecessarily.

The objective is to establish whether the professional signals are reasonably consistent.

57. Resume Validation Framework

When reviewing a public resume, evaluate:

1. Job title
2. Technical skills
3. Years of experience
4. Recent employer
5. Employment chronology
6. Location
7. Education
8. Certifications
9. Projects
10. Portfolio
11. GitHub
12. LinkedIn

Use only information relevant to legitimate recruiting purposes.

58. Resume Authenticity Signals

Potential positive signals:

Consistent employment chronology
Consistent technology progression
Detailed project descriptions
Specific responsibilities
Reasonable career progression
Consistent public professional profiles
Technical project evidence
Consistent employer information

Potential review signals:

Major unexplained timeline conflicts
Contradictory public profiles
Implausible technology timelines
Repeated identical content across unrelated profiles
Significant inconsistencies between resume and public professional information

These are signals for further verification, not automatic proof of fraud.

59. Duplicate Resume Detection

Search engines may surface the same resume multiple times.

Potential indicators:

Same name
Same employers
Same project descriptions
Same education
Same contact information
Same formatting
Same summary

Do not count duplicate copies as separate candidates.

60. Resume Version Detection

Candidates may have multiple versions:

Resume_John_Doe.pdf
John_Doe_Resume.pdf
JohnDoe_CV.pdf
John_Doe_Java.pdf
John_Doe_Updated.pdf

The newest or most complete version should be evaluated when identifiable.

Do not assume filename chronology is definitive.

61. Search by Resume Filename

Sometimes filenames contain useful signals.

Examples:

"Java Developer" filetype:pdf
"Software Engineer Resume" filetype:pdf
"John Doe Resume" filetype:pdf

Filename signals should supplement—not replace—content-based searching.

62. Search by Professional Summary

Common phrases:

professional summary
summary
career summary
profile summary
professional profile

Example:

"professional summary" "Java Developer" filetype:pdf
63. Search by Technical Skills

Example:

"technical skills"
Java
"Spring Boot"
filetype:pdf

Another:

"technical skills"
Python
AWS
filetype:pdf
64. Search by Professional Experience
"professional experience"
"Java Developer"
filetype:pdf

This can increase the likelihood that results are actual career documents.

65. Search by Education
"education"
"Computer Science"
"Software Engineer"
filetype:pdf
66. Search by Certifications
"certifications"
AWS
"Software Engineer"
filetype:pdf
67. Search by Projects
"projects"
Python
AWS
"Software Engineer"
filetype:pdf
68. Search by Employer + Technology
"Java Developer"
"Spring Boot"
"Company Name"
filetype:pdf

This is useful when building a target-company talent map.

69. Target Company Talent Mapping

A recruiter can create:

TARGET COMPANY
      │
      ├── Current / Former Employees
      │
      ├── Target Technologies
      │
      ├── Job Titles
      │
      ├── Geographic Market
      │
      └── Public Professional Signals

Example:

"Software Engineer"
Java
"Company Name"
Michigan
filetype:pdf
70. Search by Industry + Technology
"Java Developer"
Automotive
"Spring Boot"
filetype:pdf

Another:

"Data Engineer"
Banking
Python
AWS
filetype:pdf
71. Search by Multiple Locations
"Java Developer"
("Detroit" OR "Chicago" OR "Dallas")
"Spring Boot"
filetype:pdf

Keep geographic groups manageable.

Very large OR groups can make searches harder to analyze.

72. Search by Multiple Titles
("Java Developer" OR
 "Java Engineer" OR
 "Java Software Engineer")
"Spring Boot"
filetype:pdf
73. Search by Multiple Technologies
Java
("Spring Boot" OR Spring)
(Microservices OR "Micro Services")
filetype:pdf
74. Search by Skill Families

Instead of:

"React.js"

consider:

(React OR "React.js" OR ReactJS)

Instead of:

Node.js

consider:

(Node OR "Node.js" OR NodeJS)
75. The Resume X-Ray Query Ladder

Start broad:

"Java Developer" filetype:pdf

Then add technology:

"Java Developer" "Spring Boot" filetype:pdf

Then location:

"Java Developer" "Spring Boot" Michigan filetype:pdf

Then supporting technology:

"Java Developer" "Spring Boot" Microservices Michigan filetype:pdf

Then employer or industry:

"Java Developer" "Spring Boot" Microservices Michigan Automotive filetype:pdf

Stop adding constraints when result quality is sufficient.

76. Search Query Debugging

If results are poor, ask:

Problem

Too many results?

Solution

Add:

Job title
Location
Technology
Industry
Employer
Resume signal
Problem

Too few results?

Solution

Remove:

One technology
Exact location
Experience requirement
Industry
Employer
Resume-specific phrase
77. Search Noise Categories

Common noise:

Job postings
Training courses
Tutorials
Certification pages
Technology documentation
News articles
University courses
Recruiting advertisements
Staffing advertisements
Generic PDFs
Conference documents

Use exclusions where appropriate.

Example:

"Java Developer"
"Spring Boot"
filetype:pdf
-jobs
-course
-tutorial
78. Don't Over-Exclude

A recruiter can accidentally remove qualified resumes.

For example:

-java

would obviously destroy a Java search.

More subtle exclusions can also remove useful documents.

Use exclusions only when a recurring noise pattern has been observed.

79. Search Engine Comparison

Different search engines may return different indexed results.

A practical workflow:

GOOGLE
   ↓
BING
   ↓
DUCKDUCKGO
   ↓
COMPARE
   ↓
DEDUPLICATE
   ↓
VALIDATE

The objective is to expand discovery rather than repeatedly searching identical queries.

80. Google → Bing → DuckDuckGo Workflow

Example base query:

"Java Developer"
"Spring Boot"
Michigan
filetype:pdf

Run the concept across:

Google
Bing
DuckDuckGo

Record useful results.

Then deduplicate candidates.

81. Resume X-Ray Search Matrix
Dimension	Examples
Job Title	Java Developer, SDET, DevOps Engineer
Technology	Java, Python, React, AWS
Location	Michigan, Detroit, Dallas
Industry	Automotive, Banking
Employer	Target company
Experience	Senior, Lead, Architect
Education	Computer Science
Certification	AWS, PMP, CISSP
Resume Signal	Resume, CV, Experience
File Type	PDF, DOC, DOCX
Source	Public website, .edu, portfolio
82. Requisition-to-Resume Framework

Start with the requisition.

REQUISITION
     │
     ▼
MANDATORY SKILLS
     │
     ▼
PREFERRED SKILLS
     │
     ▼
TITLE VARIATIONS
     │
     ▼
TECHNOLOGY SYNONYMS
     │
     ▼
LOCATION VARIATIONS
     │
     ▼
RESUME SEARCH
83. Example: Senior Java Developer
Requirement
Senior Java Developer
Spring Boot
Microservices
AWS
Michigan
Query 1
"Senior Java Developer" "Spring Boot" filetype:pdf
Query 2
("Senior Java Developer" OR
 "Senior Java Engineer" OR
 "Java Software Engineer")
"Spring Boot"
filetype:pdf
Query 3
("Senior Java Developer" OR
 "Senior Java Engineer" OR
 "Java Software Engineer")
"Spring Boot"
Microservices
Michigan
filetype:pdf
Query 4
("Senior Java Developer" OR
 "Senior Java Engineer" OR
 "Java Software Engineer")
"Spring Boot"
Microservices
(AWS OR "Amazon Web Services")
Michigan
filetype:pdf
84. Example: React Developer
("React Developer" OR
 "React Engineer" OR
 "Frontend Developer")
(React OR "React.js" OR ReactJS)
JavaScript
filetype:pdf

Add location:

("React Developer" OR
 "React Engineer" OR
 "Frontend Developer")
(React OR "React.js" OR ReactJS)
JavaScript
Michigan
filetype:pdf
85. Example: Python Full Stack
("Full Stack Developer" OR
 "Full Stack Engineer")
Python
(React OR Angular)
(Django OR Flask OR FastAPI)
filetype:pdf
86. Example: QA Automation
("QA Automation Engineer" OR
 "SDET" OR
 "Automation Engineer")
(Selenium OR Cypress OR Playwright)
(Java OR Python)
filetype:pdf
87. Example: DevOps
("DevOps Engineer" OR
 "Cloud Engineer")
(AWS OR Azure OR GCP)
(Docker OR Kubernetes)
(Terraform OR Jenkins)
filetype:pdf
88. Example: Data Engineer
("Data Engineer" OR
 "ETL Developer" OR
 "Big Data Engineer")
Python
(Spark OR PySpark)
(SQL)
filetype:pdf
89. Example: Cybersecurity
("Cybersecurity Engineer" OR
 "Security Engineer" OR
 "Security Analyst")
(Splunk OR SIEM OR SOC)
filetype:pdf
90. Example: AI / ML
("AI Engineer" OR
 "Machine Learning Engineer" OR
 "ML Engineer")
Python
(TensorFlow OR PyTorch)
filetype:pdf
91. Example: GenAI
("AI Engineer" OR
 "Generative AI Engineer" OR
 "Machine Learning Engineer")
(Python)
(LLM OR RAG OR "Large Language Model")
filetype:pdf
92. Resume X-Ray for Passive Candidates

Public resumes do not automatically indicate:

Actively looking
Open to work
Available immediately
Interested in your position
Authorized to work
Willing to relocate

Therefore:

A public resume is a sourcing signal, not a statement of candidate availability.

The recruiter must qualify these points through appropriate recruiting processes.

93. Resume X-Ray and Work Authorization

Do not infer work authorization from:

Name
Location
School
Nationality
Language
Photo
Resume formatting

Work authorization should be discussed and verified through appropriate lawful hiring processes.

Avoid making assumptions based on personal characteristics.

94. Resume X-Ray and Candidate Privacy

Use publicly available professional information responsibly.

Do not:

Attempt to access private accounts
Bypass authentication
Circumvent access controls
Scrape restricted systems
Collect unnecessary sensitive information
Store unrelated personal information
Misrepresent your identity to obtain restricted information

Focus on legitimate professional sourcing.

95. Resume X-Ray and Search Engine Terms

Search-engine behavior changes over time.

Operators may:

change behavior
return different results
interpret syntax differently
ignore unsupported combinations
personalize results
alter indexing

Therefore:

Treat search operators as tools to test, not permanent guarantees.

96. Search Results Are Not Candidate Truth

A search result is only a discovery signal.

SEARCH RESULT
      ↓
DOCUMENT
      ↓
CANDIDATE IDENTIFICATION
      ↓
PUBLIC SIGNAL CORRELATION
      ↓
QUALIFICATION
      ↓
OUTREACH

Do not skip the validation stages.

97. Resume X-Ray Candidate Workflow
1. Receive requisition
2. Extract mandatory skills
3. Extract preferred skills
4. Build title families
5. Build technology families
6. Build location families
7. Create initial query
8. Run Google
9. Run Bing
10. Run DuckDuckGo
11. Collect relevant results
12. Remove obvious noise
13. Deduplicate candidates
14. Validate professional signals
15. Compare against requisition
16. Contact qualified candidates
17. Record sourcing source
18. Track response
98. Search Result Qualification

Use a simple framework:

Signal	Question
Title	Does the candidate perform the target function?
Technology	Are mandatory technologies present?
Experience	Is the experience level appropriate?
Location	Does geography align?
Industry	Is relevant domain experience present?
Recency	Is the technical experience reasonably current?
Consistency	Do public signals broadly align?
Relevance	Does the profile justify outreach?
99. Resume X-Ray Scorecard

Example:

TECHNOLOGY MATCH      0–30
JOB TITLE MATCH       0–20
EXPERIENCE MATCH      0–15
LOCATION MATCH        0–10
INDUSTRY MATCH        0–10
PROJECT MATCH         0–10
OTHER SIGNALS         0–05
----------------------------
TOTAL                 100

This is a sourcing prioritization framework—not an objective measure of candidate quality.

100. Search Optimization Rules
Rule 1

Start with the core requirement.

Rule 2

Use title alternatives.

Rule 3

Use technology synonyms.

Rule 4

Add location only when useful.

Rule 5

Use filetype:pdf for PDF discovery.

Rule 6

Use exclusions only after observing noise.

Rule 7

Do not over-constrain the query.

Rule 8

Compare multiple search engines.

Rule 9

Deduplicate results.

Rule 10

Validate before outreach.

101. Advanced Search Construction

General framework:

(
  "TITLE 1"
  OR
  "TITLE 2"
  OR
  "TITLE 3"
)
AND
(
  TECHNOLOGY 1
  OR
  TECHNOLOGY 2
)
AND
(
  LOCATION 1
  OR
  LOCATION 2
)
filetype:pdf

Remember that search engines may interpret Boolean syntax differently.

Test the actual query.

102. Resume Search Template
("JOB TITLE 1" OR "JOB TITLE 2" OR "JOB TITLE 3")
("TECHNOLOGY 1" OR "TECHNOLOGY 2")
"LOCATION"
filetype:pdf
103. Technical Resume Template
("JOB TITLE")
("MANDATORY TECHNOLOGY 1" OR "MANDATORY TECHNOLOGY 2")
("SUPPORTING TECHNOLOGY 1" OR "SUPPORTING TECHNOLOGY 2")
filetype:pdf
104. Geographic Resume Template
("JOB TITLE 1" OR "JOB TITLE 2")
TECHNOLOGY
("CITY" OR "STATE" OR "METRO")
filetype:pdf
105. Employer Resume Template
("JOB TITLE")
TECHNOLOGY
"TARGET COMPANY"
filetype:pdf
106. Industry Resume Template
("JOB TITLE")
TECHNOLOGY
("INDUSTRY 1" OR "INDUSTRY 2")
filetype:pdf
107. Certification Resume Template
("JOB TITLE")
TECHNOLOGY
("CERTIFICATION")
filetype:pdf
108. Education Resume Template
("JOB TITLE")
TECHNOLOGY
("Computer Science" OR "Information Technology")
filetype:pdf
109. Search Funnel

Use a funnel rather than a single massive query.

                 ALL PUBLIC DOCUMENTS
                         │
                         ▼
                    RESUME SIGNAL
                         │
                         ▼
                    JOB TITLE
                         │
                         ▼
                    TECHNOLOGY
                         │
                         ▼
                     LOCATION
                         │
                         ▼
                     INDUSTRY
                         │
                         ▼
                 QUALIFIED RESULTS
110. Search Funnel Example
Stage 1
Java filetype:pdf
Stage 2
"Java Developer" filetype:pdf
Stage 3
"Java Developer" "Spring Boot" filetype:pdf
Stage 4
"Java Developer" "Spring Boot" Michigan filetype:pdf
Stage 5
"Java Developer" "Spring Boot" Microservices Michigan filetype:pdf
111. When to Stop Searching

Do not search indefinitely.

Stop expanding when:

Relevant candidate pool
+
Reasonable diversity
+
Acceptable quality
+
Sufficient sourcing coverage

has been achieved.

Then move from discovery to qualification.

112. Sourcing Diversity

A healthy sourcing strategy can combine:

ATS
LinkedIn
Google X-Ray
Bing X-Ray
DuckDuckGo
GitHub
Public resumes
Portfolios
Technical communities
Job boards
Professional networks
Referrals

Resume X-Ray is one component of the larger sourcing ecosystem.

113. Resume X-Ray vs LinkedIn X-Ray
Resume X-Ray	LinkedIn X-Ray
Targets documents	Targets public profiles
Often uses filetype:	Often uses site:
Strong for PDF discovery	Strong for profile discovery
Resume-focused	Profile-focused
May reveal older documents	May reveal current public profile
Requires document validation	Requires profile validation

Use both when appropriate.

114. Resume X-Ray vs GitHub X-Ray
Resume X-Ray	GitHub X-Ray
Career document	Technical activity
Experience history	Code/project evidence
Skills section	Repository evidence
Education	Technical contribution
Certifications	Open-source signals

The strongest sourcing workflow can correlate both.

115. Resume X-Ray Research Stack
             REQUISITION
                  │
                  ▼
          BOOLEAN BUILDER
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
      GOOGLE     BING    DUCKDUCKGO
        │         │         │
        └─────────┼─────────┘
                  ▼
            RESUME RESULTS
                  │
                  ▼
             DEDUPLICATE
                  │
                  ▼
          PROFILE CORRELATION
                  │
          ┌───────┼────────┐
          ▼       ▼        ▼
      LINKEDIN  GITHUB  PORTFOLIO
          │       │        │
          └───────┼────────┘
                  ▼
            QUALIFICATION
                  │
                  ▼
              OUTREACH
116. Advanced Recruiter Technique: Query Mutation

Do not simply edit the same query.

Create mutations.

Mutation A — Title
"Java Developer"
Mutation B — Technology
"Java Developer" "Spring Boot"
Mutation C — Synonym
("Java Developer" OR "Java Engineer") "Spring Boot"
Mutation D — Location
("Java Developer" OR "Java Engineer") "Spring Boot" Michigan
Mutation E — Document
("Java Developer" OR "Java Engineer") "Spring Boot" Michigan filetype:pdf
117. Search Experimentation

Maintain a simple search log.

QUERY
RESULT QUALITY
NOISE
USEFUL SIGNALS
NEXT CHANGE

Example:

Query:
"Java Developer" filetype:pdf


Quality:
Low


Noise:
Training PDFs


Next:
Add Spring Boot + resume
118. Search Log Template
Date:
Requisition:
Role:
Search Engine:
Query:
Approximate Result Quality:
Relevant Results:
Noise:
Changes Made:
Final Query:
Candidates Identified:
119. Recruiter Search Library

Build reusable query components.

Title library
Java Developer
Java Engineer
Java Software Engineer
Backend Engineer
Full Stack Developer
Technology library
Java
Spring Boot
Microservices
AWS
Docker
Kubernetes
Location library
Michigan
Detroit
Chicago
Dallas
Atlanta
Charlotte

Then combine them.

120. Reusable Search Blocks
TITLE BLOCK
("Java Developer" OR "Java Engineer" OR "Java Software Engineer")
TECHNOLOGY BLOCK
("Spring Boot" OR Spring) (Microservices OR "Micro Services")
CLOUD BLOCK
(AWS OR "Amazon Web Services")
LOCATION BLOCK
(Michigan OR Detroit OR "Metro Detroit")
DOCUMENT BLOCK
filetype:pdf

Combined:

("Java Developer" OR "Java Engineer" OR "Java Software Engineer")
("Spring Boot" OR Spring)
(Microservices OR "Micro Services")
(AWS OR "Amazon Web Services")
(Michigan OR Detroit OR "Metro Detroit")
filetype:pdf
121. Search Precision Checklist

Before running a search:

☐ Is the job title correct?
☐ Did I include title alternatives?
☐ Did I identify mandatory technologies?
☐ Did I identify technology synonyms?
☐ Did I identify location variants?
☐ Do I need industry targeting?
☐ Do I need employer targeting?
☐ Should I use filetype:pdf?
☐ Am I over-constraining?
☐ Am I excluding unnecessary noise?
122. Search Recall Checklist

If results are too limited:

☐ Remove one technology
☐ Remove exact location
☐ Add title synonyms
☐ Add technology synonyms
☐ Remove experience wording
☐ Remove industry
☐ Try another search engine
☐ Search without filetype
☐ Search broader geography
123. Search Precision Checklist

If results are too broad:

☐ Add mandatory technology
☐ Add job title
☐ Add location
☐ Add industry
☐ Add employer
☐ Add resume terminology
☐ Add filetype:pdf
☐ Add targeted exclusions
124. Common Recruiter Mistakes
Mistake 1

Using only one job title.

Mistake 2

Using only one technology name.

Mistake 3

Adding every JD keyword.

Mistake 4

Using an enormous Boolean string.

Mistake 5

Ignoring location variations.

Mistake 6

Assuming every PDF is a resume.

Mistake 7

Treating search results as verified candidate information.

Mistake 8

Ignoring duplicate resumes.

Mistake 9

Failing to validate professional identity.

Mistake 10

Assuming public information means candidate availability.

125. The "Don't Build Monster Queries" Rule

A query like this can become counterproductive:

("Title A" OR "Title B" OR "Title C" OR "Title D")
("Skill A" OR "Skill B" OR "Skill C" OR "Skill D")
("Skill E" OR "Skill F" OR "Skill G")
("City A" OR "City B" OR "City C")
("Industry A" OR "Industry B")
("Certification A" OR "Certification B")
filetype:pdf

Instead:

BUILD
↓
TEST
↓
MEASURE
↓
REFINE
126. Query Layering Strategy

Use mandatory requirements first.

MANDATORY
    ↓
HIGH-VALUE PREFERRED
    ↓
LOCATION
    ↓
INDUSTRY
    ↓
NICE-TO-HAVE

Do not make every nice-to-have mandatory.

127. Requisition Decomposition

Example:

ROLE:
Senior Java Developer


MANDATORY:
Java
Spring Boot
Microservices


PREFERRED:
AWS
Kubernetes


LOCATION:
Michigan


INDUSTRY:
Automotive

Initial query:

("Senior Java Developer" OR
 "Senior Java Engineer" OR
 "Java Software Engineer")
"Spring Boot"
Microservices
Michigan
filetype:pdf

Then introduce preferred skills.

128. Public Resume Discovery Workflow
RESEARCH
   ↓
DISCOVER
   ↓
FILTER
   ↓
VALIDATE
   ↓
QUALIFY
   ↓
CONTACT

This keeps search and candidate evaluation separate.

129. Ethical Resume Sourcing

Use public professional information for legitimate recruiting purposes.

Do not:

Bypass login systems
Circumvent privacy controls
Access private documents
Use leaked databases
Purchase unauthorized personal information
Attempt to defeat technical restrictions

Respect:

Privacy
Terms of Service
Applicable law
Employer policies
Candidate expectations
Data minimization
130. Candidate Data Minimization

Collect only information necessary for the recruiting workflow.

Prefer:

Name
Professional profile
Relevant experience
Relevant technical skills
Professional location
Public professional links

Avoid unnecessary collection of unrelated personal information.

131. Resume X-Ray + AI

AI can assist with:

JD decomposition
Skill extraction
Title synonym generation
Technology synonym generation
Boolean drafting
Search mutation
Resume summarization
Candidate comparison
Search-quality analysis

AI should not replace recruiter validation.

132. AI Search Prompt Framework

Example:

Analyze this job description.


Extract:


1. Mandatory technical skills
2. Preferred technical skills
3. Job title variants
4. Technology synonyms
5. Location variants
6. Industry keywords
7. Certification keywords
8. Resume-specific search terms


Then generate:
- Broad Resume X-Ray
- Balanced Resume X-Ray
- Narrow Resume X-Ray
133. Search Quality Model

Think of search quality as:

SEARCH QUALITY
=
RELEVANCE
+
COVERAGE
+
SIGNAL QUALITY
-
NOISE

A large result count is not automatically a successful search.

134. Resume X-Ray Maturity Model
Level 1 — Beginner

Uses:

job title
filetype:pdf
Level 2 — Intermediate

Adds:

technology
location
Boolean
Level 3 — Advanced

Adds:

synonyms
industry
employer
search mutations
Level 4 — Strategic

Uses:

multi-engine sourcing
candidate signal correlation
talent mapping
search analytics
Level 5 — Expert

Builds:

repeatable sourcing systems
query libraries
search frameworks
market maps
AI-assisted workflows
135. Resume X-Ray Master Framework
                  REQUISITION
                       │
                       ▼
              REQUIREMENT EXTRACTION
                       │
                       ▼
                TITLE FAMILIES
                       │
                       ▼
             TECHNOLOGY FAMILIES
                       │
                       ▼
               LOCATION FAMILIES
                       │
                       ▼
                SEARCH BUILD
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
       GOOGLE         BING       DUCKDUCKGO
          │            │            │
          └────────────┼────────────┘
                       ▼
                RESUME DISCOVERY
                       │
                       ▼
                  DEDUPLICATION
                       │
                       ▼
               SIGNAL CORRELATION
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
      LINKEDIN       GITHUB      PORTFOLIO
          │            │            │
          └────────────┼────────────┘
                       ▼
                  QUALIFICATION
                       │
                       ▼
                    OUTREACH
                       │
                       ▼
                  ATS / CRM
136. Master Resume X-Ray Template

Copy and adapt:

(
  "JOB TITLE 1"
  OR
  "JOB TITLE 2"
  OR
  "JOB TITLE 3"
)
(
  "MANDATORY TECHNOLOGY 1"
  OR
  "MANDATORY TECHNOLOGY 2"
)
(
  "SUPPORTING TECHNOLOGY 1"
  OR
  "SUPPORTING TECHNOLOGY 2"
)
LOCATION
filetype:pdf
137. Broad Search Template
"JOB TITLE" TECHNOLOGY filetype:pdf
138. Balanced Search Template
("JOB TITLE 1" OR "JOB TITLE 2")
("TECHNOLOGY 1" OR "TECHNOLOGY 2")
LOCATION
filetype:pdf
139. Narrow Search Template
("JOB TITLE 1" OR "JOB TITLE 2")
("MANDATORY TECHNOLOGY 1" OR "MANDATORY TECHNOLOGY 2")
"LOCATION"
"INDUSTRY"
filetype:pdf
140. Talent Mapping Template
"TARGET COMPANY"
("JOB TITLE 1" OR "JOB TITLE 2")
TECHNOLOGY
LOCATION
filetype:pdf
141. Resume Discovery Decision Tree
START
  │
  ▼
Do I know the target title?
  │
  ├── YES ──► Add title
  │
  └── NO ───► Derive title family
                  │
                  ▼
          Do I know mandatory skills?
                  │
                  ├── YES ──► Add skills
                  │
                  └── NO ───► Extract from JD
                                  │
                                  ▼
                          Do I need geography?
                                  │
                                  ├── YES ──► Add location
                                  │
                                  └── NO
                                  │
                                  ▼
                           Add filetype:pdf
                                  │
                                  ▼
                              SEARCH
                                  │
                                  ▼
                          REVIEW RESULTS
                                  │
                                  ▼
                        TOO MANY RESULTS?
                           /          \
                         YES           NO
                         │              │
                         ▼              ▼
                    ADD SIGNAL      TOO FEW?
                                      │
                                      ▼
                                REMOVE CONSTRAINT
                                      │
                                      ▼
                                   SEARCH
142. Recruiter Operating Principle

Search broadly enough to discover the market, then narrow intelligently enough to identify the right candidates.

Do not confuse search complexity with search quality.

143. Final Resume X-Ray Checklist
☐ Requisition analyzed
☐ Mandatory skills identified
☐ Preferred skills identified
☐ Job-title family created
☐ Technology synonyms created
☐ Location variants created
☐ Initial query created
☐ Google tested
☐ Bing tested
☐ DuckDuckGo tested
☐ PDF targeting tested
☐ Search noise reviewed
☐ Query refined
☐ Duplicate results removed
☐ Candidate signals reviewed
☐ Relevant professional information validated
☐ Candidate qualified
☐ Outreach appropriate
☐ Source recorded
144. Quick Reference
Core Operators
filetype:pdf
site:
intitle:
inurl:
"exact phrase"
OR
-
Core Resume Signals
resume
CV
curriculum vitae
professional summary
professional experience
technical skills
education
certifications
projects
work history
Core Recruiting Dimensions
TITLE
SKILLS
TECHNOLOGY
LOCATION
INDUSTRY
EMPLOYER
EXPERIENCE
CERTIFICATION
EDUCATION
145. 30-Second Resume X-Ray

When time is limited:

1. Identify title
2. Identify 2–3 mandatory technologies
3. Add location
4. Add filetype:pdf
5. Search
6. Review first results
7. Remove noise
8. Expand synonyms
9. Validate candidates

Example:

"Senior Java Developer"
"Spring Boot"
Microservices
Michigan
filetype:pdf
146. 5-Minute Recruiter Workflow
MINUTE 1
Extract JD requirements


MINUTE 2
Build title + technology groups


MINUTE 3
Run Google / Bing / DuckDuckGo


MINUTE 4
Review and deduplicate


MINUTE 5
Prioritize candidates for qualification
147. Resume X-Ray Golden Rules
Rule #1

Do not search only by job title.

Rule #2

Do not depend on one technology spelling.

Rule #3

Do not make every JD keyword mandatory.

Rule #4

Do not assume every PDF is a resume.

Rule #5

Do not treat public information as verified information.

Rule #6

Do not assume a public resume means the candidate is available.

Rule #7

Do not use sensitive personal characteristics as sourcing filters.

Rule #8

Do not bypass privacy or access controls.

Rule #9

Do not stop at the first search query.

Rule #10

Build a repeatable search system.

148. Resume X-Ray Master Equation
RELEVANT CANDIDATES
=
TITLE MATCH
+
TECHNOLOGY MATCH
+
EXPERIENCE SIGNAL
+
LOCATION SIGNAL
+
INDUSTRY SIGNAL
+
PUBLIC PROFESSIONAL SIGNALS
-
SEARCH NOISE
149. From Search to Sourcing Intelligence

The long-term objective is not simply:

Find resumes

It is:

DISCOVER
      ↓
UNDERSTAND
      ↓
MAP
      ↓
QUALIFY
      ↓
ENGAGE
      ↓
LEARN
      ↓
IMPROVE SEARCH

Every sourcing project should improve the recruiter's future search capability.

150. Final Framework
                    RESUME X-RAY MASTER
                           │
                           ▼
                    REQUISITION
                           │
                           ▼
                 REQUIREMENT EXTRACTION
                           │
                           ▼
               ┌───────────────────────┐
               │ TITLE + SKILL + GEO   │
               └───────────┬───────────┘
                           │
                           ▼
                    BOOLEAN LOGIC
                           │
                           ▼
                    FILE TARGETING
                           │
                           ▼
              ┌────────────┼────────────┐
              ▼            ▼            ▼
           GOOGLE         BING       DUCKDUCKGO
              │            │            │
              └────────────┼────────────┘
                           ▼
                    PUBLIC RESUMES
                           │
                           ▼
                     DEDUPLICATE
                           │
                           ▼
                   SIGNAL CORRELATION
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
          LINKEDIN       GITHUB      PORTFOLIO
              │            │            │
              └────────────┼────────────┘
                           ▼
                     QUALIFICATION
                           │
                           ▼
                        OUTREACH
                           │
                           ▼
                     SOURCING DATA
                           │
                           ▼
                   SEARCH IMPROVEMENT
🚀 Module Outcome

After completing this module, a recruiter should be able to:

Build resume-focused X-Ray searches
Use filetype:pdf
Identify resume-specific search signals
Build title synonym groups
Build technology synonym groups
Target geographic markets
Search public professional documents
Reduce irrelevant PDF results
Run searches across multiple engines
Correlate resumes with professional profiles
Identify duplicate documents
Build repeatable sourcing queries
Optimize search precision and recall
Create talent maps
Integrate Resume X-Ray into a broader sourcing workflow
🔗 Continue the X-Ray Search Master Series
Module	Topic
01	Fundamentals
02	Boolean Search
03	Google X-Ray
04	Bing X-Ray
05	DuckDuckGo
06	LinkedIn X-Ray
07	GitHub X-Ray
08	Resume X-Ray
09	Portfolio X-Ray
10	Stack Overflow / Technical Communities
11	Job Board X-Ray
12	Company / Talent Mapping
13	Advanced Search Operators
14	Search Engine Comparison
15	Recruiter X-Ray Master Framework
⚠️ Responsible Sourcing Notice

This repository is intended for legitimate professional recruiting, sourcing education, research, and talent-discovery workflows.

Use public information responsibly and in accordance with:

Applicable laws and regulations
Search-engine terms
Website terms of service
Privacy requirements
Employer policies
Candidate expectations
Data-minimization principles

Do not use search techniques to bypass authentication, access private information, circumvent technical restrictions, or collect unnecessary sensitive personal information.

🧠 Core Principle

The best X-Ray recruiter is not the recruiter with the biggest Boolean string.

The best X-Ray recruiter is the recruiter who can understand the talent market, construct the right search, evaluate the results, refine the query, and turn search signals into qualified recruiting conversations.
