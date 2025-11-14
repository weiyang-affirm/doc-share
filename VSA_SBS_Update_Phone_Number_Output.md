# VSA.SBS - Update Phone Number - Tool References

**2. Procedure — Summary**
| Sub-Category | 🗂 Mordor | 🪄 Generic | ✉️ Email |
|---------------|-------------|------------|----------|
| Sending an identity verification form | 1 | 1 | 1 |
| Reviewing submissions | 1 | 0 | 0 |

**3. Exceptions — Summary**
| Sub-Category | 🗂 Mordor | ⚙️ Agent Portal |
|---------------|-------------|-----------------|
| The name/DOB does not match sources | 1 | 0 |
| Relinking a phone number | 2 | 1 |

===

| Main Category | Sub-Category | Step | Tool | Subtool | Type | Verbatim |
|---------------|--------------|------|------|---------|------|----------|
| 2. Procedure | Sending an identity verification form | 3a. | 🪄 Generic | NetVerify | Instruction | Open Netverify and click "Create Verification" |
| 2. Procedure | Sending an identity verification form | 3b. | 🪄 Generic | Customer Internal Reference | Data Entry | Enter the Case ID in the "Customer Internal Reference" field |
| 2. Procedure | Sending an identity verification form | 3c. | 🪄 Generic | User Reference | Data Entry | Enter the Customer ARI in the "User Reference" field |
| 2. Procedure | Sending an identity verification form | 3d. | 🪄 Generic | Create verification | Process | Click the "Create NVW v4 verification" button to create NetVerify Link |
| 2. Procedure | Sending an identity verification form | 3e. | 🪄 Generic | Copy link | Instruction | Highlight and copy the link created by NetVerify |
| 2. Procedure | Sending an identity verification form | 3f. | ✉️ Email | Email with link | Process | Insert the link copied from Netverify as a hyperlink and send to the customer's email address on file |
| 2. Procedure | Reviewing submissions | 4ai. | 🗂 Mordor | Risk > List Contact Change Request | Navigation | Access phone number change using the List Contact Change Request tool in Mordor |
| 2. Procedure | Reviewing submissions | 4aii. | 🪄 Generic | Search | Lookup | Search for the user id (Command F) |
| 2. Procedure | Reviewing submissions | 4aiii. | 🪄 Generic | Select autocomm | Instruction | Select 'Yes, automatically send decision usercomm' |
| 2. Procedure | Reviewing submissions | 4aiv. | 🪄 Generic | Deny | Process | Click 'deny' |
| 2. Procedure | Reviewing submissions | 4bi. | 🗂 Mordor | Risk > List Contact Change Request | Navigation | Access phone number change using the List Contact Change Request tool in Mordor |
| 2. Procedure | Reviewing submissions | 4bii. | 🪄 Generic | Search | Lookup | Search for the user id (Command F) |
| 2. Procedure | Reviewing submissions | 4biii. | 🪄 Generic | Select autocomm | Instruction | Select 'Yes, automatically send decision usercomm' |
| 2. Procedure | Reviewing submissions | 4biv. | 🪄 Generic | Approve | Process | Click 'approve' |
| 3. Exceptions | The name/DOB does not match sources | 1. | 🗂 Mordor | Risk > List Contact Change Requests | Navigation | Deny the phone number request in Mordor under "List Contact Change Requests" |
| 3. Exceptions | The name/DOB does not match sources | 2. | 🪄 Generic | Disable autocomm | Instruction | Disable autocomm before clicking "Deny" |
| 3. Exceptions | The name/DOB does not match sources | 3. | ✉️ Email | Email template | Process | Email the customer using The name/DOB on the account does not match sources template |
| 3. Exceptions | Relinking a phone number | 1. | ⚙️ Agent Portal | Search phone | Lookup | Search the phone number in Agent Portal to ensure there is no other user associated with the number |
| 3. Exceptions | Relinking a phone number | 1. | ⚙️ Agent Portal | Access account | Instruction | Access the customer's account in Agent Portal to Verify it is released |
| 3. Exceptions | Relinking a phone number | 1. | 🗂 Mordor | Users > Lookup | Navigation | Search the customer in Mordor Users Lookup |
| 3. Exceptions | Relinking a phone number | 1. | 🗂 Mordor | Create Contact Info Change Request | Instruction | Select 'Create Contact Info Change Request' |
| 3. Exceptions | Relinking a phone number | 4. | 🗂 Mordor | Risk > List Contact Change Request | Navigation | Access the List Contact Change Request tool in Mordor Risk List Contact Change Request |
| 3. Exceptions | Relinking a phone number | 1. | 🪄 Generic | Search | Lookup | Search the customer's user ARI using command F and click the appropriate link |
