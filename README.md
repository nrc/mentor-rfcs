# RFC mentoring

Interested in the [Rust RFC process](https://github.com/rust-lang/rfcs)? This is
a place to improve your RFC writing skills and collaborate on writing RFCs.

If you want to improve Rust, writing an RFC is an important stage in the
process. RFCs are the gateway for major changes to the language, core libraries,
and tools. However, writing a good RFC is difficult and can be intimidating (it
can be quite a complex process to navigate and the quality bar is high). Writing
an RFC should be accessible to the whole community. This repo is a step towards
making that a reality.

Here, you can work on real RFCs which will go through the RFC process and
hopefully get accepted. We'll collaborate on RFCs and you'll get feedback and
mentoring.

The initial emphasis will be on language RFCs (since I believe these are the
hardest for people to work on). If this is successful, I hope we can expand to
other areas.

Mentoring is open to anyone - you don't need to have contributed to the RFC
process, compiler, or other parts of the project before. However, to get the
most from this, you should know Rust pretty well, and should be interested in
getting deeply involved.


## How it works

We'll work on one RFC at a time, you can find the current RFC [here](https://github.com/nrc/mentor-rfcs/labels/current-rfc).
There will (hopefully) be multiple people collaborating on each RFC. Once an RFC
is ready for submission, we'll start work on the next one.

There will be [issues](https://github.com/nrc/mentor-rfcs/issues) for mentored
RFCs to work on. The issue will describe the subject of the RFC and link to any
previous discussion. It will cover some of the points that should be considered
and discussed in the RFC (e.g., tricky edge cases, or overlap with other
potential features). An issue will be assigned to a mentor, you don't need to be
assigned to work on the RFC.

You should ask any questions about an RFC or the RFC process in the issue.

There will be a directory for the current RFC (and for previous ones, for the
curious). All work should be in that directory. You should submit drafts of
parts of the RFC at a time (don't wait until you've written the whole RFC, and
don't polish too much before submitting initial drafts). Send PRs for your
work, you'll get most of the feedback as reviews of your PR. Feel free to give
constructive feedback on other people's PRs. Don't worry about duplicating work.

We'll pick the best bits from all the drafts to start the RFC. We will
then collaborate (again with PRs) to improve the RFC until it is ready for
submission. The mentor will then either submit the RFC into the RFC process, or
ask one of the collaborators to do so. The mentor will then
[shepherd](https://github.com/rust-lang/rfcs#the-role-of-the-shepherd) the RFC.
Collaborators should take part in the RFC discussion and keep improving the RFC
through the RFC process.


### Getting started

There should be enough info on the issue to get started. See [the FAQ](faq.md)
(WIP) for more general info. If you're still not sure, ask on the issue.


### Requesting an RFC for mentoring

RFCs to work on in the future are [queued](https://github.com/nrc/mentor-rfcs/issues?q=is%3Aopen+is%3Aissue+label%3Aqueued-rfc).
If there's one you're keen to work on, show your interest by voting with emoji.

If there's an RFC that you'd like to see mentored, file a new issue (we'll label
it [requested-rfc](https://github.com/nrc/mentor-rfcs/issues?q=is%3Aopen+is%3Aissue+label%3Arequested-rfc)).
To be a suitable RFC for this mentoring project, it should have a good chance of
being accepted (which means it should be motivated by the Rust roadmap), there
should be an appropriate mentor, and it should be of general enough interest
that we'd expect others to want to work on it. If it doesn't meet these
criteria, but you'd like help with writing the RFC, don't hesitate to reach out
to me (@nrc) or a member of the appropriate team.
