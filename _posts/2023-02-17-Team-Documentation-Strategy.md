---
layout: post
title: "Team Documentation Strategy"
description: "Setting up a team documentation strategy."
categories: [Personal-Knowledge-Management]
tags: [Documentation, Team]
redirect_from:
  - /2023/02/17/
---

# Team Documentation Strategy

For my current assignment I had the opportunity to migrate our documentation from Word files and Teams wikis to Confluence. As I was one of the most vocal ones about the issues to find what you were looking for in our documentation they asked me to be the driver for the migration, which I happily accepted. They also asked me to write down what was in my head on how the documentation strategy should work. The customer so kindly let me create a blog post based on the document that I created. The following text is what I created, rewritten to remove internal references and links.

One important thing to keep in mind is that these were not rules put in place for the team, just ideas, and opinions of how I as a team member would find it most optimal. The documentation is collaborative collection and ownership. Different people have different preferences and different teams have different needs, visions, and missions.

![Documentation]({{site.url}}/assets/images/documentation.jpg)

## Vision
- The goal is that it should be low friction for the team to create, update and read the documentation.
- Team members own the documentation together.
- Team members should be free to add, reformulate and remove the content as seen needed.
	- This will ensure that only the information the team members find relevant is part of the documentation.
- The team should aim for cross-referencing instead of duplication of documentation.
	- Cross-referencing lowers the risk of info and instructions branching.

## Structure

### Home Page
The first page in the team's space is the home page. When someone is located here, they should never feel lost. It should at least contain what we do, who we are and the major locations of information are stored. A few other examples of what it can include:
- List of team members.
- Links to tools that are commonly used by the team.
- Latest updates made to the documentation.

### First-Level in the Page Tree
The first level of pages in the documentation structure should cover major distinct areas. Having the right granularity is hard and different people most probably have different opinions on what granularity is the most correct. Having too low granularity there will be few top-level pages and information will be buried deep and hard to find. Having high granularity it will be many top-level pages and it will be hard to know in what tree, the information of interest is located.

A good rule of thumb if the information should be on its own page at the top level or in a sub-level is to ask on selves. Does it make sense to put this information as a sub-page to any of these major areas already listed?

When I asked ChatGPT for feedback on this section it said I should give some examples of first-level pages:
- Administrative Info: Collection of documentation about time reporting, vacation list, and other administrative tasks.
- Way of Working: Documentation of how the team should work together.
- Technical Wiki: Collection of guides and references that team members could use in their daily work
- Deliverables: If the team has a clear scope of deliverables that are expected from them. Each deliverable could then have its own first-level page collecting documentation needed for those deliveries.

### Second-Level in the Page Tree
The structure of pages under the top level is quite shallow and does not contain many sub-levels. This is due to that it is hard to find information that is structured deep down in nested pages. Nested pages are mostly found if there is a hard connection between the parent page and the sub-pages. Having many nested pages can be tempting as a long list of pages can be seen as overwhelming as they lay in an unsorted order. One method rising in popularity to combat the chaos that comes with a lot of pages is Map of Contents (MoC) which is a page where links to relevant information are stored.

For more information on Map of Contents, the following resources can be read:
- [Olof Haglund's Working With Map of Contents](https://olofhaglund.name/blog/2022/10/15/Working-With-Map-of-Contents/)
- [Sébastien Dubois' Maps of Content (MoCs) for better Knowledge Graphs](https://dsebastien.net/blog/2022-05-15-maps-of-content)

### Naming Pages
The name of the pages should reflect what the content is about. A person knowing exactly what they are searching for will likely search for that. What is most likely searched are either concepts or names (persons, tools, ideas...). Naming a page after the concept or tools that are used, will make the documentation much easier to find.

### Write Once, Use Everywhere
Confluence has multiple features where you can include information from one part in another part. The easiest one is the *include page* macro. This allows us to write information in one place and then include the same information on another page and when the original page is updated the same update is reflected on all pages. This allows one to have information on multiple locations without the risk of having information and instructions branching.

If some content is too large or contains more text than you want to be included it is better to break that content down into smaller modules than manually writing or copy-pasting the same information to the other location. By having it in modules the same brick can be used to build multiple houses!

# Images
[Sigmund on Unspash.com](https://unsplash.com/photos/k3Y2iBBCag8?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
