+++
title = "Pactus Newsletter, July 2026"
description = """
Two things defined July: a new software release and a protocol upgrade that
changes how new PAC tokens enter circulation. Both were planned, both went smoothly.
"""
author = "Pactus Team"
date = "2026-08-06T00:00:00"
tags = ["newsletter"]
image = "pactus-newsletter-july-2026.png"
+++

## What Happened in July

Two things defined July: a new software release, and a protocol upgrade that
changes how new PAC tokens enter circulation. Both were planned, both went smoothly.

## Pactus 1.16.0 (New Jersey)

**Released July 9, 2026.** The headline change in this release is
**Block Reward Halving**, introduced through
**[PIP-55](https://pips.pactus.org/PIPs/pip-55)**. In simple terms, the number of
new PAC coins created for every new block will shrink at defined points in the future
instead of staying the same forever. This is called a "halving" because the reward
cuts in half each time.

New Jersey also activates **Secp256k1** support. This lets Pactus addresses work
with the same cryptographic method used by Bitcoin and most hardware wallets, so more
wallet types can now interact with Pactus directly.

> **Important:** Starting with this release, every wallet must have a password.
> If your wallet currently has no password, set one before you upgrade.
> Wallets without a password will not open after the upgrade.

Several security issues were also fixed, covering how the software handles unusual or
malformed network data. No user action is needed for these; they are resolved
automatically once you upgrade.

**[Download the latest version →](https://pactus.org/download/)**

> **If you run a validator node:** upgrade now. Nodes on the old version cannot
> produce blocks or earn rewards.

## PIP-55 Activated: New Reward Schedule Live

**Activated July 14, 2026, at block 7,675,113.** Following the release above,
the network itself switched over to the new rules. This is called Protocol Version 4.

Pactus does not use "hard forks" the way some other blockchains do. Instead, once
enough validators signal support for a change, the whole network switches to the new
rules at the same time, with no chain split and no interruption. That is what happened
here.

**[Read the full announcement →](https://pactus.org/2026/07/14/pip-55-activated-block-reward-halving-successfully-implemented/)**

The new reward schedule is:

| Block Height            | Block Reward |
| ----------------------- | -----------: |
| 1 – 8,000,000           |    1.000 PAC |
| 8,000,001 – 24,000,000  |    0.500 PAC |
| 24,000,001 – 56,000,000 |    0.250 PAC |
| 56,000,001 onward       |    0.125 PAC |

The 70/30 reward split between validators and the Pactus Foundation stays the same
at every stage.

A shrinking reward over time means PAC issuance slows down gradually instead of
remaining fixed forever. Over time, transaction fees are expected to make up a
larger share of what validators earn.

> **If you run a validator:** your node must be on a Protocol Version 4 compatible
> release. If it is not, it can no longer sync with the network, join consensus,
> or earn rewards.

## Stay Connected

Pactus community activity continues across Discord, Telegram, and X. Wherever you
are most active, that is the right place to ask questions or follow along.

## Thank You

Thanks to every validator who upgraded on time, and to everyone who helped others
do the same. July was a clean, well-coordinated upgrade.

On to the next one.
