Source code for [sajnikanth.com](http://sajnikanth.com)

Setup
=====

* gihub pages throw a 302 sometimes. Read more about the issue [here](http://davidensinger.com/2014/04/transferring-the-dns-from-namecheap-to-cloudflare-for-github-pages/)
* To avoid that, use [cloudflare](https://cloudflare.com)
* Transfer DNS from namecheap to cloudfare
* Use CNAME instead of A record to point to sajnikanth.github.io
    * MX records not affected because cloudflare uses [CNAME flattening](https://support.cloudflare.com/hc/en-us/articles/200169056-CNAME-Flattening-RFC-compliant-support-for-CNAME-at-the-root)
