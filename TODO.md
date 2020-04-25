# Quickies

- [ ] Rename DevOps part to MLOps
  - https://en.wikipedia.org/wiki/MLOps
  - https://cloud.google.com/solutions/machine-learning/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning#devops_versus_mlops

# Finish first version of Table of Contents

- [ ] I think one of your biggest concerns when choosing which topics to include should be “will this be relevant in 5 years? In particular, I think you should not focus too much on specific technologies (e.g. docker, airflow and “best practices”) otherwise as soon as the next hype train arrives everybody will forget about your book. In a similar spirit, focus on the core ideas, trade-offs and alternatives: why/when agile? Why/when containers? Why/when microservices? 
- [ ] Define a first MVP, then write that. Backlog all other chapters.

# Decisions

- [X] Focus on Python? Or do both? Will be hard for presenting software (e.g. must write about Shiny and Dash)

# Sources to still distill

-https://www.linkedin.com/pulse/failure-rates-data-products-michele-dallachiesa-ph-d-
	- and http://radar.oreilly.com/2012/07/data-jujitsu.html
- https://towardsdatascience.com/data-science-project-flow-for-startups-282a93d4508d
- The feedback from your google doc
  - https://docs.google.com/document/d/1eMOY7S3s4S3ongvTRll33hA--kfgT9zKiyaTnNurTzw
- https://21lessons.com/7/
  - you can't know everything. be humble
- FSDS, Time series methods: https://otexts.com/fpp3/what-can-be-forecast.html
- FSDS, datsci skills: https://r4ds.had.co.nz/
- https://www.reddit.com/r/datascience/comments/fuyoai/i_find_this_data_science_map_really_useful_where/
- https://www.joelonsoftware.com/category/reading-lists/new-developer/
- https://github.com/amitkaps/full-stack-data-science
- List of "ML into production": https://www.reddit.com/r/datascience/comments/eufeqm/how_to_learn_data_science_best_practices_if_youre/
- https://vimeo.com/275834171 von https://www.m3-konferenz.de/rueckschau.php
- David Kriesel: Bahnmining: "Wie man Datenprojekte angeht": https://youtu.be/0rb9CfOvojk?t=1265
- Martin Zinkevich: https://developers.google.com/machine-learning/guides/rules-of-ml
- https://towardsdatascience.com/deploy-monitor-and-scale-machine-learning-models-on-aws-408dfd397422
- http://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf
- Google "DataOps"
- https://stackoverflow.blog/2019/09/05/they-didnt-teach-us-this-a-crash-course-for-your-first-job-in-software/
- Include a big chapter on Deep Work. http://calnewport.com/blog/2018/11/07/on-physician-burnout-and-the-plight-of-the-modern-knowledge-worker/
- https://sifted.eu/articles/machine-learning-full-stack/
- One guy's company and their production setup
  - https://news.ycombinator.com/item?id=20985875
- Kubernetes Workshop: https://github.com/eon01/kubernetes-workshop
- https://vsupalov.com/deployment/
  - This guy is also awesome for Django deployment
- Booking.com: 6 lessons from 150 successful ML models
  - https://dl.acm.org/doi/10.1145/3292500.3330744

## Topics to think about including

- Public speaking
  - Recommend Toastmasters?

## Talks

- https://www.youtube.com/watch?v=ErrHRMiNNXE
- https://www.youtube.com/watch?v=huqpXMNFD54
- https://www.youtube.com/watch?v=LLvvNNWp3D0
- https://www.youtube.com/watch?v=kwh5yuuI8Mg
- https://www.youtube.com/watch?v=-GVA65xGPYY
- https://www.youtube.com/watch?v=iT3l8HfcGLE&list=PLtRYQXROMrfQpO4jWwUye5tzk07IqLv5x

## Books

- Self-Published Book – “Data Science in Production” https://news.ycombinator.com/item?id=21955527
  - https://leanpub.com/ProductionDataScience
  - https://towardsdatascience.com/data-science-in-production-13764b11d68e
- Agile Data Science 2.0
  - https://www.amazon.com/_/dp/1491960116

# Expert Interviews

- To find book topics, get opinions about favorite tools, pipelines, practices
  etc., or even include entire interviews in the book as a section.

# Case Studies

- Janek is working on a Fraunhofer paper on a case study / consulting project which he might be allowed to publish.

# Practice projects / Labs

- Encourage reader to code along with *his own* practice project. If he doesn't have one, provide one example project in the book and you code along using that one

- A real-time backtesting tool (or a stub for it, at least)
   - daily ingest Google Finance API
   - Write to your SQL
   - monthly training + store model
   - API for model access (some sort of prediction)
- Or: have all the practical exercises as a lab in the appendix
  - That can then become a separate repository, and even a YouTube course or a 3-day course (online or live)
