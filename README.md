# NextCore

TechNext internal project (plan v5, 5 Nov 2026): a production system for client materials. Client information goes in once, becomes one client profile, and NextCore builds every material from it automatically:

1. Input: Client information, Client profile (with brand kit), Build order
2. Build materials (one builder each, queue order): Sales Proposal, Data Gathering page, Service Level Agreement, Presentation, Social media posts, Nexi video
3. Check: Quality checks, Your review
4. Deliver: Client material pack, Rebuild on update

Each card opens a panel with its build pipeline, data (reads, template, produces, checked by) and the Claude skills, tools and people it needs; drag the panel edge to widen it. Deep links: #info #profile #order #proposal #data #sla #deck #social #nexi #qa #review #pack #rebuild

Live: https://technextmarketing.github.io/technext-new-client-build-flow/

Source of truth: Marketing drive, 02. TechNext Folder/24. NextCore (New Client Build)/nextcore-build-flow.html (index.html = that file wrapped in a full HTML document). Northgate Trading Corp. is sample data.
