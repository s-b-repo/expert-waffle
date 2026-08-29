# expert-waffle

`freemoney.py` is a gag script — six lines that intentionally do not
work. Two "constants" (`white`, `black`) are set to `1E999 ** 1E999
** …` which Python evaluates to `inf`, and the main loop calls
`open(os.walk('/'))`, which raises `TypeError` immediately (`open`
doesn't accept a generator).

There's nothing here to run. The repo exists as a joke; it's included
in the account's history and left as-is.

**Recommendation:** archive this repo on GitHub — `gh repo archive
s-b-repo/expert-waffle` — so it's clearly frozen. No functional code
is being lost.
