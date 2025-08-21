---
title: 'My Summer as an MP Intern'
date: 2025-08-20
---

I recently completed my internship for the **Materials Project** in the **Persson Group** at **Lawrence Berkeley National Lab**. This was an incredible experience for me, both as an eager young materials scientist and aspiring software engineer. I got great exposure to the behind-the-scenes operations of a massive, open database and helped develop some pipelines to keep entries up-to-date. Namely, I rebuilt the [**MPCite**](https://github.com/materialsproject/MPCite), the python package that the team uses to streamline the submission and validation of materials datasets for DOI number allocation, in an orchestrated and parallelized fashion. The package interfaces with the Office of Scientific and Technical Information's ELink API, orchestrates operations with Dagster, parallelizes its workflow with Dask, and queries the internal Materials Project MongoDB database with pymongo.

{{< figure 
    src="/images/berkeley.jpg" 
    alt="A photograph taken from LBL"
    link="https://www.lbl.gov/"
    caption="The view from LBL"
    class="ma0 w-75"
>}}
