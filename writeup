# Small writeup on gobuster

gobuster cmd
EXAMPLE:
  gobuster dir -u http(s)://IP ADRESS -w /path/to/wordlist -x php 

will brute force directories on IP ADDRESS, using the wordlist in /path/to/wordlist and it will look specifically for PHP files.

EXAMPLE:
  gobuster dir -u http://example.com -w /usr/share/wordlists/dirb/common.txt -o output.txt -t 50 -s 200,204,301,302,307,403 -x php,html,txt -v

this will brute force directories on example.com, using the wordlist in /usr/share/wordlists/dirb/common.txt, saving the output in output.txt, using 50 threads, will only search for status codes 200,204,301,302,307,403, will look for files with extension php, html and txt and will be verbose

-u, --url	Target URL
-w, --wordlist	Wordlist to use
-o, --output	Save output to a file
-k, --insecure	Skip SSL/TLS certificate verification
-t, --threads	Number of concurrent threads (default is 10)
-p, --proxy	Use a proxy (example: http://127.0.0.1:8080)
-s, --status-codes	Only show these status codes
-b, --status-codes-blacklist	Hide these status codes
-e, --expanded	Show full URLs and status codes
-r, --follow-redirect	Follow redirects
-c, --cookies	Cookies to send with requests
-H, --headers	Specify HTTP headers
-q, --quiet	Only show found entries (quiet mode)
-v, --verbose	Verbose output (more detail)
-x, --extensions	File extensions to append (e.g., .php,.html)
-a, --useragent	Set a custom User-Agent
--timeout	Request timeout (default 10 seconds)
--no-error	Don't display "error" messages
--wildcard	Force continued guessing even if wildcard responses are detected
