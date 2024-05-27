# The Pre-requisites or requirements to start a security testing #

### Requirements for a security testing task: ###
  * Point Of Contact if faced any issues/need clarification on app functionality and other related queries
  * Testing Period and time constraints for security testing/scanning
  * Reporting/Bug Tracking tool
  * Reporting Template
  * Required permissions from the owner of the system to perform the security testing activities
  * Any VM or server is available for security testing activities or use our own machines?

### Requirements for manual/automatic security testing (DAST) on web application: ###
  * URL of the Web application
  * In-scope functionality walkthrough/demo
  * User roles details with security matrix
  * 2 sets of user credentials with required test data for each user role (atleast Higher and Lower privileged user roles)
  * Test data for input fields
  * List of security testing tools to use:
    * Manual Security Testing
      - Burp Suite Community/Pro
      - OWASP ZAP Proxy tool
    * Automated Security Testing
      - Burp Suite Pro
      - Web Inspect
      - AppScan
      - Other tools if any
  * Any limitations on the web application such as functionality/test cases

### SAST Scan and Analysis Requirements: ###
  * Code base access
  * Code branch details for SAST scanning
  * Automated scanning 
  * Scanning tools:
    * Automated Scanning Tool
      - Checkmarx
      - Veracode
      - Other tools if any
    * Code viewer tool for manual analysis of reported findings by scanning tool
      - Visual Studio
      - Other tools if any

### API Security Testing Requirements: ###
  * For SOAP - Web services WSDL file containing all in-scope web service details
  * For REST - Postman Collection file containing all in-scope API endpoints with valid request/response data
  * User roles details with security matrix
  * External facing endpoints or internal facing endpoints?
  * 2 sets of user credentials with required test data for each user role (atleast Higher and Lower privileged user roles)
  * Test data for all request parameters (atleast mandatory parameters)
  * Client certificate if required
  * Security Testing Tools:
    * SOAP UI for SOAP web services
    * Postman for REST API endpoints
    * Burp Suite
    * Other tools if any
   
### Network Scanning/Testing Requirements: ###
  * In-scope IP address/domain list
  * Architecture Diagrams if any
  * Scanning/Testing Tools:
    * nmap
    * Kali Linux
    * Wireshark
    * Metasploit
    * openCAS
    * Tenable Nessus
    * Qualys
    * Other paid tools

### Cloud Security Testing Requirements: ###

  * Aechitecture Diagrams if any
  * Cloud services platform
  * Cloud services used
  * Permissions from cloud platform owner to initiate security scanning/testing on cloud services
  * Access to native security scanning tools of cloud platform
<br />    
<br />    
<br />    
*This list of requirements is not final. Needs improveement. Feel free to suggest the changes.*
