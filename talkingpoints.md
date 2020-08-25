# ZIO => Future as you expect it to behave

# Stacktrace
- Stack trace unreadable
- Not always possible to see where it failed

# Execution context is like a cocroach, it will be found everywhere
- Eager
- Memoization

# Future doesn't describe an execution it executes it
- Referencial transparency


# Error handling
- Errors are not reflected in types
  - Using eithers
- Errors are thrown away
- Error composition

# Integration with Future

# Requirements

# Cancellation
- When we race Futures they losers are not cancelled

