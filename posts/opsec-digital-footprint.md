# OPSEC Playbook for Cleaning Up Your Digital Footprint

<br>

[Privacy Guides](https://www.privacyguides.org/en/basics/why-privacy-matters/) is referenced heavily here. I think they have a logical method of breaking down this complex topic into easy-to-understand sections on their website. They also continuously curate trusted lists of recommended apps and best practices without any outside influence or sponsorships. They have a forum as well with some good discussions on privacy.

<br>

* * *

## ⭐My Star Ranking System⭐

I have ranked each section with 1-3 stars based on how much impact I think each step will have towards the assumed goal(s) of:

- **Public Exposure** - Limiting the information about you that is accessible online
- **Anonymity** - Shielding your online activity from your real identity

<br>

* * *


## Public Data Removal (⭐⭐⭐)

https://www.privacyguides.org/en/data-broker-removals/

Obvious first step is to try and wipe out your current digital footprint

See what is easily searchable yourself and take steps to remove by request deletion / deleting

Results will be cached in web search results for some time even after deletion

Take steps to opt-out of data broker services

- [ ] Stalk yourself - the first place a potential stalker would look to find your personal information is through a web search
    - [ ] Write down a list of keywords to search:
        - [ ] All combinations of first/last names
        - [ ] Nicknames, gamer tags, online aliases or pseudonyms
    - [ ] Perform a web search / image search using each keyword on many different search engines and see what comes back.
        - [ ] Search Engines:
            - [ ] https://www.google.com/
            - [ ] https://www.bing.com/
            - [ ] https://duckduckgo.com/
            - [ ] https://search.brave.com/
            - [ ] https://www.mojeek.com/
            - [ ] https://yandex.com/
            - [ ] https://search.yahoo.com/
            - [ ] https://www.qwant.com/?l=en
- [ ] Opt-out of data broker services
    - [ ] Use lists of people search and data broker websites to manually opt-out one by one (this will take a long time, chip away at)
        - [ ] https://www.privacyguides.org/en/data-broker-removals/#manual-opt-outs-free
        - [ ] https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List
        - [ ] https://dashboard.operationprivacy.com/category/614938e95db6810016b7df55 (requires free account)
    - [ ] Use a paid service to perform opt outs
        - [ ] [Privacy Guides recommends EasyOptOuts](https://www.privacyguides.org/en/data-broker-removals/#easyoptouts-paid)
- [ ] Attempt to remove Wayback Machine results
    - [ ] https://www.reddit.com/r/privacy/comments/eut3na/can_i_get_personal_information_removed_from_the/ 

<br>

* * *

## Account Deletion (⭐⭐⭐)

https://www.privacyguides.org/en/basics/account-deletion/

Leaving old accounts out there is just leaving a trail of public data unnecessarily

Information in old accounts can be used to build a profile on you and help with hacking into other accounts

- [ ] Find old / forgotten online accounts you no longer need
    - [ ] Check your password manager (saved in browser, saved in phone) for accounts
    - [ ] Search email client for "welcome" or "verify" to find old account signup emails

For each account...

- [ ] (optional) Log in and overwrite account information with fake data (name, phone# address, location, email alias - delete after)
    - [ ] For social media accounts this means editing all posts with garbage text. There are automated tools to do this if needed.
- [ ] This will help to poison your account data in case the provider doesn't really delete it
- [ ] Request deletion / delete the account
    - [ ] Helpful information on deleting accounts: https://justdeleteme.xyz/
- [ ] If you cannot delete it, follow hardening steps under "Account Hardening"

<br>

* * *

## Account Hardening (⭐⭐⭐)

https://www.privacyguides.org/en/basics/account-creation/#email-and-password

Here are some hardening tips for accounts that you need or cannot delete.

You want to prevent anyone from getting access to one of your accounts and exposing your activity on the platform.

They can also use that access to compromise additional accounts and lead to information exposure.

- [ ] Enable two-factor authentication
    - [ ] TOTP (Time-Based One-Time Passwords) is better than SMS
    - [ ] TOTP requires an authenticator app to store the TOTP codes
        - [ ] Bitwarden has TOTP storage built-in
        - [ ] [Secondary TOTP storage apps](https://www.privacyguides.org/en/multi-factor-authentication/)
- [ ] Use a randomly generated username and store in password manager
    
    - [ ] Don't reuse gamer tags or online aliases
- [ ] Use an email alias service to generate a unique email and store in password manager
    
- [ ] Use a randomly generated password and store in password manager
    
- [ ] Do not provide / delete any optional account information
    
- [ ] Avoid services that require a phone number if possible
    
- [ ] Use fake information if required (name, address, location, email alias)
    
- [ ] Check privacy settings:
    
    - [ ] These settings vary based on the service, and the settings change all the time and sometimes opt you in by default. Each account deserves its own privacy audit, but generally:
        - [ ] Opt out of any data sharing and collection
        - [ ] Enable all available privacy settings

<br>

* * *

## Password Managers (⭐⭐⭐)

https://www.privacyguides.org/en/basics/passwords-overview/

Password managers are essential to storing and remembering all of the unique information (usernames, passwords, email aliases) you generate for each account.

- [ ] Sign up for a cloud-based password manager
    
- [ ] Install apps / browser extensions on each of your devices that allow access to it
    
- [ ] Use password / username generation features to randomly generate information for accounts
    

### Recommended Software/Service:

- [Bitwarden](https://bitwarden.com/) (free)
- [Proton](https://proton.me/) (paid software suite)
- https://www.privacyguides.org/en/passwords/

<br>

* * *

## Email Aliasing (⭐⭐⭐)

Allows you to generate a random / unique email address for every account

Each unique email address forwards to your main email account

Can optionally disable individual email aliases if you start receiving spam

- [ ] Sign up for an email aliasing service
    
- [ ] Either use its app or integration with your password manager to create / manage email aliases
    

### Recommended Software/Service:

- [Addy.io](https://addy.io/) (paid)
- [Proton](https://proton.me/) (paid software suite)
- https://www.privacyguides.org/en/email-aliasing/

<br>

* * *

## Data and Metadata Redaction (⭐⭐)

When sharing files, be sure to remove associated metadata. Image files commonly include [Exif](https://en.wikipedia.org/wiki/Exif) data. Photos sometimes even include GPS coordinates in the file metadata.

Don't bother doing this when sharing on secure messaging channels to trusted contacts, but if posting online publicly this is a must.

### Recommended Software/Service:

- Haven't done this much myself
- https://www.privacyguides.org/en/data-redaction/

<br>

* * *

## VPN (⭐)

https://www.privacyguides.org/en/basics/vpn-overview/#should-i-use-a-vpn

Hides your internet traffic from your ISP

Hides your IP from third party websites, but does not make you anonymous to the website owners

Isn't super useful for masking your public digital footprint or making you truly anonymous

Certain websites will block you when behind a VPN

- [ ] Sign up for a paid (!) VPN service
    
- [ ] Install VPN app on phone and computer
    
- [ ] Ideally, leave VPN on and only disable if you get blocked
    

### Recommended Software/Service:

- Mullvad
- https://www.privacyguides.org/en/vpn/

<br>

* * *

## Real-Time Communication (⭐)

Most messaging platforms send your messages un-encrypted or store the encryption keys themselves and therefore can be intercepted or read by the messaging provider (if they wanted to).

- [ ] Download and install secure messaging app and convince your social network to do so
    
- [ ] Only send sensitive messaging using the secure encrypted messaging app
    

### Recommended Software/Service:

- [Signal](https://signal.org/)
- https://www.privacyguides.org/en/real-time-communication/

<br>

* * *

## Other Topics of Interest

These are areas that I think are worth mentioning, but are of limited use for the stated goals of limiting public exposure as they mostly prevent other entities like your ISP, website owners themselves, or law enforcement from tracking you and not the general public.

- Social Media Frontends
    - When directly using social media via their native apps or website they have many ways to track and profile you. Accessing them through a "front-end" without an account allows you to browse their content indirectly without directly interacting with the website itself.
    - https://www.privacyguides.org/en/frontends/?h=
- Web Browsers
    - Website owners use your "browser fingerprint" to identify you even when behind a VPN. A hardened browser can obfuscate that fingerprint. Worth mentioning Tor here as the standard for anonymity but I have never personally used it.
    - https://www.privacyguides.org/en/desktop-browsers/
    - https://www.privacyguides.org/en/mobile-browsers/
- Search Engines
    - All search queries are logged by the search provider. I prefer to use metasearch engines.
    - https://www.privacyguides.org/en/search-engines/
- Email
    - Your email provider can see all emails sent to/from your account unless using an encrypted email service. Generally consider communication using email as public.
    - https://www.privacyguides.org/en/email/
- DNS Resolvers
    - Your ISP can see every website you visit unless you use a VPN & change your default DNS resolver on your router and phone.
    - https://www.privacyguides.org/en/dns/
- Cloud Storage
    - Cloud storage providers require your full trust that they will not look at your files... but they can if they wanted to.
    - https://www.privacyguides.org/en/cloud/
- Phone / Desktop OS and App Permissions
    - This is a big topic where the operating system itself or the apps installed on it have telemetry or other methods of harvesting your information, but generally it doesn't contribute to data exposure to the general public (unless there is a data breach or you get hacked).
