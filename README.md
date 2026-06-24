This repository contains reusable Cursor rules and commands for Java Spring Boot development.

The goal is to provide a consistent AI-assisted development workflow that helps teams design, implement, review, test, and document applications more effectively.

What this repo is for: 


Standardize AI-assisted Spring Boot development

Improve consistency across projects

Reduce repetitive prompt engineering

Encourage architecture-first development

Generate better code, tests, documentation, and reviews


What it contains : 


Rules :
Located in .cursor/rules/

ai-development-workflow.mdc - Structured Plan → Ask → Agent → Review → Refactor → Documentation → RCA workflow

spring-architecture.mdc - Spring Boot architecture and design standards

code-review.mdc - Code review checklist and quality standards

testing.mdc - Unit and integration testing guidelines

documentation.mdc - Documentation generation standards

rca.mdc - Root Cause Analysis framework for production issues


Commands : 
Located in .cursor/commands/

add-documentation.md

add-error-handling.md

code-review.md

optimize-performance.md

write-unit-test.md

These commands can be executed directly from Cursor to automate common development tasks.



How to use: 

Option 1 - Import from GitHub (Recommended)
Open Cursor.
Navigate to Settings → Rules.
Click New Rule → Import from GitHub/GitLab.
Select this repository.
Import the rules into your workspace.

Cursor will automatically apply the imported rules when working on your Spring Boot projects.

Option 2 - Copy into a Project
Clone or download this repository.
Copy the .cursor directory into the root of your Spring Boot project.




Recommended For:

Java Developers

Spring Boot Developers

Backend Engineers

Technical Leads

Teams adopting AI-assisted development workflows

