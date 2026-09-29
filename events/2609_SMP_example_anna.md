Example: Anna's Software Management Plan (Low management level)
=================================================================

Based on the sample SMP template for the "low" management level in the
Netherlands eScience Center / NWO *Practical Guide to Software Management
Plans* (2022), Section 6.3.1, DOI: 10.5281/zenodo.7038280.

Context: Anna is a researcher in environmental sciences. She writes R
scripts to clean and analyse climate datasets from multiple sources, as
part of a 3-year research project with a postdoc collaborator.

1. Please provide a brief description of your software, stating its
   purpose and intended audience.

   A set of R scripts that clean multi-source climate datasets, run
   comparative analyses, and generate the figures for my publications.
   Intended primarily for my own use and for my postdoc collaborator.

2. How will you manage versioning of your software?

   Git repository, hosted on our institute's GitLab during the project;
   tagged at each major analysis milestone.

3. How will your software be documented for users? Please provide a
   link to the documentation if available.

   A README in the repository explaining how to run each script and
   what input data format is expected. No separate documentation site
   is needed at this scale.

4. How will you document the installation requirements of your
   software? Please provide a link to the installation documentation
   if available.

   An environment/lockfile listing the R package versions used,
   referenced from the README.

5. What type of licence will your software have?

   MIT licence, so my postdoc and any future collaborators can reuse
   the scripts freely.

6. Does your software respect the licences of libraries and
   dependencies it uses?

   Yes — checked that the R packages used (e.g. tidyverse, sf, terra)
   are permissively licensed and compatible with MIT.
