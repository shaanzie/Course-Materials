# Software as a Service

- SaaS: The capability provided to the consumer to use the provider's applications running on a cloud infrastructure
- The applications are accessible from various client devices through a thin client interface
- Characteristics
  - Network delivered access to commercially available software
  - Application delivery is one-to-many model
  - Built on optimized and robust platform
  - Pay for need
- Benefits
  - No local infrastructure or software
  - Operating costs reduced
  - Improved availability
  - Lower TCO
- Revenue options
  - Subscription
  - Tiered pricing
  - Usage based pricing
  - Per active user pricing
  - Per feature pricing
  - Ad based revenue 
- Business logic is frequently implemented as microservices on the cloud

## Salesforce

- Customer Relationship Management
  - Sales
    - Representatives
    - Managers
  - Marketing
    - Campaigns and studies
  - Customer Service
    - Handle calls
    - Workflow
- Salesforce terms
  - Opportunity : A potential sales deal you want to track
  - Lead : A lead is a prospect or potential opportunity
  - Account: A company or org you want to manage
  - Contact : A person that works for an account
  - Tasks and Events : Activities associated to any of these
  - Reports : Real time summaries
- Tools in Salesforce
  - Sales cloud : Helps close deals
  - Service Cloud : Increases agent productivity
  - Collaboration cloud
- Workflow 
  - Create application description
    - Define data model, rules for validations
  - Automate process using workflow
    - Workflow rules, email alerts and tasks
    - Set workflow rule
    - Test workflow rule
    - Build approval process
    - Create email template
    - Create approval process
    - Create a custom profile
    - Create a user
    - Test approval process
  - Creating reports and dashboards
    - Customized dashboards
  - Adding programming logic to apex
    - Development platform to access backend database and client server interface
  - Adding testing to apps
  - Building custom UI
    - Visualforce for streamlined UX
- Application Building Blocks
  - Declarative - Simplicity and Speed
    - UI - applications, tabs, page layouts, record types
    - Business logic - Workflow, validation rules, assignment rules
    - Data model -  Objects, fields, relationships
  - Programmatic - Control and Flexibility
    - UI - Visualforce pages, web controls, Force.com
    - Business logic - Visualforce controllers, apex, Web services API
    - Data model - Web services API, Metadata API
- Scaling
  - Built on PaaS
  - Multitenancy
  - Query optimization
- Modules
  - Building blocks for Gmail clients
  - Based on entry points
- Backend design
  - Break the solution into multiple workflows
  - Define customizations and GUI
  - Handle schema and customizations
  - Define web services
- Trove provides database as a service in OpenStack
- Multitenancy levels
  - Ad hoc / Custom
    - Each tenant has own version of software
  - Configurable
    - Only one version of software
    - Leads to manageability savings
  - Configurable, Multitenant efficient
    - One instance
  - Scalable, Configurable, multitenant efficient
    - Software hosted on cluster
    - No performance bottleneck