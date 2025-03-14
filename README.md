# Memo
**Memo** generates token-optimized test and code quality reports specifically designed for LLM context. It transforms verbose test outputs, coverage metrics, and static analysis results into structured summaries that maximize information density while minimizing token usage.

## Key Features

 * Domain-based test result aggregation with intelligent failure categorization
 * Warning deduplication and pattern recognition to reduce repetitive logs
 * Progressive information disclosure with critical issues highlighted
 * Code quality integration with Black, isort, Radon complexity metrics, and MyPy
 * HTML reports for human consumption alongside tokenized reports for LLM ingestion
 * Customizable output formats optimized for different LLM context windows

Memo helps you feed relevant testing context to language models without overwhelming them with thousands of lines of logs, enabling more effective debugging assistance and code quality discussions with AI tools.

