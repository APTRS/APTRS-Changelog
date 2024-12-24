# APTRS Changelog
Version and Change log for APTRS

## Version 1.0.1
- 🚨 Fixed High Severity CVE-2024-56363 SSTI To Code Execution https://github.com/APTRS/APTRS/security/advisories/GHSA-h4w2-hvcg-938j
- Added CWE Support 
- Fixed Multiple errors in Frontend
- Updated Dark Mode in frontend
- Added Support for Font size in Word Report for CKeditor Fields
- Fixed error in deleting company; caused error in existing projects


## Version 1.0
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


## Version 0.1 Beta  Oct 28, 2022
- Initial Release 
