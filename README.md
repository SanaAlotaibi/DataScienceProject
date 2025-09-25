Data Source:
The data was collected using the GitHub API, which provides structured access to repositories and their metadata.

Date of Collection:
Data was collected in September 2025.

Collection Method:

API queries were executed through Python on Google Colab.

The search query targeted the top 250 most-starred AI-related repositories per quarter for the years 2020–2025 (1000 repositories per year).

This resulted in a dataset of approximately 5000 repositories.

Challenges Encountered:

Rate limits: The GitHub API restricts the number of requests per hour. To overcome this, a personal access token (PAT) was used.

Contributors count: The API often returns incomplete or minimal contributor data (frequently set to “1”), which limits the accuracy of contributor analysis.

Bias in repository selection: Since only most-starred repositories were included, the dataset may overrepresent projects that gained attention due to marketing or creators’ popularity rather than purely language usage trends.
