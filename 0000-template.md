# Title-cased Name of the Feature

- Status: proposed ("proposed", "agreed", "active", "implemented" or "rejected")
- Related to: (fill me with either "Kernel" or "CpcdosC+")
- Start Date: (fill me in with today's date, YYYY-MM-DD)
- Supersedes: (fill me in with a link to RFC this supersedes - if applicable)
- Superseded by: (fill me in with a link to RFC this is superseded by - if applicable)

# Summary
[summary]: #summary

One paragraph explanation of the feature.

## Conventions
[conventions]: #conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](http://tools.ietf.org/html/rfc2119).

# Motivation
[motivation]: #motivation

Why are we doing this? What use cases does it support? What is the expected outcome?

#Guide-level-explanation
[guide-level-explanation]: #guide-level-explanation

Explain the proposal as if it were already included in the language, or in the kernel, and you were teaching it to another CC+ programmer or Cpcdos OS2.2 contributor. This usually means :

- Introducing new named concepts.
- Explaining the functionality largely through examples.
- Explaining how CC+ programmers should *think* about the feature and how it should impact on the way they use it. The impact should be explained in as concrete a way as possible.
- Explain how the feature fits into the kernel and its relationship to different parts of it.
- If applicable, provide examples of error messages, depreciation warnings or migration advice.
- If applicable, describe the differences between teaching this functionality to existing CC+ programmers and to new CC+ programmers. The same applies to features to be added to the kernel.


# Reference-level explanation
[reference-level-explanation]: #reference-level-explanation

This is the technical portion of the RFC. Explain the design in sufficient detail that:

- Its interaction with other features is clear.
- It is reasonably clear how the feature would be implemented.
- Corner cases are dissected by example.

The section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

# Drawbacks
[drawbacks]: #drawbacks

Why should we *not* do this?

# Rationale and alternatives
[rationale-and-alternatives]: #rationale-and-alternatives

- Why is this design the best in the space of possible designs?
- What other designs have been considered and what is the rationale for not choosing them?
- What is the impact of not doing this?

#prior art
[prior-art]: #prior-art

Discuss prior art, the good and the bad, in relation to this proposal.
Here are some examples of what this might include:

- For language, library, cargo, tool and compiler proposals: Does this feature exist in other programming languages and what has been the experience of their community?
- For kernel proposals: Does this functionality exist in other kernels and what has been the experience of their community?
- For community proposals: Does this functionality exist in other communities and what has been their experience with it?
- For other teams: What lessons can we learn from what other communities have done here?
- Documents: Are there any published articles or interesting papers that deal with this topic? If you have relevant articles to refer to, they can serve as a more detailed theoretical basis.

This section is intended to encourage you as an author to think about the lessons from other languages, provide readers of your RFC with a fuller picture.
If there is no prior art, that is fine - your ideas are interesting to us whether they are brand new or if it is an adaptation from other languages.

Note that while precedent set by other languages is some motivation, it does not on its own motivate an RFC.
Please also take into consideration that rust sometimes intentionally diverges from common language features.

# Unresolved questions
[unresolved-questions]: #unresolved-questions

- What parts of the design do you expect to resolve through the RFC process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?

#Future possibilities
[future-possibilities]: #future-possibilities

Think about what the natural extension and evolution of your proposal would be
and how this would affect the project as a whole, in a holistic way.
Try to use this section as a tool to consider more fully all possible interactions with the project.
Also consider how this fits into the roadmap of the project and the sub-team concerned.

This is also a good place to 'throw out ideas', if they are out of scope for the RFC you are writing, but otherwise related.

If you have tried and can't think of any other possibilities,
you can simply state that you can't think of anything.

Note that having something written in the future possibilities section
is not a reason to accept the current or a future RFC; such notes should be in the
in the motivation or rationale section of this or subsequent RFCs.
This section simply provides additional information.
