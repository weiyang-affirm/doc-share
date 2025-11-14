# VFO.SBS - Update Phone Number - Tool References

**2. Procedure — Summary**
| Sub-Category | 🗂 Mordor | ⚙️ Agent Portal | ✉️ Email |
|---------------|-------------|-----------------|----------|
| Phone Contact - Affirm or Amazon Brand | 1 | 7 | 2 |
| Phone Contact - Shop Pay Brand | 1 | 5 | 0 |
| Email Contact | 0 | 1 | 1 |

**3. Exceptions — Summary**
| Sub-Category | 🗂 Mordor | ⚙️ Agent Portal |
|---------------|-------------|-----------------|
| Customer Cannot Use Self-Service | 1 | 5 |
| The name/DOB does not match sources | 1 | 0 |
| Relinking a phone number | 2 | 1 |

===

| Main Category | Sub-Category | Step | Tool | Subtool | Type | Verbatim |
|---------------|--------------|------|------|---------|------|----------|
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 3. | ⚙️ Agent Portal | Verify account | Lookup | Verify that the customer has an active account |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 4. | ⚙️ Agent Portal | Check case | Lookup | Check if there is a pending case on hold in the Senior Agents queue |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 7. | ⚙️ Agent Portal | Outbound call | Instruction | Complete an outbound call to the phone number the customer wishes to update their account to |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 11. | ⚙️ Agent Portal | Review eligibility | Lookup | Review eligibility: If the customer's account is ineligible for a phone number change, a modal will appear |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 12. | ⚙️ Agent Portal | Update phone number tool | Instruction | Access the update phone number tool in Agent Portal by clicking the 3 dots |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 12a. | ⚙️ Agent Portal | Send Verification Link | Process | Send Verification Link to customer's email address on file to approve of account change |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 2. | ⚙️ Agent Portal | Enter phone number | Data Entry | Enter the customer's new phone number in the "Phone" text box in the format +1-XXX-XXX-XXXX |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 3. | ⚙️ Agent Portal | Select inbound method | Instruction | Select "Phone" from the "Inbound Contact Method" drop-down box |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 5. | ⚙️ Agent Portal | Save | Process | Click "Save" once complete. A modal will appear requiring you to confirm the changes you are making |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 6ai. | ✉️ Email | Email customer template | Process | Email the customer to let them know the next steps using Request Submitted template |
| 2. Procedure | Phone Contact - Affirm or Amazon Brand | 6cii. | ✉️ Email | Email customer | Process | Email the customer using The name/DOB on the account does not match sources template |
| 2. Procedure | Phone Contact - Shop Pay Brand | 3. | ⚙️ Agent Portal | Access account | Instruction | Access customer's account within the Agent Portal |
| 2. Procedure | Phone Contact - Shop Pay Brand | 3. | ⚙️ Agent Portal | Verify account | Lookup | Verify that the customer has an ACTIVE account |
| 2. Procedure | Phone Contact - Shop Pay Brand | 4. | ⚙️ Agent Portal | Check pending request | Lookup | Verify that the customer does not already have a pending phone change request |
| 2. Procedure | Phone Contact - Shop Pay Brand | 6. | ⚙️ Agent Portal | Banner | Lookup | If the customer has done this successfully, a banner will appear In Agent Portal |
| 2. Procedure | Phone Contact - Shop Pay Brand | 17. | ⚙️ Agent Portal | Click banner | Navigation | In Agent Portal, click the yellow banner under "Contact Information" |
| 2. Procedure | Email Contact | 1. | ⚙️ Agent Portal | Locate account | Lookup | Locate the customer's account in Agent Portal |
| 2. Procedure | Email Contact | 3. | ✉️ Email | Email customer | Process | Email the customer with information on how to update their phone number through the Help Center |
| 3. Exceptions | Customer Cannot Use Self-Service | 1. | ⚙️ Agent Portal | Access account | Instruction | Access the customer's account within the Agent Portal |
| 3. Exceptions | Customer Cannot Use Self-Service | 2. | ⚙️ Agent Portal | Verify account | Lookup | Verify that the customer has an active account |
| 3. Exceptions | Customer Cannot Use Self-Service | 5. | ⚙️ Agent Portal | Send Verification Link | Process | If able to verify sufficiently on both the inbound and outbound call, select the 3 dots to the phone number and send security Verification Link |
| 3. Exceptions | Customer Cannot Use Self-Service | 7. | ⚙️ Agent Portal | Edit icon | Instruction | Once verified, select the "Edit" icon. This will automatically check the customer's user status |
| 3. Exceptions | Customer Cannot Use Self-Service | 8. | ⚙️ Agent Portal | Cases tab | Lookup | Confirm that the customer was not denied a phone number change request in the past by checking the cases tab |
| 3. Exceptions | Customer Cannot Use Self-Service | 9. | ⚙️ Agent Portal | Check pending request | Lookup | Check if the customer already has a pending phone number change request |
| 3. Exceptions | The name/DOB does not match sources | 1. | 🗂 Mordor | Risk > List Contact Change Requests | Navigation | Deny the phone number request in Mordor under "List Contact Change Requests" |
| 3. Exceptions | The name/DOB does not match sources | 2. | 🪄 Generic | Disable autocomm | Instruction | Disable autocomm before clicking "Deny" |
| 3. Exceptions | Relinking a phone number | 1. | ⚙️ Agent Portal | Search phone | Lookup | Search the phone number in Agent Portal to ensure there is no other user associated with the number |
| 3. Exceptions | Relinking a phone number | 1. | ⚙️ Agent Portal | Access account | Instruction | Access the customer's account in Agent Portal to Verify it is released |
| 3. Exceptions | Relinking a phone number | 1. | 🗂 Mordor | Users > Lookup | Navigation | Search the customer in Mordor Users Lookup |
| 3. Exceptions | Relinking a phone number | 1. | 🗂 Mordor | Create Contact Info Change Request | Instruction | Select 'Create Contact Info Change Request' |
| 3. Exceptions | Relinking a phone number | 1. | 🗂 Mordor | Risk > List Contact Change Request | Navigation | Access the List Contact Change Request tool in Mordor Risk List Contact Change Request |
| 3. Exceptions | Relinking a phone number | 1. | 🪄 Generic | Search | Lookup | Search the customer's user ARI using command F and click the appropriate link |
