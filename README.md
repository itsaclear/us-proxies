#us-proxies

##Proxy lists used
* http://us-proxy.org/
* http://sslproxies.org/
* http://google-proxy.net/
* http://free-proxy-list.net/
* http://free-proxy-list.net/uk-proxy.html
* http://free-proxy-list.net/anonymous-proxy.html

##Database format

| ip          | port    | type   | code    | country         | anonymity   | google        | https         | lastchecked                  |
|-------------|---------|--------|---------|-----------------|-------------|---------------|---------------|------------------------------|
| text        | integer | text   | text    | text            | text        | text          | text          | text                         |
| "123.5.1.4" | 8080    | "free" | "[us]"    | "United States" | "anonymous" | "yes" or "no" | "yes" or "no" | "[2016-03-29T17:34:54.814Z]"   |

##Types of proxy servers
* "free"
* "ssl"
* "us"
* "uk"
* "google"
* "anonymous"

##Types of proxy anonymity
* Level 1 - Elite Proxy / Highly Anonymous Proxy: The web server can't detect whether you are using a proxy.
* Level 2 - Anonymous Proxy: The web server can know you are using a proxy, but it can't know your real IP.
* Level 3 - Transparent Proxy: The web server can know you are using a proxy and it can also know your real IP.
