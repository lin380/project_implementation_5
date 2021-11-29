# README

<!-- REMEMBER: 
You can preview a formatted version of this README.md document by clicking the 'Preview' button in the RStudio toolbar.
-->

## Preparation

- Reflect on your interests in language and linguistics
- Continue to refine your [project statements](https://lin380.github.io/coursebook/framing-research.html), [data acquisition implementation](https://lin380.github.io/coursebook/acquire-data.html), and [dataset curation](https://lin380.github.io/coursebook/curate-data.html) and [transformation](https://lin380.github.io/coursebook/transform-data.html).
- Review the concepts on implementing analysis steps in [TAD Chapter 8 "Inference"](https://lin380.github.io/coursebook/inference.html), [Chapter 9 "Prediction"](https://lin380.github.io/coursebook/prediction.html), and/or [Chapter 10 "Exploration"](https://lin380.github.io/coursebook/exploration.html) as well as the relevant Recipes and Labs.
- Review the steps for working with RStudio, Git, and GitHub in [Recipe #5](https://lin380.github.io/tadr/articles/recipe_5.html) and Lab #5. 

## Objectives

- Continue to refine your text analysis project
- Add your data analysis strategy(ies) to your project
- Apply the edit, add, commit, push workflow to update your GitHub page
- Continue to apply your growing knowledge of R

## Instructions

### Setup

1. Open your research project (`project_<your_last_name>`) on RStudio Cloud. 
2. Open the `4_analyze_dataset.Rmd` file in the `analysis/` directory. 

### Project

In this project implementation step you will be performing the steps to analyze and interpret your dataset. You will build on the transformed dataset you have created and documented and move apply either a inferential, predictive, or exploratory data analysis approach and then choose and describe the specific methods you employ and the results that you obtain. Keep in mind the research question(s) that frame your research project and the supporting literature that supports these questions in your evaluation and interpretation of the results.

The `4_analyze_dataset.Rmd` file has a similar template structure (to the previous analysis files) in the prose section of the .Rmd document. This includes 'About' , 'Setup', 'Run', and 'Finalize' sections with some relevant subsections. This structure is not set in stone and merely helps you start to think about the steps that your processing and documentation should most likely include. Each of the (sub)sections has a comment (`<!-- ... -->`) to guide you as to what you might expect to add in these sections.

**Tasks**

1. Provide a description that overviews the aim of this script (.Rmd). 
2. Include any information necessary for someone to know to be able to reproduce this script. 
3. Load the appropriate packages that you will need. 
4. Make sure that the dataset used in your analysis is stored on disk in a plain-text format (most likely `.csv`) inside the `data/derived/` directory.  
5. Include the relevant code to analyze your dataset.
6. Source the `_pipeline.R` file. Either through: 
  - opening the `_pipeline.R` file and clicking the 'Source' button.
  - or, in the R Console running `source("_pipeline.R")`

### Update GitHub

1. Now run the Git commands in the Terminal to add, commit, and push your updates to your GitHub repository/ website. 

- `git status`
- `git add -A`
- `git commit -m '<briefly describe what you've done>'`
- `git push`

**Remember:** your PAT has probably expired (it only lasts 12 hours in RStudio Cloud) so you will need to run `gitcreds::gitcreds_set()` in the R Console and paste in your PAT before you run `git push` (otherwise you will get cryptic error). 

## Submission

1. Navigate to your GitHub website (where the web page shows) and copy the link to the main page where you have added your changes. 
3. Go to the Canvas submission page for "Project implementation #5" and paste this URL link into the 'website url' submission field. In the 'Text Entry' field add your self-assessment comments.

**IMPORTANT NOTE:**

We will continue using GitHub to post our work. In addition to saving our project work and hosting a website for our projects, GitHub also has a robust set of features for commenting and collaborating on code. We will use these features to receive and ask for feedback on our code and ideas.
