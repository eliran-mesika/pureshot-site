# PureShot Site Agent Notes

## Product Focus

- This repo is the static public site for PureShot at `pureshot.mesikalabs.com`.
- Keep copy aligned with the current free Process Zero Cam launch: natural capture, local media handling, visible capture controls, and no tracking in the launch app.
- Do not add paid, subscription, cloud-sync, or account-system claims unless the app repo and App Store metadata already support them.

## MesikaLabs Contact Points

- General support: `support@mesikalabs.com`
- Privacy: `privacy@mesikalabs.com`
- Billing: `billing@mesikalabs.com`
- Legal: `legal@mesikalabs.com`
- App-specific support: `pureshot@mesikalabs.com`

## Validation

- Local smoke test: `python3 -m http.server 8089 --bind 127.0.0.1`
- Check `/`, `/support/`, `/privacy/`, `/terms/`, `/blog/`, `/blog/feed.json`, `/robots.txt`, and `/sitemap.xml`.
- Hosted checks after deploy: `curl -I -L https://pureshot.mesikalabs.com/ https://pureshot.mesikalabs.com/robots.txt https://pureshot.mesikalabs.com/sitemap.xml`
