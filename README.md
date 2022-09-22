# Github Repos CSV

Generate a CSV for entire organization containing the repo title, url, description and created/updated times

## Usage

```
git clone https://github.com/ramesh2051/github-org-repos-csv.git
cd github-org-repos-csv
npm install
GITHUB_ORG="my-org" GITHUB_TOKEN="my-token" node index.js
# my-org.csv should now exist in your repository
```

### Required :
- "my-org" --- Name of the organization
- "my-token" --- PAT token with `repo` access authorize to that organization.

- Please refer the link to create PAT token https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
