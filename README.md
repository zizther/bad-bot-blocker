# Bad Bot Blocker

Apache htaccess rules to block bad bots

Bad bots are defined as:

- E-mail harvesters
- Content scrapers
- Spam bots
- Vulnerability scanners
- Aggressive bots that provide little value
- Bots linked to viruses or malware
- Government surveillance bots
- Chinese search engine Baidu

## Baidu
Unless your website is written in Chinese, you probably don't
get any traffic from them. It mostly just waste bandwidth and consume resources.

## Yandex
Yandex is a very popular search engine in Russia, and helps power DuckDuckGo.
Unless it is causing you issue, you can keep this commented. You can uncomment to block it.

## Bots Are Liars
Bots try to make themselves look like other software by disguising their
useragent. Their useragents may look harmless, perfectly legitimate even.
For example, "^Java" but according to
[Project Honeypot](https://www.projecthoneypot.org/harvester_useragents.php),
it's actually one of the most dangerous.

## Setup
If you have a bizarre or complicated setup, be sure to look everything
over before using it. But for anyone with something that resembles
a standard Apache installation, this should work without any issues.
