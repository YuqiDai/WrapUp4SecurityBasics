# Concepts and Background 
## 1. Basic Concepts
| Terminology | Description  |
|-------------|-------------|
|Information Security| Security about information based assests |
|Cyber Security|Security about the transmission or communication of information|   

&nbsp;
![information security to cyber security](./Resource4CH1/CIA%20trial.png)
&nbsp;

## 2. Attacks & Attackers
For an incident happened, we need to know:   

1. Tools -> ( Physical Attack/ Information Exchange/ User command/ Script or Program/ ...)
2. Vulnerability -> (Design/ Implementation/ Configuration)
3. Action -> (Probe/ Scan/ Flood/ Authenticate/ Bypass/ Spoof/ ...)
4. Target -> (Account/ Process/ Data/ Component/ ...)
5. Unauthorized Result -> (Increased Access/ Disclosure of Information/ ...)
6. Objectives -> (Challenge, Status, Thrill/ Political Gain/ ...)

&nbsp;
![Incident Layers](./Resource4CH1/Incident%20layers.png)
&nbsp;

After we know how they attack, it's easy to find their identity based on their way of attacking.   

&nbsp;
![Identities of attackers](./Resource4CH1/Identities%20of%20attackers.png)
&nbsp;

The definition of attack vector and attack surface.
&nbsp;
| Terminology | Description  |
|-------------|-------------|
|System Hardening| reduce the attack surface|
|Attack Vector| a path or means by which one can attack a system (network, server, …) exploiting the vulnerabilities of the system |
|Attack Surface|all the attack vectors in the system put together|

&nbsp;

**Trinity of Troubles** - Factors leading to enlarge the attack surface.
1. Extensibility: A software which could extent extral functions.
2. Connectivity: There are interconnections between softwares.
3. Complexity: Massive codes.

**Principles of easiest penetration**:   
An intruder must be expected to use any available means of penetration. The penetration may not necessarily be by the most obvious means, nor is it necessarily the one against which the most solid defense has been installed.  And it certainly does not have to be the way we want the attacker to behave.

## 3. Secure and What to secure
Some Popular **Security Models**:   
1. CIA model: Confidentiality, Integrity, Availability.
2. Parkerian Hexad: Confidentiality, Integrity, Availability, Utility, Possessing, Authenticity.
3. McCumb Cube: Security Goals(CIA), Information state(transmission, storage, processing), countermessure(Technologies, Policies&Practices, People)

&nbsp;
![Security Models](./Resource4CH1/Security%20Models.png)
&nbsp;

