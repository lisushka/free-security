# Free Security for Open-Source Projects

## Presentations

- **SeaGL 2021**, 2021-11-06 (not yet uploaded, [transcript](transcript.md))

## References

### Attacks that have actually happened

* [Postmortem for Malicious Packages Published on July 12th, 2018](https://eslint.org/blog/2018/07/postmortem-for-malicious-package-publishes), **Henry Zhu, Brandon Mills, and Kai Cataldo**, *ESLint*, 2018-07-12
* [Backdoored Ruby gems stole credentials, injected cryptomining code](https://www.helpnetsecurity.com/2019/08/21/backdoored-ruby-gems/), **Zeljka Zorz**, *Help Net Security*, 2019-08-21

### Using secure platforms

* [Dependabot](https://docs.github.com/en/code-security/supply-chain-security/keeping-your-dependencies-updated-automatically/keeping-your-actions-up-to-date-with-dependabot) ([core source code](https://github.com/dependabot/dependabot-core))
* [GitLab's AppSec tools](https://docs.gitlab.com/ee/user/application_security/)
* For secure or stripped-down Linux distributions with hardened kernels, research the current recommendation at the time that you deploy your software.

## Open-source secrets management

#### One-off secure secrets sharing

* [**Yopass**](https://yopass.se/)
* [**PrivateBin**](https://privatebin.info/)
* Open instances hosted by Seattle Matrix: [Yopass](https://yopass.seattlematrix.org/#/) | [PrivateBin](https://privatebin.seattlematrix.org/)

#### Multi-user password management

* [**KeePass**](https://keepass.info/) ([help article on setting up a database for multiple users](https://keepass.info/help/base/multiuser.html))
* [**vaultwarden**](https://github.com/dani-garcia/vaultwarden) (centralised setup to share secrets within a group; compatible with the open-core of the Bitwarden password manager)

#### Access token control for automation

* [**HashiCorp Vault**](https://www.hashicorp.com/products/vault) ([source code](https://github.com/hashicorp/vault))

### Open-source tooling

* **OWASP's application security testing tool lists** ([static](https://owasp.org/www-community/Source_Code_Analysis_Tools#) | [dynamic](https://owasp.org/www-community/Vulnerability_Scanning_Tools#))
* [**Checkov**](https://www.checkov.io/) ([source code](https://www.github.com/bridgecrewio/checkov))
* [**Terrafirma**](https://github.com/wayfair/terrafirma)
* [**Clair**](https://github.com/arminc/clair-scanner)
* [**OWASP Dependency Check**](https://owasp.org/www-project-dependency-check/) ([source code](https://github.com/jeremylong/DependencyCheck))
* [**OWASP Dependency Track**](https://owasp.org/www-project-dependency-track/) ([source code](https://github.com/DependencyTrack/dependency-track))
* [**OWASP ZAP**](https://www.zaproxy.org/) ([source code](https://github.com/zaproxy/zaproxy))
* [**Wireshark**](https://www.wireshark.org/) ([source code](https://gitlab.com/wireshark/wireshark))
* [**Kali Linux**](https://www.kali.org/) ([source](https://www.kali.org/docs/general-use/kali-linux-sources-list-repositories/))

### Closed-source tooling

* [**Snyk**](https://snyk.io/plans/)
* [**Debricked**](https://debricked.com/) ([blog post on going free for OSS](https://debricked.com/blog/debricked-made-free-for-open-source-maintainers/))

[Back to main talks repo](https://github.com/lisushka/talks)
