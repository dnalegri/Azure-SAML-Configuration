# Microsoft-Entra-ID-SAML-Configuration

## Objective
[Brief Objective - Remove this afterwards]

The SAML project aims to establish an SSO in Microsoft Entra ID to save time, boost productivity, and enhance the overall user experience. The primary focus was establishing an identity once for Enterprise applications and services across the Microsoft Entra ID environment.

### Skills Learned

- Understanding of basic SAML configuration.
- Create a SAML toolkit in Azure.
- Ability to configure a user account in Azure AD for SSO.
- Knowledge and understanding of zero-trust framework.
- Development of active directory administration.

### Tools Used

- Microsoft Entra ID (formerly Azure Active Directory).
- Microsoft Entra SAML toolkit.

## Steps

*Ref 1: Navigate to Enterprise Applications and create Microsoft Entra SAML Toolkit*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/5f9ee58e-0bf9-4455-b5ae-8f52465672f6" />
*Ref 2: Create a new user in Microsoft Entra ID* 

<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/e7a121a8-196f-4b20-9479-a8169fe4b997" />

*Ref 3: Add user to SAML*
<img src=https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/2e6f6ab5-55b0-4062-810e-b149d97e840c />

*Ref 4: Register the user you are provisioning with SAML*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/3a53ebd2-3bc0-4b16-996e-7aac2199df95" />
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/9cef657e-687b-4cee-b0f0-759dfed312a8" />


*Ref 5: Create SAML configuration*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/67f93086-0cc9-42ae-bc6c-7309d4cf894a" />

*Ref 6: Navigate back to the SAML toolkit and set up SSO*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/74604c27-9f98-4c67-a175-d327037787a9" />

*Ref 7: Edit the basic SAML configuration*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/8a991cf4-77e3-45ba-8677-841edea3d21d" />

*Ref 8: Download the Raw SAML certificate and copy the login URL, Microsoft Entra identifier, and the logout URL. Paste the info into the correct fields and create the configuration*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/b764d359-a917-4f03-995a-878627170100" />
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/ec7abae5-9a8d-4a2d-a9a5-60e550ff09f2" />

*Ref 9: Retrieve the Microsoft Entra identifier and the SP initiated login URL*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/695bc5f2-3342-46d0-96e2-3375ba404578" />
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/ae169155-f0b9-4fb7-8250-cc28aeaf2bd5" />

*Ref 10: Navigate back to the basic SAML configuration page in Entra and update the entity ID, reply URL, and sign-on URL*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/d1ca8ac0-06e2-4247-a15b-43edd818a298" />

*Ref 11: Test the implementation. A successful test will allow you to sign on without entering any of your login details*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/9c2d20c7-535b-440a-b335-31493ffa4cd5" />
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/d4d9c6a3-7822-4ba6-b548-24f9bf772fee" />

*Ref 12: A successful test will display the home page*
<img src="https://github.com/dnalegri/Azure-SAML-Configuration/assets/164395911/417daeef-cb20-46b5-b3b5-21d045926c63" />
