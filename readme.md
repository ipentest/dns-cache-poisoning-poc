Simple shell script which takes up the domain input, checks it against the findsubdomains or spyse.com
It then adds a header X-Forwarded-Host with kirankarnad.com value and sends in a request. If there's a 200 response and includes kirankarnad.com, it means the site might be vulnerable.

