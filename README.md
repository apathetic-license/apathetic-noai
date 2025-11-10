# Apathetic No-AI Use Rider (aNOAI)

The **Apathetic No-AI Use Rider** (aNOAI) is a short, versioned addendum to
permissive licenses (e.g., MIT) that restricts use of a project for
training, fine-tuning, or improving machine-learning or AI systems. It is
designed to be **portable and easy to adopt**, and intended so that in the
future, once a majority of adopters feel the Rider is no longer necessary, its
restrictions can be removed.

> [!NOTE]
> This Rider does not restrict the use of AI tools in a project (which is nearly
> unenforceable). It only restricts the project licensed with it from being
> used as training data for AI.

## Usage

To apply the Rider to your project:

1. Include the text from [`RIDER_v1.md`](RIDER_v1.md) in your repository.
2. Include or reference it in your LICENSE (see our [MIT-aNOAI](LICENSE)
   license as an example) or documentation as needed.
3. Ensure you comply with the restrictions as described.

The Rider is **Version 1 or later**. Later versions may modify, replace, or
remove these restrictions. Always refer to the canonical source for the
latest version:

[https://github.com/apathetic-license/apathetic-noai](https://github.com/apathetic-license/apathetic-noai)

> [!WARNING]
> Adding this Rider changes the rights users have under your Base license,
> and the resulting modified license can no longer be considered official or
> OSI approved.

## Future versions

By saying `v1 or later`, users of your project may adopt any future version
published by the Apathetic License Collective.

The intent is that when members (see below) feel the legal and ethical
framework around AI properly compensates and represents contributions, all
projects using this Rider can remove their restrictions without relicensing,
including projects that are not actively maintained.

See our hypothetical future version
[`drafts/DRAFT_v99.md`](drafts/DRAFT_v99.md), which removes all restrictions.
This draft is **not intended for adoption** and exists solely for reference.

## Apathetic License Collective

The Rider is maintained by the **Apathetic License Collective**, a group of
contributors and projects who support oversight of the AI-use restrictions.

### Joining the Collective

To join the Collective:

* Your repository must be public.
* You must adopt a version of the Apathetic No-AI Use Rider.
* Your repository should have a minimal level of community visibility
  (e.g., ~5 GitHub stars or three contributors) to avoid spam entries.
* Organizations and individual accounts may register one vote each through a
  representative.
* Submit a PR updating [members.jsonc](members.jsonc) with your membership
  details for approval.

### Governance

* Members may propose changes to the Rider or future versions.
* Voting starts if 2 voting members support the change (or 1/3 of the
  membership, whichever is less) and lasts one month.
* Changes take effect if approved by a supermajority of members (80%) after
  the voting period ends. Only members who vote count toward the majority.
* The Collective may vote to modify, replace, or remove the restrictions in
  future versions, including a potential “null” version (v99) with no
  restrictions.

The Collective is intended to be **lightweight, transparent, and apolitical**,
providing a community-backed mechanism for versioning the Rider without
overcomplicating adoption.

## License

This repository is licensed under the MIT License with the **Apathetic No-AI
Use Rider v1.0 or later**. See [LICENSE](LICENSE) for details.
