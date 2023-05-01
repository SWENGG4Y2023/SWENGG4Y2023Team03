# Asset Manager App SRS 
  -----------------------------------------------------------------------

  -----------------------------------------------------------------------



**Introduction**

**1.1** **Purpose**

We are developing an Asset Manager application which can handle IT
assets for a particular team. It is suitable for any IT group who wants
to organize their IT assets and keep a record of their assets for future
reference. Through this application an IT asset Manager can easily add
delete search view and even check the history of who have used a
particular asset previously. The user interface is very simple to
understand and use. This the first release of our product and it has all
the basic functionality like inserting an asset deleting an asset,
searching etc in the scope

**1.2 Document Conventions**

In this release we are focusing on basic requirements of the product. we
have considered basic functionality as top priority task apart from that
the underlying requirements by the stakeholders are taken as top
priority and are finished in this release. The other requirement based
on the feedback from the stake holder would be taken for the next
release.

**1.3 Intended Audience and Reading Suggestions**

This product is a need for any kind of professionals who are tasked with
maintaining and keeping a record of official assets be it a laptop,
headphones, charger or even a shareable devices like printer, speaker
etc. This product can be useful for every professional in a team.

A team lead or a developer can use this product to check the status of
his team's asset. Even this product can be useful for developers who
want to check for an asset specification and want to check whether a
shareable resource is available or not so that he can obtain it. This
Product is particularly useful for business IT team who wants to check
the overall status of the business assets whether any asset is out of
date, not required or is free to obtain for proper utilization of the
resources. To get a proper understanding about the project he can start
with the overall description and go through all the sections including
the system feature which will help him to get a proper understanding
about the product

**1.4** **Project Scope**

The Asset Management Software is a centralized system for managing and
tracking the assets assigned to IT employees within an organization. It
will provide an efficient and user-friendly way to keep track of the
assets, their assignments, and their history.

Benefits:

-   Organize companies' asset with less time and money

-   Provide a proper description about the asset including
    specification, history of usage, employee who is currently using it

-   It specifies whether an asset is available or obtained by an
    employee

-   Shows the list of assets and its description in a card layout for
    proper visibility

The main objective or goal of this product is to provide an Asset
Management solution which can save companies time and money by
organizing its asset effortlessly with the help of simple UI design that
can be easily understand and provide a proper description about the
product with proper functionality

**1.5 References**

To get a proper understanding please go through the
[website](https://www.manageengine.com/products/service-desk/it-asset-management/inventory-management-software.html?network=g&device=c&keyword=asset%20management%20system&campaignid=11606196139&creative=493067112127&matchtype=e&adposition=&placement=&adgroup=116775094047&targetid=kwd-63450690&location=9061994&gclid=CjwKCAjwuqiiBhBtEiwATgvixM5ZW9jDI3uiWOTfqkYlnjuBCBIIUwEKMRkegNRc4sAjucV5BzqdYhoCeLYQAvD_BwE)
to get an understanding of what is asset management. The UI interface is
custom build with angular components and is made simple for better
usability

**Overall Description**

**2.1 Product Perspective**

Asset Manager is a new concept for IT industries totally built from
scratch. It does not belong to any product family and is also not a
continuation of existing software. This product is created based on the
real business use case as stated by the stakeholders.

**2.2 Product Features**

For this release we are focusing on key features for Asset Manager App.
It enables an IT management team to easily insert an Asset, delete an
Asset, check history of usability of the Asset, search a particular
asset. The UI of the main page is highly interactive and easy to use the
Assets are in form of card layout which provides essential information
about the assets like specification, employee who is currently using and
its availability. Any user be it a developer or any professional can
easily acquire an asset with the click of a simple button. There is a
"Acquire" button located at the bottom of each card where user can
simply click and enter it user ID and based on it the device would be
registered for the user. More details regarding the feature are
available in Section. 3

![](vertopal_d9472fab4c764680a2ffd9ca07fc03e2/media/image3.png)
**Top Level data flow diagram of Asset Manager APP**

**2.3 User Classes and Characteristics**

Favoured user classes will likely be IT Managers and IT Technicians, as
they will be the primary users of the app. IT Procurement Officers, IT
Security Officers, and IT Executives will also be important users, but
they may have more specialized needs that require additional
customization and functionality.

Potential user classes are as follows:

-   IT Managers: These users are likely to be the primary users of the
    app. They will need to manage the entire IT infrastructure and
    assets, which may include hardware, software, licenses, and
    peripherals. They will need to be able to track the inventory,
    lifecycle, usage, and maintenance of each asset. They may also need
    to generate reports on asset usage, costs, and compliance.

-   IT Technicians: These users may need to perform maintenance, repair,
    and replacement tasks on IT assets. They may use the app to view
    asset specifications, troubleshooting guides, and repair histories.
    They may also need to update asset information in real-time as they
    perform their tasks.

-   IT Developers: These users may use this product to acquire new
    hardware bases on the requirement.

-   IT Security Officers: These users may need to ensure that the IT
    assets are secure and compliant with regulations and standards. They
    may use the app to track security vulnerabilities, apply security
    patches, and monitor access to sensitive data. They may also need to
    generate security audit reports and compliance documentation.

-   IT Executives: These users may need to oversee the entire IT asset
    management process and make strategic decisions based on the asset
    data. They may use the app to view high-level reports and
    dashboards, set budgetary priorities, and make decisions on asset
    investments.

2.4 Operating Environment

**This product can be accessible from any device that has browser
support.**

**Some preferred browsers:**

-   **Chrome: Any version of chrome can be used. Preferred version
    112.0.5615.137 and above.**

-   **Microsoft Edge: 112.0.1722.64 and above is preferred.**

-   **Brave: Any version can be used**

**2.5 Design and Implementation Constraints**

Here are some items or issues that may limit the options available to
developers when creating an IT asset manager app in the IT industry:

-   Regulatory Policies: The app may need to comply with regulatory
    policies related to data privacy, security, and accessibility. For
    example, the app may need to adhere to GDPR or HIPAA regulations,
    which may limit the types of data that can be stored and how that
    data can be used.

-   Hardware Limitations: The app is needed to operate within certain
    hardware limitations, such as timing and memory requirements. The
    main limitation is it requires browser compatibility.

-   Interfaces to Other Applications: The app may need to interface with
    other applications or systems, such as enterprise resource planning
    (ERP) systems or customer relationship management (CRM) systems.
    These interfaces may be subject to certain protocols or data
    formats, which may limit the options available to the developers.

-   Specific Technologies, Tools, and Databases: The app may need to be
    developed using specific technologies, tools, and databases. For
    example, the app is needed to be developed using a specific
    programming language, such as Java, Mongo dB for database
    compatibility

-   Security Considerations: The app is needed to be developed with
    security considerations in mind. This may require the use of
    specific security protocols or the integration of specific security
    tools or libraries.

-   Design Conventions or Programming Standards: The app is needed to
    adhere to specific design conventions or programming standards. For
    example, the app is needed to follow the Model-View-Controller (MVC)
    design pattern.

Overall, developers may need to navigate several limitations and
considerations when creating an IT asset manager app, including
regulatory policies, hardware limitations, interfaces to other
applications, specific technologies, security considerations, and design
conventions or programming standards.

**2.6 User Documentation**

Here are some user documentation components that may be delivered along
with asset manager app:

-   User Manual: This document provides a detailed description of the
    app\'s features, functions, and workflows. It may also include
    step-by-step instructions on how to perform specific tasks within
    the app.

-   Online Help: This is an interactive component that provides users
    with contextual help while they are using the app. It may include
    tooltips, pop-up windows, and search functionality to help users
    quickly find the information they need.

-   Tutorials: These are interactive components that guide users through
    specific tasks or workflows within the app. They may include videos,
    animations, and quizzes to help users learn the app\'s functionality
    in a hands-on way.

-   Release Notes: These documents provide information on the app\'s
    latest release, including any new features, bug fixes, and
    improvements.

-   Technical Documentation: This may include API documentation, data
    dictionaries, or system architecture diagrams that provide technical
    details on the app\'s underlying structure.

The delivery format for user documentation components may vary depending
on the specific needs of the user. Some common formats include:

-   PDF Documents: User manuals and release notes may be delivered in
    PDF format, which can be easily downloaded and printed by the user.

-   HTML Pages: Online help and tutorials may be delivered as HTML
    pages, which can be easily accessed from within the app or from a
    web browser.

-   Videos: Tutorials may be delivered as videos, which can be accessed
    through an online video platform or downloaded for offline viewing.

-   Online Help System: An online help system may be delivered as part
    of the app, which can be accessed by the user through a search bar
    or a dedicated help button within the app.

In terms of standards, user documentation for an IT asset manager app
may need to adhere to industry standards for technical writing, such as
the Microsoft Manual of Style or the Apple Style Guide. It may also need
to comply with any regulatory requirements for documentation, such as
those related to data privacy or accessibility.

**2.7 Assumptions and Dependencies**

Assumed factors that could affect the requirements stated in the SRS for
an IT asset manager app for IT industries could include:

1.  Third-party or commercial components: The app may need to integrate
    with other third-party or commercial components for example we are
    planning to integrate SAP angular web components which might affect
    some devices.

2.  Development environment: Assumptions about the development
    environment, such as the availability of development tools,
    programming languages, or development frameworks, could impact the
    requirements of the app. For example, if the development team
    assumes that a certain development framework will be available, but
    it is not, it could impact the development timeline and the
    requirements of the app.

3.  Operating environment: Assumptions about the operating environment,
    such as the hardware and software configurations of end-user
    devices, could impact the requirements of the app. For example, if
    the app is assumed to be used on a particular operating system or
    device type, but end-users use a different system or device, it
    could impact the functionality and usability of the app.

4.  Constraints: Assumptions about constraints, such as budget,
    timeline, or resources, could impact the requirements of the app.
    For example, if the development team assumes that a certain budget
    or timeline will be available, but it is not, it could impact the
    functionality and quality of the app.

**System Features**

The list of Features is given below with their priorities. We are
focusing on the basic requirement for this release which are required by
the stake holders.

**Adding Asset**

**3.1.1 Description and Priority**

This feature enables to add a new asset to the list. It takes Asset
name, specification, and Employee Id as input and then it maps the asset
to that employee. If the user does not wish to map any employee, then he
can make the employee field as empty this will make the status of the
asset as available. The priority of this feature in high as this is a
basic feature.

**3.1.2. Stimulus/Response Sequences**

Steps to add an Asset:

-   User clicks on the add Asset button in the title bar

-   A pop up appears for Asset name, details, and employee Id

-   User fills the details and then click on create

-   System creates a new asset and maps it to the employee

**3.1.2 Functional Requirements**

REQ 1 - Stable internet connection: The internet connection should be
stable while creating an asset or else it will throw an error "Network
not found".

REQ2 -- Stable browser version: The browser should be stable and should
not crash in the middle of a session.

**Deleting Asset**

**3.2.1 Description and Priority**

This feature enables user to delete an existing asset from the list.
This feature is also taken as high priority since this is a basic
feature.

**3.2.2 Stimulus/Response Sequences**

Steps to delete an Asset:

-   User clicks on the trash icon in the card layout of a particular
    asset

-   A pop up appears stating if he wants to delete

-   User clicks 'YES'

-   System first removes all the mapping for acquire employee if present
    and then remove the list and deletes the asset document from the DB.

**3.2.3 Functional Requirements**

REQ 1 - Stable internet connection: The internet connection should be
stable while deleting an asset or else it will throw an error "Network
not found".

REQ2 -- Stable browser version: The browser should be stable and should
not crash in the middle of a session.

**Searching an Asset**

**3.3.1 Description and Priority**

This feature enables user Search an asset from the list. It is
particularly helpful when list is comparatively huge. The search query
can also be made complex in order to enhance customer experience. This
is also a high priority feature and would be delivered in the first
release.

**3.3.2 Stimulus/Response Sequences**

Steps to search an Asset:

-   User clicks on the search button in the title bar

-   User enters the desired asset name and hit 'Enter'.

-   System does a get all asset call to data base and display the list

**3.3.3 Functional Requirements**

REQ 1 - Stable internet connection: The internet connection should be
stable while deleting an asset or else it will throw an error "Network
not found".

REQ2 -- Stable browser version: The browser should be stable and should
not crash in the middle of a session.

**History of an Asset**

**3.4.1 Description and Priority**

This feature enables user to check who have used the asset. It is in the
form of a horizontal list with comma separated element with first in the
list is the one who is currently using and followed by who have recently
used.

**3.4.2. Stimulus/Response Sequences**

Steps to check history an Asset:

-   User clicks on the history icon (clock symbol) which is present for
    all asset

-   System gets all the history for the asset from the database

**3.4.3. Functional Requirements**

REQ 1 - Stable internet connection: The internet connection should be
stable while checking history an asset or else it will throw an error
"Network not found".

REQ2 -- Stable browser version: The browser should be stable and should
not crash in the middle of a session

**Acquiring an Asset**

**3.5.1 Description and Priority**

This user enables user to acquire an asset with the click of a button.
The System takes care of the rest of the processing and register the
asset with the respective user. This is a basic functionality and is
taken as high priority.

**3.5.2. Stimulus/Response Sequences**

Steps acquire an Asset:

-   User clicks on the acquire which is present for all assets.

-   Pop up appears for entering the employee Id.

-   After entering system validates the employee Id and maps the asset
    to the user

**3.5.3. Functional Requirements**

REQ 1 - Stable internet connection: The internet connection should be
stable or else it will throw an error "Network not found".

REQ2 -- Stable browser version: The browser should be stable and should
not crash in the middle of a session

External User Requirements

**4.1 User interface**

Sample image of Asset Manager UI

![](vertopal_d9472fab4c764680a2ffd9ca07fc03e2/media/image4.png)

All the icons, buttons, layouts etc. are custom made using html and CSS
based on angular framework.

**4.2 Hardware Interfaces**

The logical and physical characteristics of the interface between a
software product, such as an Asset manager app, and hardware components
of a system can vary depending on the specific requirements of the
application and the devices being used. However, there are some common
elements that are generally present in these interfaces:

-   Supported device types: This software is supported for any device
    which have browser compatibility.

-   Communication protocols: The interface between the software and
    hardware must use specific communication protocols to ensure that
    data and control interactions are reliable and secure. Some common
    communication protocols used in IT industries include TCP/IP, SNMP,
    WMI, SSH, and HTTP.

-   Physical connectivity: The hardware components of the system must be
    physically connected to the software through various interfaces,
    such as USB, Ethernet, Wi-Fi, Bluetooth, or other wireless or wired
    connections.

In summary, the interface between an IT asset manager app and hardware
components of a system must support specific device types, allow for
data, and control interactions, use appropriate communication protocols,
and be physically connected through various interfaces. The exact
characteristics of the interface will depend on the specific
requirements of the software and the hardware being used.

Other Non-functional Requirements

5.1 Performance Requirements

Here are some basic performance requirements for our asset management
app:

-   Speed: The app should be responsive and load quickly. Users should
    not have to wait too long for the app to perform tasks.

-   Scalability: The app should be able to handle a growing number of
    users and data without compromising its performance.

-   Reliability: The app should be able to perform consistently and
    reliably without crashing or losing data.

-   Availability: The app should be always available to users, with
    minimal downtime for maintenance or upgrades.

-   Compatibility: The app should be compatible with different operating
    systems and devices, including desktop and mobile devices.

-   Integration: The app should integrate with other systems and
    applications, allowing users to easily import and export data.

-   Reporting and analytics: The app should provide comprehensive
    reporting and analytics capabilities, allowing users to analyse and
    track their assets\' performance.

-   Customization: The app should be customizable, allowing users to
    tailor the app\'s functionality to meet their specific needs.

5.2 **Safety Requirements**

Here are some basic safety requirements for our asset management app:

-   Encryption: The app should use encryption to protect sensitive data,
    such as passwords and financial information, during transmission and
    storage.

-   Authentication and Authorization: The app should require users to
    authenticate and authorize themselves before accessing sensitive
    data or performing critical actions.

-   Access Controls: The app should have access controls in place to
    ensure that users can only access the data and functions that they
    are authorized to use.

-   Audit Trails: The app should maintain audit trails that record user
    actions and events in the app, allowing for the detection of
    unauthorized activity and the reconstruction of events.

-   Data Backup and Recovery: The app should have a robust data backup
    and recovery system in place to ensure that data can be recovered in
    case of accidental deletion, hardware failure, or other incidents.

-   Secure Development Practices: The app should be developed using
    secure development practices, including regular code reviews and
    vulnerability testing, to prevent the introduction of security
    flaws.

-   Regular Updates and Maintenance: The app should receive regular
    updates and maintenance to address security vulnerabilities, patch
    bugs, and improve performance.

-   Compliance with Regulations: The app should comply with relevant
    regulations and industry standards, such as GDPR, CCPA, and ISO
    27001.

-   Penetration Testing: The app should undergo regular penetration
    testing to identify and address potential security weaknesses.

-   Incident Response Plan: The app should have an incident response
    plan in place to address security incidents and ensure that users
    are notified in a timely and transparent manner.

5.3 Security Requirements

Specific important security requirements for our asset management app:

-   Authentication and Authorization: The app should use strong
    authentication methods, such as multi-factor authentication, to
    ensure that only authorized users can access the app and its data.

-   Secure Data Storage: The app should store sensitive data, such as
    passwords and financial information, securely using
    industry-standard encryption methods.

-   Secure Communications: The app should use secure communication
    protocols, such as SSL/TLS, to ensure that data transmitted between
    the app and its users is protected from interception and tampering.

-   Role-Based Access Control: The app should enforce role-based access
    control to limit access to sensitive data and functionality based on
    users\' roles and permissions.

-   Secure Coding Practices: The app should be developed using secure
    coding practices to prevent the introduction of security
    vulnerabilities during development.

-   Regular Security Testing: The app should undergo regular security
    testing, such as penetration testing and vulnerability scanning, to
    identify and address potential security weaknesses.

-   Security Incident Response Plan: The app should have a security
    incident response plan in place to detect, respond to, and recover
    from security incidents.

-   Compliance with Regulations: The app should comply with relevant
    regulations, such as GDPR, CCPA, and HIPAA, as well as
    industry-specific security standards, such as ISO 27001.

-   Secure Third-Party Integrations: The app should ensure that any
    third-party integrations, such as APIs, meet the app\'s security
    requirements and do not introduce security vulnerabilities.

-   Continuous Security Monitoring: The app should implement continuous
    security monitoring to detect and respond to security threats in
    real-time.

5.4 Software Quality Attributes

Here are the most important software quality attributes for our asset
management app:

-   Reliability: The app should perform consistently and accurately,
    even under heavy usage or in the presence of errors. This is
    essential to ensure that users can manage their assets without any
    disruptions.

-   Security: The app should be secure, with features like
    authentication, encryption, and access controls to protect user data
    and prevent unauthorized access. This is crucial to maintain user
    trust and protect sensitive financial information.

-   Usability: The app should be easy to use and navigate, with a clear
    and intuitive user interface that makes it easy for users to manage
    their assets. This is important to ensure that users can efficiently
    and effectively manage their assets.

-   Performance: The app should be fast and responsive, with quick load
    times, minimal lag, and smooth transitions between screens. This is
    essential to ensure that users can use the app without any delays or
    frustration.

-   Maintainability: The app should be easy to maintain, with code that
    is well-organized, modular, and easy to update or extend. This is
    important to ensure that the app can evolve over time as user needs
    change, and to minimize downtime for maintenance or updates.

Other Requirements

Additional Requirements:

-   Integration Requirements: The IT asset manager app should be able to
    integrate with other software systems commonly used in IT industries
    such as IT service management (ITSM) systems, enterprise resource
    planning (ERP) systems, and configuration management databases
    (CMDBs). Integration requirements should specify the interfaces,
    protocols, and data formats used to enable communication with other
    systems.

-   Reporting Requirements: The app should provide the ability to
    generate reports on asset data, such as inventory, maintenance
    history, and asset utilization. Reporting requirements should
    specify the types of reports needed, the data to be included in each
    report, and the format and frequency of report delivery.

-   Mobile Access Requirements: The app should be accessible on mobile
    devices, such as smartphones and tablets, to enable users to access
    asset data from anywhere at any time. Mobile access requirements
    should specify the mobile platforms supported, the user interface
    design for mobile devices, and the security measures required for
    mobile access.

-   Customization Requirements: The app should allow for customization
    to meet the unique needs of different organizations and industries.
    Customization requirements should specify the degree and type of
    customization allowed, the tools and methods provided for
    customization, and the level of support provided for customizations.

-   Audit Requirements: The app should provide the ability to track
    changes to asset data and user actions, and generate audit trails
    for compliance and accountability purposes. Audit requirements
    should specify the types of audit data to be collected, the level of
    detail required, and the retention period for audit data.

-   Training and Support Requirements: The app should be supported by
    comprehensive training and support services to ensure users are able
    to effectively use the app and troubleshoot any issues that may
    arise. Training and support requirements should specify the types of
    training and support provided, the methods of delivery, and the
    availability of support resources.

-   Scalability Requirements: The app should be designed to be scalable,
    with the ability to handle increasing amounts of data and users
    without compromising performance. Scalability requirements should
    specify the expected growth rate of the app, the maximum number of
    users and assets supported, and the strategies used to ensure
    scalability, such as load balancing and horizontal scaling.

Appendix A : Glossary

Glossary of terms :

-   ITAM - IT Asset Management

-   SRS - Software Requirements Specification

-   ERP - Enterprise Resource Planning

-   ITSM - IT Service Management

-   CMDB - Configuration Management Database

-   API - Application Programming Interface

-   GDPR - General Data Protection Regulation

-   CCPA - California Consumer Privacy Act

-   HIPAA - Health Insurance Portability and Accountability Act

-   OWASP - Open Web Application Security Project

Appendix B : Analysis models

![](vertopal_d9472fab4c764680a2ffd9ca07fc03e2/media/image3.png)

Diagram to Show how data flow in Asset Manager app

Appendix C : Issue List

-   List of Open Requirements Issues:

-   Database Design: The exact database schema has not been finalized,
    and there are still decisions to be made regarding data types,
    indexing, and normalization.

-   Third-Party Component Selection: There are several third-party
    components that could be used to implement certain features of the
    app, but a final decision has not been made regarding which
    components to use.

-   Security Requirements: Although the app is intended to be secure,
    there are still unresolved issues regarding authentication and
    authorization mechanisms, data encryption, and protection against
    common security threats.

-   User Interface Design: The user interface design is still in the
    early stages, and there are pending decisions regarding layout,
    color scheme, and user interaction patterns.

-   Internationalization Requirements: There is still information needed
    regarding the specific languages and cultures that the app will need
    to support, and how to properly localize the app for those regions.

-   Legal Compliance Requirements: There are still unresolved issues
    regarding compliance with data privacy regulations such as GDPR and
    CCPA, as well as industry-specific regulations such as HIPAA.

-   Performance Requirements: Although the app is intended to be
    performant, there are still pending decisions regarding acceptable
    response times and throughput rates, as well as how to measure and
    monitor performance.

-   Testing Requirements: The specific testing strategies and
    methodologies to be used have not yet been decided, including which
    types of tests (unit, integration, acceptance, etc.) to use and how
    to automate testing.

-   Deployment Requirements: The specific deployment architecture and
    processes to be used have not yet been decided, including whether to
    use cloud-based or on-premises hosting, and how to handle updates
    and maintenance.

-   User Access Control: There are still decisions to be made regarding
    user roles and permissions, as well as how to enforce access control
    policies.
