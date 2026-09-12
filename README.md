# wellbe.social

> wellbe.social will help you connect and share with the people in your life.
> In a healthy way. On your terms.

We are going to build a place to keep up with the people in your life, as a
democratically organised non-profit that intends to still be here in twenty
years.

What exists today is a waiting list and a statement of what we are going to be,
which is the right way round: people should get to read what we stand for
before we ask them to trust us with anything.

## What we choose, and what we are choosing it over

The long version is in [docs/principles.md](docs/principles.md), which is the
canonical text. The landing page quotes it; if the two ever disagree, this
repository is right.

1. **People's wellbeing** over **profit**.
2. **Valuable discussion** over **quick decisions**.
3. **Power split by organisation** over **technical decentralisation**.
4. **Automation in the rules we are bound by** over **promises about our good
   intentions**.

And the trade underneath all four: we are a democratically organised non-profit,
here for the long term. Democracies are slower. They also tend to create more
value, for more people, over more years.

## Where the pieces are

| | |
|---|---|
| [`pawe/wellbe-landing`](https://github.com/pawe/wellbe-landing) | The page people see today, and the waiting list behind it. Rust, axum, Postgres. |
| this repository | The product we are going to build. Currently the place where what we stand for is written down. |

## What is actually decided

Very little, deliberately, and it is worth being honest about which is which.

**Decided.** The four principles above. Non-profit, democratically organised.
Rust and Postgres. No engagement metrics, and nobody profiled so that things
can be aimed at them.

**Not decided.** The legal form and the country it is registered in. How
membership works, and what a member gets to vote on. Where the line falls
between rules that run automatically and judgements that stay with people.
Whether federation is worth its cost. How any of it is paid for — advertising
very much included, as long as it is the kind that needs neither a profile of
you nor a grip on your attention.

Those are open questions, not gaps waiting to be filled in quietly by whoever
writes the code first. They are listed in
[docs/open-questions.md](docs/open-questions.md) so that they get answered by
the organisation rather than by default.
