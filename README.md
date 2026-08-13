# Senior Code Review Mega Prompt

A language-agnostic mega prompt for reviewing, refactoring, testing, and improving code with a senior software engineering mindset.

**Version:** 1.0.0

## What it does

The prompt guides an AI assistant through a structured review of code in any programming language, including:

- correctness and hidden assumptions
- readability and maintainability
- function and architecture design
- defensive programming and error handling
- edge cases
- data structures and algorithms
- time and space complexity
- performance and profiling
- idiomatic language-specific practices
- dependency and configuration review
- security, logging, and observability when relevant
- reproducibility for scientific and bioinformatics code
- testing strategy and test cases
- incremental refactoring
- minimal and professional refactor versions
- trade-offs, overengineering checks, and transferable lessons

It also includes dedicated review guidance for R, Python, C/C++, JavaScript/TypeScript, SQL, and scientific/bioinformatics workflows.

## Usage

1. Open [`PROMPT.md`](PROMPT.md).
2. Copy the full prompt into your AI coding assistant.
3. Replace the placeholder under `CODE — Version 1.0` with your code.
4. Optionally provide project context, workload size, environment, and priorities.
5. Ask the assistant to start from Step 1 and work through the relevant review stages.

## Recommended input

For the best review quality, provide:

- the code
- the intended behavior
- sample input/output when available
- runtime or dependency constraints
- approximate data/workload size
- your priority: correctness, learning, performance, maintainability, or production readiness

## Philosophy

The prompt prioritizes:

1. Correctness
2. Clarity
3. Maintainability
4. Testability
5. Robustness
6. Performance

The goal is not to add as many abstractions or design patterns as possible. The goal is to produce the simplest design that reliably solves the real problem and remains understandable, testable, and maintainable.

## Prompt

See [`PROMPT.md`](PROMPT.md).
