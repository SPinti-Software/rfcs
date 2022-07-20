# CpcdosC+ Specification

- Status: draft
- Related to: CpcdosC+
- Start Date: 2022-05-18
- Supersedes: 
- Superseded by: 

# Summary
[summary]: #summary

This RFC formalise CpcdosC+ syntax and basic spec, it's may be superseed by future RFC in order to extends CpcdosC+.

**This RFC may difer from other RFCs and from the template, since it's a special one**

## Conventions
[conventions]: #conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119).

# Motivation
[motivation]: #motivation

CpcdosC+, at the time of writing, lack of formal specification and his syntax lack of consistency. This RFC aim to address these problems.

```bnf
<alpha> ::= [a-zA-Z]
<num> ::= [0-9]
<alphanum> ::= <alpha> | <num>
<identifier> ::= (<alpha> | "_") (<alphanum> | "_")* 

<program> ::= <statement>+

<statement> ::= "let/" <identifier> "=" <expr>
    | "while/" <expr> ":" <statement>* "end/"
    | "txt/" <expr>

<expr> ::=
```