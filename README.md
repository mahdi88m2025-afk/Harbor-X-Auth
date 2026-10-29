# Harbor X authorization callback

Minimal original static return pages for the Harbor X desktop application by Splash.
Sign in only on each provider's official website. This site has no sign-in form,
token exchange, analytics, external assets, browser storage or automatic app launch.
Only the desktop app can validate its pending OAuth state and PKCE verifier.

GitHub can receive callback query parameters and logs visitor IPs. Fragment tokens
are not in HTTP requests, but remain sensitive to the browser, clipboard, extensions
and trusted code hosted on this same origin. No guarantee of no-store, frame-ancestors
HTTP headers, complete history erasure, or free-hosting uptime is made.
Project paths on the same account's github.io host share an origin.

Keep callback paths and repository/account names stable. Do not add third-party
scripts, telemetry, redirects, service workers or secrets. HTTPS must be enforced.
Original callback source is maintained in the private Harbor X development workspace;
only these reviewed static files are intended for this standalone public repository.
Provider registration and live sign-in acceptance are verified separately.
