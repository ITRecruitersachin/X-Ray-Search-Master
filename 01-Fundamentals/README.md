# 🔎 X-Ray Search Fundamentals

> The foundation of internet sourcing for technical recruiters.

This module explains the core concepts behind **X-Ray Search, Boolean Search, search-engine operators, search anatomy, query construction, search precision, search recall, and recruiter search strategy**.

The objective is not to memorize hundreds of search strings.

The objective is to understand **how to build, evaluate, modify, and combine searches** to discover relevant professional talent.

---

## 📚 Learning Path

```text
X-RAY SEARCH FUNDAMENTALS
          │
          ▼
UNDERSTAND SEARCH ENGINES
          │
          ▼
UNDERSTAND BOOLEAN LOGIC
          │
          ▼
UNDERSTAND SEARCH OPERATORS
          │
          ▼
BUILD SEARCH COMPONENTS
          │
          ├── Titles
          ├── Technologies
          ├── Locations
          ├── Companies
          └── Domains
          │
          ▼
COMBINE COMPONENTS
          │
          ▼
RUN SEARCH
          │
          ▼
REVIEW RESULTS
          │
          ▼
OPTIMIZE QUERY
          │
          ▼
VALIDATE CANDIDATE
```

---

# 🎯 What You Will Learn

After completing this module, a recruiter should understand:

* What X-Ray Search means
* What Boolean Search means
* How X-Ray and Boolean Search work together
* How search engines discover and index public pages
* How to use search operators
* How to build search queries
* How to expand a search
* How to narrow a search
* How to reduce irrelevant results
* How to increase candidate discovery
* How to recognize search-engine limitations
* How to avoid common recruiter search mistakes
* How to construct searches systematically

---

# 1. What Is X-Ray Search?

**X-Ray Search** is a sourcing technique that uses a search engine to discover publicly indexed information from a specific website or domain.

The basic concept is:

```text
SEARCH ENGINE
     +
TARGET DOMAIN
     +
SEARCH TERMS
     =
X-RAY SEARCH
```

A common pattern is:

```text
site:domain.com search terms
```

For example:

```text
site:linkedin.com/in/ "Java Developer" "Spring Boot"
```

The recruiter is asking the search engine to return publicly indexed pages from a particular domain that contain the specified terms.

---

# 2. Why Recruiters Use X-Ray Search

Recruiters may use X-Ray Search when:

* Internal platform search is insufficient
* A candidate is difficult to find
* A profile is publicly indexed
* A technical community contains useful professional signals
* A resume is publicly indexed
* A portfolio is easier to discover through a search engine
* A recruiter wants to search multiple public sources
* A niche skill combination requires a different discovery strategy

X-Ray Search is therefore best understood as a **candidate discovery technique**, not as a replacement for every recruiting platform.

---

# 3. What X-Ray Search Does NOT Mean

X-Ray Search does not mean:

* Accessing private profiles
* Bypassing authentication
* Circumventing access controls
* Accessing restricted databases
* Obtaining private information
* Guessing passwords
* Circumventing platform security
* Automatically obtaining someone's contact information

This repository focuses on **publicly available professional information**.

---

# 4. What Is Boolean Search?

Boolean Search is a method of combining keywords using logical operators.

The most important concepts are:

```text
AND
OR
NOT
```

Recruiters commonly also use:

```text
"Exact Phrases"
(Parentheses)
-Exclusions
```

Boolean logic allows a recruiter to control the relationship between search terms.

---

# 5. AND

`AND` generally means that multiple concepts should be present in the search.

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

The recruiter is looking for results associated with both concepts.

Example:

```text
"Java Developer" AND "Spring Boot" AND AWS
```

This can be useful when all three concepts are important to the sourcing requirement.

---

# 6. OR

`OR` is used to represent alternatives.

Example:

```text
Java OR J2EE
```

A broader recruiter title search might be:

```text
"Java Developer"
OR
"Java Engineer"
OR
"Java Software Engineer"
```

Combined:

```text
("Java Developer"
OR "Java Engineer"
OR "Java Software Engineer")
```

`OR` is especially useful for:

* Title variations
* Abbreviations
* Alternate terminology
* Technology variations
* Location variations

---

# 7. NOT

`NOT` can be used in Boolean environments to exclude a term.

Example:

```text
Java NOT Android
```

However, search-engine support for Boolean syntax can vary.

For general web searching, the minus operator is commonly used for exclusions:

```text
Java -Android
```

Always verify the behavior of the search engine being used.

---

# 8. Exact Phrase Searching

Quotation marks are used to search for an exact phrase.

Example:

```text
"Senior Java Developer"
```

Compare:

```text
Senior Java Developer
```

with:

```text
"Senior Java Developer"
```

The quoted version communicates that the phrase itself is important.

Exact phrases are particularly useful for:

* Job titles
* Technology names
* Certifications
* Framework names
* Project names
* Organization names

---

# 9. Parentheses

Parentheses group related search concepts.

Example:

```text
("Java Developer" OR "Java Engineer")
AND
("Spring Boot" OR Spring)
AND
AWS
```

The structure can be visualized as:

```text
            TITLE
              │
      ┌───────┴────────┐
      │                │
Java Developer    Java Engineer
      │
      ▼
      AND
      │
      ▼
   TECHNOLOGY
      │
 ┌────┴─────┐
Spring Boot Spring
      │
      ▼
      AND
      │
      ▼
     AWS
```

Parentheses become increasingly important as a query becomes more complex.

---

# 10. The `site:` Operator

The `site:` operator limits results to a particular domain or website.

Basic pattern:

```text
site:example.com keyword
```

Recruiting example:

```text
site:linkedin.com/in/ "Java Developer"
```

GitHub example:

```text
site:github.com "Python" "FastAPI"
```

Technical community example:

```text
site:stackoverflow.com "React" "TypeScript"
```

Resume example:

```text
filetype:pdf "Java Developer"
```

The actual availability and indexing of pages depend on the search engine and the target website.

---

# 11. The `filetype:` Operator

`filetype:` can be used to search for specific file formats where supported.

Example:

```text
filetype:pdf "Java Developer"
```

Another example:

```text
filetype:pdf "AWS" "Terraform"
```

Resume-oriented search:

```text
filetype:pdf "Senior Software Engineer" "Python"
```

Possible use cases include:

* Public resumes
* CVs
* Technical documents
* Public presentations
* Documentation
* Public research material

### Important

A PDF found through a search engine is not necessarily:

* Current
* Authentic
* Complete
* Owned by the person named in the document
* Representative of current employment

Treat the result as a discovery signal and validate it.

---

# 12. The `intitle:` Operator

`intitle:` is used to target terms appearing in page titles where supported.

Conceptual example:

```text
intitle:"Java Developer"
```

Combined with a domain:

```text
site:example.com intitle:"Software Engineer"
```

This can sometimes help when a relevant page title contains the professional role.

Search-engine behavior can change, so platform-specific operator behavior should be verified before being documented as guaranteed functionality.

---

# 13. The `inurl:` Operator

`inurl:` can be used to target terms appearing in URLs where supported.

Example:

```text
inurl:resume "Java Developer"
```

Another example:

```text
site:example.com inurl:portfolio React
```

This can be useful for discovering pages whose URL structure contains meaningful words.

---

# 14. Combining Operators

The real power of X-Ray Search comes from combining search dimensions.

Example:

```text
site:linkedin.com/in/
"Java Developer"
"Spring Boot"
Michigan
```

Conceptually:

```text
TARGET DOMAIN
      +
TITLE
      +
TECHNOLOGY
      +
LOCATION
```

A more structured search:

```text
site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
("Spring Boot" OR Spring)
(AWS OR "Amazon Web Services")
(Michigan OR MI)
```

---

# 15. Search Anatomy

A recruiter search can be decomposed into several components.

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
COMPANY
   +
OPTIONAL SIGNALS
   -
EXCLUSIONS
```

Not every search requires every component.

A recruiter should only add a search dimension when it improves the search objective.

---

# 16. Title Cluster

A title cluster contains multiple ways a professional role may be described.

Example:

```text
("Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer"
OR "Backend Developer")
```

Why use title expansion?

Because organizations and professionals do not always use identical titles.

One company may use:

```text
Java Developer
```

Another may use:

```text
Java Engineer
```

Another may use:

```text
Backend Engineer
```

Title expansion increases potential recall.

---

# 17. Technology Cluster

A technology cluster contains relevant technical terms.

Example:

```text
(Java
AND "Spring Boot"
AND Microservices
AND AWS)
```

A broader version might be:

```text
(Java
AND ("Spring Boot" OR Spring)
AND (Microservices OR "Micro Services")
AND (AWS OR "Amazon Web Services"))
```

The broader version may discover additional results but can also introduce more noise.

---

# 18. Location Cluster

Location terminology can vary.

Example:

```text
("Detroit" OR "Detroit, MI" OR Michigan OR MI)
```

For a broader Michigan search:

```text
(Michigan OR MI)
```

For a metro-focused strategy, a recruiter may include relevant nearby markets.

Location expansion should reflect the actual recruiting requirement.

Do not automatically treat every nearby city as equivalent.

---

# 19. Company Cluster

A company cluster can target professional profiles associated with an organization.

Example:

```text
"Ford" AND Java
```

A domain-specific example:

```text
site:linkedin.com/in/ "Ford" "Java"
```

Company searches require validation because a company name may appear because the person:

* Worked there
* Previously worked there
* Worked on a client project
* Mentioned the company
* Discussed the company
* Referenced the company in an article
* Listed the company in unrelated content

Therefore:

```text
COMPANY KEYWORD
≠
PROVEN CURRENT EMPLOYMENT
```

---

# 20. Skill Stacking

Skill stacking means combining multiple technical requirements.

Example:

```text
Java
Spring Boot
Microservices
Kafka
AWS
```

Search:

```text
"Java Developer"
"Spring Boot"
Microservices
Kafka
AWS
```

Skill stacking increases specificity.

However, excessive skill stacking can eliminate candidates who possess the required experience but use different terminology.

---

# 21. Keyword Stacking

Keyword stacking means intentionally placing multiple relevant terms into one query.

Example:

```text
"Software Engineer"
Java
Spring Boot
Microservices
AWS
Kafka
REST
```

Keyword stacking can help establish a technical context.

But more keywords are not automatically better.

---

# 22. Synonym Expansion

Different candidates may describe the same or related concept differently.

Example:

```text
Java
J2EE
Java EE
Java SE
```

Another example:

```text
JavaScript
JS
ECMAScript
```

Another:

```text
Kubernetes
K8s
```

The repository will distinguish between:

```text
True synonym
Abbreviation
Alternate terminology
Related technology
Associated technology
Different technology
```

This distinction is important.

Do not blindly place every related technology into an `OR` group.

---

# 23. Search Precision

**Precision** refers to the relevance of the results returned by a search.

A highly precise search attempts to minimize irrelevant results.

Example:

```text
site:linkedin.com/in/
"Senior Java Developer"
"Spring Boot"
Microservices
Detroit
```

Compared with:

```text
Java
```

The first search is generally more constrained.

---

# 24. Search Recall

**Recall** refers to how much of the potentially relevant candidate population your search can discover.

A very narrow search may have high relevance but miss candidates.

For example:

```text
"Senior Java Developer"
"Spring Boot"
"Kafka"
"Detroit, MI"
"AWS"
```

could exclude someone whose profile says:

```text
Java Engineer
Spring
Messaging
Cloud
Michigan
```

even if the candidate may be relevant.

This is why sourcing requires iteration.

---

# 25. Precision vs Recall

Think of sourcing as a balance:

```text
                 HIGH RECALL
                     ▲
                     │
                     │
             BROAD   │
                     │
                     │
LOW PRECISION ────────┼──────── HIGH PRECISION
                     │
                     │
             NARROW  │
                     │
                     ▼
                 LOW RECALL
```

A recruiter should adjust the search based on the results.

---

# 26. Over-Constrained Search

A search becomes over-constrained when too many conditions must be satisfied.

Example:

```text
site:linkedin.com/in/
"Senior Java Developer"
"Spring Boot"
"Microservices"
"Kafka"
"AWS"
"Terraform"
"React"
"Detroit"
"Michigan"
"Automotive"
"Master's Degree"
```

This may eliminate potentially relevant candidates who simply do not mention every term on their public profile.

### Symptoms

```text
Very few results
Zero results
Only highly obvious candidates
Missing known candidates
```

### Fix

Remove non-essential requirements one at a time.

---

# 27. Under-Constrained Search

A search is under-constrained when it contains insufficient information to separate relevant results from noise.

Example:

```text
Java Developer
```

This may produce a very large number of results.

### Improve it by adding:

```text
Technology
Location
Domain
Company
Additional skill
```

Example:

```text
"Java Developer"
"Spring Boot"
AWS
Michigan
```

---

# 28. Search Broadening

When results are insufficient, broaden the search.

### Method 1 — Expand titles

From:

```text
"Java Developer"
```

to:

```text
("Java Developer"
OR "Java Engineer"
OR "Java Software Engineer"
OR "Backend Engineer")
```

### Method 2 — Expand technology terms

From:

```text
"Spring Boot"
```

to:

```text
("Spring Boot" OR Spring)
```

### Method 3 — Expand location

From:

```text
"Detroit, MI"
```

to:

```text
(Detroit OR Michigan OR MI)
```

### Method 4 — Remove non-essential requirements

Do not require every desirable skill if it is not truly necessary.

---

# 29. Search Narrowing

When results are too broad, narrow the search.

### Add a technology

```text
Java
+
Spring Boot
```

### Add a location

```text
Java
+
Michigan
```

### Add a domain

```text
Java
+
Automotive
```

### Add a company

```text
Java
+
"Company Name"
```

### Add exclusions

Example:

```text
Java Developer -Android
```

Only use exclusions when the excluded term is genuinely creating noise.

---

# 30. Search Iteration

A recruiter should not expect the first search to be perfect.

Use:

```text
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
```

Example:

### Search 1

```text
"Java Developer" Michigan
```

Too broad.

### Search 2

```text
"Java Developer" "Spring Boot" Michigan
```

Better.

### Search 3

```text
("Java Developer" OR "Java Engineer")
"Spring Boot"
Microservices
Michigan
```

More targeted.

### Search 4

```text
site:linkedin.com/in/
("Java Developer" OR "Java Engineer")
"Spring Boot"
Microservices
Michigan
```

Now the recruiter is targeting a specific public source.

---

# 31. Search Source Strategy

Different sources provide different discovery signals.

```text
SOURCE
  │
  ├── LinkedIn
  │     └── Professional profiles
  │
  ├── GitHub
  │     └── Technical activity
  │
  ├── Resume
  │     └── Career information
  │
  ├── Portfolio
  │     └── Projects / technical identity
  │
  ├── Technical Community
  │     └── Technical participation
  │
  └── Company Website
        └── Public professional information
```

A multi-source strategy is often stronger than repeatedly modifying one query on one platform.

---

# 32. Search Engine Indexing

Search engines maintain indexes of pages they discover and are permitted to index.

Conceptually:

```text
PUBLIC WEB PAGE
      │
      ▼
SEARCH ENGINE DISCOVERY
      │
      ▼
INDEXING
      │
      ▼
SEARCH QUERY
      │
      ▼
SEARCH RESULT
```

Not every public page will appear in search results.

A page may be:

* Not indexed
* Removed from the index
* Recently published
* Inaccessible to crawlers
* Restricted from indexing
* Poorly indexed
* Indexed differently than expected

Therefore:

```text
NOT FOUND IN SEARCH
≠
DOES NOT EXIST
```

---

# 33. Search Indexing vs Platform Search

A search engine and a platform's internal search system are different systems.

For example:

```text
SEARCH ENGINE
     │
     └── Searches its own index
```

while:

```text
PLATFORM SEARCH
     │
     └── Searches according to platform-specific systems
```

An X-Ray query can therefore discover something that is difficult to discover through a platform's internal search.

But the reverse can also happen.

---

# 34. Public Indexing Limitations

A recruiter should expect:

```text
Incomplete indexing
Stale pages
Duplicate pages
Missing pages
Changed URLs
Removed pages
Search ranking variation
Different results between search engines
```

This is why search results should be treated as **discovery inputs**, not absolute databases of truth.

---

# 35. Recruiter Search Anatomy

A strong recruiter search generally has a deliberate structure.

Example requirement:

```text
Senior Java Developer
Detroit, MI
Spring Boot
Microservices
AWS
Kafka
```

Convert it into:

```text
ROLE
Senior Java Developer

TITLE VARIATIONS
Java Developer
Java Engineer
Java Software Engineer
Backend Engineer

CORE TECHNOLOGY
Java

FRAMEWORK
Spring Boot

ARCHITECTURE
Microservices

CLOUD
AWS

MESSAGING
Kafka

LOCATION
Detroit
Michigan
MI
```

Then build searches from those components.

---

# 36. JD → Search Conversion

Use this process:

```text
JOB DESCRIPTION
       │
       ▼
REQUIRED SKILLS
       │
       ▼
MUST-HAVE vs NICE-TO-HAVE
       │
       ▼
TITLE VARIATIONS
       │
       ▼
TECHNOLOGY VARIATIONS
       │
       ▼
LOCATION VARIATIONS
       │
       ▼
DOMAIN / INDUSTRY
       │
       ▼
EXCLUSIONS
       │
       ▼
SEARCH STRINGS
```

---

# 37. Beginner Search Formula

Start simple.

```text
TITLE + CORE SKILL + LOCATION
```

Example:

```text
"Java Developer" "Spring Boot" Michigan
```

---

# 38. Intermediate Search Formula

Add title and technology variations.

```text
(TITLE VARIATIONS)
AND
(TECHNOLOGY VARIATIONS)
AND
LOCATION
```

Example:

```text
("Java Developer"
OR "Java Engineer"
OR "Backend Engineer")
AND
("Spring Boot"
OR Spring)
AND
(Michigan OR MI)
```

---

# 39. Advanced Search Formula

An advanced search may include multiple dimensions.

```text
TARGET DOMAIN
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
EXCLUSIONS
```

Example:

```text
site:linkedin.com/in/
("Java Developer"
OR "Java Engineer"
OR "Backend Engineer")
("Spring Boot"
OR Spring)
(Microservices OR "Micro Services")
(AWS OR "Amazon Web Services")
(Detroit OR Michigan OR MI)
-Android
```

The query should only contain terms that support the sourcing objective.

---

# 40. Common Beginner Mistakes

## Mistake 1 — Searching only one title

```text
"Java Developer"
```

Potential issue:

Relevant candidates may use another title.

---

## Mistake 2 — Adding every JD keyword

A huge query can become too restrictive.

---

## Mistake 3 — Treating related technologies as synonyms

For example, two technologies may commonly appear together without being equivalent.

---

## Mistake 4 — Ignoring location variations

A candidate may list:

```text
Detroit
Michigan
MI
Metro Detroit
```

---

## Mistake 5 — Assuming public information is current

Public information can become outdated.

---

## Mistake 6 — Treating a search result as a validated candidate

Discovery and validation are separate steps.

---

## Mistake 7 — Using one search for everything

Different searches should serve different objectives.

---

# 41. Search Components Checklist

Before running a search, ask:

```text
[ ] What exact role am I sourcing?
[ ] What title variations exist?
[ ] What is the true must-have technology?
[ ] What technologies are secondary?
[ ] What location terms are relevant?
[ ] Is industry/domain important?
[ ] Is company targeting useful?
[ ] Are there obvious false-positive terms?
[ ] Which source should I search?
[ ] Should the search prioritize recall or precision?
```

---

# 42. Candidate Discovery vs Candidate Validation

These are different processes.

## Candidate Discovery

The question is:

> Who might be relevant?

Sources may include:

```text
Search engines
LinkedIn
GitHub
Resumes
Portfolios
Technical communities
Job boards
Professional websites
```

## Candidate Validation

The question is:

> What can I reasonably verify about this person through appropriate professional recruiting processes?

Validation may involve reviewing:

```text
Professional profile
Resume
Public technical evidence
Employment history
Skills
Projects
Interview responses
Recruiter screening
Candidate-provided information
```

Never treat an X-Ray result alone as proof of candidate suitability.

---

# 43. Professional Public Information

This repository focuses on information such as:

```text
Public professional profiles
Public GitHub repositories
Public technical articles
Public conference speaker pages
Public portfolios
Public certifications
Publicly indexed resumes
Public professional websites
Public technical contributions
```

---

# 44. Sensitive / Private Information

Recruiter sourcing should not become an attempt to uncover private information.

Do not use this repository to facilitate:

```text
Credential harvesting
Password discovery
Authentication bypass
Private-account access
Doxxing
Stalking
Private-location discovery
Sensitive personal information collection
Restricted database access
Access-control circumvention
```

The purpose is **professional talent discovery**.

---

# 45. GitHub Signals Require Context

GitHub can provide valuable technical evidence.

However:

```text
GitHub activity
≠
Current employment
```

and:

```text
Repository contribution
≠
Professional seniority
```

and:

```text
Programming language used
≠
Years of professional experience
```

GitHub should therefore be used as one component of a broader sourcing and validation workflow.

---

# 46. Resume Search Requires Validation

A public resume may be:

```text
Old
Duplicated
Incomplete
Archived
Incorrect
No longer representative
```

A resume search can therefore help discover candidates, but recruiters should validate the information before relying on it.

---

# 47. Search Quality Model

Every search should be evaluated using:

```text
RELEVANCE
+
RECALL
+
PRECISION
+
SOURCE QUALITY
+
QUERY MAINTAINABILITY
```

A good search is not necessarily the longest search.

A good search is one that produces useful candidates efficiently.

---

# 48. The 3-Question Search Test

Before using a complex query, ask:

### 1. What am I trying to find?

```text
Candidate
Technology
Company
Project
Portfolio
Technical contributor
```

### 2. Where is the information likely to exist?

```text
LinkedIn
GitHub
Resume
Portfolio
Technical Community
Company Website
```

### 3. What search terms best represent it?

```text
Title
Technology
Location
Company
Domain
Project
```

If these three questions are clear, building the query becomes easier.

---

# 49. Search Optimization Loop

Use this loop for difficult requirements:

```text
                    START
                      │
                      ▼
               BUILD SEARCH
                      │
                      ▼
                RUN SEARCH
                      │
                      ▼
              REVIEW RESULTS
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
       TOO FEW     RELEVANT    TOO MANY
          │           │           │
          ▼           ▼           ▼
       EXPAND       VALIDATE     NARROW
          │           │           │
          └───────────┼───────────┘
                      ▼
                 RUN AGAIN
```

---

# 50. Fundamental Rule

> **Do not build one giant Boolean string and assume the sourcing problem is solved.**

Instead:

```text
Build
→ Search
→ Review
→ Learn
→ Modify
→ Search Again
→ Validate
```

This is the core mindset behind effective X-Ray sourcing.

---

# 51. Recommended Learning Sequence

After completing this module, continue with:

### Next: Boolean Search

`../02-Boolean-Search/`

Learn:

* Boolean operators
* Search formulas
* Parentheses
* Synonym expansion
* Exclusions
* Search construction
* Beginner → advanced Boolean

### Then: Google X-Ray

`../03-Google-X-Ray/`

Learn:

* Google search operators
* LinkedIn discovery
* GitHub discovery
* Resume discovery
* Portfolio discovery
* Search optimization

### Then: Bing

`../04-Bing-X-Ray/`

### Then: DuckDuckGo

`../05-DuckDuckGo/`

### Then: LinkedIn

`../06-LinkedIn/`

### Then: GitHub

`../07-GitHub/`

---

# 52. Fundamental Search Formula

Remember this model:

```text
             SEARCH OBJECTIVE
                    │
                    ▼
             TITLE CLUSTER
                    │
                    ▼
          TECHNOLOGY CLUSTER
                    │
                    ▼
            LOCATION CLUSTER
                    │
                    ▼
             DOMAIN / COMPANY
                    │
                    ▼
               EXCLUSIONS
                    │
                    ▼
              SEARCH QUERY
                    │
                    ▼
             SEARCH RESULTS
                    │
                    ▼
               VALIDATION
```

---

# 53. Recruiter Search Mindset

The strongest sourcing mindset is:

```text
Do not ask:

"Where is the candidate?"

Ask:

"Where is the evidence that a relevant professional exists?"
```

That evidence may appear in:

```text
Professional profiles
Repositories
Technical discussions
Public resumes
Portfolios
Conference pages
Technical publications
Company pages
Open-source projects
```

The recruiter then connects those professional signals into a legitimate sourcing workflow.

---

# 54. Fundamentals Summary

X-Ray Search is fundamentally about **using search engines to discover publicly indexed professional information from targeted sources**.

Boolean Search provides the logical structure.

Search operators provide targeting mechanisms.

Synonym expansion improves recall.

Specificity improves precision.

Multiple sources increase discovery opportunities.

Iteration improves search quality.

Validation separates a search result from a recruiting decision.

Ethical sourcing protects the boundary between professional discovery and private information.

---

# 55. Core Formula to Remember

```text
GOOD SOURCING
=
RIGHT TERMS
+
RIGHT SOURCE
+
RIGHT SEARCH STRUCTURE
+
ITERATION
+
VALIDATION
```

And the complete recruiter workflow is:

```text
JOB DESCRIPTION
      ↓
DECOMPOSE REQUIREMENTS
      ↓
BUILD TITLE CLUSTER
      ↓
BUILD TECHNOLOGY CLUSTER
      ↓
BUILD LOCATION CLUSTER
      ↓
SELECT SOURCE
      ↓
BUILD SEARCH
      ↓
RUN SEARCH
      ↓
REVIEW RESULTS
      ↓
OPTIMIZE
      ↓
DISCOVER
      ↓
VALIDATE
      ↓
SCREEN
```

---

## 📌 Next Module

➡️ **[02 — Boolean Search](../02-Boolean-Search/)**

The next module will focus specifically on building recruiter-grade Boolean searches from simple requirements through complex US IT sourcing scenarios.

---

## 🔗 Repository

**X-Ray Search Master**

The Recruiter's Internet Sourcing Intelligence Hub.

Built around:

```text
Boolean
+
X-Ray
+
Internet Sourcing
+
Technical Discovery
+
Recruiter Intelligence
+
AI-Assisted Search
```

---

**Last Verified:** 2026-08-14

**Verification Note:** Search-engine operators and platform behavior can change. Verify current behavior before treating any operator or platform-specific search pattern as guaranteed.
