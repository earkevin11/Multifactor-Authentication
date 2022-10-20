# Multifactor-Authentication

# What is the purpose of Azure Active Directory Multifactor Authentication?
- MFA helps safeguard access to data and applications by acting as an <em> additional layer of protection. </em> Think defense in depth.
- Organizations that need to be compliant with industrty standards, such as the Payment Card Industry (PCI) Data Security Standard (DSS) version 3.2, MFA must be enabled to authentucate users.
- MFA is a minimum of two-step verification. If attackers learn a user's password, MFA would mitigate the attack since the attacker also needs to have possession of the additional authentication method.
- MFA methods include:
- - Something you know (password or pin)
- - Something you have ( a trusted compliant device, like a phone)
- - Something you are (biometrics)
- - Somewhere you are (location)

# MFA Authentication Options
- Call to phone
- Text message to phone
- Push notifications through mobile app
- Verification code from mobile app

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/166756511-3414b355-1bf7-4867-80e9-19ba5de77f2c.png" height="70%" width="70%" alt="AZ Active Directory"/>
  
<p/>

# What are the MFA statuses?
- Enforced (After user has set up MFA) 
- Enabled - user has been enrolled in MFA, but has not completed the registration process. User will be prompted to complete the process the next time they sign in.
- Disabled - is the default state for a new user not enrolled in MFA.

# Deploying MFA to users

- Navigate to Users within the Azure AD > Per-User MFA 
- Within Per-User MFA, you can see all the users defined within the AD.


# MFA Settings

# Within <em> Service Settings </em>, a IT admins can:
- enable "remember MFA on trusted device" for a number of days 
- - When this setting is enabled, the user will not be prompted for MFA
- Skip MFA for
- - Federated users 
- - List of IP Address subnets

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167274126-5ce63e0a-1c05-4d70-b6e3-666ca9f56954.png" height="70%" width="70%" alt="AZ Active Directory"/>
  
<p/>

