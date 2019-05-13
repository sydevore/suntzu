# suntzu

Sun Tzu is meant to be a security lifecycle system that assists in building a secure service at every stage. Upon inception, various components can be created, and those that the system knows about will offer guidance, as well as generic language security pointers. When a service has been created and the architecture updated within Sun Tzu, it will assist in threat modeling and more specific recommendations. Finally, it will have links for compliance and pentesting artifacts. TODOs will include ticketing integration.

## Project inception

When a team is creating a new service, it can initialize a new spot in SunTzu that will take generic info (team lead, repo, description, language, and generic components). Output will be a URL containing generic language and component security information for a service team to ignore.

TODO will be to put the components into a network diagram.

## Service creation

Once a service has been created, a selection within the UI will expand to a more detailed threat analysis baseline. 

Initial profile questions:

  * Basic info
  ** Service name
  	** Repo
  	** Team contact alias
  	** Resource filling out this form
  	** Description of the project to be threat modeled
  	** Links to architecture diagrams
  * Service profile
    ** Components list
    ** Data assets
    ** Pojrect dependencies
    ** Webapp/API/OS/Agent/Library/Framework/Application/Storage - select all that apply and include quantity of each
    ** Position - public/private/customer/mgmt/
    ** Compliance frameworks
  * Initial questions
    ** Does this store data? If so, what's the sensitivity?
    ** How does the app handle users?
    ** Where/how is authN/Z handled?
    ** How are secrets managed?
    ** Per component, what privilege/user/role does each run under?
    ** Compute isolation
    ** Network isolation
    ** Encryption at rest
    ** Encryption in transit
    ** Logging & non-repudiation
    ** Logging of sensitisve data
    ** Frameworks, languages and injection prevention
    ** Dependency management
    ** Security release/CSIRT-ready
    ** Known issues



TODO will be to output links to testing tools (code scanners, unit tests, etc)

TODO will be to include more detailed recommendations and a more specific diagram.

TODO will be to interface with a ticketing system to create tickets on discovered risks from the baseline.

## Compliance and pentesting

Annually, a ticket will be created for the baseline to be 're-upped' and reviewed (with historical reviews held in prior tabs). There will be input fields for links to compliance artifacts (code scan output, etc.), and pentest reporting.
