author:
  name: Ralph Meier
  twitter: ralphmeier
  url: http://daraff.ch
output: caching.html

--

# Caching

--

### Different Kind of Caches

* Browser Caches
* Proxy Caches
* Gateway Caches (Reverse Proxy Caches)
-> image

--

### HTTP Expiration and Validation
* Expiration = Can i take the ressource from my cache without requesting the server?
* Validation = Check on the server, if my ressource is still valid

--

#### Expiration - Expires Header

`Expires: Fri, 30 Oct 1998 14:19:41 GMT`

+ easy to use
+ good for static ressources (long caching time)
- Date is based on server time

--

#### Expiration - Cache Control Header
 
Cache-Control: max-age=600, s-maxage=600
private / public

#### Validation
Etag / Last-Modified


->image

--



