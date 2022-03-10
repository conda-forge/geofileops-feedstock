<!--
Thank you for pull request.
Below are a few things we ask you kindly to self-check before getting a review. Remove checks that are not relevant.
-->
Checklist
* [ ] Used a [personal fork of the feedstock to propose changes](https://conda-forge.org/docs/maintainer/updating_pkgs.html#forking-and-pull-requests)
* [ ] Bumped the build number (if the version is unchanged)
* [ ] Reset the build number to `0` (if the version changed)
* [ ] [Re-rendered]( https://conda-forge.org/docs/maintainer/updating_pkgs.html#rerendering-feedstocks ) with the latest `conda-smithy` (Use the phrase <code>@<space/>conda-forge-admin, please rerender</code> in a comment in this PR for automated rerendering)
* [ ] Verify if the release channel is correctly set to main, geofileops_rc or geofileops_dev (depending on stable, rc or dev version), especially after rerender changed files!
* [ ] If rerender changed files, verify if .github/PULL_REQUEST_TEMpLATE.md is still present 

<!--
Please note any issues this fixes using [closing keywords]( https://help.github.com/articles/closing-issues-using-keywords/ ):
-->

<!--
Please add any other relevant info below:
-->