# Kyverno AI Policy

**AI is welcome. Humans are responsible.**

Current AI tools are useful as coding assistants — but not as autonomous contributors. Anyone submitting content to Kyverno is fully responsible for the correctness, intent, testing, and licensing compliance of the contribution.

## General Guidelines

1. Contributors are fully responsible and accountable for all their submissions. This includes Pull requests (PRs), issues, comments or any other form of engagement with the project and its maintainers.

2. To avoid maintainer overload, contributors are limited to 8 open PRs at any given time across all repositories. Contributors are required to address all open PR comments and merge all open PRs, before creating additional PRs.

3. Contributors using AI to generate content should:

   * Thoroughly review all AI-generated content before submission

   * Understand the reason and impacts of the changes

   * Refine AI output to meet project quality standards

   * Take full ownership of all submitted content regardless of origin

   * Ensure content does not violate legal copyright or other laws

4. Pull Requests that include AI generated code can only be for issues that are accepted i.e., not labeled as “triage”.

5. Contributors SHOULD disclose any substantial use of AI. Disclosure SHOULD take the form of a trailer line within the commit attributing the AI tool used. Acceptable formats include:

   * Assisted-by: Claude \<noreply@anthropic.com\>

   * Co-authored-by: Claude \<noreply@anthropic.com\>

   * Generated-by: Claude \<[noreply@anthropic.com](mailto:noreply@anthropic.com)\>

   Many AI coding tools automatically add `Co-authored-by` trailers—this is acceptable and need not be changed to `Assisted-by`.

[Kyverno Maintainers](https://github.com/kyverno/community/blob/main/MAINTAINERS.md) are exempt from these rules and may use AI tools at their discretion; they've proven themselves trustworthy to apply good judgment.

## Website & Blog Guidelines

Kyverno accepts blog post contributions from maintainers and external contributors. For blog posts:

1. AI-generated images **are permitted** if disclosed correctly at the time of contribution

2. Contributors must ensure they have the right to use and publish any AI-generated media and cite AI usage

3. Media must not infringe on third-party copyrights or trademarks

4. AI-generated images should support the content and should never be used to replace thoughtful writing.

**Blog Content Expectations**

Blog posts are considered project contributions and must reflect original human authorship.

Contributors are expected to:

* Share original ideas, experiences, or informed perspectives

* Own the narrative, structure, and technical accuracy

* Use AI as a drafting or editing aid—not as the sole author

Blog posts that are primarily or entirely AI-generated, with minimal human insight, will be rejected.

Disclosure of AI assistance for blogs is encouraged for transparency but not mandatory unless requested.

## Legal and Licensing Considerations

Contributors must ensure:

* AI tool terms do not conflict with Apache 2.0 licensing

* No copyrighted or improperly licensed material is included

* All third-party content is properly attributed

* The Developer Certificate of Origin (DCO) can be truthfully signed

Contributors must also comply with their employer’s policies regarding AI-assisted open source work.

Kyverno follows CNCF / Linux Foundation guidance on AI-assisted development.

## Policy Evolution

This policy will be reviewed and updated as needed to reflect:

* Changes in AI tooling and use of this tooling across open source projects

* Legal or regulatory developments

* Maintainer and Reviewer experience in conjunction with community feedback

* Evolution of CNCF and industry best practices

## Questions and Feedback

Please share feedback and any questions or concerns about this policy including areas that feel too strict, or too permissive, enforcement concerns, gaps in the policy related to Kyverno-specific workflows, or any other thoughts:

* Open an issue in the community repo

* Discuss openly in the following community slack channels \#kyverno on CNCF and K8s Slack

* Adding topics to the weekly community meeting agenda

## References:

* CNCF / Linux Foundation: Guidance Regarding Use of Generative AI Tools for Open Source Software Development

* Ghostty AI Usage Policy

* KubeVirt AI Contribution Policy

* QEMU Code Provenance Policy

* Mitchell Hashimoto Blog

* [AGENT.md](https://github.com/ghostty-org/ghostty/blob/ca07f8c3f775fe437d46722db80a755c2b6e6399/src/inspector/AGENTS.md)

