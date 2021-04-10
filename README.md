# Resume Supporting Documents
Hi! Thanks for your extended interest in my work and experience. This repo stores some supporting documentation that may or may not appear on my resume, depending on which version you've seen. If anything catches your eye, do let me know!

As time passes servers change, links move and content goes down. Please excuse any dead links on this page and know that if I were in control of those servers, this would not happen.
## Documents
This section presents a brief overview of the files found on this repository.
### Securing Publish/Subscribe
#### Links
* [File](masc/thesis.pdf)
* [Middleware Systems Research Group website](http://msrg.org/profiles/javier) -- This link is working as of this writing, but that may change in the future. I have no control over it.
#### Description
My University of Toronto MASc thesis. A lot of blood, sweat and tears went into this. It contains an exhaustive overview of all the existing research work done to provide any measure of security in a publish/subscribe system, accurate to 2018. It also contains my original work on bringing Trusted Execution Environments to publish/subscribe.

This thesis is (as of this writing) available at my profile page at the . I re-uploaded to this repo to have a permanent link to it that I have control over.

### Secret Sharing in Pub/Sub Using Trusted Execution Environments
#### Links
* [File](masc/secret_sharing.pdf)
* [Early development presentation](masc/secret_sharing_presentation.pdf)
* [ACM Library](https://doi.org/10.1145/3210284.3210290)
#### Description
Originally published in [DEBS 2018](https://2018.debs.org/), which meant I got to travel to New Zealand to present this work. I ended up spending a month there. It was an unforgettable experience.

![Zip Lining in New Zealand](zip-lining-nz.jpg)

The paper itself combines [Shamir's secret sharing scheme](https://en.wikipedia.org/wiki/Shamir%27s_Secret_Sharing) with [Trusted Execution Environments](https://en.wikipedia.org/wiki/Trusted_execution_environment) and applies it to publish/subscribe. It is an interesting way for keeping the content of events in a pub/sub system completely confidential without using traditional symmetric or asymmetric encryption techniques. The tradeoff is that this will not scale well as you increase the number of brokers.