# Spec Template

This document below defines the operations expected of {name of system}.

[[_TOC_]]

{links to sections}

//TODO include configuration?

## Operations

The following defines the signatures (parameters and return values) for each operation expected of {name of system}.

### {Operation 1}

This operation is expected to {insert description here}

```typescript
function functionName(args): ReturnValue;
```

#### {Operation 1} Args

Encapsulates the arguments required to {operation 1's goal}

```text
{Argument class definition in code}
```

#### {Operation 1} Result

The result should include {description of operation 1's result definition}.

Interface

```text
{Result class definition in code}
```

#### {Operation 1} Errors

The following outlines errors that can be thrown by the operation.

### Error Handling

The following outlines the strategy for {name of system}.

### Error Guiding Principals

1. {principal 1}
2. {principal 2}
3. ...

### Error Types

The following defines the known errors that could be thrown.

The properties included within the error are expected to be used to construct a meaningful error message and/or included as part of any error logging/telemetry.

#### {Error Type 1}

This error is intended to {description}.

```text
{Error type definition in code}
```

#### {Error Type 2}

This error occurs when {description}.

```text
{Error type definition in code}
```

## Outstanding Questions

- [ ] {question needing an answer}? _Answer to the question._

## References

- {link to other documents here}
