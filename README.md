# Catalyst 9500 StackWise Virtual — Dual-Active Detection Lab

A step-through lab for Cisco Catalyst 9500 StackWise Virtual in a core/distribution/access campus design. It shows what happens when a member fails, when the StackWise Virtual Link (SVL) splits, and how each dual-active detection (DAD) method, Fast Hello and enhanced Port Aggregation Protocol (ePAgP), takes the old active switch out of the network. Each step has an animated topology, an explanation and the matching CLI (command-line interface) output.

**Open the lab:** https://alexpacket.github.io/catalyst-stackwise-virtual-guide/

## What's inside

- Seven scenarios: normal operation, active switch failure, SVL split with no DAD, Fast Hello DAD, ePAgP DAD, both methods together, and SVL plus DAD link cut together
- Release history from IOS XE 16.6.1 to 26.2.1
- Platform limits and restrictions for C9500, C9500H, C9500X and C9550
- Caveats, troubleshooting commands and a reference configuration

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The lab: one self-contained HTML page |
| `404.html` | Shown by GitHub Pages for missing paths |
| `favicon.svg`, `favicon.png` | Site icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Updating the lab

1. Edit `index.html` (or replace it with a new export).
2. Commit with a message that says what changed, for example `26.2.1: C9550 limits`.
3. Push to `main`. GitHub Pages republishes in about a minute.

Tag a commit when a new IOS XE release changes StackWise Virtual behavior (for example `release-26.2`) so earlier versions stay easy to find.

## Contributing

Corrections are welcome as pull requests (PRs). Cite the Cisco document and release that supports the change.

## Disclaimer

Built from public Cisco documentation: the Catalyst 9500 High Availability Configuration Guides (IOS XE 17.15 and 26.x), the Catalyst 9000 StackWise Virtual white paper, TAC tech note 216537 and the C9550 data sheet. Not an official Cisco publication. Verify behavior against the configuration guide and Bug Search Tool for your exact release before production use.
