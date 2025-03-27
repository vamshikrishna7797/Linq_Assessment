# Incident Response Plan

## Immediate Actions:
1. Isolate:
   - Disconnect the employee's system from the network
   - Prevent the lateral movement from further compromise.
2. Credential Invalidation:
   - Password reset on the compromised account.
   - If any active authentication tokes revoke them and reissue new tokens
   - If no MFA enable them.
3. Notification:
   - Internal:
     - Security Team
     - CISO
     - HR Department
     - Employee's Manager
   - External:
     - No Immediate Actions needed.
## Investigation:
1. Forensic Analysis:
   - conduct thorough log analysis.
   - Identify the time when email is received.
   - Identify the time when the link clicked.
   - Identify Systems accessed.
   - Identify any malware is downloaded or installed.
   - Identify Potential Data Exposure.
   - Idnetify whether the compromised credentials are used elsewhere.
   - Store all the digital evidence if any future investigations.
2. Email Tracing:
   -  Analyze the Email Headers.
   -  Block sender domain.
   -  Update email filtering rules.
## Improvements from Findings:
1. Security Awareness Training:
   - Develop Mandatory Monthly or Quaterly Phising simulation training.
   - Create interactive scenario based learnings
   - Implement phishing awareness tests.
2. Technical Controls:
   - Enhance email filtering with behaviour based or AI Based threat detection.
   - Implement DMACR, SPF, DKIM Email authentications.
   - Deploy advanced EDR Solutions.
3. Incident Response Refinement:
   - update the incident response playbook
   - conduct post-mortem analysis
   - Establish clearer communication protocols
## Monitoring and Follow-UP:
- Intensive monitoring of compromised systems.
- follow-up with affected employee.
