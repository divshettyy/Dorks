# Contributing to Dorks

Thanks for considering a contribution! This repo is a curated list of Google and Shodan dorks for authorized security research, recon, and OSINT. The easiest way to grow it is by submitting new, working dorks via pull request.

## Ways to contribute

- **Add a new dork** to `Google.html` or `Shodan.html`.
- **Fix or improve an existing dork** (e.g. it no longer returns useful results, or can be made more precise).
- **Improve the site** — accessibility, performance, clearer categorization, small UI fixes.
- **Fix documentation** — typos, broken links, clarity improvements in the README.

## Guidelines for new dorks

1. **Test it first.** Only submit a dork you've actually run and confirmed returns relevant results.
2. **Keep it legal and ethical.** Dorks should be for discovering publicly indexed/exposed information, not for facilitating unauthorized access. Don't include anything that only makes sense as an attack against a specific, non-consenting target.
3. **Categorize it.** Place the dork under the relevant section/category so the list stays easy to scan.
4. **Keep formatting consistent** with the surrounding entries (same markup style, same quoting conventions).
5. **No secrets or live-target examples.** Use generic placeholders (e.g. `example.com`) rather than real domains, and never include credentials, tokens, or API keys in a PR.

## Submitting a change

1. Fork the repo.
2. Create a branch: `git checkout -b add-dork-<short-description>`.
3. Make your change in `Google.html` or `Shodan.html` (or the README).
4. Open a pull request describing what the dork finds and why it's useful.

## Reporting issues

If you find a broken dork, a dead link, or a bug on the live pages, please open an issue describing what you expected vs. what happened.

By contributing, you agree your submission is for authorized/educational security research use, consistent with the repo's [responsible use notice](README.md#️-use-responsibly).
