<h1>Azure Adminitsration</h1>

# Configure Azure Active Directory

<b>Azure Active Directory benefits and features</b>

Windows Server AD is using Kerberos and NTLM authentication to on-premises applications. 
Azure AD uses HTTP Authentication through SAML/OAuth/WSFederation etc

<image src="azure-ad.png">

<b>Azure AD features</b>
<ul>
<li>Single sign-on (SSO) access	</li>
<li>Ubiquitous device support: Support IOS, Android, windows, MAC etc</li>
<li>Secure remote access</li>
<li>Cloud extensibility</li>
<li>Sensitive data protection</li>
<li>Self-service support</li>
</ul>

<b>Azure Active Directory concepts</b>

<ul>
<li>Identity: Object that can autheticate</li>
<li>Account: Identity that has data associated</li>
<li>Azure AD Account: Azure AD account is an identity that's created through Azure AD or another Microsoft cloud service</li>
<li>Azure Tenent: An Azure tenant is a single dedicated and trusted instance of Azure AD. Each tenant (also called a directory) represents a single organization</li>
<li>Azure Subscription:  Azure subscription is used to pay for Azure cloud services</li>
</ul>

# Active Directory Domain Services Vs Azure Active Directory
Active Directory Domain Services (AD DS) types:
<ul> 
<li>Active Directory Certificate Services (AD CS)</li>
<li>Active Directory Lightweight Directory Services (AD LS)</li>
<li>Active Directory Federation Services (AD FS)</li>
<li>Active Directory Rights Management Services (AD RMS).</li>
</ul>

<b>Things to consider when using Azure AD rather than AD DS</b>
    - AD DS is primarily a directory service, while Azure AD is a full identity solution. 
    - Azure AD is designed for internet-based applications that use HTTP and HTTPS communications.

<b>Azure AD Subscriptions</b>

<ul>
<li>Free</li>
<li>Microsoft 365 Apps</li>
<li>Premium P1</li>
<li>Premium P2</li>
</ul>

Azure AD join feature works with SSO to provide access to organizational apps and resources. Azure Active Directory enables single sign-on (SSO) to devices, applications, and services from anywhere.
<img source="azure-joined-devices.png">

Connect your device to Azure AD in one of two ways:
<ul>
<li>Register your device to Azure AD</li>
<li>Join your device to Azure AD:  extension of registering a device. sign into a device by using an organizational work or school account instead of a personal account.</li>
</ul>

<b>Azure Active Directory self-service password reset (SSPR)</b>
The Azure Active Directory self-service password reset (SSPR) feature lets you give users the ability to bypass helpdesk and reset their own passwords.

Features:<br>
    - SSPR requires an Azure AD account with Global Administrator privileges to manage SSPR options. This account can always reset their own passwords, no matter what options are configured.<br>
    - SSPR uses a security group to limit the users who have SSPR privileges.<br>
    - All user accounts in your organization must have a valid license to use SSPR.<br>