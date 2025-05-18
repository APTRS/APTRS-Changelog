# APTRS Changelog
Version and Change log for APTRS

# Version 2.0
### Security Fixes
- Fixed DOM XSS vulnerability

### New Features
- Customer Login now available
- Customer Dashboard where customers can login and see projects for their company (all past and ongoing projects)
- Customers can download PDF and Excel reports directly from the portal
- Added new Project Status "On Hold"
- Email support for "Project Complete" and "On Hold" notifications to customers
- No need to set passwords for new customers - customers will receive an invitation email to accept and set passwords themselves
- Added Forgot password functionality
- Project type and Report standard now support Edit and Delete operations
- Project vulnerabilities can be published or unpublished

### Changes
- New Internal Dashboard
- Improved Dark Mode with fixes and consistent implementation across all interfaces
- Edit profile now prevents both internal users and customer users from editing their email from profile edit
- Project and Retest now share and align the same status
- Report Standards are now saved within Project and no longer needed to be selected each time to generate a report
- Project can allow new vulnerabilities only if the project is not completed and has scope details added

### Build & API Changes
- APTRS no longer provides OpenAPI schema file
- APTRS no longer uses Postman for API collection
- APTRS APIs migrated from Postman to Bruno
- APTRS docker build is now migrated from DockerHub to GitHub Registry

# Version 1.0.1
- 🚨 Fixed High Severity CVE-2024-56363 SSTI To Code Execution https://github.com/APTRS/APTRS/security/advisories/GHSA-h4w2-hvcg-938j
- Added CWE Support
- Fixed Multiple errors in Frontend
- Updated Dark Mode in frontend
- Added Support for Font size in Word Report for CKeditor Fields
- Fixed error in deleting company; caused error in existing projects


# Version 1.0
- New Frontend with ViteJS, Thanks to [DJ Scruggs](https://github.com/djscruggs?) for creating a new frontend from scratch
- Added Rest APIs
- Added support for Customers to be part of the User (Customer login, APIs and Dashboard not supported yet)
- Support for Retest
- Updated PDF report template
- Support for DOCX report template - Experimental feature
- Support for EXCEL report
- Added Option to select Project owners
- Added Project Status option
- The project can have multiple scopes
- Ability to select Project Service type with Ability to add custom service types
- Ability to select report standards with Ability to add custom report standards
- Vulnerability Instances can now have its status
- Support for AWS S3 cloud bucket for media files including vulnerability POC and company logo
- Added User Permissions
- Added Password change and edit profile for users
- Support Nessus CSV report parser
- Partial Windows support removed
- Added docker support
- Fixed Remote Code execution via File upload vulnerability
- Fixed SSRF Vulnerability
- Fixed multiple bugs


# Version 0.1 Beta  Oct 28, 2022
- Initial Release
