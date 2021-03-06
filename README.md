# vault-associate-study-notes

My study notes for the HashiCorp Certified: Vault Associate certification exam.

 <img align="right" alt="Vault Associate badge" src="https://github.com/kristinjeanna/vault-associate-study-notes/blob/main/vault-associate-badge.jpg?raw=true" width="300" />
 
 *Note: this is a work-in-progress.*

## Exam Objectives

- **1** &ndash; Compare authentication methods
  - [**1a** &ndash; Describe authentication methods](1/1a.md)
  - [**1b** &ndash; Choose an authentication method based on use case](1/1b.md)
  - [**1c** &ndash; Differentiate human vs. system auth methods](1/1c.md)
- **2** &ndash; Create Vault policies
  - [**2a** &ndash; Illustrate the value of Vault policy](2/2a.md)
  - [**2b** &ndash; Describe Vault policy syntax: path](2/2b.md)
  - [**2c** &ndash; Describe Vault policy syntax: capabilities](2/2c.md)
  - [**2d** &ndash; Craft a Vault policy based on requirements](2/2d.md)
- **3** &ndash; Assess Vault tokens
  - [**3a** &ndash; Describe Vault token](3/3a.md)
  - [**3b** &ndash; Differentiate between service and batch tokens. Choose one based on use-case](3/3b.md)
  - [**3c** &ndash; Describe root token uses and lifecycle](3/3c.md)
  - [**3d** &ndash; Define token accessors](3/3d.md)
  - [**3e** &ndash; Explain time-to-live](3/3e.md)
  - [**3f** &ndash; Explain orphaned tokens](3/3f.md)
  - [**3g** &ndash; Create tokens based on need](3/3g.md)
- **4** &ndash; Manage Vault leases
  - [**4a** &ndash; Explain the purpose of a lease ID](4/4a.md)
  - [**4b** &ndash; Renew leases](4/4b.md)
  - [**4c** &ndash; Revoke leases](4/4c.md)
- **5** &ndash; Compare and configure Vault secrets engines *(reordered more logically)*
  - **5d** &ndash; Define secrets engines
  - **5b** &ndash; Contrast dynamic secrets vs. static secrets and their use cases
  - **5a** &ndash; Choose a secret method based on use case
  - **5c** &ndash; Define transit engine
- **6** &ndash; Utilize Vault CLI
  - **6a** &ndash; Authenticate to Vault
  - **6b** &ndash; Configure authentication methods
  - **6c** &ndash; Configure Vault policies
  - **6d** &ndash; Access Vault secrets
  - **6e** &ndash; Enable Secret engines
  - **6f** &ndash; Configure environment variables
- **7** &ndash; Utilize Vault UI
  - **7a** &ndash; Authenticate to Vault
  - **7b** &ndash; Configure authentication methods
  - **7c** &ndash; Configure Vault policies
  - **7d** &ndash; Access Vault secrets
  - **7e** &ndash; Enable Secret engines
- **8** &ndash; Be aware of the Vault API
  - **8a** &ndash; Authenticate to Vault via Curl
  - **8b** &ndash; Access Vault secrets via Curl
- **9** &ndash; Explain Vault architecture
  - **9a** &ndash; Describe the encryption of data stored by Vault
  - **9b** &ndash; Describe cluster strategy
  - **9c** &ndash; Describe storage backends
  - **9d** &ndash; Describe the Vault agent
  - **9e** &ndash; Describe secrets caching
  - **9f** &ndash; Be aware of identities and groups
  - **9g** &ndash; Describe Shamir secret sharing and unsealing
  - **9h** &ndash; Be aware of replication
  - **9i** &ndash; Describe seal/unseal
  - **9j** &ndash; Explain response wrapping
  - **9k** &ndash; Explain the value of short-lived, dynamically generated secrets
- **10** &ndash; Explain encryption as a service
  - **10a** &ndash; Configure transit secret engine
  - **10b** &ndash; Encrypt and decrypt secrets
  - **10c** &ndash; Rotate the encryption key
