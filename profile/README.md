<p align="center">
  <img src="./assets/trabyos-mark.png" width="88" alt="TrabyOS" />
</p>

<h1 align="center">TrabyOS</h1>

<p align="center">
  <strong>A voice-first trading workspace that stays at the top of your Mac.</strong><br />
  Ask about the market, prepare a paper trade, inspect the card, then approve, correct, or cancel it by voice.
</p>

<p align="center">
  <a href="https://github.com/TrabyOS/trabyos-test/releases/latest"><strong>Download the free paper-trading build</strong></a>
</p>

<p align="center">
  <a href="https://trabyos-website.vercel.app/">Website</a> ·
  <a href="https://github.com/TrabyOS/trabyos-test">Install & test guide</a> ·
  <a href="https://github.com/TrabyOS/trabyos-test#trabyos-test-한국어">한국어 안내</a>
</p>

## Speak, check, decide

Hold **Fn + Control**, speak, and release. TrabyOS turns the request into a card in the island anchored at the top
of the screen. A price or news request can be read immediately. A trade request remains a proposal: you see the
instrument, side, amount, order type, and leverage before anything can happen.

If something is missing, TrabyOS asks for it. If the amount is wrong, say the revised amount while the card is
waiting. Then approve, reject, or let the card expire. Confirmation belongs to that one proposal and is never
reused for the next one.

## What the public test build can do

| Ask for | What appears |
| --- | --- |
| Bitcoin price or chart | Live Binance market data and a candle chart |
| Account balance | The current simulated balances |
| A spot market order | A complete order card waiting for approval |
| A leveraged perpetual trade | A simulated position after approval |
| Closing a position | Realized paper P&L after the close is approved |
| Bitcoin news | A headlines card after a conversational follow-up |

Natural replies work while a card is waiting: “Yes, go ahead and place it,” “Actually make it 0.003,” or “No,
cancel that.” The interface keeps the original transcript with the proposal so the user can compare what was said
with what is about to be simulated.

## Real market context, no real-money path

The downloadable build uses live public Binance prices but connects to a simulated exchange. It starts each launch
with a fresh test account and has no exchange account attached, so it cannot place a real order. Balance checks,
order cards, fills, positions, and P&L all belong to that paper account.

This separation is deliberate: the public build lets anyone test the voice interaction, correction flow, and
approval boundary without supplying exchange credentials or risking funds.

## Try it on an Apple Silicon Mac

The current test build requires macOS 13 or later, an Apple Silicon Mac, an internet connection, and about 3 GB of
free space. The release includes a SHA-256 checksum and the repository explains first launch, microphone and
Accessibility permissions, local logs, and complete removal.

<p align="center">
  <a href="https://github.com/TrabyOS/trabyos-test/releases/latest"><strong>Download TrabyOS Test</strong></a>
</p>
