# Nostha

1. Scoping

The test scope agreement is usually defined upfront with the penetration test vendor, and should include the testing methods and the level of exploitation allowed when vulnerabilities are discovered. Penetration testing is a white hat process—the attacker is a tester who works according to the rules of engagement established in the scope definition. Therefore, a penetration test should never interfere with normal business operations.

 

The ethical hacker performing the penetration test can gain access to sensitive insights and information, and must sign a confidentiality agreement before starting the penetration testing process.

 

 
2. Reconnaissance

In the reconnaissance stage, the tester attempts to collect as much information as possible on the organization’s systems, potential targets and their vulnerabilities. Penetration testers primarily rely on open source intelligence sources and independent scans of IT systems.

 

The penetration tester may or may not have access to information about the organization’s internal systems. In some cases, an organization may point the attacker in the direction of specific targets or vulnerabilities they are concerned about.

 

Some common information gathering techniques are:

 

    Search engine querying
    DNS or WHOIS lookups
    Social engineering
    Tax records or other public records
    Email addresses, user accounts and social profiles available on the Internet
    Ping probes, port scans, reverse DNS, packet sniffing
    Shoulder surfing, or publically accessible physical locations like dumpsters

 
3. Vulnerability Assessment

In this step, the penetration tester applies a probe to the target network, collects preliminary information, and reviews the results to investigate directions for exploitation.

   

This step may result in discoveries like:

 

    The directory structure of a specific server
    Open authenticated access to an FTP servers
    SMTP access points that provide details about the network architecture through error messages
    Possibility for remote code execution
    Cross-site scripting vulnerabilities
    An internal code-signing certificate that can be used to sign new scripts and inject them into the network

 
4. Penetration Testing

One the tester has identified the key vulnerabilities they want to exploit, and created a threat model and attack plan, the next step is to penetrate the target system. There is no guarantee that all vulnerabilities found will be exploited in the test, either because they were less convenient for the attacker, or because they are outside the scope of the test. 

 

The main goal of the penetration tester is to find at least one vulnerability that allows them to access the target system, either compromising it or accessing sensitive data. Once inside, the tester will collect more detailed data from the target network to facilitate the next step.

 
5. Gaining Access

6. Maintining Access

7. Risk Analysis, Post-Test Recommendations and Cleanup

Once the penetration tester has completed their activity, they should carefully document the vulnerabilities discovered, what they did to gain access to the organization’s systems or data, and the value of compromised systems to a real attacker.

 

An important part of a penetration tester’s analysis should be recommendations for closing security gaps found in the environment. The penetration testing vendor should provide an actionable recommendation on remediating any significant vulnerability discovered in the test.

 

Finally, the penetration tester must perform cleanup of the organization, removing any components they have added to the environment, and removing access or privilege they received. 

 

The cleanup process typically includes:

 

    Deleting temporary files, executable files, scripts or rootkits from target systems
    Reverting configurations to original settings
    Reverting credentials or access rights to their original state
    Removing new user accounts created for lateral movement purposes


8. Penetration Test Report

Finally, the penetration tester submits a report to the organization. The report should communicate the results of the test to two audiences: management and technical or security teams.

 

The penetration testing report should include:

 

    An executive summary—explaining the penetration test strategy in business terms, identifying test results by risk rating. It is intended for the business team, and will be used to make decisions about what to fix, and which issues represent an acceptable level of risk.

 

    Technical details—which should be descriptive and specific, and can be used by technical teams to take action and fix security issues discovered during the penetration test.
