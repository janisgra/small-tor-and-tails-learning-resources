# small-tor-and-tails-learning-resources

# Tor Security Learning Guide

## START HERE: Essential Setup

- **Tails OS** (Most important): https://tails.net/
- **Tails Installation Guide**: https://tails.net/install/linux/index.en.html
- **Tor Project Official Site**: https://www.torproject.org/
- **Tor Browser Manual**: https://tb-manual.torproject.org/
- **Security Rule**: Don't trust any links you can't verify

---

## CRITICAL SECURITY PRACTICES

### DO NOT:
- Log into personal accounts while using Tor (email, social media, banking, etc.)
- Download files over Tor (they can contain tracking elements)
- Use BitTorrent with Tor (this WILL expose your real IP address)
- Mix VPNs with Tor unless you fully understand the implications (can expose your identity)
- Maximize your browser window (creates unique fingerprint)
- Install browser plugins or extensions

### DO:
- Always use HTTPS connections when available
- Adjust Tor Browser security levels (Standard, Safer, Safest) based on your needs
- RESTART Tor Browser after changing security levels for settings to fully apply
- Use Tor Bridges if Tor is censored in your region
- Keep Tor Browser updated
- Use separate identities for different activities

---

## Core Privacy Tools & Documentation

### Operating Systems
- **Tails** (amnesic live OS): https://tails.net/
- **QubesOS** (security-focused OS): https://www.qubes-os.org/
- **Whonix** (anonymity-focused OS): https://www.whonix.org/

### Encryption & Storage
- **VeraCrypt** (disk encryption): https://veracrypt.io/en/Documentation.html
- **OnionShare** (secure file sharing over Tor): https://onionshare.org/

### Secure Communication
- **Signal** (encrypted messaging): https://signal.org/
- **ProtonMail** (encrypted email): https://proton.me/mail

### VPN Services
- **Mullvad VPN**: https://mullvad.net/en
- **ProtonVPN**: https://protonvpn.com/

### Password Management
- **Bitwarden**: https://bitwarden.com/
- **KeePassXC**: https://keepassxc.org/

---

## Key Technologies to Learn

- **PGP/GPG** (Pretty Good Privacy - encryption)
- **Proxy chains** (routing traffic through multiple proxies)
- **Darknet Bible** (comprehensive reference guide)
- **Tor Bridges** (censorship circumvention)
- **End-to-End Encryption (E2EE)**
- **Operational Security (OpSec)**

---

## Understanding Tor Browser Security Levels

Tor Browser offers three security levels that can be accessed by clicking the shield icon:

### Standard (Default)
- All Tor Browser and website features are enabled
- Provides basic anonymity through the Tor network
- JavaScript enabled on HTTPS sites
- Best for general browsing where full functionality is needed

### Safer
- Disables website features that are often dangerous
- JavaScript disabled on all non-HTTPS sites
- Some fonts and math symbols disabled
- Audio and video (HTML5 media) are click-to-play
- May cause some sites to lose functionality

### Safest
- Only allows website features required for static sites and basic services
- JavaScript disabled on ALL sites
- Some fonts, icons, math symbols, and images disabled
- Audio and video (HTML5 media) are click-to-play
- Maximum security but significant functionality limitations

**CRITICAL**: After changing security levels, you MUST restart Tor Browser for all protections to fully apply. Simply changing the setting does not immediately enable all security features. Click "Save and restart" or manually restart the browser.

---

## Onion Service Directories

(do not trust them completely)

- dark.fail
- Tor.li
- Daunt.link

---

## Educational Videos

### Introductory
- https://youtu.be/LEbAxsYRMcQ
- https://youtu.be/1opKW6X88og
- https://youtu.be/R_aeQPYyyN0

### Technical Deep Dives
- https://youtu.be/QrHsFZBab4U
- https://youtu.be/7CD_Nl3iwhE
- https://youtu.be/MGGIvaF234c
- https://youtu.be/MqG01J1h2n8
- https://youtu.be/y8bIt4K_Kfo

### Additional Learning
- https://www.youtube.com/watch?v=mVKAyw0xqxw
- https://youtu.be/XDsLDhKG8Cs
- https://youtu.be/K3wmLvny5tg
- https://youtu.be/QRYzre4bf7I
- https://youtu.be/WkphgF6Hn4w

---

## Background Reading (Wikipedia)

- **Dark web overview**: https://en.wikipedia.org/wiki/Dark_web
- **The Hidden Wiki**: https://en.wikipedia.org/wiki/The_Hidden_Wiki
- **DeepDotWeb**: https://en.wikipedia.org/wiki/DeepDotWeb
- **List of Tor onion services**: https://en.wikipedia.org/wiki/List_of_Tor_onion_services
- **All Things Vice**: https://en.wikipedia.org/wiki/All_Things_Vice
- **Eileen Ormsby's site**: https://eileenormsby.com/

---

## Comprehensive Privacy Guides

- **EFF Surveillance Self-Defense**: https://ssd.eff.org/
- **Security in a Box**: https://securityinabox.org/en/
- **PRISM Break** (Privacy alternatives): https://prism-break.org/en/
- **The Book of Secret Knowledge**: https://github.com/trimstray/the-book-of-secret-knowledge

---

## Community Resources & Best Practices

- **Reddit Tor Wiki**: https://reddit.com/r/TOR/w/index
- **Reddit Darknet Wiki**: https://www.reddit.com/r/darknet/wiki/index/
- **Stack Exchange Best Practices**: https://security.stackexchange.com/questions/43369/best-practices-for-tor-use-in-light-of-released-nsa-slides/43485#43485

---

## Privacy & Rights Organizations

- **Electronic Frontier Foundation (EFF)**: https://www.eff.org/
- **Reporters Without Borders**: https://rsf.org/en
- **Privacy International**: https://privacyinternational.org/
- **Citizen Lab**: https://citizenlab.ca/
- **Tor Project**: https://www.torproject.org/

---

## Recommended Learning Path

### Foundation
1. Install and familiarize yourself with Tails OS
2. Watch introductory videos to understand Tor basics
3. Read the Tor Browser Manual
4. Practice basic security hygiene (HTTPS, no personal logins)
5. Learn about security levels and practice changing them with proper restart

### Core Skills
1. Learn PGP/GPG encryption basics
2. Set up Signal for secure communications
3. Read EFF's Surveillance Self-Defense guide thoroughly
4. Practice with password managers and encrypted email

### Advanced
1. Study OpSec principles from community wikis
2. Learn about Tor Bridges and censorship circumvention
3. Explore technical deep-dive videos
4. Practice compartmentalization (separate identities for different activities)

### Ongoing Education
1. Stay updated with Tor Project announcements
2. Follow privacy organizations (EFF, Privacy International)
3. Engage with community resources
4. Continue learning about emerging privacy technologies

---

## Common Mistakes to Avoid

1. **Identity Linking**: Using the same identity across Tor and regular internet
2. **File Downloads**: Downloading and opening files that can "phone home"
3. **Browser Fingerprinting**: Customizing Tor Browser or maximizing window
4. **Poor OpSec**: Revealing personal information in communications
5. **VPN Misuse**: Incorrectly configuring VPN+Tor combinations
6. **Outdated Software**: Not keeping Tor Browser and tools updated
7. **BitTorrent Usage**: Using BitTorrent over Tor exposes your real IP address
8. **Trust Issues**: Blindly trusting .onion sites without verification
9. **Security Level Changes**: Changing security levels without restarting browser

---

## Why BitTorrent and Tor Don't Mix

BitTorrent over Tor is extremely dangerous for your anonymity:

1. **IP Address Leakage**: Many BitTorrent clients ignore proxy settings and send your real IP address directly to trackers and peers
2. **Protocol Design**: BitTorrent's peer-to-peer nature means all participants can see each other's IP addresses
3. **DHT Exposure**: The Distributed Hash Table (DHT) uses UDP which Tor doesn't support, forcing clients to use your real network connection
4. **Port Information**: Clients share listening port information that can be correlated to identify you
5. **Network Strain**: BitTorrent traffic overloads the volunteer-run Tor network

The Tor Project explicitly recommends against using BitTorrent over Tor. If you need to torrent anonymously, use a VPN service designed for P2P traffic instead.

---

## Special Considerations for Singapore Users

### Legal Status
- Using Tor is LEGAL in Singapore - there are no laws prohibiting Tor or similar anonymity tools
- Accessing the dark web itself is NOT illegal in Singapore
- However, conducting illegal activities (drug trade, stolen data, illegal content) remains illegal regardless of the technology used
- Activities are judged by their nature, not the tools used to perform them

### Regulatory Environment
- Internet content is regulated by the Infocomm Media Development Authority (IMDA)
- IMDA states it "does not restrict or monitor individuals' access to online content"
- ISPs are required to block a limited number of websites (mainly pornography, content harmful to racial/religious harmony)
- Copyright holders can obtain court orders to block piracy sites
- The Personal Data Protection Act (PDPA) governs data privacy
- The Computer Misuse Act and Cybersecurity Act 2018 regulate cybersecurity offenses

### Practical Considerations
- Your ISP can see that you are connecting to Tor (though not what you do on it)
- Educational institutions (MOE, universities) may have additional filtering on their networks
- Government has taken action under the Sedition Act and other laws for online speech deemed harmful
- POFMA (Protection from Online Falsehoods and Manipulation Act) allows government to issue correction directions
- Singapore has strong rule of law - avoid any activities that could be interpreted as terrorism, inciting violence, or undermining racial/religious harmony

### Best Practices for Singapore
- Consider using Tor Bridges to obscure Tor usage from your ISP if you prefer additional privacy
- Be aware that while Tor usage is legal, authorities may investigate if suspicious activity is detected
- Follow all standard OpSec practices even more carefully in a well-monitored environment
- Remember that Singapore's small size and strong governance means online activities may receive more scrutiny
- Keep informed about changes to Singapore's cybersecurity and online safety regulations
- Never engage in activities that could be seen as undermining Singapore's social fabric or national security

### Singapore-Specific Resources
- Cybersecurity Agency of Singapore (CSA): https://www.csa.gov.sg/
- Personal Data Protection Commission (PDPC): https://www.pdpc.gov.sg/
- IMDA Cybersecurity Resources: https://www.imda.gov.sg/
- Singapore Computer Emergency Response Team (SingCERT): https://www.csa.gov.sg/singcert

**Note**: This information is for educational purposes. While Tor is legal in Singapore, users should understand both the technical aspects and the local regulatory context before use.

---

## Emergency Resources

- **Tor Project Support**: https://support.torproject.org/
- **EFF Contact**: https://www.eff.org/about/contact
- **Access Now Digital Security Helpline**: https://www.accessnow.org/help/

---

## Remember

- Security is a practice, not a product
- Always verify links before clicking
- Use Tails for maximum security
- Never compromise your operational security
- When in doubt, ask the community
- Privacy requires constant vigilance and learning
- In Singapore: Tor is legal, but activities conducted through it must comply with Singapore law
- Always restart Tor Browser after changing security levels
- Never use BitTorrent over Tor
