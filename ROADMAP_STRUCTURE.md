# QE Center of Excellence - Roadmap Structure
## Source of Truth Document

---

# QE (Quality Engineer) Roadmap

## Junior

### Black Box Techniques
- Equivalence Partition
- Boundary Value Analysis
- Decision Table
- State Transition

### API Fundamentals
- REST Architecture
- HTTP Methods
- HTTP Status Codes
- Data Formats
- Request/Response Structure 
  - Headers, body, query parameters, path parameters
- Authentication Basics 
  - API Keys, Bearer tokens (conceptual)
- JSON Structure 
  - Objects, arrays, nesting, reading JSON
- Common Headers 
  - Content-Type, Authorization, Accept
- API Documentation Reading 
  - How to read Swagger/OpenAPI specs
- Error Responses 
  - Understanding error payloads

### SQL Fundamentals
- SELECT statement
- COUNT keyword
- WHERE Clause Operators - AND, OR, IN, BETWEEN, LIKE
- Basic Joins Explained - INNER JOIN, LEFT JOIN (visual understanding)
- ORDER BY & LIMIT - Sorting and pagination
- Aliases - Table and column aliases
- NULL Values - Understanding NULL behavior
- Aggregate Functions Intro - COUNT, SUM, AVG, MIN, MAX


### API Testing Fundamentals
- Postman
  - Collections
  - Requests
  - Variables
- Status Code Validation
- Payload and Schema Validation
- Header Verification

### Software Testing Fundamentals
- Software Testing Lifecycle
- Testing Approaches
  - Dynamic Testing
  - Static Testing
- Bug Lifecycle
- Psychology of Testing
- Types of Testing
  - Regression
  - Smoke
  - E2E
  - Sanity
  - Ad-hoc
  - Functional
  - Integration
  - Automation
- Test Case Design
- Test Maintenance
- Principles of Testing

### Programming Basics 
- OOP Fundamentals
- Variables & Constants - Declaration, scope, naming conventions
- Operators - Arithmetic, comparison, logical
- Functions/Methods - Parameters, return values, reusability
- Arrays & Lists - Basic collections
- Loops - For, while, foreach (practical examples)
- Conditionals - If/else, switch statements
- Basic Debugging - Reading error messages, print debugging

### Module: AI Fundamentals
- What is Artificial Intelligence
  - Machine Learning vs Deep Learning
  - What are LLMs (Large Language Models)
  - How AI Models are Trained
- AI Tools Overview
  - ChatGPT / Claude / Gemini
  - GitHub Copilot
  - AI in Testing Tools (Testim, Mabl)
- AI Limitations & Risks
  - Hallucinations
  - Bias in AI
  - When NOT to Trust AI

### Module: Prompt Engineering Basics
- Anatomy of a Good Prompt
  - Clear Instructions
  - Specific Requests
  - Expected Output Format
- Basic Prompt Patterns
  - Question Prompts
  - Task Prompts
  - Role Assignment ("Act as a...")
- Common Mistakes to Avoid

### Module: Context Engineering Basics
- What is Context in AI
  - Tokens Explained
  - Context Window Limits
- Providing Effective Context
  - Background Information
  - Relevant Examples
  - Constraints and Rules

---

## Intermediate 1-4

### Advanced API Testing
- Postman
  - Newman
    - Executing Newman Locally
    - JavaScript Validations
- Swagger
- Data-Driven & Parameterized Testing
- Authentication & Role-Based Access Control

### Accessibility Testing
- WCAG Principles
  - Level A
  - Level AA
  - Level AAA
- Color Contrast
- Text Alternatives
- ARIA Testing
- Keyboard Accessibility

### Mobile Testing
- Mobile Testing Techniques
  - Interruption
  - Localization
  - Performance
  - Network Testing
- Mobile Cloud
  - Testflight
  - Simulators
- Platforms
  - Native/Hybrid/Responsive
  - Real Devices
  - Emulators

### Programming
- Hands-On Experience
  - Abstraction
  - Encapsulation
  - Inheritance
  - Polymorphism
- Collections & Data Structures
  - Lists
  - Maps
  - Sets
  - Arrays (practical usage)
- String Manipulation
  - Regex basics,parsing, validation
-File I/O Operations
  - Reading/writing files (CSV, JSON, logs)
- Exception Handling
  - Try/catch, custom exceptions
- Unit Testing Basics
  - What are Unit tests and benefits
- Code Reading & Debugging
  - Understanding existing code
  - Using debuggers

### SQL Intermediate
- Advanced Joins
  - Right Join
  - Full-outer Join
  - Self Join
- Aggregations
- Subqueries
- Constraints
- GROUP BY & HAVING 
  - Grouping with conditions
- CASE Statements 
  - Conditional logic in queries
- UNION / INTERSECT / EXCEPT 
  - Combining result sets
- NULL Handling 
  - COALESCE, NULLIF, IS NULL patterns
- Date/Time Functions 
  - Date manipulation, formatting

### Module: AI Deep Dive
- LLM Architecture (Conceptual)
  - Transformers Overview
  - Token Prediction
  - Temperature & Creativity Settings
- AI Model Comparison
  - GPT vs Claude vs Gemini
  - Strengths & Weaknesses
  - Cost Considerations
- Hands-on Tool Experience
  - Copilot
  - Claude Code
  - AI Browser Extensions

### Module: Prompt Engineering Intermediate
- Prompt Frameworks
  - TRICE+ (Task, Role, Instructions, Context, Examples)
  - RACE (Role, Action, Context, Execute)
  - CREATE Framework
- Advanced Techniques
  - Few-Shot Prompting (Examples)
  - Chain of Thought (Step-by-step)
  - Zero-Shot vs Few-Shot
- QE-Specific Prompts
  - Test Case Generation
  - Bug Report Writing
  - Requirements Analysis
  - Test Data Creation

### Module: Context Engineering Intermediate
- Context Optimization
  - Prioritizing Information
  - Trimming Irrelevant Data
  - Structured Context Templates
- Multi-Turn Conversations
  - Building on Previous Responses
  - Conversation Memory
  - When to Start Fresh
- Context for QE Tasks
  - Providing Requirements Context
  - Sharing Test Scenarios
  - Including Error Logs

---

## Senior 1-2

### Software Automation
- Front-end Automation
  - Low Code
  - Testim
  - Mabl
  - Cypress Prompt
- Selenium / Playwright
  - XPaths
  - Script Maintenance
  - Test Frameworks
    - TestNG
    - NUnit
    - Cucumber

### Performance Testing (Conceptual)
- Testing Types
  - Load Testing
  - Stress Testing
  - Volume Testing
  - Soak Testing
  - Scalability Testing
- Performance Testing Tools
    - JMeter
    - Load Runner
    - Blaze Meter

### Advanced Testing
- DoD & DoR Analysis
- Release Management
- Advanced Test Techniques
  - Risk-Based Testing
  - Dynamic Test Selection
- Estimations
  - Algorithmic & Probabilistic Forecasting
- Reporting
  - Defect Leakage
  - Defect-Reopen Rate
  - Test Coverage
  - Story Coverage

### Advanced SQL
- Views
- Stored Procedures
- SQL Injection
- Windows Functions
- Query Optimization & Execution Plans 
  - Understanding EXPLAIN/ANALYZE to identify slow queries
- Indexing Strategies 
  - When and how to use indexes effectively
- Transactions & Locking 
  - ACID properties, deadlocks, isolation levels
- Database Performance Testing 
  - Identifying bottlenecks, query profiling
- Data Integrity Validation - Constraints verification, referential integrity checks


### Module: AI Mastery
- Advanced LLM Concepts
  - Fine-Tuning vs Prompting
  - RAG (Retrieval Augmented Generation)
  - Embeddings & Vector Databases
- AI Integration Strategies
  - API Access (OpenAI, Anthropic, Azure)
  - AI in CI/CD Pipelines
  - Custom AI Workflows
- AI Governance
  - Security & Privacy
  - Data Handling Policies
  - AI Ethics in Testing

### Module: Prompt Engineering Advanced
- Complex Prompt Design
  - Multi-Step Task Chains
  - Self-Reflection Prompts
  - Validation & Verification Prompts
- Prompt Patterns Library
  - Creating Reusable Templates
  - Team Prompt Standardization
  - Version Control for Prompts
- Advanced QE Applications
  - AI-Powered Test Planning
  - Automated Defect Analysis
  - Predictive Quality Metrics
  - Risk Assessment with AI

### Module: Context Engineering Advanced
- System Prompt Design
  - Persona Configuration
  - Behavioral Rules
  - Output Formatting
- RAG Implementation
  - Document Retrieval
  - Knowledge Base Integration
  - Dynamic Context Injection
- Context for Complex QE
  - Full Project Context Management
  - Cross-Team Knowledge Sharing
  - AI Memory Strategies

### Module: Synthetic Data Generation
- AI-Generated Test Data
  - Realistic Data Patterns
  - Edge Case Generation
  - Boundary Value Data
- Privacy-Safe Data
  - PII Anonymization
  - Compliant Test Data
- Data Validation
  - Verifying AI-Generated Data
  - Quality Checks

---

# SDET (Software Development Engineer in Test) Roadmap

## Junior

### Front-end Automation Fundamentals
- Selenium / Playwright
  - Handling Web Elements
  - Advantages and Limitations
  - Exceptions
  - Synchronization
  - Debugging Techniques
  - Assertions

### Programming Fundamentals
- OOP In Practice 
  - Classes, objects, constructors, access modifiers
- Inheritance & Polymorphism 
  - Abstract classes, interfaces, method overriding
- Error Handling Patterns 
  - Try/catch/finally, custom exceptions, throwing exceptions
- Data Structures Implementation 
  - Arrays, Lists, Maps/Dictionaries, Sets, Queues, Stacks
- Algorithms Basics 
  - Searching, sorting, iteration vs recursion
- Working with Libraries/Packages 
  - Package managers (npm, Maven, NuGet, pip)
- Unit Testing 
  - Writing testable code, assertions, mocking basics
- Code Organization 
  - Namespaces, modules, project structure
- SOLID Principles Introduction 
  - Single Responsibility, Open/Closed basics
- Generics/Templates 
  - Type-safe collections and methods
- Lambda Expressions 
  - Anonymous functions, functional basics

### API Automation Basics
- Bridge: Postman to Code
  - Reproduce Postman request in code
  - Read/navigate JSON response
  - Print/filter response fields
- Writing Your First API Test
  - GET request & assert status
  - POST request with JSON body
  - Validate response field
  - Chain two requests
- Making Tests Reusable
  - Extract base URL to config
  - Reuse headers across tests
  - Read body from JSON file
  - Read data from CSV file
- Working Without a Backend
  - Set up Postman mock server
  - Write tests against mock
  - Simulate error responses

### SQL Fundamentals
- DDL & Schema Understanding 
  - CREATE, ALTER, DROP, understanding table design
- All JOIN Types 
  - INNER, LEFT, RIGHT, FULL OUTER, CROSS, SELF
- Complex WHERE Clauses 
  - Compound conditions, subqueries in WHERE
- Aggregate Functions & GROUP BY 
  - COUNT, SUM, AVG with grouping and HAVING
- Database Connectivity from Code 
  - JDBC, ADO.NET, database drivers
- Parameterized Queries 
  - Preventing SQL injection, prepared statements
- Transaction Basics 
  - BEGIN, COMMIT, ROLLBACK from code
- Result Set Handling 
  - Mapping query results to objects
- Database Schema Navigation 
  - Understanding ERDs, foreign keys, relationships
- Indexes Awareness 
  - What they are, why they matter

### Module: Code Versioning Fundamentals
- Version Control Fundamentals
  - Understand why version control matters in automation projects
  - Difference between centralized and distributed systems
  - Clone, add, commit, push and pull in daily workflow

- GIT Basics
  - Set up GIT locally and connect to a remote repository
  - Track and stage changes before committing
  - Write meaningful commit messages for automation changes
  - View history and compare changes with git log and git diff

- Branching and Merging
  - Create and switch between feature branches
  - Merge a branch and resolve basic conflicts
  - Delete stale branches after merging
  - Understand the difference between merge and rebase conceptually

- Collaboration Basics
  - Fork and clone an existing automation repository
  - Open a pull request with a clear description
  - Apply feedback from a code review
  - Keep a branch up to date with main

### Module: CI / CD Fundamentals
- Core Concepts
  - Understand the difference between CI, CD and CD (delivery vs deployment)
  - Identify where automation tests fit in a pipeline
  - Read and interpret a basic YAML pipeline file
- Working with Pipelines
  - Trigger a pipeline manually and on code push
  - Read pipeline logs to identify why a test failed
  - Distinguish between pipeline failure and test failure
  - Re-run a failed pipeline and verify the fix
- Running Tests in CI
  - Configure a job to execute an existing test suite
  - Set environment variables for different test environments
  - Capture and publish test reports as pipeline artifacts
  - Notify the team on pipeline failure


### Module: AI for Developers
- What is Artificial Intelligence
  - Machine Learning vs Deep Learning
  - What are LLMs (Large Language Models)
  - How Code Generation Works
- AI Coding Assistants
  - GitHub Copilot Setup
  - VS Code AI Extensions
  - Reading AI Suggestions
- AI Safety & Limitations
  - Reviewing AI-Generated Code
  - Security Vulnerabilities
  - License Concerns

### Module: Prompt Engineering Fundamentals
- Writing Prompts for Code
  - Describing What You Need
  - Specifying Language/Framework
  - Requesting Explanations
- Basic Patterns
  - "Write a function that..."
  - "Explain this code..."
  - "Fix this error..."
- Learning from AI
  - Understanding Suggestions
  - Iterating on Results

### Module: Context Engineering Fundamentals
- Code Context Fundamentals
  - What Context AI Needs
  - File Structure Awareness
  - Dependency Information
- Providing Code Context
  - Sharing Relevant Files
  - Explaining Architecture
  - Specifying Constraints
---

## Intermediate 1-4

### Design Patterns Fundamentals
- Page Object Model
-   Creation of Scripts (Established Framework)
- Screen Play Pattern
  - Creation of Scripts (Established Framework)
- Singleton
- Page Factory
- Testing Approaches
  - BDD
  - TDD
- Testing Frameworks Implementation
  - TestNG - JUnit
  - NUnit - MsTest - Mocha
  - Cucumber / Specflow

### Front-end Automation Intermediate
- Dynamic Xpath Strategies
- Chrome DevTools Protocol
- Waits/Retry Management
- Handling Advanced Web Elements
  - Shadow DOM
  - iFrames
- Improved Debugging
- Multi-Framework Exposure
  - Selenium
  - Playwright
  - Cypress

### SQL Intermediate
- Window Functions 
  - ROW_NUMBER, RANK, DENSE_RANK, LEAD, LAG, PARTITION BY
- Common Table Expressions (CTEs) 
  - Recursive and non-recursive
- Complex Subqueries 
  - Correlated subqueries, EXISTS, IN vs JOIN
- Query Optimization 
  - Execution plans, EXPLAIN/ANALYZE, query tuning
- Indexing Strategies 
  - Clustered, non-clustered, composite, when to use
- Stored Procedures & Functions 
  - Writing, parameters, output handling
- Triggers & Events 
  - Understanding side effects, audit trails
- Views & Materialized Views 
  - When to use, performance implications
- Transactions & Locking 
  - Isolation levels, deadlocks, concurrency
- Dynamic SQL 
  - Building queries programmatically, security considerations
- Database Testing 
  - Data integrity validation, test data management
- NoSQL Awareness 
  - When relational vs document/key-value stores

### API Automation Intermediate
- Serialization / Deserialization
  - Map JSON response to a model/object automatically
  - Serialize request objects and handle nested arrays
  - Validate deserialized object fields against expected values
- Data Driven Testing
  - Parameterize tests using external JSON and CSV files
  - Run the same test with multiple data sets
  - Separate test data from test logic
- Response Validation
  - Assert nested fields, arrays and response time
  - Validate response against a JSON schema
  - Compare responses between environments (dev vs staging)
- Authentication and Security
  - Automate token retrieval and inject into requests
  - Handle token expiration and refresh flows
  - Test role-based access and unauthorized request responses
- API Test Organization
  - Chain requests to simulate real user flows
  - Build reusable request builders and response validators
  - Apply service class pattern (API equivalent of POM)
- Non-Functional Hands-on Experience
  - Performance Testing
    - Measure and assert baseline response times
    - Detect performance regression between builds
  - Stress Testing
    - Send concurrent requests and validate system behavior
  - Load Testing
    - Simulate sustained traffic and monitor error rate and latency
- Reporting and Debugging
  - Log full request and response details on failure
  - Capture and analyze failed request payloads
  - Integrate API test results into CI/CD pipeline reports

### Mobile Automation Intermediate
- Environment Setup
  - Configure Appium server and dependencies
  - Connect real device (USB debugging) and emulator/simulator
  - Validate device connection with ADB commands
  - Set desired capabilities for Android and iOS
- Locators and Element Interaction
  - Locate elements using Appium Inspector
  - Use resource-id, accessibility-id, xpath strategies
  - Handle dynamic elements with explicit waits
  - Scroll to find off-screen elements
- Gestures
  - Tap, long press, swipe, drag and drop
  - Pinch, zoom and multi-touch actions
- App Interaction
  - Install, launch and navigate between screens
  - Handle permissions, keyboard and background/foreground states
  - Switch between native and webview contexts
- Mobile-Specific Scenarios
  - Interrupt testing (calls, SMS, push notifications)
  - Network condition changes and device orientation
  - Handle OS-level popups, alerts and deep links
- Framework Integration
  - Apply Page Object Model for mobile
  - Capture screenshots on failure and generate reports
  - Run tests across emulator and real device

### Code Versioning Intermediate

- Git Workflows
  - Understand and apply Gitflow, trunk-based and feature branch strategies
  - Define branching conventions for a test automation repository
  - Collaborate on shared automation frameworks without conflicts
- Undoing Changes
  - Use git revert to safely undo commits in shared branches
  - Use git reset (soft, mixed, hard) to unstage or discard changes
  - Recover lost commits using git reflog
- Tagging and Releases
  - Create annotated and lightweight tags for test suite versions
  - Push tags to remote and link them to CI/CD release pipelines
  - Use tags to track automation framework versions against app releases
- Cherry-picking
  - Apply specific commits from one branch to another
  - Resolve conflicts that arise during cherry-pick
  - Use cherry-pick to hotfix automation scripts in release branches
- Squashing
  - Squash multiple commits into a single meaningful commit
  - Rewrite commit history before merging automation PRs
  - Use interactive rebase to clean up local commit history
- Rebase
  - Rebase a feature branch on top of main to keep history linear
  - Resolve conflicts during an interactive rebase
  - Understand rebase vs merge and when to use each
- Pull Requests and Code Review
  - Structure automation code changes into reviewable PRs
  - Write meaningful commit messages and PR descriptions
  - Review and comment on automation code changes
  - Resolve review feedback and re-request review
- Conflict Resolution
  - Identify and resolve merge conflicts in test files and configs
  - Use a diff tool to compare conflicting versions
  - Prevent conflicts by syncing branches frequently

### Module: AI-Augmented Development
- Advanced AI Tools
  - Copilot Advanced Features
  - Claude Code
  - Cursor IDE / AI-Powered IDEs
- AI for Test Automation
  - Generating Test Scripts
  - Creating Page Objects
  - Writing Assertions
- AI-Assisted Debugging
  - Error Analysis
  - Log Interpretation
  - Root Cause Suggestions

### Module: Prompt Engineering Intermediate
- Code Generation Prompts
  - Framework-Specific Prompts
  - Test Pattern Prompts
  - Refactoring Requests
- Prompt Techniques
  - Few-Shot with Code Examples
  - Chain of Thought for Algorithms
  - Specification-Based Prompts
- SDET-Specific Patterns
  - Test Framework Setup
  - API Test Generation
  - UI Automation Prompts
  - CI/CD Configuration

### Module: Context Engineering Intermediate
- Repository-Aware Prompting
  - Project Structure Context
  - Existing Code Patterns
  - Team Conventions
- Multi-File Context
  - Related File References
  - Import/Dependency Context
  - Test-Code Relationships
- Documentation as Context
  - API Specs
  - Requirements
  - Existing Test Plans

---

## Senior 1-2

### Programming Advanced / Best Practices
- Data Structures and Algorithms
- Design Patterns
  - SOLID
  - Behavioral Patterns
  - Structural Patterns
- Interfaces and Abstract Classes
- Functional Programming
- Clean Code Principles
- Test Driven Development - Hands-on experience

### Automation Design Pattern Development
- Framework Development & Implementation
- POM / Page Factory
- Screen Play Pattern / Screenplay BDD
- Singleton Design Pattern
- Parallel Execution

### Module: GIT Advanced

- Repository Architecture
  - Structure a mono-repo for multiple automation frameworks
  - Manage sub-modules for shared test libraries
  - Define and enforce branching strategies across teams
  - Set up branch protection rules and required reviewers
- Advanced History Management
  - Rewrite history across multiple commits with interactive rebase
  - Split a large commit into smaller logical units
  - Use git bisect to identify which commit introduced a bug
  - Audit and clean up stale branches at scale
- Automation Framework Versioning
  - Version and publish shared automation libraries
  - Manage dependency updates across multiple test projects
  - Maintain changelogs aligned to app release versions
  - Use semantic versioning for framework releases
- Git Hooks and Automation
  - Enforce code style and linting on pre-commit
  - Run smoke tests before push with pre-push hooks
  - Automate ticket references and commit message validation
  - Share hooks across the team using a hooks manager
- Governance and Best Practices
  - Define and document GIT conventions for QE/SDET teams
  - Conduct GIT training and onboarding for new team members
  - Audit repository health (branch count, stale PRs, commit quality)
  - Lead code review culture within the automation team

### CI/CD Advanced Topics
- YAML and Pipeline as Code
  - Write and maintain complex multi-stage pipeline definitions
  - Use variables, conditions and templates to avoid duplication
  - Parameterize pipelines to support multiple environments
  - Version control pipelines alongside automation code
- Docker in CI/CD
  - Build and maintain custom Docker images for test execution
  - Run test suites inside containers for environment consistency
  - Optimize image size and layer caching for faster builds
  - Use Docker Compose to spin up app and dependencies locally
- Multi-Stage Pipelines
  - Design stages for build, test, report and deploy
  - Run smoke, regression and API suites in parallel stages
  - Configure stage dependencies and failure conditions
  - Trigger specific test suites based on changed file paths
- Artifact Management
  - Publish and version test reports as pipeline artifacts
  - Share build artifacts between pipeline stages
  - Manage and publish shared automation libraries
  - Archive and retrieve historical test results
- Infrastructure as Code
  - Provision test environments using IaC tools
  - Tear down and recreate environments on demand
  - Manage environment variables and secrets securely
  - Validate environment health before test execution
- Pipeline Optimization and Governance
  - Identify and reduce bottlenecks in test execution time
  - Configure retry strategies for flaky tests in pipeline
  - Monitor pipeline health, failure trends and execution time
  - Define and document CI/CD standards for QE/SDET teams

### Module: API Automation Advanced Topics

- Contract Testing
  - Write consumer-driven contract tests with Pact
  - Publish and verify contracts between services
  - Integrate contract validation into CI/CD pipeline
  - Detect breaking API changes before they reach production
- API Mocking at Scale
  - Build and maintain mock servers for unavailable services
  - Simulate third-party APIs and edge case responses
  - Use mocks to unblock parallel development and testing
  - Version and manage mock definitions alongside tests
- Advanced Security Testing
  - Automate OWASP top 10 checks on API endpoints
  - Test for SQL injection and XSS via API payloads
  - Validate rate limiting, throttling and brute force protection
  - Automate OAuth 2.0 and JWT validation flows
- API Performance and Reliability
  - Define and automate SLA assertions (response time thresholds)
  - Run baseline and regression performance tests per build
  - Simulate traffic spikes and measure degradation points
  - Integrate performance results into pipeline quality gates
- Framework Design for API Testing
  - Design a reusable API testing framework from scratch
  - Build shared clients, interceptors and response validators
  - Support multi-environment configuration and auth strategies
  - Onboard and document the framework for team adoption
- Observability and Debugging
  - Correlate API test failures with backend logs and traces
  - Use distributed tracing to diagnose cross-service failures
  - Build dashboards to monitor API test coverage and health
  - Identify untested endpoints using coverage gap analysis

### Mobile Automation Advanced Topics
- Parallel Execution
  - Run tests simultaneously across multiple devices
  - Configure thread management and device allocation
  - Handle test isolation in parallel runs
- Multiple App Contexts
  - Automate flows across two or more apps
  - Handle deep links between apps
  - Manage state and data across app switches
- Mobile Device Virtualization
  - Configure and manage emulator/simulator farms locally
  - Optimize virtual device performance for CI runs
  - Simulate GPS, battery, network and sensor conditions
- Cloud Device Farms Integration
  - SauceLabs
  - BrowserStack
  - AWS Device Farm
  - Upload and execute test suites remotely
  - Analyze test results, logs and video recordings from cloud
  - Optimize cost by selecting device/OS coverage strategy
- CI/CD Integration
  - Trigger mobile test suites from pipeline
  - Distribute test execution across cloud and local devices
  - Configure reporting and failure notifications
- Performance and Stability
  - Detect memory leaks and CPU spikes during test runs
  - Measure app launch time and screen transition speed
  - Identify flaky tests and apply retry strategies

### Secondary Skillset Experience

### Module: AI Architecture
- LLM Integration
  - OpenAI / Anthropic APIs
  - Azure AI Foundry / AWS Bedrock
  - Self-Hosted Models (Ollama)
- AI in Test Infrastructure
  - AI-Powered Test Selection
  - Intelligent Test Prioritization
  - Self-Healing Locators
- Building AI Agents
  - Autonomous Test Agents
  - Multi-Agent Orchestration
  - Agent Frameworks (LangChain, etc.)

### Module: Prompt Engineering Advanced
- Complex Automation Prompts
  - Full Framework Generation
  - Migration Prompts (Selenium to Playwright)
  - Architecture Design Prompts
- Prompt Management
  - Prompt Version Control
  - Team Prompt Libraries
  - A/B Testing Prompts
- Advanced Patterns
  - Self-Correcting Prompts
  - Validation Chains
  - Multi-Model Orchestration

### Module: Context Engineering Advanced
- System Prompt Design
  - Custom AI Personas for Testing
  - Framework-Specific Instructions
  - Output Format Control
- RAG for Testing
  - Test Documentation Retrieval
  - Historical Test Data
  - Codebase Knowledge Bases
- Context Architecture
  - Dynamic Context Loading
  - Context Caching Strategies
  - Token Optimization

### Module: AI-Powered Frameworks
- Integrating LLMs in Frameworks
  - AI Test Data Factories
  - Dynamic Assertion Generation
  - Natural Language Test Steps
- Intelligent Reporting
  - AI-Generated Test Reports
  - Failure Analysis
  - Trend Prediction
- Self-Healing Automation
  - Locator Recovery
  - Test Self-Repair
  - Adaptive Wait Strategies
