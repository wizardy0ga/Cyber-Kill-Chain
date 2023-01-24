# The Cyber Kill Chain

<p align="center">
<img src="https://user-images.githubusercontent.com/90923369/214336518-ff0ea707-4e71-4f4c-8036-e80b3f77e058.png">
</p>

# Overview

<p align="center">
The cyber kill chain is an intrusion model developed by Lockheed Martin in 2011, based on the kill chain military model, which displays the necessary stages for a successful attack. The cyber kill chain breaks down the seven stages that an attacker may go through to accomplish their intrusion objectives. As a defender, this model provides a framework for placing obstacles at each step of the attacker's cyber intrusion attempt. Incorporating the cyber kill chain into an organization's defense posture can provide a robust defense against attackers with TTP's that follow the stages of the kill chain. This model is not inclusive of all TTP's in use by attackers and should not be regarded as a monolithic structure for all attacks.
</p>

# Reconnaissance

Recon is the first stage in the cyber kill chain model. During this stage, the attacker will enumerate their target both passively and actively with the goal of collecting as much information about the target organization as possible. In active recon, the attacker will make contact with with their target through various ways such as portscanning internet facing devices or contacting the organization. In passive recon, the attacker relies entirely on OSINT to collect information about their target rather than what the data the collected from ineracting with the target. When the attacker feels that an actionable vulnerability has been found, they will move into the second phase of the kill chain.

# Weaponization

This is the second phase of the kill chain. When the attacker has found an actionable vulnerability, their next goal will be coupling the vulnerability with an exploit that executes a piece of malware on the target host. This process is called weaponization and during this time, the attacker will be focused on engineering their malware into a deliverable payload that will evade known security mechanisms and perform the functions that the attacker seeks to execute on the target computer. More or less time will be spent researching, acquiring and configuring available malware or developing ones own malware depending on the needs and sophistication of the attacker. When the final payload is ready for delivery to the target, the attacker moves into the delivery phase. 
