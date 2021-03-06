---
layout: primer
title: Home
permalink: /
nav_order: 1
---

<center>
    <img src="https://ghicons.github.com/assets/images/light/Pull%20Request.png" alt="" 
width="84" height="84" />
    <h2>A MLOps Dashboard Automatically Created With GitHub Pages</h2>
    <p>This dashboard renders information in your repo relevant to machine learning projects automatically by using GitHub Actions and GitHub Pages.</p>
    <a href="">Learn more</a>
</center>

### Sections:

- **[Summary]({{ "pages/summary" | relative_url }})**: uses the `/project/model_card.md` file located your repo.  This is meant to be a high level summary of your model.  A recommended format for this is discussed in [Model Cards for Model Reporting](https://arxiv.org/pdf/1810.03993.pdf).

- **[Reports]({{ "pages/reports" | relative_url }})**: these pages automatically render Jupyter notebooks located in the `/notebooks` directory of your repo.

- **[Model Timeline]({{ "pages/model_timeline" | relative_url }})**:  this is a timeline view of relevant milestones for your ML project.  This page is generated by `/project/model_timeline.csv` in your repo, which is system generated [^1].

- **[Completed Pipeline Runs]({{ "pages/pipeline_runs" | relative_url }})**:  This shows the most recent pipeline runs.  This page is generated by `/metadata/pipeline_runs.json` in our repo, which is system generated [^1].

- **[Deploy]({{ "pages/deploy" | relative_url }})**: A click-to-deploy mechanism for others to run your training pipeline and serve your model on the infrastructure of your choice.  This is under construction.

---

[^1]: *This system has not been designed yet.*