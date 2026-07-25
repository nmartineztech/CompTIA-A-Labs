Lab 05 – Configure Windows Firewall
Objective

In this lab, I practiced configuring the Windows Firewall on the HOMEPC computer. The goal was to make sure the computer could communicate with authorized services on the local network while keeping the firewall enabled for security.

I configured the network connection as a Private network and allowed Get Help and Remote Assistance through the Windows Firewall.

Skills Practiced
Configuring Windows Firewall
Managing Windows network profiles
Configuring Private network settings
Allowing applications through Windows Firewall
Understanding firewall permissions
Basic Windows network security
Troubleshooting network connectivity
Environment
Windows
HOMEPC computer
Windows Security
Windows Firewall
Private network profile
Local network
Scenario

Tasks Performed
1. Set the Network Profile to Private

I opened the network connection settings and located the Ethernet connection. I then changed the network profile to Private.

This was important because the firewall uses different rules depending on whether a computer is connected to a Private or Public network.

2. Checked Windows Firewall

I opened Windows Security and went to Firewall & network protection.

I verified that:

Windows Firewall was turned on.
The Private network profile was active.
The computer was using the correct network profile.
3. Allowed Applications Through the Firewall

I opened the Allow an app through the firewall settings and selected Change settings.

I then checked the list of applications and made sure that:

Get Help was allowed on Private networks.
Remote Assistance was allowed on Private networks.
The applications were not enabled for Public networks.
4. Verified My Work

After making the changes, I went back through the firewall settings to make sure everything was configured correctly.

I confirmed that the firewall was still enabled, the Private network profile was active, and both required applications were allowed through the firewall.

The task was successfully evaluated, and the required firewall settings were configured correctly.

Best Practices I Followed
Kept Windows Firewall enabled instead of disabling it.
Used the Private network profile for the trusted local network.
Allowed only the applications that were required for the task.
Limited the firewall exceptions to the Private network.
Avoided allowing the applications on Public networks.
Verified the configuration after making the changes.
Difficulty

Difficulty Level:Intermediate

The main challenge in this lab was understanding how Windows network profiles work with firewall settings. I had to make sure the computer was using the Private network profile before configuring the firewall rules.

I also had to pay attention to which network profiles the applications were allowed on. This helped me understand why it is important to avoid unnecessarily allowing applications through the firewall on Public networks.

What I Learned

This lab helped me better understand how the Windows Firewall protects a computer and controls which applications are allowed to communicate over the network.

I learned that Windows Firewall can be configured to allow specific applications without completely disabling the firewall. I also learned how network profiles affect firewall rules and security settings.

One of the biggest takeaways from this lab was that firewall configuration is about finding the right balance between connectivity and security. Instead of opening everything up, an administrator should only allow the services that are actually needed and limit those permissions to trusted networks when possible.

CompTIA A+ Connection

This lab connects to CompTIA A+ objectives related to:

Configuring Windows network settings.
Configuring Windows Firewall.
Managing firewall permissions.
Troubleshooting network connectivity.
Applying appropriate security settings to Windows systems.
Outcome

I successfully configured the HOMEPC computer to use a Private network profile and configured Windows Firewall to allow the required applications.

Key Results
Set the network profile to Private.
Verified that Windows Firewall was enabled.
Confirmed the Private firewall profile was active.
Allowed Get Help through the firewall.
Allowed Remote Assistance through the firewall.
Limited the firewall exceptions to the Private network.
Successfully verified the firewall configuration.
