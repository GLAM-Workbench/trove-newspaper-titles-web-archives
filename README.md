# Historical data about Trove newspaper titles harvested from web archives

Current version: [v1.2](https://github.com/GLAM-Workbench/trove-newspaper-titles-web-archives/releases/tag/v1.2)

The number of digitised newspapers available through Trove has increased dramatically since 2009. Understanding when newspapers were added is important for historiographical purposes, but there's no data about this available directly from Trove. These datasets were created by harvesting information about newspaper titles in Trove from web archives. The harvesting method is documented by [Gathering historical data about the addition of newspaper titles to Trove](https://glam-workbench.net/trove-newspapers/historical-data-newspaper-titles/) in the GLAM Workbench.

This dataset contains three files:

- `trove_newspaper_titles_2009_2021.csv`
- `trove_newspaper_titles_first_appearance_2009_2021.csv`
- `titles_list.md`


## `trove_newspaper_titles_2009_2021.csv`

CSV formatted data file containing details of newspaper titles extracted from web archive captures.

This file contains the following columns:

| Column | Contents |
|--------|----------|
`title_id` | title identifier
`full_title` | full title (including location and dates)
`title` | newspaper title
`place` | place of publication
`dates` | date range in Trove
`capture_date` | date of web archive capture
`capture_timestamp` | timestamp of web archive capture

## `trove_newspaper_titles_first_appearance_2009_2021.csv`

CSV formatted data file containing details of the first appearance of newspaper titles in web archive captures, indicating when the titles were (approximately) added to Trove. The complete list of captures has been filtered to include only the first appearance of each title / place / date range combination.

The file contains the following columns:

| Column | Contents |
|--------|----------|
`title_id` | title identifier
`full_title` | full title (including location and dates)
`title` | newspaper title
`place` | place of publication
`dates` | date range in Trove
`capture_date` | date of web archive capture
`capture_timestamp` | timestamp of web archive capture

## `titles_list.md`

An alphabetical list of newspaper titles showing approximately when they first appeared in Trove.