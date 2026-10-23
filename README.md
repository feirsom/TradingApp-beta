# TickSync (beta)

TickSync is a Windows desktop app for active day traders. It combines real-time
tick charts, candle charts (VWAP, EMAs, volume profile, footprint/delta, RVOL),
Level 2 and Time & Sales from IQFeed, DAS Trader Pro hotkey integration with
safety interlocks, trade lines on the chart, and built-in discipline rules.

The download also includes **TickSync Scanner**, which watches the whole U.S. market for names
that are moving and loads them into TickSync's charts, and **TickSync Analyzer**, which reviews
the sessions TickSync records.

**Invitation-only beta: the app needs a beta key.**

## Download

**[Download the latest release](https://github.com/feirsom/TradingApp-beta/releases/latest)**

## Requirements

- Windows 10 or 11 (64-bit)
- Your own DTN IQFeed subscription (market data; Level 2 optional). Start IQFeed and log
  in before opening TickSync. The scanner and TickSync's charts share your IQFeed symbol limit.
- About 20 GB of free disk space (TickSync keeps the last 5 trading days of recorded
  session data and deletes older days)
- DAS Trader Pro (optional). The charts, the scanner and the Analyzer work with any broker, or
  none; numpad hotkeys and symbol sync need DAS. During the beta, automatic exits and entry lines
  are Off to start; set one to Audit to see what it would send (it sends nothing).
- A beta key from the developer

TickSync connects to your own IQFeed and DAS Trader accounts. It does not
provide market data or brokerage services.

## Install

1. Download the zip from the [latest release](https://github.com/feirsom/TradingApp-beta/releases/latest).
2. Extract it to a folder.
3. Run `TickSync.exe`. Windows SmartScreen may say "Windows protected your PC"
   because the beta is not code-signed. Click **More info**, then **Run anyway**.
4. Paste your beta key when asked. The same key works in TickSync Scanner and TickSync
   Analyzer, which are in the same folder and open from TickSync's Menu.

## Beta key

TickSync is in an invitation-only beta, and the app needs a beta key. Keys are
issued by the developer and arrive with your invitation email. To request one,
email [hello@ticksync.app](mailto:hello@ticksync.app).

## Feedback

Send feature requests, changes and bug reports from the app (**Menu → Send Feedback...**), or
with the [feedback form](https://docs.google.com/forms/d/e/1FAIpQLScuv4PbIlL9dnwybhs4-Zd53YcjyRG9sggGZZ62tjjqsEh_6g/viewform).

Website: [ticksync.app](https://ticksync.app)

## Disclaimer

Trading involves risk, including the possible loss of capital. TickSync is beta
software provided as-is, without warranty of any kind. Nothing here is
investment advice. Not affiliated with DTN/IQFeed or DAS Trader.

© 2026 TickSync
