# dns-resolvers

### What
A list of reliable DNS name servers (`resolvers.txt`) updated twice daily via GitHub Actions. This list uses [public-dns.info](https://public-dns.info/nameservers.txt) as its source, combining vortex's [dnsvalidator](https://github.com/vortexau/dnsvalidator) to validate DNS name servers.

### Why
The output can be a handy resource where resolvers are inputs for other tools (e.g. [massdns](https://github.com/blechschmidt/massdns])).

### Thanks
*Inspiration for this repo is heavily derived from [janmasarisk's similar repo](https://github.com/janmasarik/resolvers). The main reason for this project is to create a **larger** list of resolvers to work with (though working with a small list of resolvers can help to reduce false positives)!*
