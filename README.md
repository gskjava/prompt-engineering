# prompt-engineering
1️⃣ Create Full Spring Boot Project (Production Ready)
Act as a senior Spring Boot architect.

Generate a production-ready Spring Boot project with:

- Java 17
- Maven
- REST API structure
- Layered architecture (controller, service, repository)
- PostgreSQL integration
- JPA/Hibernate
- DTO pattern
- Global exception handling
- Validation
- Logging (SLF4J)
- application.yml configuration
- Unit tests using JUnit 5

Follow clean architecture and SOLID principles.


This gives complete structure.

🔥 2️⃣ Create CRUD Project (Simple)
Generate a Spring Boot CRUD project for managing Employees.

Include:
- Entity
- Repository
- Service
- Controller
- DTO
- Exception handling
- Proper HTTP status codes

🔥 3️⃣ Create Microservice-Style Project
Generate a Spring Boot microservice project structure.

Include:
- REST controller
- Service layer
- Repository
- Feign client example
- Dockerfile
- application.yml
- Proper package structure
- Health check endpoint

🔥 4️⃣ Add Security (JWT)
Add JWT-based authentication to this Spring Boot project.

Include:
- SecurityConfig
- JWT filter
- Authentication endpoint
- Password encoding
- Role-based authorization

🔥 5️⃣ Add Pagination + Sorting
Update this project to support pagination and sorting in all GET endpoints.

Use Pageable and Page<T>.
Return proper metadata in response.

🔥 6️⃣ Performance Optimized Template
Generate a Spring Boot project optimized for performance.

Include:
- HikariCP tuning
- Proper fetch strategies
- Caching example (Redis)
- Async processing example
- Logging best practices

🔥 7️⃣ Enterprise-Level Project Template
Act as a senior enterprise architect.

Generate a scalable Spring Boot project template including:

- Clean architecture
- DTO mapping using MapStruct
- Global exception handling
- Logging interceptor
- Request/response logging
- Validation layer
- Database migration using Flyway
- Test coverage structure
- Proper package naming conventions


This is strong for senior-level work.

🎯 How to Get Better Results from Copilot

Instead of:
❌ "Create spring boot project"

Say:
✅ "Create a production-ready Spring Boot 3 project with Java 17, PostgreSQL, layered architecture, validation, exception handling, and test structure."

Specific prompts = better output.

🚀 If Your Goal Is Recognition

You should use prompts like:

Generate a Spring Boot project following enterprise best practices suitable for a fintech application.


That makes you look architect-level.

Now tell me:

Do you want:

Basic project template?

Enterprise template?

Microservices template?

High-performance template?

Interview-ready template?

I’ll give you the exact best prompt for that goal.

Architecture,Refactoring and Optimization

Excellent 👌
Now you’re thinking at senior / architect level.

You want Copilot prompts for:

🏗 Architecture

🔄 Refactoring

⚡ Optimization

I’ll give you high-impact, real-world prompts you can use in a Spring Boot project.

🏗 1️⃣ ARCHITECTURE PROMPTS (Think Like an Architect)
🔥 Analyze Existing Architecture

Open root project and ask:

Act as a senior Spring Boot architect.

Analyze this project and explain:

- Architecture pattern used
- Package structure quality
- Dependency flow between layers
- Design patterns used
- Violations of clean architecture
- Tight coupling areas
- Scalability risks

Provide improvement suggestions.


This helps you see structural weaknesses.

🔥 Convert to Clean Architecture
Refactor this project structure to follow Clean Architecture.

Separate:
- Domain layer
- Application layer
- Infrastructure layer
- Controller layer

Explain folder restructuring and required changes.

🔥 Identify Architectural Risks
Review this Spring Boot project for:

- Layer leakage
- Direct repository usage in controllers
- Circular dependencies
- Transaction misplacement
- Hard-coded configurations

Rank risks by severity.


This is architect-level analysis.

🔄 2️⃣ REFACTORING PROMPTS
🔥 Reduce Cognitive Complexity
Refactor this class to reduce cognitive complexity below 10.

Maintain functionality.
Improve readability.
Apply SOLID principles.

🔥 Remove Code Duplication
Identify duplicate logic in this project.
Suggest reusable utility or service extraction.

🔥 Convert Field Injection to Constructor Injection
Refactor all service classes to use constructor injection.
Do not change business logic.

🔥 Improve Exception Handling
Replace local try-catch blocks with global exception handling using @ControllerAdvice.

🔥 Improve Testability
Refactor this service to improve unit testability.
Remove static calls.
Ensure proper dependency injection.

⚡ 3️⃣ PERFORMANCE OPTIMIZATION PROMPTS
🔥 Detect N+1 Query
Analyze this service and repository for N+1 query issues.
Suggest optimized fetch strategy.

🔥 Optimize JPA Fetch Strategy
Review entity relationships.
Suggest Lazy/Eager adjustments for performance.

🔥 Replace Loop with Set-Based Query

If dealing with DB loops:

Rewrite this logic to use batch processing or set-based operations.

🔥 Improve Transaction Boundaries
Review @Transactional usage.
Identify long-running transactions.
Suggest readOnly optimization.

🔥 High-Load Optimization
If this API must handle 10,000 requests per minute:

- Identify bottlenecks
- Suggest caching
- Suggest async processing
- Suggest connection pool tuning

🚀 Advanced Combined Prompt (Very Powerful)
Act as a senior enterprise architect.

Review this Spring Boot project for:

- Architecture quality
- Code smell issues
- Performance bottlenecks
- Scalability limitations
- Maintainability concerns

Provide:

1. Risk assessment
2. Refactoring roadmap
3. Optimization roadmap
4. Priority order of improvements


This is how senior engineers think.

🎯 How This Improves Recognition

If you start saying things like:

“I identified layer leakage and transaction misplacement.”
“There is potential N+1 risk in order service.”
“We can reduce response time by changing fetch strategy.”

You automatically move from developer → architect mindset.

Recognition increases naturally.

Now I want to focus you properly.

Which one is your biggest current pain?

Messy legacy project?

Performance issues?

Poor architecture?

Sonar complaints?

Hard-to-test code?

Tell me the real situation — I’ll give a targeted strategic plan, not generic advice.

code understanding and documentation

Excellent 👍
Code understanding + documentation is one of the strongest skills for senior recognition.

Most developers write code.
Few can understand large systems and document clearly.

If you master this using Copilot, you become the “go-to person”.

Let’s make this practical for Spring Boot.

🧠 PART 1 — Understanding a Spring Boot Project Using Copilot
🔥 1️⃣ Get High-Level Overview

Open root folder and ask:

Act as a senior Spring Boot architect.

Analyze this project and provide:

- Architecture overview
- Package responsibilities
- Request flow summary
- Database interaction overview
- External integrations
- Key business logic areas

Summarize clearly for onboarding a new developer.


This gives big-picture clarity.

🔥 2️⃣ Understand One Feature Completely

Open a controller and ask:

Trace this endpoint end-to-end.

Explain:
- Controller role
- Service logic
- Repository queries
- Transaction boundaries
- Exception handling
- Data transformations (DTO mapping)

Explain in simple terms.


This helps you explain confidently in meetings.

🔥 3️⃣ Understand Complex Method
Explain this method step-by-step.

- What problem does it solve?
- What are edge cases?
- What assumptions are made?
- Potential risks?

🔥 4️⃣ Detect Hidden Risks
Review this class and identify:

- Tight coupling
- Hidden side effects
- Null risks
- Concurrency issues
- Performance risks


Understanding risks = senior thinking.

📄 PART 2 — Generate Documentation Using Copilot

Now comes the powerful part.

🔥 1️⃣ Generate Technical Documentation
Generate technical documentation for this Spring Boot project including:

- Architecture overview
- Module description
- API endpoints summary
- Database schema explanation
- Configuration details
- Known limitations


You can paste into Confluence.

🔥 2️⃣ Generate API Documentation

Open controller and say:

Generate API documentation for these endpoints.

Include:
- Endpoint URL
- HTTP method
- Request body
- Response format
- Validation rules
- Example request/response

🔥 3️⃣ Generate Class-Level Documentation
Generate professional JavaDoc for this class.

Explain:
- Purpose
- Key methods
- Dependencies
- Usage example

🔥 4️⃣ Generate README File
Generate a README.md for this Spring Boot project including:

- Project overview
- Tech stack
- Setup instructions
- Configuration guide
- Running locally
- Testing
- Deployment steps


Very useful for visibility.

🔥 5️⃣ Generate Sequence Flow Documentation
Create a sequence flow explanation (text format) for this API request.

Show interaction between:
Controller → Service → Repository → Database

🚀 Advanced Prompt (Architect Level)
Act as a system architect.

Create onboarding documentation for this project including:

- System context
- Architectural decisions
- Dependency map
- Risk areas
- Future improvement recommendations


This is extremely powerful for recognition.

🎯 How This Improves Your Recognition

When you:

Explain system clearly in meetings

Create structured documentation

Help new joiners understand project

Identify risk areas early

You move from:

Developer → Technical Leader

Managers value clarity more than coding speed.

💡 Pro Strategy

When you finish documentation, send message like:

I have created technical documentation for better onboarding and future maintenance.

Visibility increases.
=========================================================================================
Act as a senior Java architect.

Review this code for:

- Clean code principles
- SOLID violations
- Design pattern misuse
- Readability issues
- Maintainability concerns
- Naming improvements
- Code duplication
- Error handling quality

Be specific and suggest improved code examples.
====================================================================================================

⚡ 2️⃣ Spring Boot Specific Review
Review this Spring Boot class for:

- Proper layering (Controller/Service/Repository separation)
- Dependency injection best practices
- Transaction management issues
- Exception handling strategy
- REST best practices
- DTO vs Entity separation
- Validation correctness
- Logging quality

Suggest improvements following industry standards.

🚀 3️⃣ Performance Review Prompt
Analyze this code for performance issues:

- N+1 query problems
- Inefficient loops
- Unnecessary object creation
- Blocking calls
- Large memory usage
- Improper caching

Suggest optimized version.


Very useful for slowness issues.

🔐 4️⃣ Security Review Prompt
Review this code for security vulnerabilities:

- SQL injection risks
- Input validation gaps
- Authentication/authorization flaws
- Sensitive data exposure
- Hardcoded secrets
- Logging of confidential data

Suggest secure alternatives.


This makes you look senior in reviews.

🧠 5️⃣ Refactoring-Oriented Review
Suggest refactoring opportunities in this code.

Focus on:
- Reducing complexity
- Improving modularity
- Removing tight coupling
- Improving testability
- Applying design patterns if appropriate

📊 6️⃣ Code Smell Detection Prompt
Identify code smells in this class.

Classify them as:
- Critical
- Major
- Minor

Explain why each is a smell and how to fix it.

🧪 7️⃣ Unit Test Review Prompt
Review these unit tests for:

- Coverage gaps
- Missing edge cases
- Mock misuse
- Flaky test risks
- Assertion quality
- Test readability

Suggest improvements.

🎯 8️⃣ PR Summary Generator (Very Powerful for Recognition)

After review:

Generate a professional PR review summary including:

- Strengths
- Improvement areas
- Risks
- Final recommendation

Keep it constructive and team-friendly.


You can paste directly in Git review.

🏆 Pro-Level Prompt (Architect Mode)
Act as a principal engineer.

If this code will scale to 1 million users:

- What will break first?
- What needs redesign?
- What technical debt exists?
- What monitoring is missing?
- What architectural risks exist?
- =======================================================================
- Act as a senior Spring Boot architect.

Based on this JIRA ticket, generate:

- Functional understanding
- Technical approach
- Affected modules
- Database changes (if any)
- API changes
- Validation rules
- Edge cases
- Risks
- Suggested implementation steps

Make it structured and clear.
=======================================================================
Break this JIRA story into technical development tasks.

Include:
- Backend tasks
- Database tasks
- API updates
- Unit test tasks
- Integration test tasks
- Deployment considerations
Great for sprint planning.

📄 3️⃣ Convert JIRA → Developer Notes
Create developer notes from this JIRA ticket including:

- Business context
- Assumptions
- Open questions
- Technical clarifications required
- Dependencies
- ====================================================================================
- enerate detailed test cases from this JIRA description.

Include:
- Positive scenarios
- Negative scenarios
- Edge cases
- Boundary conditions
- Validation tests
QA will respect you for this.

🔎 5️⃣ Find Gaps in JIRA (Senior Move)
Review this JIRA story critically.

Identify:
- Missing acceptance criteria
- Ambiguities
- Edge cases not covered
- Technical risks
- Performance concerns
- Security considerations
- ===========================================================================================
- 🎯 1️⃣ Convert JIRA Story → Technical Implementation Plan

Paste JIRA description and ask:

Act as a senior Spring Boot architect.

Based on this JIRA ticket, generate:

- Functional understanding
- Technical approach
- Affected modules
- Database changes (if any)
- API changes
- Validation rules
- Edge cases
- Risks
- Suggested implementation steps

Make it structured and clear.


This helps before you even start coding.

🧠 2️⃣ Convert JIRA → Task Breakdown
Break this JIRA story into technical development tasks.

Include:
- Backend tasks
- Database tasks
- API updates
- Unit test tasks
- Integration test tasks
- Deployment considerations


Great for sprint planning.

📄 3️⃣ Convert JIRA → Developer Notes
Create developer notes from this JIRA ticket including:

- Business context
- Assumptions
- Open questions
- Technical clarifications required
- Dependencies


Very useful for grooming discussions.

🧪 4️⃣ Convert JIRA → Test Cases
Generate detailed test cases from this JIRA description.

Include:
- Positive scenarios
- Negative scenarios
- Edge cases
- Boundary conditions
- Validation tests


QA will respect you for this.

🔎 5️⃣ Find Gaps in JIRA (Senior Move)
Review this JIRA story critically.

Identify:
- Missing acceptance criteria
- Ambiguities
- Edge cases not covered
- Technical risks
- Performance concerns
- Security considerations


This is how senior engineers stand out.

🚀 6️⃣ Generate API Contract from JIRA

If ticket is API-related:

From this JIRA ticket, generate:

- REST endpoint definition
- Request JSON
- Response JSON
- Validation rules
- Error responses
- HTTP status codes

🏗 7️⃣ Architecture Impact Analysis
Analyze architectural impact of this JIRA story.

- Will this increase coupling?
- Does it violate layering?
- Does it affect scalability?
- Does it require caching?
- Does it introduce transaction risks?


Managers love this thinking.

📊 8️⃣ Convert JIRA → PR Description

After coding:

Generate a professional PR description based on this JIRA.

Include:
- Summary
- Technical changes
- Testing done
- Risks
- Rollback strategy
- ===================================================================================
Explain this PostgreSQL stored procedure in detail:

- Input parameters meaning
- Output type
- Business logic flow
- Conditional branches
- Loops (if any)
- Transaction behavior
- Exception handling
- Performance concerns
This helps you explain it in meetings confidently.

🏗 3️⃣ Convert Procedure → Business Logic Explanation
Translate this procedure into business-level explanation.

Explain:
- What business problem it solves
- When it should be executed
- What assumptions it makes
- Possible failure scenarios
- =====================================================================
- Review this stored procedure for:

- SQL injection risks
- Unsafe dynamic SQL
- Permission issues
- Data exposure risks
🧪 7️⃣ Convert Procedure → Java Repository Call
Generate Spring Data JPA or JDBC code to call this PostgreSQL procedure.

Include:
- Parameter binding
- Transaction handling
- Exception handling
📄 8️⃣ Generate Documentation for Procedure
Generate technical documentation for this PostgreSQL procedure:

- Purpose
- Inputs
- Outputs
- Internal logic summary
- Tables touched
- Side effects
- Performance considerations
You can store in Confluence.

🚀 Advanced: Refactor DB Logic
Sometimes procedures are too complex.

Use:

Suggest how to simplify or refactor this procedure.

- Can logic move to application layer?
- Can query be broken into smaller parts?
- Can indexing strategy improve?

================================================================================
5️⃣ Performance-Oriented Refactoring
Refactor this code for better performance:

- Remove unnecessary loops
- Optimize stream usage
- Avoid repeated DB calls
- Improve memory efficiency
- Suggest caching if needed

🔄 6️⃣ Convert Imperative → Functional Style
Refactor this code using modern Java features:

- Streams
- Optional
- Lambda expressions
- Method references
- Collectors

Keep it readable.

🧪 7️⃣ Testability Refactoring
Refactor this class to improve unit testability:

- Reduce tight coupling
- Use dependency injection properly
- Remove static dependencies
- Improve separation of concerns


Very strong senior move.

🧹 8️⃣ Remove Code Smells
Identify and refactor code smells in this class.

Classify them as:
- Critical
- Major
- Minor

Provide improved version.

🏛 9️⃣ Architectural Refactoring
If this application needs to scale to high traffic:

Refactor this design to:

- Reduce coupling
- Improve modularity
- Support horizontal scaling
- Improve resilience
- Improve logging and monitoring


This is principal engineer thinking.

🧩 10️⃣ Large Method Refactoring

If method is 200+ lines:

Break this large method into smaller cohesive methods.

Each method should:
- Have single responsibility
- Clear naming
- Be independently testable

🧠 11️⃣ Legacy Code Refactoring
Refactor this legacy code:

- Replace deprecated APIs
- Modernize Java version usage
- Remove outdated patterns
- Improve exception handling

🎯 12️⃣ Refactor for Maintainability (Recognition Booster)
Refactor this code to improve long-term maintainability.

Focus on:
- Readability
- Clear boundaries
- Explicit contracts
- Logging improvements
- Error handling clarity

💡 Pro Strategy (Very Important)


















