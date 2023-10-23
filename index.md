---
layout: project
color: "#a864bd"
logo: Visual Database Interfaces
---

<div class="callout">
  <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1845638&HistoricalAwards=false">NSF IIS-1845638</a>
</div>

As access to data becomes more widespread, more and more people want to benefit from the ability to analyze data. Unfortunately, the dominant database interface ? SQL ? is very complex and inaccessible. It is possible to design and develop custom interactive form and visualization interfaces that are easy to understand and efficient to use, however, they are out of reach for all but the most widespread (general-purpose) or highest value tasks due to the considerable time and resources to build them. Unfortunately, this overlooks a long tail of simple analyses that may never see millions of users but are still crucial towards making scientific progress, reaching individual goals, and seizing commercial opportunities. Thus, there is a need to drastically reduce the costs to build new interfaces. The proposed research will develop scalable techniques to automatically generate interactive visual analysis interfaces that are customized to the user?s analysis needs and preferences. This research can have a transformative impact on data-driven fields such as earth sciences or bioinformatics, and help democratize access to data. Finally, the focus on data interfaces is naturally suited as an educational tool to introduce data analysis to students and the public.

This project develops scalable techniques to generate Visual Database Interfaces (VDIs), each tailored to specific analysis tasks. Rather than conform to the interface defined by SQL or a generic database exploration tool, users can use VDIs that are more accessible to non-technical users, more efficient for performing tasks, and reduces user reliance on technical experts. To bootstrap the interface generation process, the PI proposes to leverage logs of existing analysis queries and workflows that users have previously attempted. Using these logs, the PI will develop two novel and complementary systems. The first system scalably extracts analyses from query logs, and automatically generates interactive analysis interfaces that are customized to the queries in each analysis. The second is a human-in-the-loop interface design tool that helps designers further improve the interaction design of VDIs with consideration of the optimizations and systems modifications need to ensure the interactions are responsive. It does so by bridging the divide between interaction design requirements that affect the end-user?s experience, and data structure and system architecture decisions that affect resource requirements. The project will evaluate VDIs based on the ability for users to complete analysis tasks as compared to using legacy or manually designed interfaces. The PI will also evaluate VDIs in university courses on Data Science, and share the curricula publicly along with the software.



## Principal Investigators

* [Eugene Wu](https://www.eugenewu.net), Columbia University 

## Open Source Software

* [Learned Interfaces](https://github.com/learnedinterfaces/PI2): generate interfaces from natural language and queries.

## Galleries and Tutorials

* Relational Visualization Tutorial: [Short Paper](./files/tutorial-vis-sigmod19.pdf), [Slides](#)
