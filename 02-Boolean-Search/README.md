# 🧩 Boolean Search for Recruiters

> A practical Boolean Search handbook for US IT recruiting, technical sourcing, passive candidate discovery, and search optimization.

Boolean Search is one of the most important skills in technical sourcing.

A strong recruiter does not simply copy a large Boolean string.

A strong recruiter understands:

```text
WHAT TO SEARCH
      +
HOW TO GROUP TERMS
      +
WHAT TO MAKE MANDATORY
      +
WHAT TO MAKE OPTIONAL
      +
WHAT TO EXCLUDE
      +
WHEN TO BROADEN
      +
WHEN TO NARROW
```

---

# 📚 Module Navigation

| Section | Topic                     |
| ------- | ------------------------- |
| 1       | What Is Boolean Search?   |
| 2       | Boolean Operators         |
| 3       | AND                       |
| 4       | OR                        |
| 5       | NOT                       |
| 6       | Exact Phrases             |
| 7       | Parentheses               |
| 8       | Exclusions                |
| 9       | Title Clusters            |
| 10      | Technology Clusters       |
| 11      | Location Clusters         |
| 12      | Company Clusters          |
| 13      | Domain Clusters           |
| 14      | Boolean Architecture      |
| 15      | Beginner Searches         |
| 16      | Intermediate Searches     |
| 17      | Advanced Searches         |
| 18      | Broadening Searches       |
| 19      | Narrowing Searches        |
| 20      | Precision vs Recall       |
| 21      | Common Mistakes           |
| 22      | Troubleshooting           |
| 23      | US IT Recruiting Examples |
| 24      | JD → Boolean Conversion   |
| 25      | Search Optimization       |
| 26      | Validation                |
| 27      | Boolean Quality Checklist |
| 28      | Final Framework           |

---

# 1. What Is Boolean Search?

Boolean Search is a method of combining search concepts using logical operators.

The core operators are:

```text
AND
OR
NOT
```

Recruiters commonly combine these with:

```text
"Exact Phrases"
(Parentheses)
-Exclusions
```

A basic Boolean search might look like:

```text
Java AND AWS
```

A more advanced search might look like:

```text
("Java Developer" OR "Java Engineer")
AND
("Spring Boot" OR Spring)
AND
(AWS OR "Amazon Web Services")
```

The objective is to describe the candidate population you want to discover.

---

# 2. Why Boolean Search Matters

Technical recruiting often involves terminology variation.

One candidate may write:

```text
Java Developer
```

Another may write:

```text
Java Engineer
```

Another:

```text
Java Software Engineer
```

Another:

```text
Backend Engineer
```

Similarly, a technology may appear as:

```text
JavaScript
JS
ECMAScript
```

Boolean logic lets recruiters combine these variations into structured searches.

---

# 3. Boolean Search vs X-Ray Search

These are related but not identical.

## Boolean Search

Boolean Search describes how search terms are logically combined.

Example:

```text
("Java Developer" OR "Java Engineer")
AND
AWS
```

## X-Ray Search

X-Ray Search uses a search engine to target a particular public source.

Example:

```text
site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
AWS
```

The second search combines:

```text
X-Ray
+
Boolean
```

This distinction is important.

```text
BOOLEAN
=
SEARCH LOGIC

X-RAY
=
SOURCE TARGETING
```

---

# 4. AND Operator

`AND` represents a combination of required concepts.

Example:

```text
Java AND AWS
```

Conceptually:

```text
Java
  +
AWS
```

A recruiter searching for a Java professional with AWS exposure might use:

```text
"Java Developer" AND AWS
```

Adding another requirement:

```text
"Java Developer"
AND
AWS
AND
"Spring Boot"
```

The more mandatory concepts you add, the narrower the search can become.

---

# 5. OR Operator

`OR` represents alternatives.

Example:

```text
Java OR J2EE
```

Title example:

```text
"Java Developer"
OR
"Java Engineer"
```

Grouped:

```text
("Java Developer" OR "Java Engineer")
```

Technology example:

```text
("Spring Boot" OR Spring)
```

Location example:

```text
(Detroit OR Michigan OR MI)
```

`OR` is particularly useful for expanding candidate discovery.

---

# 6. NOT Operator

`NOT` represents exclusion in Boolean systems that support it.

Example:

```text
Java NOT Android
```

However, search-engine syntax varies.

For general web search, an exclusion is often expressed using a minus sign:

```text
Java -Android
```

Always verify the behavior of the specific search engine or platform.

Do not assume every recruiting platform interprets Boolean operators identically.

---

# 7. Exact Phrase Search

Quotation marks are used to preserve a phrase.

Example:

```text
"Senior Java Developer"
```

Instead of searching each word independently, the quoted expression represents the phrase as a unit.

Useful examples:

```text
"Spring Boot"
"Machine Learning Engineer"
"Solutions Architect"
"Technical Project Manager"
"Data Scientist"
```

Exact phrases are useful for:

* Titles
* Certifications
* Frameworks
* Product names
* Technologies
* Organizations
* Project names

---

# 8. Parentheses

Parentheses are one of the most important tools for building complex Boolean searches.

Example:

```text
("Java Developer" OR "Java Engineer")
AND
("Spring Boot" OR Spring)
```

The parentheses group alternatives together.

Without grouping, complex queries can behave differently from what the recruiter intended.

Think of parentheses as creating logical blocks:

```text
TITLE BLOCK
     +
SKILL BLOCK
     +
LOCATION BLOCK
```

---

# 9. Title Cluster

A title cluster contains alternative titles for the same recruiting objective.

Example:

```text
("Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer"
OR "Backend Developer")
```

This can increase recall.

### Important

Do not assume every title is perfectly equivalent.

For example:

```text
Backend Engineer
```

may cover a broader population than:

```text
Java Developer
```

Use title expansion strategically.

---

# 10. Technology Cluster

A technology cluster groups terms associated with a technical requirement.

Example:

```text
(Java
OR J2EE
OR "Java EE")
```

Framework cluster:

```text
("Spring Boot"
OR Spring)
```

Cloud cluster:

```text
(AWS
OR "Amazon Web Services")
```

Container cluster:

```text
(Kubernetes
OR K8s)
```

Technology groups must be technically reviewed before being used.

Related technologies should not automatically be presented as synonyms.

---

# 11. Location Cluster

Location can also be represented as a Boolean group.

Example:

```text
(Detroit OR "Detroit, MI" OR Michigan OR MI)
```

Another example:

```text
(Dallas OR "Dallas, TX" OR Texas OR TX)
```

For a broader market:

```text
(Michigan OR MI)
```

For a city-specific requirement:

```text
("Detroit, MI" OR Detroit)
```

Location expansion should reflect the actual recruiting requirement.

---

# 12. Company Cluster

Company targeting can be represented using:

```text
("Company A"
OR "Company B"
OR "Company C")
```

Example:

```text
("Ford"
OR "General Motors"
OR "Stellantis")
```

This can be useful when targeting a specific industry or talent market.

However, a company keyword appearing in a profile does not automatically prove current employment.

---

# 13. Domain Cluster

Domain keywords can help distinguish candidates from unrelated professionals.

Example:

```text
(Automotive OR "Automotive Industry")
```

Banking:

```text
(Banking OR "Financial Services" OR FinTech)
```

Healthcare:

```text
(Healthcare OR HealthTech)
```

Manufacturing:

```text
(Manufacturing OR Industrial)
```

Domain terms should be selected based on the actual requirement.

---

# 14. Skill Cluster

A skill cluster combines technical requirements.

Example:

```text
(Java
AND "Spring Boot"
AND Microservices)
```

A broader variation:

```text
(Java
AND ("Spring Boot" OR Spring)
AND (Microservices OR "Micro Services"))
```

The second query introduces alternatives.

---

# 15. Boolean Architecture

A recruiter-grade Boolean search can be constructed using:

```text
TITLE
+
CORE TECHNOLOGY
+
SECONDARY TECHNOLOGY
+
DOMAIN
+
LOCATION
+
OPTIONAL TARGET
-
EXCLUSIONS
```

Example:

```text
("Java Developer" OR "Java Engineer")
AND
Java
AND
("Spring Boot" OR Spring)
AND
Microservices
AND
(AWS OR "Amazon Web Services")
AND
(Michigan OR MI)
```

---

# 16. The Boolean Building Blocks

A useful mental model is:

```text
┌─────────────────────────┐
│ TITLE                   │
│ Java Developer          │
│ Java Engineer           │
└────────────┬────────────┘
             │
             AND
             ▼
┌─────────────────────────┐
│ CORE TECHNOLOGY         │
│ Java                    │
└────────────┬────────────┘
             │
             AND
             ▼
┌─────────────────────────┐
│ FRAMEWORK               │
│ Spring Boot             │
└────────────┬────────────┘
             │
             AND
             ▼
┌─────────────────────────┐
│ ARCHITECTURE            │
│ Microservices           │
└────────────┬────────────┘
             │
             AND
             ▼
┌─────────────────────────┐
│ LOCATION                │
│ Michigan                │
└─────────────────────────┘
```

---

# 17. Beginner Boolean Search

Start with three components:

```text
TITLE
+
CORE SKILL
+
LOCATION
```

Example:

```text
"Java Developer" AND "Spring Boot" AND Michigan
```

Another:

```text
"Python Developer" AND Django AND Texas
```

Another:

```text
"React Developer" AND TypeScript AND Florida
```

---

# 18. Intermediate Boolean Search

Introduce title and technology alternatives.

Example:

```text
("Java Developer" OR "Java Engineer")
AND
("Spring Boot" OR Spring)
AND
(AWS OR Azure)
AND
Michigan
```

This provides greater flexibility while maintaining search structure.

---

# 19. Advanced Boolean Search

An advanced search may combine several structured groups.

Example:

```text
("Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer")
AND
(Java)
AND
("Spring Boot" OR Spring)
AND
(Microservices OR "Micro Services")
AND
(AWS OR "Amazon Web Services")
AND
(Kafka OR "Apache Kafka")
AND
(Michigan OR MI)
```

This is powerful but should not automatically be considered better.

The recruiter must evaluate whether each condition is truly necessary.

---

# 20. Broad Search Strategy

A broad search is useful when candidate supply appears limited.

Example:

```text
("Java Developer" OR "Java Engineer")
AND
Java
AND
Michigan
```

If the result set remains too small:

```text
("Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer")
AND
(Java OR J2EE OR "Java EE")
AND
(Michigan OR MI)
```

---

# 21. Narrow Search Strategy

A narrow search is useful when there is too much noise.

Start:

```text
Java Developer
```

Then:

```text
"Java Developer" "Spring Boot"
```

Then:

```text
"Java Developer"
"Spring Boot"
Microservices
AWS
```

Then potentially:

```text
site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
"Spring Boot"
Microservices
AWS
Michigan
```

Each step introduces another search dimension.

---

# 22. Search Broadening Ladder

Use this sequence when results are too limited:

```text
LEVEL 1
Exact Title
        ↓
LEVEL 2
Title Variations
        ↓
LEVEL 3
Technology Variations
        ↓
LEVEL 4
Location Variations
        ↓
LEVEL 5
Remove Non-Essential Requirements
        ↓
LEVEL 6
Search Additional Sources
```

Example:

```text
"Senior Java Developer"
```

↓

```text
("Senior Java Developer"
OR "Java Developer"
OR "Java Engineer")
```

↓

```text
("Senior Java Developer"
OR "Java Developer"
OR "Java Engineer"
OR "Backend Engineer")
AND
(Java OR J2EE)
```

---

# 23. Search Narrowing Ladder

When results are too broad:

```text
LEVEL 1
Add Core Technology
        ↓
LEVEL 2
Add Secondary Technology
        ↓
LEVEL 3
Add Location
        ↓
LEVEL 4
Add Domain
        ↓
LEVEL 5
Add Company
        ↓
LEVEL 6
Add Targeted Exclusions
```

Do not add everything at once.

Change one major dimension at a time so you can understand what improved the search.

---

# 24. Precision vs Recall

Boolean search involves a balance.

```text
HIGH RECALL
     │
     │    BROAD SEARCH
     │
     │
     ├─────────────── BALANCE
     │
     │
     │    NARROW SEARCH
     │
     ▼
HIGH PRECISION
```

### High Recall

Goal:

> Discover as many potentially relevant candidates as possible.

Strategy:

* More title variations
* More technology variations
* Broader locations
* Fewer mandatory terms

### High Precision

Goal:

> Reduce irrelevant results.

Strategy:

* Specific titles
* Specific technologies
* Specific locations
* Domain terms
* Targeted exclusions

---

# 25. Must-Have vs Nice-to-Have

One of the most important Boolean decisions is determining which requirements should be mandatory.

Suppose a JD contains:

```text
Java
Spring Boot
Microservices
AWS
Kafka
React
Docker
Kubernetes
```

The recruiter should determine:

```text
MUST HAVE
Java
Spring Boot
Microservices

IMPORTANT
AWS
Kafka

NICE TO HAVE
React
Docker
Kubernetes
```

A Boolean search should not necessarily require every technology listed in the JD.

---

# 26. Boolean Requirements Matrix

Use this framework:

| Requirement          | Search Treatment                 |
| -------------------- | -------------------------------- |
| Core role            | Required                         |
| Core technology      | Usually required                 |
| Critical framework   | Usually required                 |
| Secondary technology | Optional or grouped              |
| Domain               | Add when useful                  |
| Location             | Add according to requirement     |
| Nice-to-have skill   | Usually avoid making mandatory   |
| Ambiguous keyword    | Review first                     |
| Exclusion            | Add only when noise justifies it |

---

# 27. Example — Senior Java Developer

Requirement:

```text
Senior Java Developer
Detroit, MI

Java
Spring Boot
Microservices
AWS
Kafka
REST APIs
```

### Title cluster

```text
("Senior Java Developer"
OR "Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer")
```

### Core technology

```text
Java
```

### Framework

```text
("Spring Boot" OR Spring)
```

### Architecture

```text
(Microservices OR "Micro Services")
```

### Cloud

```text
(AWS OR "Amazon Web Services")
```

### Messaging

```text
(Kafka OR "Apache Kafka")
```

### Location

```text
(Detroit OR "Detroit, MI" OR Michigan OR MI)
```

---

# 28. Complete Boolean Example

```text
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
(Detroit OR "Detroit, MI" OR Michigan OR MI)
```

This is a structured search.

But the recruiter should test whether each condition improves candidate relevance.

---

# 29. Example — Python Developer

Requirement:

```text
Python
Django
REST APIs
AWS
Dallas
```

Search:

```text
("Python Developer"
OR "Python Engineer"
OR "Backend Engineer"
OR "Software Engineer")
AND
Python
AND
(Django OR "Django Framework")
AND
("REST API" OR "REST APIs" OR RESTful)
AND
(AWS OR "Amazon Web Services")
AND
(Dallas OR "Dallas, TX" OR Texas OR TX)
```

---

# 30. Example — React Developer

```text
("React Developer"
OR "React Engineer"
OR "Frontend Engineer"
OR "Frontend Developer"
OR "UI Engineer")
AND
(React OR "React.js" OR ReactJS)
AND
(JavaScript OR JS OR TypeScript)
AND
(HTML OR CSS)
AND
(Florida OR FL)
```

---

# 31. Example — Data Engineer

```text
("Data Engineer"
OR "Senior Data Engineer"
OR "Data Platform Engineer")
AND
(Python OR PySpark)
AND
(Spark OR PySpark)
AND
SQL
AND
(AWS OR Azure OR GCP)
AND
("Data Pipeline" OR ETL)
```

---

# 32. Example — DevOps Engineer

```text
("DevOps Engineer"
OR "DevOps Developer"
OR "Platform Engineer"
OR "Site Reliability Engineer"
OR SRE)
AND
(AWS OR Azure OR GCP)
AND
(Docker OR Kubernetes)
AND
(Terraform OR "Infrastructure as Code")
AND
("CI/CD" OR Jenkins OR "GitHub Actions")
```

---

# 33. Example — QA Automation Engineer

```text
("QA Automation Engineer"
OR "Automation Engineer"
OR "SDET"
OR "Test Automation Engineer")
AND
(Selenium OR Cypress OR Playwright)
AND
(Java OR Python OR JavaScript OR TypeScript)
AND
(API OR "API Testing")
```

---

# 34. Example — Cybersecurity Engineer

```text
("Cybersecurity Engineer"
OR "Security Engineer"
OR "Information Security Engineer")
AND
(Security
OR Cybersecurity)
AND
(Vulnerability OR "Vulnerability Management")
AND
(SIEM OR SOC)
```

This search should be adjusted according to the actual requirement.

---

# 35. Example — AI / GenAI Engineer

```text
("AI Engineer"
OR "Machine Learning Engineer"
OR "ML Engineer"
OR "Generative AI Engineer"
OR "GenAI Engineer")
AND
(Python)
AND
("Machine Learning" OR ML)
AND
(LLM OR "Large Language Model" OR GenAI)
AND
(RAG OR "Retrieval Augmented Generation")
```

Do not assume every AI-related technology represents the same skill set.

---

# 36. Title Stacking

Title stacking is the practice of grouping multiple relevant job titles.

Example:

```text
("Cloud Engineer"
OR "Cloud Developer"
OR "Cloud Architect"
OR "Cloud Infrastructure Engineer")
```

Use title stacking when:

* The market uses inconsistent titles
* The role has several common titles
* You are conducting a broad sourcing pass
* You want to discover passive candidates

Use fewer titles when precision is more important.

---

# 37. Technology Stacking

Technology stacking combines technical concepts.

Example:

```text
(Java
AND
"Spring Boot"
AND
Microservices
AND
Kafka)
```

This is useful for niche combinations.

For example:

```text
Java + Spring Boot + Kafka
```

can produce a more targeted population than:

```text
Java
```

alone.

---

# 38. Location Stacking

Location stacking can be used when geography has multiple representations.

Example:

```text
(Detroit OR Michigan OR MI)
```

A metro strategy might include:

```text
(Detroit
OR "Metro Detroit"
OR Michigan
OR MI)
```

The exact location terms should be based on the recruiting requirement.

---

# 39. Company Stacking

Example:

```text
("Company A"
OR "Company B"
OR "Company C")
AND
Java
AND
AWS
```

This can be useful for:

* Competitor sourcing
* Industry mapping
* Talent-pool research
* Target-company sourcing

Company associations should always be validated.

---

# 40. Domain Stacking

Example:

```text
(Automotive
OR "Automotive Industry"
OR Mobility)
```

Combined:

```text
Java
AND
Spring Boot
AND
(Automotive OR Mobility)
```

Domain stacking is particularly useful when the technical skill exists across many industries but the client requires specific domain experience.

---

# 41. Exclusion Strategy

Exclusions should solve a known problem.

Example:

```text
Java -Android
```

Potentially useful when Android results create significant noise.

Another example:

```text
"Data Analyst" -"Business Analyst"
```

Use exclusions carefully.

An exclusion can remove relevant candidates if the excluded term appears legitimately in their profile.

---

# 42. Avoid Overusing Exclusions

Bad approach:

```text
Java
-Android
-Junior
-Intern
-Student
-Teacher
-Training
-Course
-Certification
```

This may accidentally eliminate legitimate candidates.

Instead:

1. Run the search.
2. Identify actual noise.
3. Add the smallest useful exclusion.
4. Re-test.

---

# 43. Boolean Nesting

Nested Boolean structures can become complex.

Example:

```text
(
  ("Java Developer" OR "Java Engineer")
  AND
  ("Spring Boot" OR Spring)
)
AND
(
  AWS
  OR Azure
)
AND
(
  Michigan
  OR MI
)
```

The logical structure is:

```text
TITLE
   +
FRAMEWORK
   +
CLOUD
   +
LOCATION
```

Keep nesting readable.

---

# 44. The Modular Boolean Method

Instead of writing one large query immediately, build modules.

### Module 1 — Title

```text
("Java Developer" OR "Java Engineer")
```

### Module 2 — Technology

```text
(Java AND "Spring Boot")
```

### Module 3 — Architecture

```text
(Microservices OR "Micro Services")
```

### Module 4 — Cloud

```text
(AWS OR Azure)
```

### Module 5 — Location

```text
(Michigan OR MI)
```

Then combine:

```text
MODULE 1
AND
MODULE 2
AND
MODULE 3
AND
MODULE 4
AND
MODULE 5
```

This makes troubleshooting much easier.

---

# 45. Search Debugging

When a search produces zero results, do not immediately rewrite everything.

Test the modules separately.

### Test title

```text
("Java Developer" OR "Java Engineer")
```

### Test technology

```text
(Java AND "Spring Boot")
```

### Test architecture

```text
Microservices
```

### Test location

```text
Michigan
```

Then combine them gradually.

---

# 46. Zero Results

Possible causes:

```text
Too many mandatory terms
Wrong title
Wrong synonym
Overly specific location
Rare technology combination
Search engine limitations
Poor indexing
Unsupported syntax
```

### Fix sequence

```text
1. Remove secondary skills
2. Expand titles
3. Expand technology terminology
4. Expand location
5. Remove unnecessary exclusions
6. Search another source
```

---

# 47. Too Many Results

Possible causes:

```text
Search is too broad
Title is too generic
Technology is too common
Location is missing
Domain is missing
No exclusions
```

### Fix sequence

```text
1. Add core technology
2. Add specific framework
3. Add location
4. Add domain
5. Add company
6. Add targeted exclusion
```

---

# 48. Wrong Candidates

If the results are technically related but not relevant:

Ask:

```text
Which keyword is creating the noise?
```

Example:

```text
Java
```

may produce:

```text
Java Developer
Java Trainer
Java Instructor
JavaScript Developer
Android Developer
```

Add context:

```text
"Java Developer"
"Spring Boot"
```

or use appropriate exclusions when justified.

---

# 49. Search Query Length

Long Boolean strings can become difficult to:

* Read
* Debug
* Maintain
* Modify
* Reuse

Instead of one enormous search, create several focused searches.

Example:

```text
SEARCH A
Title + Core Skills

SEARCH B
Title + Core Skills + Location

SEARCH C
GitHub + Technology

SEARCH D
Resume + Technology

SEARCH E
Company + Technology
```

Multiple focused searches can outperform one giant query.

---

# 50. Boolean Search Matrix

A useful way to design a search:

| Dimension        | Example                         |
| ---------------- | ------------------------------- |
| Role             | Java Developer                  |
| Title Variations | Java Engineer, Backend Engineer |
| Core Technology  | Java                            |
| Framework        | Spring Boot                     |
| Architecture     | Microservices                   |
| Cloud            | AWS                             |
| Messaging        | Kafka                           |
| Domain           | Automotive                      |
| Location         | Michigan                        |
| Company          | Target companies                |
| Exclusion        | Only when justified             |

---

# 51. JD → Boolean Workflow

Use:

```text
JOB DESCRIPTION
      ↓
EXTRACT REQUIREMENTS
      ↓
CLASSIFY REQUIREMENTS
      ↓
MUST-HAVE
      ↓
NICE-TO-HAVE
      ↓
TITLE EXPANSION
      ↓
TECHNOLOGY EXPANSION
      ↓
LOCATION EXPANSION
      ↓
BUILD BOOLEAN MODULES
      ↓
COMBINE
      ↓
TEST
      ↓
OPTIMIZE
```

---

# 52. Must-Have Extraction

Ask:

> If the candidate does not have this, can they realistically perform the job?

If yes, it may be a must-have.

If no, it may be a nice-to-have.

Example:

```text
Role:
Java Developer

Must Have:
Java
Spring Boot
Microservices

Preferred:
AWS
Kafka
Docker
```

Initial search:

```text
("Java Developer" OR "Java Engineer")
AND
Java
AND
("Spring Boot" OR Spring)
AND
Microservices
```

Then add preferred skills as optimization signals rather than mandatory conditions when appropriate.

---

# 53. Boolean Search Versions

For difficult searches, maintain multiple versions.

### Version A — Broad

```text
("Java Developer" OR "Java Engineer" OR "Backend Engineer")
AND
Java
AND
Michigan
```

### Version B — Balanced

```text
("Java Developer" OR "Java Engineer" OR "Backend Engineer")
AND
Java
AND
("Spring Boot" OR Spring)
AND
Microservices
AND
Michigan
```

### Version C — Narrow

```text
("Senior Java Developer" OR "Java Engineer")
AND
Java
AND
"Spring Boot"
AND
Microservices
AND
AWS
AND
Kafka
AND
Michigan
```

This gives the recruiter three search depths.

---

# 54. Search Versioning

Use labels such as:

```text
BROAD
BALANCED
NARROW
```

Avoid constantly editing one search without documenting what changed.

---

# 55. Search Quality Test

Before saving a Boolean string, ask:

```text
[ ] Is the title relevant?
[ ] Are title variations justified?
[ ] Is the core technology correct?
[ ] Are technology synonyms accurate?
[ ] Are related technologies incorrectly treated as synonyms?
[ ] Is location appropriate?
[ ] Are exclusions necessary?
[ ] Is the query too restrictive?
[ ] Is the query too broad?
[ ] Can another recruiter understand it?
[ ] Can the query be easily modified?
```

---

# 56. Boolean Anti-Patterns

Avoid:

```text
Everything from the JD
+
Every technology synonym
+
Every location
+
Every company
+
Every possible exclusion
```

This produces a difficult-to-maintain search.

Instead:

```text
CORE REQUIREMENTS
+
RELEVANT VARIATIONS
+
TARGETED CONTEXT
```

---

# 57. Boolean Search for Passive Candidates

Passive candidates may use different titles from the job description.

For example, JD:

```text
Senior Java Developer
```

Possible search:

```text
("Senior Java Developer"
OR "Java Engineer"
OR "Backend Engineer"
OR "Software Engineer")
AND
Java
AND
"Spring Boot"
AND
Microservices
```

This increases the possibility of discovering professionals whose public title differs from the requisition title.

---

# 58. Boolean Search for Niche Skills

Suppose the requirement is:

```text
PLS-CADD
Transmission Line
Electrical Engineering
```

Search:

```text
("Transmission Line Engineer"
OR "Transmission Line Design Engineer"
OR "Electrical Engineer")
AND
("PLS-CADD" OR "PLS CADD")
AND
("Transmission Line" OR "Transmission Lines")
```

For a niche requirement, technical terminology accuracy becomes especially important.

---

# 59. Boolean Search for AI / GenAI

Example:

```text
("AI Engineer"
OR "GenAI Engineer"
OR "Generative AI Engineer"
OR "Machine Learning Engineer")
AND
Python
AND
(LLM OR "Large Language Model")
AND
(RAG OR "Retrieval Augmented Generation")
```

Additional terms can be added only when supported by the actual requirement.

---

# 60. Boolean Search for Cloud

Example:

```text
("Cloud Engineer"
OR "Cloud Infrastructure Engineer"
OR "Cloud Platform Engineer")
AND
(AWS OR Azure OR GCP)
AND
(Kubernetes OR K8s)
AND
(Terraform OR "Infrastructure as Code")
```

---

# 61. Boolean Search for QA

Example:

```text
("QA Automation Engineer"
OR SDET
OR "Test Automation Engineer")
AND
(Selenium OR Cypress OR Playwright)
AND
(Java OR Python OR JavaScript OR TypeScript)
```

---

# 62. Boolean Search for Data

Example:

```text
("Data Engineer"
OR "Senior Data Engineer"
OR "Data Platform Engineer")
AND
(Python OR PySpark)
AND
SQL
AND
(Spark OR PySpark)
AND
(AWS OR Azure OR GCP)
```

---

# 63. Boolean Search for Cybersecurity

Example:

```text
("Security Engineer"
OR "Cybersecurity Engineer"
OR "Information Security Engineer")
AND
(Vulnerability OR "Vulnerability Management")
AND
(SIEM OR SOC)
```

The exact Boolean should be customized to the actual security requirement.

---

# 64. Boolean Search for Full Stack

Example:

```text
("Full Stack Developer"
OR "Full Stack Engineer"
OR "Software Engineer")
AND
(React OR ReactJS OR "React.js")
AND
(Node.js OR Node OR NodeJS)
AND
(JavaScript OR TypeScript)
AND
(AWS OR Azure)
```

---

# 65. Boolean Search for .NET

Example:

```text
(".NET Developer"
OR ".NET Engineer"
OR "C# Developer"
OR "C# Engineer")
AND
(C# OR "C Sharp")
AND
(".NET" OR "ASP.NET" OR ".NET Core")
AND
(Azure OR AWS)
```

Technology mappings should be reviewed for the specific search objective.

---

# 66. Boolean Search for Salesforce

Example:

```text
("Salesforce Developer"
OR "Salesforce Engineer"
OR "Salesforce Technical Consultant")
AND
Salesforce
AND
(Apex OR Lightning)
```

---

# 67. Boolean Search for ServiceNow

Example:

```text
("ServiceNow Developer"
OR "ServiceNow Engineer"
OR "ServiceNow Consultant")
AND
ServiceNow
AND
(ITSM OR "IT Service Management")
```

---

# 68. Boolean Search for SAP

Example:

```text
("SAP Consultant"
OR "SAP Developer"
OR "SAP Technical Consultant")
AND
SAP
AND
("S/4HANA" OR "S4 HANA")
```

Additional modules should be added according to the requirement.

---

# 69. Boolean Search + X-Ray

Boolean logic becomes particularly powerful when combined with source targeting.

Example:

```text
site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
AND
"Spring Boot"
AND
AWS
AND
Michigan
```

The structure is:

```text
SOURCE
+
TITLE
+
TECHNOLOGY
+
CLOUD
+
LOCATION
```

---

# 70. Boolean Search + GitHub

Example:

```text
site:github.com
("Java" OR "Spring Boot")
Microservices
AWS
```

GitHub results should be interpreted as technical discovery signals.

Do not assume a repository contributor is automatically:

* A current employee
* A full-time developer
* Senior
* Available
* Interested in a job

---

# 71. Boolean Search + Resume Search

Example:

```text
filetype:pdf
("Java Developer" OR "Java Engineer")
"Spring Boot"
AWS
Michigan
```

Resume searches can help uncover publicly indexed documents.

Always consider document age and relevance.

---

# 72. Boolean Search + Portfolio Search

Example:

```text
("Java Developer" OR "Java Engineer")
("portfolio" OR "resume" OR "CV")
"Spring Boot"
AWS
```

This can help discover personal professional websites and portfolio pages.

---

# 73. Multi-Search Strategy

For a difficult role, create several searches.

```text
SEARCH 1
LinkedIn

SEARCH 2
GitHub

SEARCH 3
Resume

SEARCH 4
Portfolio

SEARCH 5
Company Targeting

SEARCH 6
Technical Communities
```

Do not assume one Boolean query should discover the entire talent market.

---

# 74. Search Documentation Template

When adding a Boolean search to this repository, document it like this:

````markdown
### Search Name

**Objective:**  
Describe what the search is designed to discover.

**Boolean:**

```text
SEARCH STRING
````

**Title Logic:**
Explain the title cluster.

**Technology Logic:**
Explain the technology cluster.

**Location Logic:**
Explain the location cluster.

**Best Use Case:**
Explain when a recruiter should use it.

**Broaden:**
Explain how to expand it.

**Narrow:**
Explain how to make it more precise.

**Limitations:**
Explain what the search cannot establish.

````

---

# 75. Boolean Search Troubleshooting Matrix

| Problem | Likely Cause | First Fix |
|---|---|---|
| Zero results | Too restrictive | Remove secondary skills |
| Very few results | Title too specific | Expand title cluster |
| Too many results | Too broad | Add core skill |
| Wrong technology | Ambiguous term | Add context |
| Wrong location | Location too restrictive | Expand geography |
| Wrong candidates | Title too broad | Add technical requirements |
| Too much noise | Missing exclusion | Add targeted exclusion |
| Query difficult to maintain | Too many terms | Split into modules |
| Missing known candidates | Over-constrained | Remove non-essential terms |

---

# 76. One-Change-at-a-Time Rule

When optimizing a Boolean query, change one major component at a time.

Bad:

```text
Change title
+
technology
+
location
+
exclusions
````

Good:

```text
Change title
→ test

Change technology
→ test

Change location
→ test

Add exclusion
→ test
```

This allows you to understand what actually improved the search.

---

# 77. Boolean Search Documentation Standard

Every important Boolean string should eventually record:

```text
Purpose
Search string
Title cluster
Technology cluster
Location cluster
Domain
Exclusions
Broad version
Balanced version
Narrow version
Known limitations
Last verified date
```

---

# 78. Boolean Search Quality Principles

A high-quality recruiter Boolean should be:

```text
Readable
Relevant
Technically accurate
Maintainable
Adjustable
Purpose-driven
```

Avoid optimizing for:

```text
Maximum length
Maximum number of synonyms
Maximum number of keywords
```

---

# 79. The Recruiter Boolean Formula

Remember:

```text
TITLE
+
CORE SKILL
+
CONTEXT
+
LOCATION
+
OPTIONAL SIGNALS
-
NOISE
```

Where:

```text
TITLE
=
Who are you looking for?

CORE SKILL
=
What must they know?

CONTEXT
=
What makes the requirement specific?

LOCATION
=
Where should they be?

OPTIONAL SIGNALS
=
What can improve relevance?

NOISE
=
What should be removed?
```

---

# 80. Final Boolean Workflow

```text
                    JD
                     │
                     ▼
             EXTRACT REQUIREMENTS
                     │
                     ▼
              CLASSIFY REQUIREMENTS
                     │
            ┌────────┴────────┐
            ▼                 ▼
        MUST-HAVE         NICE-TO-HAVE
            │                 │
            ▼                 │
       TITLE CLUSTER           │
            │                 │
            ▼                 │
     TECHNOLOGY CLUSTER        │
            │                 │
            ▼                 │
      LOCATION CLUSTER         │
            │                 │
            └────────┬────────┘
                     ▼
              BUILD BOOLEAN
                     │
                     ▼
               RUN SEARCH
                     │
            ┌────────┴────────┐
            ▼                 ▼
         TOO FEW           TOO MANY
            │                 │
            ▼                 ▼
          EXPAND             NARROW
            │                 │
            └────────┬────────┘
                     ▼
                RUN AGAIN
                     │
                     ▼
                 VALIDATE
```

---

# 81. Boolean Search Cheat Sheet

## Core Operators

```text
AND
OR
NOT
```

## Exact Phrase

```text
"Java Developer"
```

## Grouping

```text
("Java Developer" OR "Java Engineer")
```

## Exclusion

```text
Java -Android
```

## Title Cluster

```text
("Java Developer" OR "Java Engineer" OR "Backend Engineer")
```

## Technology Cluster

```text
("Spring Boot" OR Spring)
```

## Location Cluster

```text
(Detroit OR Michigan OR MI)
```

## Combined

```text
("Java Developer" OR "Java Engineer")
AND
("Spring Boot" OR Spring)
AND
(Microservices OR "Micro Services")
AND
(AWS OR "Amazon Web Services")
AND
(Michigan OR MI)
```

---

# 82. Boolean Search Golden Rules

### Rule 1

Do not copy a Boolean string without understanding it.

### Rule 2

Do not make every JD keyword mandatory.

### Rule 3

Use `OR` for genuine alternatives.

### Rule 4

Use `AND` for important combined requirements.

### Rule 5

Use exclusions only when they solve an identified problem.

### Rule 6

Use parentheses to make logical groups clear.

### Rule 7

Expand titles when candidate recall is too low.

### Rule 8

Expand technology terminology when appropriate.

### Rule 9

Add specificity when results are too broad.

### Rule 10

Validate every important search against real results.

---

# 83. Boolean Search Quality Checklist

Before saving a search:

```text
[ ] Search objective is clear
[ ] Target role is defined
[ ] Title variations are relevant
[ ] Core technology is identified
[ ] Technology synonyms are technically valid
[ ] Must-have skills are separated from nice-to-have skills
[ ] Location strategy is appropriate
[ ] Domain terms are justified
[ ] Company terms are justified
[ ] Exclusions are evidence-based
[ ] Parentheses are used correctly
[ ] Search is not unnecessarily restrictive
[ ] Search is not unnecessarily broad
[ ] Query can be modified easily
[ ] Search has been tested
[ ] False positives have been reviewed
[ ] Limitations are understood
```

---

# 84. Final Boolean Framework

The complete recruiter approach is:

```text
                 BOOLEAN SEARCH
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
      TITLE         SKILLS         LOCATION
        │              │              │
        ▼              ▼              ▼
   Variations      Technology      Geography
   Synonyms        Frameworks      Metro
   Abbreviations   Platforms       State
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                    DOMAIN
                       │
                       ▼
                    COMPANY
                       │
                       ▼
                  EXCLUSIONS
                       │
                       ▼
                  FINAL QUERY
                       │
                       ▼
                  TEST RESULTS
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
          BROADEN              NARROW
             │                   │
             └─────────┬─────────┘
                       ▼
                    VALIDATE
```

---

# 85. Key Takeaway

> **Boolean Search is not about creating the biggest search string. It is about creating the right logical structure for the sourcing objective.**

The best Boolean searches are:

```text
Purpose-driven
+
Technically accurate
+
Readable
+
Flexible
+
Tested
+
Easy to optimize
```

---

# 🔗 Next Module

➡️ **[03 — Google X-Ray Search](../03-Google-X-Ray/)**

The next module will combine Boolean logic with search-engine targeting to build practical Google X-Ray searches for:

* LinkedIn
* GitHub
* Resumes
* Portfolios
* Technical communities
* Company targeting
* Location sourcing
* US IT recruiting

---

**Last Verified:** 2026-08-14

**Verification Note:** Boolean syntax and search behavior can differ between search engines and recruiting platforms. Verify current behavior before treating platform-specific syntax as guaranteed.
