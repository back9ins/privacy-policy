# Privacy Notice

BackNine Insurance and Financial Services, Inc. ("BackNine," "we," "us") provides this notice for information collected through https://back9ins.com and for the BackNine plugin connection between ChatGPT and your BOSS account. The website practices below continue to apply to the website. The plugin section explains the additional processing involved when you connect and use BackNine in ChatGPT.

## Website information

- What personally identifiable information is collected from you through the website, how it is used and with whom it may be shared.
- What choices are available to you regarding the use of your data.
- The security procedures in place to protect the misuse of your information.
- How you can correct any inaccuracies in the information.

### Information Collection, Use, and Sharing

We are the sole owners of the information collected on this site. We only have access to/collect information that you voluntarily give us via email or other direct contact from you. We will not sell or rent this information to anyone.

We will use your information to respond to you, regarding the reason you contacted us. We will not share your information with any third party outside of our organization, other than as necessary to fulfill your request.

Unless you ask us not to, we may contact you via email in the future to tell you about specials, new products or services, or changes to this privacy policy.

### Your Access to and Control Over Information

You may opt out of any future contacts from us at any time. You can do the following at any time by contacting us via the email address or phone number given on our website:

See what data we have about you, if any.

Change/correct any data we have about you.
Have us delete any data we have about you.
Express any concern you have about our use of your data.

### Security

We take precautions to protect your information. When you submit sensitive information via the website, your information is protected both online and offline.

Wherever we collect sensitive information, that information is encrypted and transmitted to us in a secure way. You can verify this by looking for a lock icon in the address bar and looking for "https" at the beginning of the address of the Web page.

While we use encryption to protect sensitive information transmitted online, we also protect your information offline. Only employees who need the information to perform a specific job (for example, billing or customer service) are granted access to personally identifiable information. The computers/servers in which we store personally identifiable information are kept in a secure environment.

If you feel that we are not abiding by this privacy policy, you should contact us immediately via telephone at (800) 790-1951 or via email at privacy@back9ins.com.


## BackNine plugin for ChatGPT

### Connecting your account

Using the plugin requires a BackNine account with ChatGPT access enabled and your authorization through BackNine's sign-in and consent flow. Sign in directly to BackNine; do not enter your BOSS password, authentication codes, API keys, or other secrets into a chat message.

Authorization is tied to the BackNine user and agent or agency login that approved the connection. Changing your active BOSS login does not transfer an existing connection to a different agent or agency. The connection uses an OAuth access token to authenticate requests on your behalf.

### Information processed and purposes

Depending on your request and account permissions, we process:

- **Account and connection information:** BackNine user, login, agent or agency identifiers; authorization scope; connection creation, expiration, revocation, and last-used timestamps; and a hashed access-token value. We use these to authenticate requests, enforce permissions, manage connections, and prevent unauthorized access.
- **Task-specific requests:** Tool names, search terms, filters, record identifiers, and other arguments sent by ChatGPT to fulfill your request. A navigation search, for example, sends the task you want help completing. The plugin does not require your full conversation history.
- **BOSS results:** Authorized case and electronic-application information, including available party names and contact details, status, carrier and product information; carrier appointments; commission payments and pay periods; and supported document information. We retrieve and return the information needed for the requested task.
- **Catalog and guidance information:** Carrier and product catalogs, supported product-guide content, and customer-facing BOSS or Quote & Apply navigation guidance.
- **Illustration information:** If you request an illustration for an authorized cached quote, the service sends the quote information needed by the carrier to generate an illustration and stores the resulting document.
- **Operational and security records:** Request timestamps, network IP addresses, user-agent information, request identifiers, routes, response status, account and connection identifiers, tool usage, and diagnostic errors. These support service operation, troubleshooting, access auditing, and abuse prevention.

Only request information you are authorized to use and disclose. Do not submit Social Security numbers, government identifiers, payment-card or banking credentials, medical records or protected health information, or authentication secrets through the plugin. The service applies filtering to known sensitive fields and patterns before returning tool results. Filtering is not a guarantee that arbitrary free-text notes or documents contain no sensitive information; sensitive records should be viewed directly in BOSS.

The connection retrieves information and provides navigation guidance. The illustration-generation tool additionally sends quote information to a carrier and stores the resulting illustration. The plugin does not create or modify electronic applications or send text messages.

### Recipients and sharing

When you use the plugin, BackNine sends the requested tool results to OpenAI so ChatGPT can respond to you. These results can include personal information from the authorized BOSS records described above. OpenAI's handling of information in ChatGPT is governed by its applicable privacy policy, terms, account settings, and any agreement with your organization. See [OpenAI's privacy policy](https://openai.com/policies/privacy-policy/).

When you request illustration generation, the relevant insurance carrier and its illustration service receive the quote information needed to generate it. BackNine's infrastructure and service providers process information needed to host, secure, and operate the service. Authorized BackNine personnel can access information needed for support, operations, and security. We may also disclose information when required by law or to address fraud or security incidents.

We do not sell or rent information collected through this connection.

### Retention

Authorization validity and data deletion are different:

- **Authorization codes:** A code can be used once and expires after five minutes if unused.
- **Access tokens:** A newly issued token is valid for up to 30 days unless revoked sooner. BackNine stores a hash of the token, together with connection metadata. Expiration or revocation prevents further authorized use; it does not itself delete the stored connection record.
- **Illustration download links:** Links returned by the plugin expire after ten minutes. Link expiration does not delete the underlying illustration document.
- **Connection records, tool-usage records, application/security logs, and backups:** [CONFIRM BEFORE PUBLICATION: specify the actual retention period for each category, deletion trigger, and any backup removal delay. Do not substitute token validity for record retention.]
- **BOSS records and generated documents:** Connecting or disconnecting the plugin does not change the retention of the underlying BOSS records. [CONFIRM BEFORE PUBLICATION: specify the applicable retention periods or concrete retention criteria for BOSS records and illustrations, including legal or carrier obligations.]

Information already returned to ChatGPT is subject to OpenAI's retention rules and your ChatGPT controls. Disconnecting BackNine does not erase previous ChatGPT conversations or their contents.

### Your choices and requests

You can decline authorization. You can stop future access by using the ChatGPT connection-removal control in BOSS. This revokes the user's BackNine ChatGPT grants; reconnecting requires authorization again. You can also remove the plugin or its connection in ChatGPT. Removing a connection does not delete underlying BOSS records, connection history, or previous chat messages.

Contact privacy@back9ins.com or (800) 790-1951 to request access, correction, deletion, or information about retention, or to raise a privacy concern. We may need to verify your identity and your authority over the affected records. Some BOSS records concern clients or other parties and may be subject to legal, contractual, or carrier retention requirements. We will explain any applicable limitation when responding to your request.

For information already held in ChatGPT, use ChatGPT's account and data controls or contact OpenAI. BackNine cannot remove information from another provider's systems by revoking an OAuth token.

### Security

The connection uses HTTPS, OAuth authorization with PKCE, scoped account permissions, token hashing, and access checks. Sensitive authentication parameters are filtered from application parameter logs. These safeguards reduce risk but do not guarantee that all free-text content is safe to disclose. Keep credentials out of prompts and use BOSS directly for sensitive information.

## Contact and changes

For questions about this notice or the BackNine plugin, contact privacy@back9ins.com or (800) 790-1951. Updates to this notice will be published at this URL.

Proposed revision date: October 7, 2026. The plugin retention disclosures marked above must be completed and confirmed before this revision is published.
