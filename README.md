# Payment Fraud Prevention: A Practical Guide for Global Businesses

(Working title, in progress)

Selling to customers in many countries means dealing with the rules of the international card networks, the risk controls of thousands of issuers, and attackers who probe every gap between them. This book sets out to cover card payment fraud prevention end to end: how a card payment works, where attackers get in, what authentication and card network rules can and cannot stop, how to build your own fraud program, and how to respond when something goes wrong.

## Who this book is for

1. Product, engineering, risk and operations teams at companies that sell across markets.
2. Engineers responsible for payment integrations, subscription billing and acquiring relationships.
3. Founders and leaders who want a structured view of card payment risk.

The book focuses on online, card not present payments on the international card networks.

## Status

The full outline is in [SUMMARY.md](SUMMARY.md).

| Section | Status |
|---|---|
| Preface | Draft |
| Chapter 4: What 3DS Stops, and What It Misses | First draft complete |
| Other chapters | Planned |

This English edition is adapted for a global audience from the Chinese edition, which is written for teams in China selling overseas. The two editions share the same structure, but the framing, examples and emphasis can differ.

## Building locally

The book is built with [mdBook](https://rust-lang.github.io/mdBook/):

```sh
mdbook serve --open
```

Mermaid sources and the rendered PNG files for each figure live in the matching chapter folder under `assets/`.

## Disclaimer

The views in this book are those of the author alone and do not represent any employer or organization. The book is for industry education and security awareness only, and is not risk, compliance or legal advice for any specific situation. Card network rules, regulations and statistics change over time; always check the latest official publications.

## Copyright

See [LICENSE.md](LICENSE.md).
