# Evidence for openclaw/openclaw#146143

Artifacts referenced from the pull request description. This branch holds only
captures and logs; it is not part of the pull request diff.

- `real-desktop-redacted.png`, `real-narrow-390-redacted.png` — grouped account
  quota cards rendered by this branch against a real local Gateway with four
  real saved OpenAI subscription profiles. Account identities are replaced with
  `Saved OpenAI account N`; quota values, plans and reset times are live.
- `real-refresh-rpc-log.txt` — `codex.accountUsage` requests observed on the
  Gateway WebSocket for the initial load and for one click of the shared
  Refresh control. Profile ids are replaced with stable pseudonyms.
- `real-proof-summary.json` — machine-readable capture summary.
- `mock-*.png` — the same page under the repository's Chrome end-to-end test
  with a mocked Gateway and synthetic `*.test` accounts, before and after one
  Refresh, at 1440px and 390px.
