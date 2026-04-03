# QE Center of Excellence - Roadmap Structure
## Source of Truth Document

---

# QE (Quality Engineer) Roadmap

## Junior

### Module: Black Box Techniques (Fundamentals) 

- Equivalence Partition
  - Divide inputs into valid and invalid partitions
  - Write one test case per partition to avoid redundancy
  - Apply partitioning to ranges, strings, dropdowns and combined fields
- Boundary Value Analysis
  - Test min, min+1, max-1 and max values for every input range
  - Test just below and just above valid boundaries
  - Combine with equivalence partitioning for full coverage
- Decision Table
  - Identify conditions and actions from business requirements
  - Build a table mapping all condition combinations to expected outcomes
  - Eliminate impossible combinations and derive one test case per column
  - Spot missing or contradictory rules in requirements
- State Transition
  - Identify all possible states and map valid and invalid transitions
  - Draw a state transition diagram from requirements
  - Write test cases covering every state, valid transition and rejection
  - Apply to real flows such as login, order status and user roles
- Error Guessing
  - Anticipate common mistakes based on experience and intuition
  - Write test cases targeting empty fields, nulls and special characters
  - Test common edge cases like zero, negative numbers and max length
  - Challenge assumptions in requirements by asking "what if"
- Use Case Testing
  - Derive test cases from user stories and acceptance criteria
  - Cover the main success flow and all alternative flows
  - Identify and test exception flows and error scenarios
  - Map test cases back to requirements for traceability
- Exploratory Testing
  - Design and execute tests simultaneously without a script
  - Use time-boxed sessions with a defined charter and scope
  - Document findings, observations and bugs during the session
  - Combine with other techniques to investigate suspicious areas

### API (Fundamentals) 
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

### SQL (Fundamentals) 
- SELECT statement
- COUNT keyword
- WHERE Clause Operators 
  - AND, OR, IN, BETWEEN, LIKE
- Basic Joins Explained 
  - INNER JOIN, LEFT JOIN (visual understanding)
- ORDER BY & LIMIT 
  - Sorting and pagination
- Aliases 
  - Table and column aliases
- NULL Values 
  - Understanding NULL behavior
- Aggregate Functions Intro 
  - COUNT, SUM, AVG, MIN, MAX


### API Testing (Fundamentals)
- Postman
  - Collections
  - Requests
  - Variables
- Status Code Validation
- Payload and Schema Validation
- Header Verification

### Software Testing (Fundamentals) 
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

### Programming (Fundamentals) 
- OOP Fundamentals
- Variables & Constants 
  - Declaration, scope, naming conventions
- Operators 
  - Arithmetic, comparison, logical
- Functions/Methods 
  - Parameters, return values, reusability
- Arrays & Lists 
  - Basic collections
- Loops 
  - For, while, foreach (practical examples)
- Conditionals 
  - If/else, switch statements
- Basic Debugging 
  - Reading error messages, print debugging

### Module: AI (Fundamentals)
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

### Module: Prompt Engineering (Fundamentals) 
- Anatomy of a Good Prompt
  - Clear Instructions
  - Specific Requests
  - Expected Output Format
- Basic Prompt Patterns
  - Question Prompts
  - Task Prompts
  - Role Assignment ("Act as a...")
- Common Mistakes to Avoid

### Module: Context Engineering (Fundamentals)
- What is Context in AI
  - Tokens Explained
  - Context Window Limits
- Providing Effective Context
  - Background Information
  - Relevant Examples
  - Constraints and Rules

---

## Intermediate 1-4

### API Testing (Intermediate)
- Postman
  - Newman CLI
    - Executing Newman Locally
    - JavaScript Validations
  - Request Chaining & Workflows
    - Passing Data Between Requests
    - Pre-request & Test Scripts
  - Environment & Variable Management
    - Collection / Global / Environment Variables
    - Managing Dev / Staging / Prod Configs
  - Mock Servers
- Swagger / OpenAPI Validation
- Data-Driven & Parameterized Testing
- Negative & Edge Case Testing
  - Invalid Payloads & Missing Fields
  - Boundary Values on API Inputs
- Schema Validation
  - JSON Schema Response Validation
- Authentication & Role-Based Access Control
- API Monitoring Basics
  - Health Checks & Scheduled Runs

### Accessibility Testing (Intermediate)
- WCAG Principles
  - Perceivable
  - Operable
  - Understandable
  - Robust
  - Conformance Levels (A / AA / AAA)
- Visual Accessibility
  - Color Contrast Ratios (4.5:1 / 3:1)
  - Text Alternatives & Alt Text
  - Focus Indicators
- ARIA Testing
  - Roles, States & Properties
  - Landmarks & Live Regions
- Keyboard Accessibility
  - Tab Order & Focus Management
  - Skip Navigation
- Screen Reader Testing
  - VoiceOver (macOS/iOS)
  - NVDA / JAWS (Windows)
- Automated Tools
  - axe DevTools / Lighthouse
  - WAVE

### Mobile Testing (Intermediate)
- Mobile Testing Techniques
  - Interruption Testing
    - Calls, Notifications, Low Battery
  - Localization & Internationalization
  - Performance Profiling
    - Memory Leaks / CPU Usage
  - Network Testing
    - Throttling / Offline Mode
- Interaction Testing
  - Gestures (Swipe, Pinch, Long Press)
  - Deep Linking & Universal Links
  - Push Notifications
  - App Permissions & Privacy Prompts
- Mobile Cloud & Distribution
  - TestFlight / Firebase App Distribution
  - Simulators vs Emulators vs Real Devices
- Platforms
  - Native / Hybrid / Responsive Web
  - iOS vs Android Differences
  - Device Fragmentation

### Programming - Extension
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

### SQL (Intermediate)
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

### Module: Prompt Engineering (Intermediate)
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

### Module: Context Engineering (Intermediate)
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

### Module: Software Automation
- Automation Strategy
  - Define what should and should not be automated
  - Identify the right automation level (UI, API, unit) per scenario
  - Evaluate and recommend tools based on project needs
  - Estimate automation effort and maintain coverage metrics
- Low Code Tools
  - Testim — create and maintain AI-assisted scripts using smart locators
  - Mabl — record, maintain journeys and analyze auto-detected regressions
- Selenium / Playwright
  - Write stable locators that survive UI changes (id, css, xpath, accessibility)
  - Write scripts covering happy path and edge cases
  - Refactor and update scripts after UI changes
  - Apply basic POM structure to organize scripts
  - Use explicit waits and fix flaky tests caused by timing issues
  - Catch common exceptions and add meaningful error messages
- Test Frameworks (Conceptual Awareness)
  - TestNG / JUnit / NUnit — suites, annotations, parallel execution
  - Cucumber — feature files, step definitions and Gherkin scenarios
- Automation in the QE Process
  - Triage failures and distinguish flaky tests from real bugs
  - Report automation coverage and results to the team
  - Integrate suites into CI/CD for smoke, sanity and regression runs

### Performance Testing (Conceptual)
- Core Concepts
  - Differentiate Load, Stress, Volume, Soak and Scalability testing
  - Define performance acceptance criteria and SLAs with the team
  - Recognize common issues such as memory leaks, bottlenecks and timeouts

- Test Design and Planning
  - Identify critical user journeys worth performance testing
  - Define realistic load patterns based on real usage data
  - Document entry and exit criteria for performance test runs
- Tools
  - JMeter — execute existing scripts, adjust thread count and interpret reports
  - BlazeMeter — run cloud-based tests and share results with stakeholders
  - LoadRunner — interpret results generated by the performance engineering team
- Results Analysis
  - Identify response time degradation and error rate spikes
  - Distinguish between frontend, backend and network bottlenecks
  - Correlate results with infrastructure metrics (CPU, memory)
  - Track performance trends across builds and releases
- Collaboration and Process
  - Coordinate with developers and DevOps to resolve bottlenecks
  - Advocate for performance testing as part of the definition of done
  - Raise performance risks early based on architecture and load expectations

### Testing Best Practices (Advanced)
- Risk-Based Testing
  - Prioritize coverage using likelihood and impact per feature
  - Adjust depth and scope based on risk level
  - Document and communicate risk decisions to stakeholders
- Dynamic Test Selection
  - Select regression tests based on scope of change
  - Reduce execution time without sacrificing meaningful coverage
- Estimations
  - Break down effort by complexity and risk
  - Apply algorithmic forecasting for predictable work
  - Apply probabilistic forecasting for ambiguous features
  - Communicate estimates with confidence ranges not single numbers
- Shift-Left Testing
  - Involve QE from requirements and design phases
  - Challenge acceptance criteria before development starts
  - Identify testability issues early to reduce cost of defects
- Continuous Testing
  - Define quality gates that block pipeline progression on failure
  - Monitor test results across builds and flag coverage gaps
  - Balance fast feedback with meaningful test depth
- Feature Flags and Progressive Delivery
  - Validate behavior when features are toggled on and off
  - Test flag combinations and coordinate scope with canary releases
- Observability and Monitoring as Testing
  - Use logs, traces and metrics to validate system behavior
  - Correlate production incidents with gaps in test coverage
  - Treat production monitoring as an extension of the test strategy
- Reporting and Metrics
  - Defect Leakage, Defect-Reopen Rate, Test Coverage, DoR and DoD
  - Present metrics as quality signals not just numbers
- Release Management
  - Define testing scope, sign-off criteria and go/no-go recommendations
  - Assess readiness based on metrics, risk and open defects

### SQL (Advanced)
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


### API Testing (Advanced)
- API Test Strategy
  - Defining Coverage Across Endpoints (CRUD, Edge Cases, Security)
  - Risk-Based API Test Prioritization
  - Contract Testing Awareness (Pact, Spring Cloud Contract)
- API Security Testing
  - OWASP API Top 10 Awareness
  - Evaluating Auth Flows (OAuth2, JWT, API Keys)
  - Injection & Broken Access Control Testing
- API Governance & Quality
  - Reviewing API Documentation for Completeness
  - Evaluating Versioning & Deprecation Impact
  - Cross-Team API Dependency Mapping
- CI/CD Awareness
  - Evaluating API Test Results in Pipelines
  - Identifying Gaps in Automated API Coverage
  - Collaborating with SDETs on Test Suite Health

### Accessibility Testing (Advanced)
- Accessibility Test Strategy
  - Defining Org-Wide Standards (A vs AA targets)
  - Risk-Based Accessibility Prioritization
- CI/CD Awareness
  - Understanding a11y Gates in Pipelines
  - Evaluating Automated Scan Results (axe-core, Lighthouse)
- Accessibility Auditing
  - VPAT / ACR Documentation
  - Third-Party Audit Coordination
- Inclusive Design Advocacy
  - Shift-Left Accessibility
  - Developer & QA Coaching

### Mobile Testing (Advanced)
- Mobile Test Strategy
  - Device Matrix Strategy
  - Coverage vs Cost Trade-offs
  - Cloud Device Farms (BrowserStack, Sauce Labs)
- Mobile Automation Fluency
  - Reading & Evaluating Appium / XCUITest / Espresso
  - Reviewing Automation Coverage Gaps
  - Collaborating with SDETs on Framework Decisions
- Mobile CI/CD Awareness
  - Understanding Build Pipelines (iOS & Android)
  - Evaluating Release Readiness
- Mobile Performance & Security Evaluation
  - Interpreting Profiler Results (Instruments / Android Profiler)
  - Evaluating Certificate Pinning & API Security Posture

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

### Module: Front-end Automation Fundamentals

- Framework Awareness
  - Understand differences between Selenium and Playwright conceptually
  - Set up and run your first automated test in both frameworks
- Handling Web Elements
  - Locate elements using id, name, css and xpath
  - Interact with inputs, buttons, dropdowns, checkboxes and alerts
  - Extract and validate text, attributes, visibility and state
- Synchronization
  - Understand why timing issues cause test failures
  - Apply explicit waits for dynamic and conditional elements
  - Replace hardcoded sleeps with proper wait strategies
- Exceptions and Debugging
  - Recognize and handle common exceptions (NoSuchElement, StaleElement, Timeout)
  - Read stack traces and use DevTools to locate failure root cause
  - Capture screenshots on failure for reporting
- Assertions
  - Assert element presence, text, attributes and navigation outcomes
  - Write meaningful assertion messages for faster failure diagnosis
- Script Organization
  - Separate locators, actions and assertions
  - Apply basic POM structure to organize scripts by page
  - Write reusable methods for repeated interactions


### Module: Programming Fundamentals
- OOP Basics
  - Create classes and objects to represent test components
  - Use constructors to initialize test objects with required data
  - Apply access modifiers to protect class members
- Inheritance and Polymorphism
  - Extend a base class to share common test behavior
  - Override methods to customize behavior per page or component
  - Understand when to use abstract classes vs interfaces
- Error Handling
  - Use try/catch/finally to handle failures gracefully
  - Throw meaningful exceptions with descriptive messages
  - Distinguish between expected and unexpected exceptions in tests
- Data Structures
  - Use lists and arrays to manage collections of test data
  - Use maps to store key-value test configurations
  - Choose the right structure for the task
- Working with Libraries and Packages
  - Add and manage dependencies using npm, Maven, NuGet or pip
  - Import and use external libraries in automation code
  - Understand versioning and why it matters in shared projects
- Code Organization
  - Structure a project into logical folders and modules
  - Write readable and self-documenting code from the start
  - Break repeated logic into reusable helper methods

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
  - Creation of Scripts (Established Framework)
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

### Module: Programming Advanced / Best Practices

- Data Structures and Algorithms
  - Choose the right structure for test data management
  - Optimize framework code using efficient algorithms
  - Identify and resolve performance bottlenecks in automation code
- Design Patterns
  - SOLID — apply across page objects, helpers and framework layers
  - Behavioral — Strategy, Observer, Command applied to test flows
  - Structural — Decorator, Adapter, Facade applied to framework layers
  - Creational — Factory, Builder, Singleton for object management
- Interfaces and Abstract Classes
  - Define contracts between framework layers using interfaces
  - Decouple test logic from implementation using abstraction
- Functional Programming
  - Use lambdas and streams to process test data collections
  - Apply immutability to avoid shared state issues in parallel runs
- Clean Code Principles
  - Write self-documenting code with consistent naming conventions
  - Refactor complex methods into small single-purpose functions
  - Lead code reviews focused on maintainability
- Test Driven Development
  - Write failing tests before implementing automation helpers
  - Apply TDD to framework utilities and shared components

### Module: Automation Design Pattern Development

- Framework Development and Implementation
  - Design architecture that scales across projects and teams
  - Separate concerns into layers (drivers, pages, tests, utilities, config)
  - Build onboarding documentation and contribution guidelines
  - Evaluate and evolve the framework as product and team grow
- POM / Page Factory
  - Implement POM with inheritance for shared page components
  - Use Page Factory for element initialization and lazy loading
  - Manage complex page hierarchies without duplication
- Screenplay Pattern / BDD
  - Implement actor, task and interaction layers from scratch
  - Integrate Screenplay with Cucumber for full BDD coverage
- Design Patterns in Frameworks
  - Singleton — manage driver and config instances safely
  - Factory — create driver and browser instances dynamically
  - Builder — construct complex test data objects fluently
  - Strategy — swap execution strategies without changing test code
  - Observer — implement event-based reporting and logging
- Parallel Execution
  - Design thread-safe page objects and shared utilities
  - Manage test data isolation to prevent cross-thread conflicts
  - Optimize suite distribution for fastest possible feedback
- Framework Governance
  - Define coding standards and enforce via linting and review
  - Maintain versioned framework releases with changelogs
  - Lead framework adoption across QE and SDET team members

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
  - Generate framework scaffolding, architecture and helper classes from specs
  - Migrate test suites between frameworks (Selenium to Playwright)
- Meta Prompting
  - Write prompts that generate and improve other prompts
  - Build self-refining loops that validate their own output
  - Use LLMs to evaluate and score prompt effectiveness
- Prompt Patterns
  - Chain of thought — step by step reasoning
  - Few-shot — examples to shape output structure
  - Role prompting — expert personas for domain-specific output
  - Self-correcting — model reviews and fixes its own output
  - Validation chains — output of one prompt feeds the next
  - Tree of thought — explore multiple paths before committing
- Multi-Model Orchestration
  - Combine models for generation, validation and critique roles
  - Build pipelines where models check each other's outputs
  - Integrate into CI/CD for autonomous test generation
- Prompt Management
  - Version control prompts alongside automation code
  - Maintain team prompt libraries and A/B test variations
- AI Agent Design
  - Design agents that autonomously explore and test features
  - Define goals, constraints and human-in-the-loop validation steps
- Evaluation and Quality Control
  - Detect hallucinations and invalid outputs in generated test code
  - Build automated evaluators that score generated test cases

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
