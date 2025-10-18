# The CIA triad: 
- Confidentiality :
    - Ensure sensitive data only accessible to authorized people.
    - Examples:
      - Encryption
      - Access control
      - Data masking
      - 2FA
      - NDA

- Integrity :
    - Keeping information correct and unaltered
    - Examples:
      - Bank Transaction
      - Software Downloads
      - Medical record
      - Email security
      - Database protection
     
- Availability :
  - System data and resources accessible to authorized user when needed
  - Examples:
    - Load balancer
    - Cloud storage backup
    - Uninterrupable power supply
    - Redundant internet connection
    - Disaster recovery site / Secondary data centers
   
- Non-Repudiation :
    - Ensures that a person or system cannot deny action they performed.
    - This build trust and accountability in communication or transaction
    - Examples:
      - Digital signature
      - Blockchain transaction
      - Audit logs
      - Biometric access
      - Payment confirmation

---

# AAA - Authentication, Authorization and Accounting

- Authentication:
    - Process of verifying the identity of user to ensure that only the authorized can gain access to resources.
    - Example:
      - Password
      - Biometrics

- Authorization:
    - Process of determining and granting user permission to access specific resources based on their verified identity
    - Example:
      - Gaining the admin access
      - Admin only webpage

- Accounting or auditing:
    - Tracking and recording a user activities.
    - Example:
      - Login and logout log
      - Command execution log
     
# Multi-factor authentication

- Something you know:
    - Information only the user knows
    - Example:
      - Password
      - Pin
      - Security question

- Something you have:
    - A physical item in user possession
    - Example:
      - Smartphone
      - Smartcard
      - Token
     
- Something you are:
    - Unique biological characteristic
    - Example:
      - Fingerprint
      - Facial features
      - Iris biometric
     
- Somewhere you are:
    - Geographic or network based location
    - Example:
      - Access granted based on ip location
      - GPS
      - WI-FI location
     
# Privacy

- Refer to protection of personal informtion and adherence to law and policies governing its collection
- Data subject:
  - individuals whose personal information is being collected
  - Example:
    - Customer whose data is stored by ecommerce platform
    
- Controller vs Processor:
  - Controller:
    - Determine the purpose and means processing personal data.
    - Example:
      - Retail company managing customer data
  - Processor:
    - Process data on behalf of the controller
    - Example:
      - Cloud service provider hosting retail company data

- Ownership:
  - Clarifies who has the authority over data and who responsible for its security
  - Example:
    - Organization own operational data but must respect data subject right over their personal information

- Data inventory and retention:
  - Data inventory:
    - Comprehensive list of all data assets including location and type
    - Example:
      - Tracking stored customer record, email log and billing information
  - Retention:
    - Policies for how long data is kept and when its deleted
    - Example:
      - Retaining employee tax record for seven years as required by law

- Right to be forgotten:
  - Individual can request the deletion of their personal data when its no longer necessaryor legally required to retain
  - Example:
    - Former user requesting the removal of their account information under GDPR
   
---

   
# Element of Risk Management Process

- Risk Identification:
    - Process indentifying risk that could negatively impact the organization
    - Involves gathering input from various stakeholder, reviewing past incident and evaluating external threat
    - Help create a comprehensive risk register that lust identified risk and their potential impact
 
- Risk Assesment:
    - Process of evaluating identified risk to understand their likelyhood and impact. Helping to prioritize them for mtigation
 
# Risk Analysis

- Definition:
    - Process of evaluating identified risk to understand their likelyhood and impact. Helping to prioritize them for mtigation
    
- Qualitative:
    - A subjective approach to access risks using descriptive categories (low, medium, high)
    - Focuses on expert judgement without numerical data
    - Useful when numerical data is unavailable
 
- Quantitative:
    - Data driven approach that assign numerical value to risks to calculate potential loss
    - Uses formula like SLE, ALE and ARO
    - Provide precise insight for decision making

- Exposure Factor(EF)
    - The percentage of an assets value that lost due to specific risk event
    - Example:
      - Flood damage 70% of facility. 70% is EF

- Single Loss Expectancy(SLE)
    - Expected financial loss from single risk event
    - SLE = Asset value(AV) X Exposure Factor(EF)
 
- Probability:
    - Likelyhood a specific threat will occur
    - Expressed as percentage
 
- Likelihood:
    - Same like probability but describe as qualitative term ( Likely or unlikely )
    - help prioritize risk based on the perceived chance of occuring

- Impact:
    - Magnitude of effect caused by risk event
    - High impact risk often demand more immediate attention
 
- Risk tolerance:
    - Acceptable level of variation in outcomes that organization is willing to withstand while pursuing its objective
    - Focusing on day to day operational ability without significant disruption
 
- Risk appetite:
    - Overall level of risk an organization willing to take to achieve its strategic goal
    - Help define boundaries for decision making and prioritization
  
# Risk Management/ Treatment Strategies

- Transfer:
    - Shift the risk to 3rd party.
    - Reduce the organization direct responsibility
    - Example:
      - Purchasing cyber insurance to over data breach
     
- Accept:
    - Choose to acknowledge and bear the risk without taking any action
    - Appropriate for low impact risk
 
- Accept Exemption:
    - Formal decision to exclude certain risk from specific policies
    - Often used when risk is deemed negligible
    - Example:
      - Exempting low value asset from comprehensive security measure

- Exception:
    - Temporary allowance for deviation from standard risk policies
    - Example:
      - Allow unsupported software temporarily while replacement procured
     
- Avoid:
    - Eliminate the risk entirely by discontinuing the activity or process
    - Best for high impact risk
    - Example:
      - Avoid certain vendor with history of data breach
     
- Mitigate:
    - Reduce the risk to an acceptable levelby implementing control
    - Focuses on minimizing the impact of the risk
    - Example:
      - Installing firewall to protect againt cyber attack
     
# Risk Reporting

- Process of documenting risk related information to stakeholder
- Includes detail on identified risk and potetial impact
- Help stakeholder make informed decision and prioritize resources for risk management

---

# Categories and Types of security control

- Categories:
  - Technical
  - Managerial
  - Operational
  - Physical
 
- Types:
  - Preventive
  - Deterrent
  - Detective
  - Corrective
  - Compensating
  - Directive

---

- Technical:
  - Hardware or software used to manage the resources.
  - Example:
    - Encryption
    - Smart card
    - Password
    - Biometric
    - Firewall
    - Router

- Managerial:
  - Policies and procedures. Use planning assesment method to review organization ability to reduce risk
  - Example:
    - Policies
    - Vendor management
    - Hiring practice
    - Background check
    - Risk and vulnerability assesment
   
- Operational:
  - Help ensure day to day operation comply with their overall security. Primarily implement and executed by people
  - Example:
    - Backup and recovery procedure
    - Awareness training
    - Media protection
   
- Physical:
  - Focused on protection to facility and real world object
  - Example:
    - Guards
    - Fences
    - Alarm

---

- Deterrent:
  - Deployed to discourage violation of security
  - Example:
    - Security guard
    - Lighting
    - Separation of duties
   
- Preventive:
  - To prevent or stop unwanted activity from occuring
  - Example:
    - Fences
    - Lock
    - Firewalls
    - Access control
    - Pen testing
   
- Detective:
  - To discover ot detect unwanted activity
  - Example:
    - Honey pots
    - Security guard
    - ids
    - Violation report
   
- Compensating:
  - Provide option to other exsting control to aid in enforcement of security policies
  - Example:
    - Security policy
    - Personal supervision

- Corrective:
  - Measure taken to fix security vulnerabilitiesor mitigate damage after incident happen
  - Example:
    - Backup and restore
    - Patching
    - Anti virus
    - Disciplinary action
   
- Directive:
  - Proactive measure design to guide behavior and enforce compliance with security policies
  - Example:
    - Policies
    - Procedure
    - Guideline
    - Verbal instruction
   
---

# ISC2 Code of Ethics

- Set of principle that guide cybersecurity professional in maintaining integrity and professionalism and responsibility while protecting the public and organization
- Code of ethics Canon:
  - Protect society, the common good, necessary public trust and confidence
  - Act honorably and legally
  - Provide diligent and competent service
  - Advance and protect profession
 
  - 

