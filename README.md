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
