# REITdataSEC
Repo documenting initial steps to take to gather REIT data from the SEC's EDGAR

Present functionality includes:
 - Fetching active REITs and related info from wikipedia
 - Creating Pandas dataframe with associated values
 - Generating a valid URL to each REIT's SEC table of contents
 - Filtering out a REIT's most 10-K filing
 
 Future functionality:
  - Parse 10-K to locate specific features
  - Import and organize findings
  - Formalize storage in relationa db.
