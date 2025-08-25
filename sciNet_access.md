# Connecting to the Science Network

The National Microbiology Branch (NMLB) of PHAC maintains a suite of servers, applications, and high-performance computing clusters to support the science projects of the branch.
Collectively, this infrastructure is called the _Science Network_, and access to it has been extended to the researchers of the GRDI-AMR2 project.
This access is required to access IRIDA (the sequence repo) as well as the dashboards that are being created as outputs of the project.

## Quick links:

- The NMLB IT helpdesk email: [helpdesk@nml-lmn.phac-aspc.gc.ca](mailto:helpdesk@nml-lmn.phac-aspc.gc.ca)
- NMLConnect: [connect.nml-lmn.phac-aspc.gc.ca/](https://connect.nml-lmn.phac-aspc.gc.ca/)
- IRIDA: [ngs-archive.corefacility.ca](http://ngs-archive.corefacility.ca)
- GRDI-AMR PowerBI dashboards: [powerbi.cscscience.ca/reports/browse/GRDI-AMR2](https://powerbi.cscscience.ca/reports/browse/GRDI-AMR2)

## Getting help

For all things science-network related (e.g., requesting an account, renewing an account, or access errors) you can submit a helpdesk ticket by sending an email to the [NML's Science IT Helpdesk](mailto:helpdesk@nml-lmn.phac-aspc.gc.ca).
Alternatively, you can contact [Emil Jurga](mailto:emil.jurga@phac-aspc.gc.ca) who can help troubleshoot issues and submit tickets.

## Your Science Network Account

This is the account used to access the science network.
It generally must be requested via a ticket to the [helpdesk](mailto:helpdesk@nml-lmn.phac-aspc.gc.ca),
and for externals (i.e., those outside of the NMLB) requires a business justification and additional security checks.
Fortunately, members of the GRDI-AMR2 project _should_ already have a Science Account, which were requested at the onset of the project.
Should your account requires renewal contact either the [helpdesk](mailto:helpdesk@nml-lmn.phac-aspc.gc.ca) or [Emil Jurga](mailto:emil.jurga@phac-aspc.gc.ca).

Note that for some applications, your science account _username_ must be appended with the science network's domain, which is @CSCscience.ca
(e.g., for account flast, the fully qualified account name is flast@cscscience.ca).

## Accessing the science network

There are currently multiple ways to connect to the Science Network and access its applications:

1. **Recommeded**: via [NMLconnect](https://connect.nml-lmn.phac-aspc.gc.ca/).
2. Via the VPN. This method of connection is **legacy**, but has been extended to some users.

### Via NMLconnect

NML Connect is a webportal that provides access to the Science Network's applications and servers.
Access is provided through the use of the Citrix Workspace application.
If the Citrix Workspace application is not already installed on your Government-issued computer, it can be installed via the "Company Portal" application.
This webportal can be accessed when connected to the Corporate VPN.

The link to the portal is [https://connect.nml-lmn.phac-aspc.gc.ca/](https://connect.nml-lmn.phac-aspc.gc.ca/).
Log in to this portal using your fully qualified science credentials (formatted as _username_@**CSCScience.ca**).
The chrome application has many bookmarks pre-configured to access most of what you'll need.

**Note**: If your credentials are refused with a "wrong username/password" error, _disconnect_ from the **science network VPN** (if you are connected).

### Via the VPN

Another way to access the is via the VPN, which must be configured via the cisco AnyConnect application (the same application used to access the corporate VPN).
The science network VPN is `remote.corefacility.ca` (be warned - this address may be subject to change as the NMLB upgrades its infrastructure).
In general, this application is locked-down on corporate PCs, and will require a ticket submission to your agency's IT helpdesk.
Note also that this method of connection is impossible if your corporate PC requires a connection to the Corporate VPN -- use [NMLconnect](https://connect.nml-lmn.phac-aspc.gc.ca/) instead in this case.

Once connected to the VPN, the science network webapps can be access using a web browser.

## Accessing IRIDA

The link to IRIDA is [ngs-archive.corefacility.ca](http://ngs-archive.corefacility.ca).
Note that IRIDA requires _seperate_ credentials from your science network credentials --
contact the [helpdesk](mailto:helpdesk@nml-lmn.phac-aspc.gc.ca) to request access to IRIDA if need an account.

## PowerBI dashboards

Work Package 6 is creating dashboards in PowerBI to facilitate access to the data being submitted to the GRDI-AMR2 project.
These dashboards must be accessed through the Chrome Webapp (via NMLConnect) or otherwise when connected to Science Network VPN.
The link to PowerBI dashboards is [powerbi.cscscience.ca/reports/browse](https://powerbi.cscscience.ca/reports/browse).
You will need to be granted access to the GRDI-AMR2 reports.
Most users _should_ have access to GRDI-AMR2 dashboards already - contact [Emil Jurga](mailto:emil.jurga@phac-aspc.gc.ca) if you cannot access them.

