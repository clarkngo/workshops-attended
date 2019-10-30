# Scaling for Security 2020 
Auth0 Online Meetup #23
 
Wed, Oct 30, 2019 12:00 PM - 1:00 PM PDT
 
Speakers: 
- Eugenio Pace - CEO/Co-Founder
- Joan Pepin - CISO/VP Operations
- Jeff Moss - Product Security Lead
- Eva Sarafianou - Product Security Engineer 
 
Title: Scaling for Security in 2020
 
Description:  Rapid growth means devising a rapid plan for scaling security. How can security keep pace with dramatic change and innovation in today's compliance-driven environment? Join Auth0 CEO Eugenio Pace, CISO/VP of Operations Joan D. Pepin, and Product Security Engineer Eva Sarafianou for a lively discussion between those who make the security calls — and those who need to make them work.

## Building a Culture of Security
Joan: Behaviors that leads to secure environment. Acted on the day-to-day life of the company. It can look a little different from company to company.

### Ado: How can organizations balance speed and security?

Joan: Being involved early in the lifecycle. To have minimum amount of disruption to have a secure product.

Eugenio: During my time in Microsoft, security is embedded in the software development lifecycle. Retrofitting is very expensive, risky, and problematic.

Eva: As engineers, automate security as much as we can. Empower engineers to build secure software. Create easy and repeatable process. They don't need to be experts.

Jeff: Knowing your threat model is a must. Know your risk-tolerance as a company.

Joan: Risk is also opportunity. Know your balance. In threat model, know who would be attacking you. Security has been given a bad reputation because of the misconception of writing secure software before that you do it at the end. Another bad reputation for security is because of security for security sake that doesn't match on the organization's risk tolerance and threat model.

### Ado: How can we help individuals integrate security?

Joan: If the software product being produce is not secure, the company is responsible to add that. You don't need an CISO early on. You can hire secure software engineers, consultant, etc.

Eugenio: It's like buying a car but not paying for new tire or oil. There is one day that it's going to break down. You cannot blame the car. With my teens, I instill security on their daily interactions with social media.

Jeff: If you are in the process in building something new and a small company. There's still a lot of small tools like cert bot to manage certificates.

Eugenio: We (auth0) exist for bring security for developers. Developers can stand on the shoulders of giants (auth0) that can deal with security. Very few in the planet can spend a big amount on resources for security. You can focus your efforts/resources to the things that are more valuable to you without sacrificing security.

Ado: I believe that authentication and authorization is a solved problem. We (auth0) have it well-defined. We don't have to reinvent the wheel.

Eugenio: Reinvent the wheel is fine. It's still good to challenge the status quo. In the authentication world, it is solved from malware perspective. A misconception is that, it's easy. It looks easy in the surface, but it's deceiving. Typical login box button looks easy. But once you start poking around storing password you fall to a pithole. You don't store passwords. How about forgotten password? How about sending the email? Now it becomes a massive problem. It's not a one time thing. You need to build robustness. There's always something coming up (new type of vulnerability or attack) as software is not perfect. You don't need to reinvent a new cryptography.

Joan: A friend signed up a very expensive subscription service using social media. Couple months later, she deleted the social media accounts and now couldn't stop the subscription from the company. The company did not thought about customers deleting social accounts. They need to take that into account.

Eugenio: Joan's good example is not a problem, but a behavior. A recent announcement from Apple wherein you can sign-in with Apple with biometrics and have people trust that mechanism. Turns out Apple's implementation is within standards using OpenID connect but with subtlety. You as a developer have to dig deep and take hours and hours of your time to understand the complexity.

Ado: Apple's documentation is great, but there is small nuances that takes time away from the developers.

## Data Breaches
Facebook, CapitalOne, DoorDash data breaches because of poor security. Not because of inside hack.

### Ado: How can organizations do better to prevent data breaches?

Joan: This is the number 1 question I am asked everytime. This has been going on every decade. For example Equifax, there were so many contributing factors that's only because a simple thing. Why was the server not patched? The IT Team wasn't in the loop. The information security officer was not plugged in the loop. Underbudgeted. They were not given priority. Wasn't in the radar of the company. The was a blame to point to. The cost centers should have barely the access they need. On the security leadership level, we are also to blame as we don't really cascade the information and make sure the communication is delivered clearly.

Ado: In Equifax (I learned in Google Summit), so many different levels of failure waiting to happen.

Ava: We think everyone working here in auth0 is part of our extended security team. Reporting process for a phishing? build process for everyone to follow.

Jeff: Have security hygiene as a whole. Building security in a pipeline. Everybody goofs up but we have layers of defense like layers of skin of an onion.

## The Future of Identity Management

Ado: Defense in depth have multiple layers of security to catch failures will make a big difference. In auth0, we handle 2 billion of log-in attemps for a month. We have anomaly detection and breached password detection to protect them.

Ava: anomaly detection is where auth0 will invest heavily. To prevent automated credential stuffing attacks.
- https://auth0.com/docs/anomaly-detection

Jeff: MFA is really the line of defense for credential stuffing attacks. Not only do I know something, I have something.

Eugenio: MFA are really nice to haves anymore. They are a must-have for any kind of sensitive information. credential stuffing attacks used to be a very complicated complex attack. Now with the magic of technology, we can make automated attempts from my computer and pay servers in other locations to do the job.

Ado: It's a constant game of cat and mouse with security. As far as Identiy and Access Management, are there any new idealogy coming up?

Jeff: WebAuthn is an exciting moment. Can help us eliminate password. Like platform authentication, faceID.
- https://auth0.com/blog/introduction-to-web-authentication/

Ava: Continuous authentication to pr ovide better user experience. Each user have an authentication has an authentication score on a rolling basis and prompt them for more authentication with the authentication score is low.
- https://www.facebook.com/getauth0/posts/1273146289371857/

Eugenio: Trust is underlying behavior or value that customers and users experience. If we lose trust, there's no point in existing anymore. We all make mistakes. Technical mistakes and non-technical mistakes both builds and erodes trust. Mistake leads to innovation but we would own the mistake and not make the same mistake twice.

Joan: We are a service. We also use many services as individuals and as a company and subscribe to SaaS services that are similar to auth0 as consumers of auth. 

Ado: One of our core values in auth0 is transparency.

## Legal Landscape
Joan: I'm hopeful someday that our slow federal process will create an overarching laws for security. GDPR has made a positive impact globally. Forced the companies think about critical things because of GDPR. It goes back to Massachusetts breach notification laws with a given number of users affected. It creates business challenge and protecting consumers would be a messy evolution. There's so wealth generate from data and we should protect those data.

Eugenio: Fortunately we live in the era of technology. We should maximize that. Create a nice user experience without decreasing security. It's possible today.
