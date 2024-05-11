# Ethical Hacking Report 

**Client:** Amazon

**Date:** May 11, 2024

**Prepared by:** [Marisol R. Broqueza](https://www.facebook.com/marisol.broqueza)  and [Ralph Dexter Rhey A. Pidoc](https://www.facebook.com/dexterpidoc)


**Executive Summary:** This report presents the technical findings of the ethical hacking assessment 
conducted for [Amazon]. The assessment aimed to identify vulnerabilities within the 
organization's network infrastructure, applications, and systems. Through various testing methodologies, 
including penetration testing and vulnerability scanning, critical and high-risk issues were discovered. 
This report provides detailed descriptions of these findings, along with actionable recommendations for 
remediation.The analysis presented in this paper is theoretical and does not accurately represent Amazon's security posture. 

**Vulnerability Summary:**


1. **Network Infrastructure:**
   * Critical: Weak or default passwords on network devices may be exploited by attackers to gain unauthorized access.
* High: Vulnerable to Distributed Denial of Service (DDoS) attacks, disrupting the availability of its services.

3. **Web Applications:**
      * Critical: SQL Injection vulnerability in the login form of [Application Name], potentially 
        enabling an attacker to extract sensitive data from the database.
      * High: Cross-Site Scripting (XSS) vulnerability in [Application Name], allowing attackers to 
        execute malicious scripts in users' browsers.

4. **Operating Systems:**
      * Critical: Outdated and unpatched operating systems (Windows Server 2008 R2) on 
        critical servers [Server Names], exposing them to known exploits and malware.
      * High: Weak password policies on domain user accounts, facilitating brute-force attacks 
        and unauthorized access.

6. **Wireless Networks:**
     * Critical: Weak encryption (WEP) used in wireless networks, allowing attackers to 
       intercept and decrypt wireless traffic, exposing sensitive data.
8. **Social Engineering:
     * High: Several employees fell victim to phishing emails, providing credentials and 
       sensitive information in response

3. **Operating Systems:**
     * Critical: Outdated and unpatched operating systems (Windows 11 Server 2022) on 
       critical servers [Server Names], exposing them to known exploits and malware.
     * High: Weak password policies on domain user accounts, facilitating brute-force attacks 
       and unauthorized access.
4.**Wireless Networks:**
    *  Critical: Inadequate encryption on wireless networks may allow attackers
       to eavesdrop on network traffic and intercept sensitive information.
5. **Social Engineering:**
    * High: Several employees tricked into revealing sensitive information, such as login
      credentials, through phishing emails or phone calls.
**Recommendations:**
1.  **Network Infrastructure:**
    * Implement network segmentation to separate critical components of the infrastructure.
      Use Amazon VPC to create separate virtual networks for different tiers of services.
    * Utilize Amazon CloudWatch and GuardDuty for real-time monitoring of network traffic and to
      detect any suspicious activities or potential intrusions.
    * Implement redundant network paths and failover mechanisms to ensure high availability.
      Use Amazon Route 53 for DNS failover to redirect traffic in case of an outage.
2. **Web Applications:**
   *  Implement redundant network paths and failover mechanisms to ensure high availability.
      Use Amazon Route 53 for DNS failover to redirect traffic in case of an outage.
   * Implement AWS WAF to protect web applications from common web exploits such as SQL injection,
     cross-site scripting (XSS), and cross-site request forgery (CSRF).
   * Train developers in secure coding practices to prevent common vulnerabilities like injection attacks,
     broken authentication, and session management flaws.
3. **Operating Systems:**
   * Implement a robust patch management process to ensure that operating systems are up-to-date with
     the latest security patches and updates.
   * Follow industry-standard hardening guidelines (e.g., CIS benchmarks) for the operating systems used in the infrastructure.
   * Follow the principle of least privilege to restrict access to critical systems and resources only to those who need it.
4. **Wireless Networks:**
   * Implement a wireless intrusion detection system to monitor the wireless network for unauthorized
     access points and potential security threats.
   * Use strong encryption protocols such as WPA2-Enterprise for Wi-Fi networks to ensure that
     wireless communication is secure.
5. **Social Engineering:**
   * Conduct regular security awareness training for employees to educate
     them about social engineering tactics and how to recognize and respond to them.

  
**Conclusion:**

The findings of the ethical hacking assessment highlight several critical vulnerabilities and 
security weaknesses within XYZ Corporation's infrastructure and applications. By implementing the 
recommended remediation measures, XYZ Corporation can significantly enhance its security posture and 
mitigate the risk of cyber threats and data breaches.


**Signature:** ![Signature](signature.png)
