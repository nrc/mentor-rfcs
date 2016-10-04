# FAQ

### How do I get started writing an RFC?

The first step is to really understand what you are writing about. First
understand the motivation - what will this let you do that you can't do today?

You're likely to be extending existing parts of Rust, make sure you really
understand how those parts work. Then write some example programs using the
proposed feature - what are the rules for writing the feature? How would the
compiler check those programs? What uses of the feature should not be allowed?
How does proposed feature interact with other features?

Once you understand the feature, you can start writing. I would start with the
motivation section - make sure the RFC is well-motivated. Then iterate on the
detailed design (making sure you address points from the motivation) and
alternatives sections (I like to start early on the alternatives, since you
might find one of them is better than your original idea). Finally, write the
summary and other sections (I find it easier to write the summary *after* the
motivation and detailed design).
