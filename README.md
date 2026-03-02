# Lab-03.md: Zero Trust Policy 

Arielle Sidberry

Date: February 27, 2026

Objective: Define three Zero Trust Architecture components, and design a simplified Zero Trust Architecture policy profile for accessing this sensitive information.


1. ZTA Component Definitions

Policy Engine (PE): The Policy Engine is often referred to as the judge because it serves as the ultimate decision-maker. It evaluates security rules and determines whether access should be granted or denied.

Policy Administrator (PA): The Policy Administrator is known to be the clerk. It is the system responsible for creating, managing, and distributing policies.

Policy Enforcement Point (PEP): The Policy Enforcement Point is like the security guard that carries out the decision. It is the part of the system that enforces the access control decisions made by the Policy Engine.


2. Core Principle Application 

The 3 Core Principles of the Zero Trust Policy
1. Verify Explicitly
2. Use Least Privilege
3. Assume Breach

Protecting the Water Treatment Facility's data.

-The core principle I am choosing is Verify Explicitly. This principle means always authenticating and authorizing access based on all available data points, including user identity, location, device health, and data classification.

This principle is important for the water treatment facility’s data because many potential threats may come through proxy services or suspicious network activity. To keep sensitive information secure and out of the wrong hands, Verify Explicitly ensures that details such as IP address, location, and device status are validated before access is granted.

As mentioned in the reading, one effective way to improve security and protect data is by continuously monitoring networks. Network monitoring helps organizations detect unusual activity early and defend against cyber threats and attacks.

3. Simplified Policy Table

Organization: Golden State Water Treatment Facility

Protected Resource: HR Database (Employee PII, background checks, certification status)

Security Goal: Protect Confidentiality and prevent insider threats

<img width="1276" height="352" alt="image" src="https://github.com/user-attachments/assets/9006b61c-9439-4793-89e1-b1ad023741b0" />

This Zero Trust Policy verifies user identity, device posture, and network context before granting access to the HR database. Access is only allowed when all sercurity conditions are met, protecting sensitive employee PII and maintaining confidentiality.

Proof of work

<img width="753" height="457" alt="image" src="https://github.com/user-attachments/assets/88bbbb07-c5de-4b77-8af4-210d56de0605" />


# Git Repository Metadata
