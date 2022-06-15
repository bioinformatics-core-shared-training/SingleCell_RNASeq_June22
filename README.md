# UnivCambridge_ScRnaSeqIntro_June2022

Introduction to scRNA-seq analysis, June 2022.


## Updating Materials

This repository contains very few files, including `index.md` where the content course homepage is defined. 

The actual course materials are in a submodule, which points to the [base repository](https://github.com/bioinformatics-core-shared-training/UnivCambridge_ScRnaSeqIntro_Base), where the latest materials are kept up-to-date. 

If you are updating the materials, please **make all changes in the base repo**:

- Clone the base repo locally.
- Make your changes (including rendering any markdown files to html).
- Add, commit and push those changes as you would do normally. 

Then, **to update the submodule on this repository** (so that the lastest changes show on the course website):

- Clone this repository.
- Pull/update the submodule, add, commit and push: 
    ```bash
    git submodule update --remote --merge UnivCambridge_ScRnaSeqIntro_Base
    git add bioinformatics-core-shared-training/UnivCambridge_ScRnaSeqIntro_Base
    git commit -m "update base submodule"
    git push
    ```

⚠️ **Do not attempt to update the submodule from the Git desktop app! 
It breaks everything. 
Command line only.** ⚠️

If you can’t do it, get in touch with one of the lead trainers on the course.

 
