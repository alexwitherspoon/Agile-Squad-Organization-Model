**Agile Squad Definition & Discovery**

**TL:DR** - An example template for defining an agile Squad
Source Document: https://github.com/alexwitherspoon/Agile-Squad-Organization-Model/blob/master/Agile-Squad-Definition-Discovery.md

![](https://images.unsplash.com/photo-1519636125090-67a506cc7c74?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjExNzczfQ&s=457d4670adba65cda3c031ded54d7aa6)
<small>Photo by [rawpixel.com](https://unsplash.com/@rawpixel?utm_source=ghost&utm_medium=referral&utm_campaign=api-credit) / [Unsplash](https://unsplash.com/?utm_source=ghost&utm_medium=referral&utm_campaign=api-credit)</small>

**Why Defining the Squad Matters**

For an Agile Squad to best function, they need to be able to define what they are authoritative for, the dependencies of that Squad, and describe the goals of that Squad. This helps Squads define areas of autonomy, and declare clear dependencies between Squads. 

I'll revisit this over time to continue to add additional thoughts, so consider it an incomplete WIP. If you'd like to contribute, PRs/dialogue is welcome over at the github repository for this document. The latest accepted version will be updated regularly on my website: https://log.alexwitherspoon.com/agile-squad-definition-discovery

**How do we Charter an Agile Squad or Team!?**

I'll consider that out of the scope of this document, and in the future, I'll write some ideas around how to successfully charter a team, but here is a great article to start the conversation: https://medium.com/agile-outside-the-box/inception-getting-to-rapid-alignment-on-team-vision-and-goals-47cc60b0cb9

**How to use the Template, and How to Drive Alignment**

There is certainly many ways to approach this, but I've arrived at this basic starting point. Each Squad should work to author, publish, own, maintain, and seek approval from the business for a living definition of the Squad as outline below. Being a living document, this should be revisited regularly, at least quarterly. These definitions should be published in a place that is easily seen by the entire company, and should be used to on board new employees, as well as enable a growing organization to easily learn and discover what work is being worked on, and the Squad that is accountable for the cross functional execution for a given project or asset.

## Squad Definition Template

* **Name**
    * (Example DataTeam)
* **Alias Url to Discover Squad**
    * This Url is an alias, and could point to a wiki, confluence, or other general page which contains the content of this template and more as appropriate. It's the jumping off point for anyone trying to learn about a Squad, and the work they do. This Url should be added to documentation, on application health pages, or even embedded in metadata describing the source Squad of a given dataset to help discover who the authoritative group is for a given thing.
    * (Example datateam.acme.org)
* **Charter, Mission, or Vision**
    * (Example Charter: The DataTeam will process all normalized data to apply business logic to it, and supply downstream customers while managing and striving for excellent data quality and value.)
* **Product & Asset List**
    * List should minimally include Name, Code Repository URL, and link to Metrics or further documentation.)
    * (Example: Name: engine1, github.com/acme/engine1, http://docs.acme.com/engine1 
* **Core Squad Member List**
    * Minimally List the name, and role of each member of the Squad which works consistently and daily on this Squad. These are likely the regular members of a daily Squad standup.
    * (Example: Bob, Software Engineer - Beth, Site Reliability Engineer)
* **Squad Community Dependency List**
    * List the Name, Role, and nature of dependency on outside people, process, or tools. These should be important to the function of the Squad, but are non-core members, and may be shared [functional teams](https://log.alexwitherspoon.com/agile-squad-organization-models/), or only occasionally engage with the Squad as required, such as weekly or monthly check-ins.
* **Service Level Objectives & Metrics**
    * For any asset, or product there should be defined [Service Level Objectives](https://en.wikipedia.org/wiki/Service_level_objective), definition of metrics which support those objectives, and links to the dashboard or metric data. 
    * Metric definitions should be declared in human readable form, as well as any code required to measure or generate these metrics distinctly in a tool which allows for versioning, such as Git, Wiki, or similar. This will allow for tracking the changes to SLO goals.
    * Metric data should be concisely displayed on Dashboards to help align all members of the team, as well as the organization. Metrics should be well understood and be significant to success. 
    * (Example: Name: engine1, SLO: Uptime 99.9% per Month, Code: github.com/acme/engine1/slo, Dashboard: http://dashboard.engine1.acme.org)
