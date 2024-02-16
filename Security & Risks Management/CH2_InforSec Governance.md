# Information Security Governance
## 1. Guiding principles
1. Functional Security --> What should the system do?

    1. Control:  to prevent the exploitation of a system’s vulnerabilities 
    ```
    Classification according to the purpose of controls:
    - Preventitive: authentication based access
    - Detective: intrusion detection system
    - Corrective: restore data from back-up

    Classification according to the nature of controls:
    - Physical: who can access the data center
    - Procedural: incident response process
    - Technical: user authentication
    - Legal & regulatory/compliance: privacy laws
    ```

    2. Defense in depth & layered security:   
    Defense in depth requires multi-layered defense, but multi-layered defense may not necessarily provide defense in depth.

        |Terminology|Definition|
        |-|-|
        |Defense in depth|Multiple defense methods dealing with multiple attack vectors|
        |Layered security|Could be many layers defense methods in many attack vectors, and also could be defense methods in one attack vector|
    
    3. Need-to-know principle: The need-to-know principle describes a security objective to limit access to confidential information to what is absolutely necessary. 

    4. Least privilege access: same as Need-to-know principle.

    5. Secure by design.

    6. Zero trust.


2. Security Assurance --> How to ensure the functions are achieved?

## 2. Standards and guidelines
1. Standards and guidelines are ***actionalbe*** compare with principles. In another word, priciple is ***abstract***, standard and guidelines are ***practical***.   

2. ***Why*** we need standards and guidelines?   
To eradicate ambiguity. Different understanding in different minds, if you only give people principles, they might achieve it by multiple means, but some means are unsecure, so we need to articulate specifically which means are allowed to use.

3. 
    1. ***Compliance***:  A product/organization/etc. adhering to the requirements of a standard.   
    2. ***Certified***:  Compliance vetted by an authoritative (and competent) entity.   

4. 
    1. ***ISO/IEC 27000***: Information security management systems (ISMS) family of standards: ISO27k.

    2. ***Common Criteria***: basis for evaluation of security properties of IT products. The standards used to make sure the assurance of security.

    3. shortcomings of ***CC***:
        1. It's a targetd evaluation.  
        2. It takes a lot of time and costs a lot of money.
        3. The standards may be out-of-date.

## 3. Laws and regulations
1.  Laws and regulations in Singapore.    

    1. ***Data backup regulation***:

        1. update backups regularly.
        2. encrypt the data off-site.

    2. ***Internal security***:   
        1. Never alone ( Need to have at least two people involved in a incident. )
        2. Segregation of duties. 
        3. Access control.

    3. ***Personal Data Protection Act***:   
        Develop and implement policies and practices to protect personal data. Designate at least one individual, known as the data protection officer (DPO), to oversee the data.
    
2. Laws and regulations in EU.

    1. General Data Protection Regulation (GDPR)   
        1. Revenue based fine.
        2. Data breach notification.
        3. Data protection officer.
    
    2. Right to be forgotten.

3. Laws and regulations in US.

    1. SOX -> Sarbanes Oxley Act of 2002.   

        CEO and CFO must personally certify that financial reports are accurate and complete. They must also assess and report on the effectiveness of internal controls around financial reporting.
    
    2. FISMA -> Federal Information Security Management Act of 2002.

    3. HIPPA -> Health Insurance Portability and Accountability Act.

## 4. Security Governance
1. GRC -> the umbrella term used to cover an organisation's three approches across three fields.

    1. **Governance**: The management approach used by the senior executive 
to direct and control an organization.
    2. **Risk Management**: Process to identify, analyze and when necessary act, to `mitigate risks` that otherwise would affect the business objectives.
    3. **Compliance**: 