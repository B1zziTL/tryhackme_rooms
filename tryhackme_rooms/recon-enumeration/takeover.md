**Room = TakeOver**



1. add `IP` to `/etc/hosts` (also add all the subdomains in later steps)
2. access *http://futurevera.thm*
3. using `ffuf -u` enumerate the subdomains -> *portal.futurevera.thm* and *support.futurevera.thm* discovered
4. `portal` subdomain is a redirect to main page, `support` subdomain shows a new page under maintenance
5. source page doesn't reveal nothing significant, next step is inspecting the certificate to look for `Alt Names`
6. `Subject Alt Names` reveals *secrethelpdesk934752.support.futurevera.thm* -> this URL redirects to `AWS` web with embedded ***{flag}***



