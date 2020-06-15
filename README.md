# Sample Project

This is as an example on how teams can structure their project repositories. Thanks to Lindsey Heagey and Joachim Meyer for the template, provided originally for [Geohackweek](https://github.com/geohackweek/sample_project_repository).

### Goals

1. Create a tool for identifying (near) co-indicdent measurements across varied datasets(specifically with Argo float data, MODIS and/or Sentinel imagery, and ICESat-2 tracks)

2. Formulate scripts to develop or isolate parameters from ATL03 data that might be relevant to larger science questions for which the above measurements are relevant

3. Become Python gods. 

### other notes

We would like to have 2 Notebooks as deliverables and a clear use-case story. We hope to develop some pretext for a potential GUI by incorporating widgets into the co-incident measurements tool. 


## Files

* `.gitignore`
<br> Globally ignored files by `git` for the project.
* `environment.yml`
<br> `conda` environment description needed to run this project.
* `README.md`
<br> Description of the project. [Sample](https://geohackweek.github.io/wiki/github_project_management.html#project-guidelines)

## Folders

### `contributors`
Each team member has it's own folder under contributors, where he/she can
work on their contribution. Having a dedicated folder for one-self helps to 
prevent conflicts when merging with master.

### `notebooks`
Notebooks that are considered delivered results for the project should go in
here.

### `scripts`
Helper utilities that are shared with the team
