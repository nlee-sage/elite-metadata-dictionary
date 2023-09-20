<h1>**ARCHIVED**</h1>

# AMP-AD Metadata Dictionary

Hosts the dictionary used for metadata in AMP-AD, which is composed of the
[synapseAnnotations](https://github.com/Sage-Bionetworks/synapseAnnotations/) as
well as some custom values that are used only in metadata files, and not as
annotations.

### To deploy to ShinyApps.io:

- Enable workflows in the GitHub repository
- Under [secrets](https://github.com/Sage-Bionetworks/amp-ad-metadata-dictionary/settings/secrets/actions) click 'New repository secret'
- Enter secrets for `RSCONNECT_USER`, `RSCONNECT_TOKEN`, and `RSCONNECT_SECRET`, the values for which are saved in Sage's LastPass.
- Push to new branch on Github
- Create pull request with at least one reviewer to master branch
- Upon merge of pull request, the app will deploy to staging.
Check out the app here: https://sagebio.shinyapps.io/amp-ad-metadata-dictionary-staging.
- After verifying correctness, create pull request with at least one reviewer to prod branch
- Upon merge of pull request, the app will deploy to production.
- The app' will become available at https://sagebio.shinyapps.io/amp-ad-metadata-dictionary
