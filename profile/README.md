<p align="center">
  <img src="./assets/trabyos-mark.png" width="88" alt="TrabyOS" />
</p>

<h2 align="center">TrabyOS</h2>

<p align="center">
  Voice-first AI trading for macOS.<br />
  Say it, see the card, approve it out loud.
</p>

<p align="center">
  <a href="https://github.com/TrabyOS/trabyos-test/releases/latest"><strong>⬇ Download the free test build »</strong></a>
</p>

<p align="center">
  <a href="https://trabyos-website.vercel.app/">Website</a> ·
  <a href="https://github.com/TrabyOS/trabyos-test">Setup guide</a> ·
  <a href="https://github.com/TrabyOS/trabyos-test/releases/latest">Releases</a>
</p>

---

Hold push-to-talk, speak, release. What you asked for comes back as a card anchored at the top of the
screen — the TrabyOS island. **Nothing has been sent to an exchange yet.** The card waits, and becomes an
order only when you approve it out loud.

| You say | You get |
| --- | --- |
| "Show me the Bitcoin chart." | A live price card with a candle chart |
| "What's my balance?" | Your account summary |
| "Buy 0.001 Bitcoin on Binance spot at the market." | An order card, waiting |
| "Approve." | The order is placed and filled |
| "Open a 5x long on 0.001 Bitcoin." → "Approve." | A perpetual position |
| "Close my Bitcoin long." → "Approve." | Closed, with realized P&L |
| "Any news on Bitcoin?" | A headlines card |

A card also takes ordinary phrasing — "Yes, go ahead and place it.", "Confirm.", "No, cancel that." You
are answering a question, not reciting a command. **And silence is not consent:** an unanswered card
expires instead of executing.

Speech is ambiguous and a trade is not reversible, so which market a spoken phrase refers to is resolved
deterministically against a live public catalog rather than guessed. Notional minimums, leverage limits
and balance are checked before anything leaves, each confirmation is single-use, and the transcript is
kept so that what was said and what was approved stay auditable.

### The test build

Live Binance prices against a simulated exchange. No exchange account is connected and no real order can
be placed, so you can practice an order, a leveraged position and a close without risking anything — every
launch starts a fresh test account.

Apple Silicon Mac (M1 or later) · macOS 13+ · about 3 GB free · hold `Fn`+`Control` and speak English.
Needs microphone access, and Accessibility for global push-to-talk.

<p align="center">
  <a href="https://github.com/TrabyOS/trabyos-test"><strong>Talk to your Mac about Bitcoin →</strong></a>
</p>
