* By running HTTP over SSL/TLS, you enable an extra layer of security in what is commonly known as HTTPS
* However, the first version was actually never released because of its severe bugs and flaws.
* Over time, even more bugs have been fixed, and has been put to rest in 2015.
* SSL was meant to be the answer to authentication and authorization problems on the web.
* A different key is created for each client and server connection.
* Message digests were also introduced to detect and prevent data tampering.
* Usually, this means the server key has been stolen by the attacker, or the Certificate Authority has been spoofed/is untrustworthy/has been stolen.
* SSL is also pretty limited in security, especially compared to what TLS can offer.
* Its first version was released in 1999, as an upgrade to SSL v3.0.
* The "Enhanced Pseudorandom Function" is also used to generate key data, using two hash algorithms to increase security.
* There have been a couple of cryptographic exploits, which can be fixed by disabling weak SSL ciphers, and enabling strong TLS ones.
* Luckily, some exploits, such as BEAST (Browser Exploit Against SSL/TLS) are no longer considered valid threats on most modern browsers.
* Its powers can be used for good and evil.
* They are usually part of a larger man-in-the-middle attack, and can usually be fixed by removing backward compatibility.
* These domains included [login.yahoo.com](https://login.yahoo.com), [mail.google.com](https://mail.google.com), [login.skype.com](https://login.skype.com), and [addons.mozilla.org](https://addons.mozilla.org), which are all typically trusted websites.
* Luckily, this attack was found pretty quickly, and the certificates were quickly revoked.
* Most of these can be prevented by using stricter browser controls.
* Luckily, there are a lot more measures being taken on the CA side of things to prevent similar exploits.
* The project looks like it has been untouched for the last seven years.
* HTTPS is any HTTP request encrypted over SSL/TLS as an extra step to protect traffic.
* However, more companies are coming forward with different options, and I hope soon, HTTP can be deprecated on the web altogether.
* Absolutely all pages should be served over HTTPS.
* Also remember to preload the HTTP Strict Transport Security header into browsers, and make sure all of your cookies are marked as secure.
* This will treat all of your insecure HTTP URLs as though they are served as HTTPS.
* This is only a temporary solution in a lot of cases (some are generally fine, like images hosted over HTTPS anyway) because if you try to access a resource over HTTPS that is not actually served with SSL/TLS, you will not get a response.
* It does this by setting strict declarations of which connections can be accepted, and does not run over insecure HTTP.
* HSTS should definitely be pre-loaded, since the HSTS header can be stripped by an attacker if it is their first visit.
* They are (weirdly) not sent by default, so you need to specify the policy directive and a URI for delivery.
