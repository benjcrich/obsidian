I need to perform a review of their GCP environment. Will be getting access in the next couple days. 

Need to enable `CIS Benchmark` in GCP and it'll give me most of what I need. 

- Enable Security Command Center
- They Use WIZ
- They have a captcha check at the bottom of 
- Most things kept in cloudrun
- The only deployments they manage are open telemetry deployments
- Use coreweave since they manage GPU's better
- on github team plan, but not enterprise. 
- Stability has access to their CGP env. They still need access for about the next 6 months. John reached out to Alex to see when we can remove them. 
- Never had DDOS attacks. Just some simple site scripting. 
- Payment processors
	- Used to use Stripe but now use [Paddle](https://www.paddle.com/compare/stripe). 
- Permissions management is all done manually in console. 
	- WIZ asked them to change some permissions. Look into this. 

### Deployements
- Mostly use github actions. 
- For the ML services, they don't have full CI deployements yet. So they manually make docker images and push to GCP. 
- No TF or anything.

### Outstanding sec issues
- Some cloud services not hidden by load balancer.
- Connection between GCP and coreweave is their weakest connection. "There's no security between them at all". 
	-  They deploy services on k8s cluster and they maintain k native plane. Coreweave has an open HTTP endpoint their GCP connects. There's no Auth on the endpoint. They know they can do it w/ AWS, but aren't sure if it's possible to transfer directly from GCP to Coreweave. 
- No pentests ever conducted. 
- Don't have any sort of compliance cert. Never pursued. 
- Have an API ratelimit that speaks to Redits. If you hit it, it switches to in-memory refusal. But no limit before that. 
- Bug bounty's?
	- Received a few in Zendesk
	- Didn't look through all
	- Most were fake.
- SPIF might not be configured correctly on their email domain. They need us to verify. 


### Access
- Got access to GCP
- Need access to their Github. 
- Jonathan and Hugo are the only two w/ access to GCP.
- IAM admin at Org level. 

### Tests to run
- OWASP - very intrusive
- SNYK - non intrusive
- Truffle Hog to find secrets - non intrusive
- Manual Burpsuite - non intrusive

### Owned domains (managed in google domains)
- [initml.co](https://sitecheck.sucuri.net/results/initml.co)
- [clipdrop.co](https://sitecheck.sucuri.net/results/clipdrop.co)
- cleanup.pictures

✅ Only managed by google domains. Need to add them to the domain expiration script.

### Managed machines
- They will be receiving our laptops. 