# Yadu Bhushan

Senior Backend / Platform Engineer | AI Automation, Payments, Reliability

Bengaluru, India | linkedin.com/in/yadu-bhushan-4a044aa2 | github.com/yadubhushan

## Summary

Senior backend and platform engineer with 12+ years of experience, including five years at Amazon and earlier work on credit-card APIs at Barclaycard US. Built Java services for payments, Prime membership, and Alexa routing. Since 2022, building independent products with Python, TypeScript, and Kotlin, including AI video automation and productivity apps.

## Core Expertise

- Backend engineering: Java and Python services, APIs, third-party integrations, and shared libraries.
- AI automation: OpenAI and OpenRouter integrations, media processing, background jobs, and web interfaces.
- Payments: credit-card APIs, installment-plan selection, and Prime billing recovery.
- Reliability: service migrations, shadow testing, dependency timeouts, monitoring, alarms, and runbooks.

## Technical Skills

- **Languages:** Java, Python, TypeScript, JavaScript, Kotlin, SQL
- **Backend:** Spring Boot, Spring MVC, REST APIs, SOAP APIs, Hibernate, Microservices, API Design, JMS
- **Cloud/Data:** AWS, GCP, Firebase, Firestore, Cloud Run, SQS/SNS-style queues, MySQL, Oracle DB
- **AI/Product:** OpenAI APIs, OpenRouter integrations, LLM provider abstraction, Next.js, React, Android/Kotlin, media processing
- **Reliability:** On-call, runbooks, production debugging, shadow testing, monitoring, alarms, downstream timeouts, API performance
- **Practices:** System design, design docs, PR-FAQs, code reviews, TDD/BDD, Agile/Scrum, mentoring

## Experience

### Independent Product Engineer

AI Video Automation and Productivity Apps | Nov 2022 - Present

- Built Python jobs for AI video automation, integrating AI providers, media processing, and cloud storage.
- Moved code shared across projects into a Python toolkit for database access, GCP/AWS storage, AI integrations, media processing, logging, secrets, and Cloud Run jobs.
- Shipped a Next.js and TypeScript interface for script generation. Users can configure OpenAI/OpenRouter models, save their settings, and track pipeline progress.
- Built AutoPomodoro in Kotlin with focus-session and habit tracking, camera-based face detection, and Firebase storage. Added multi-user support and task management, migrated screens to Jetpack Compose, and fixed crashes.
- Maintained personal study tools and a second-brain system for notes on system design, DDD, coding patterns, cloud services, and AI tools.

### Amazon - Software Development Engineer II

Prime Payments, Alexa Routing, Prime Internal Tools | Sep 2017 - Nov 2022

- Migrated components of Alexa's voice-routing system and added routing signals without increasing latency. Coordinated with teams supplying the data and checked the changes using shadow tests on production data.
- Helped build an event-driven Prime payment recovery flow that retried billing after members added a valid payment method. The launch projection was 450K additional memberships retained annually.
- Owned the operational setup and runbook for Prime payment recovery, covering SQS queues, visibility timeouts, monitoring, alarms, and support handoff.
- Built a configurable navigation framework for Prime content previews, replacing hardcoded paths and allowing marketplaces to customize behavior.
- Resolved blockers and correctness issues in Prime's internal preview tool. Project metrics showed usage rising from 11% to 38% and workflow failures falling from 45% to 20% in a month-over-month comparison.
- Added dependency-specific timeouts and availability and latency alarms to content-preview services, and helped prepare stress tests to address dependency risks.
- Built a reusable rule engine to select installment plans from customer and transaction data, keeping plan-selection rules separate from product integrations.
- Co-wrote the proposal and design for self-service Prime plan ingestion, implemented the G2S2 adapter, and helped transfer Prime systems from SLO to BLR without production issues.

### Veritas - Software Engineer II

Enterprise E-Discovery Platform | Jan 2017 - Sep 2017

- Developed document-review features for Clearwell, an enterprise e-discovery platform, using Java 8, REST, Hibernate, MySQL, and Struts 2.
- Implemented bulk redaction and deletion features for GDPR requirements. Contributed to investigation and refactoring of the job framework for large document operations.

### Barclaycard US - Backend Services Engineer

Business API / Credit Card Systems | Mar 2015 - Jan 2017

- Built credit-card services and APIs for accounts, payments, transactions, and rewards using Spring, Hibernate, Oracle DB, SOAP/REST, Maven, and JMS.
- Helped migrate a monolith to microservices and integrated TSYS and Maritz. Reduced a critical API's response time from about 25 seconds to 7-8 seconds.

### MetaDesign Solutions - Java/J2EE Engineer

Enterprise Web Applications | Jan 2012 - Mar 2015

- Built enterprise Java web applications and REST services with Spring and Jersey, and developed Struts 2 and SOAP features. Automated builds with Jenkins and supported remote deployments.
- Worked on Naehas Merge Server and Airmeals Pre-Buy, adding shopping-cart features and dynamic pages with JavaScript/jQuery and supporting deployments on Windows and Linux.

## Selected Work

- Alexa routing: Java service migration, integration of external signals, pre-fetching, and shadow testing on production data.
- Prime payment recovery: billing retries triggered by events, SQS queue configuration, monitoring, and support runbooks.
- AI video automation: shared Python libraries, Cloud Run jobs, Firestore, cloud storage, and AI and media-processing integrations.
- Prime preview tools: configurable navigation, validation fixes, UAT support, and service reliability improvements.
- Engineering practice: investigate existing systems, write designs and runbooks, plan incremental changes, review code, and help teammates learn the system.

## Education & Certifications

- B.Tech, Information Technology - Greater Noida Institute of Technology, UPTU (2008 - 2012)
- Coursera Machine Learning, Stanford University (2017); Java Web Component Development, NIIT (2009)
