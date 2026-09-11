# TARGET: today's build

- **Thing:** A one-page HB Design & Construction rental-property site where renters browse approved property listings and send a service request by email.
- **Audience:** HB Design & Construction's property manager, who needs a clear view of listings, and renters, who need to find their rented property and report a maintenance need.
- **Requirements:** One working primary interaction: browse property cards, select the property the renter is renting, and submit a service request addressed to `levihawes0@gmail.com`; selected property and request details are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A University of Oregon-inspired look using coordinated green and yellow, with a large stylized O as the opening visual; it is distinctly HB Design & Construction, not an official University of Oregon site.
- **Test:** I can browse the available-property cards, select exactly one property I rent, and submit a service request that opens a correctly addressed email with the chosen property and request details. The form blocks submission without a selection. After I approve and merge, the same registered Pages URL works.

Approved listing details will replace clearly labeled sample listings before publication. Rent payments, payment tracking, renter applications, and permanent property management are planned features that need separate secure services.