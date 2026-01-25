# :shield: Security Policy & Liability Disclaimer

## :balance_scale: Liability & Data Responsibility
**OpenFormLabs (OFL)** and its contributors provide this software **"AS IS"** and without any warranty of any kind. 
1. **Contributor Responsibility:** Each individual is strictly responsible for the data they commit. By contributing, you agree that you have scrubbed all sensitive data (API keys, secrets, PII) from your changes.
2. **No Liability:** No maintainer or contributor shall be held liable for any sensitive data accidentally or maliciously committed to this repository by third parties.
3. **Best Effort Cleanup:** While we are not liable, we are committed to safety. We will perform a "best effort" historical scrub (using BFG/filter-repo) if a leak is reported via the support email, but we do not guarantee the total removal of data once it has been pushed to a public network.

## :electric_plug: About Extension/Add-ons safety:
 * **Do NOT run untrusted code as "Trusted"**: Extensions in Trusted mode have full access to your system, including the file system, network, and environment variables.
 * **Malicious Code Risk**: If you run a malicious Extension/Add-on as a Trusted extension, it is fully at your own risk.
 * **Moderated Mode**: If an Extension requires more than "Untrusted" access but you do not fully trust the source, use Moderated Mode. This limits the extension to what you allow(it will ask you what to allow).

## :beetle: Reporting a Vulnerability
If you discover a security vulnerability within NWT_IDE or an official OFL component, please follow the steps and do not report it publicly.
 1. **Keep it Private:** Ensure you have not reported it publicly anywhere yet. Public disclosure can put other users at risk.
 2. **Contact Us:** Report the issue to us via the support email with a detailed description, logs, and screenshots.
 3. **Patch First:** We will work to patch the vulnerability, and only after a fix is deployed, you can make it public.