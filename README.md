# CORS
Cross-origin Resource Sharing (CORS) Summary : Cross-origin resource sharing (CORS) is a browser mechanism which enables controlled access to resources located outside of a given domain. However, it also provides potential for cross-domain based attacks, if a website's CORS policy is poorly configured and implemented. CORS can be exploited to trust any arbitrary domain attacker controlled domain name and send the data to it.  Attackers can make an exploit and ask the domain to send data of the victim to the attacker domain.

Impact : An Adversary can carry out CORS attack to exfiltrate the sensitive details of a victim.


Recommendations : 
All the REST Apis should be authenticated and the domain should not trust any other domains. Allow only selected, trusted domains in the Access-Control-Allow-Origin header.
