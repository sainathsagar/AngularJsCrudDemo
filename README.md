# AngularJsCrudDemo
Quant Engine API : Quant Engine API is an API for fetching quant style datasets from FactSet content databases. A quant style dataset is created by generating a set of dates, a universe on each date, and then fetching content via screening expressions, fql expressions, or universal screen parameters for each universe on each date.

Portfolio API: The Port API allows you to upload and edit holdings data to FactSet, this enables you to access the power of our world-class Portfolio Analytics suite and instantly start evaluating your portfolio’s performance via the Portfolio Analytics API.

Create:
A successful creation returns a 201 status code.
All accounts will leverage FactSet’s Pricing and Analytics Sources by default.

Read:
By default, the data is returned in FactSet’s own STACH v2 format (JsonStach format), but you can choose to specify a non-Stach JSON response format (AccountModel format)

Update:
Use the PUT /{name} endpoint to update an existing account with:
New date/symbol combinations
Updated values for existing date/symbol combinations
A successful update returns a 200 status code.
Note that you may not add a metadata description or create custom fields when updating an existing account. These can be specified only when creating an account.

Delete:
You cannot define or update account settings via the Portfolio API. If you are interested in getting more fine-grained, programmatic control over your portfolios’ settings, this can be done using the Portfolio Metadata API (currently in Beta)
Note that there may be certain account locations that are restricted to a specific set of users.
Use the OFDB API for uploading data for non-portfolio centric use cases like sector classification and/or mappings
Getting Started with Uploading your Holdings

