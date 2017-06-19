# Music Technology conference list

This repository hosts a list of upcoming and past conference calls
and journal calls for the wider music technology community.

It is maintained by the [Music Technology Group (MTG UPF)](http://mtg.upf.edu).

Anyone can contribute to this list by sending a pull request with
the data for a new conference or journal call. See below for
instructions.


## Contributing

### Conferences
Fork the repository and create a new file in the `_conferences` directory.
Name it `[confyear]-[confabbr][confyear].md`. For example, `2017-ismir2017.md`.
Write the conference abbreviation in lower-case.
The initial year field is used to sort the files in a directory listing.

Copy this template into the file and fill in each field. Dates should be
in `yyyy-mm-dd` format and surrounded by quotes, e.g. `'2017-04-01'`.
```
---
title:
acronym:
date: # Conference date
submission_date: # Date of submissions
ext_url: # External URL to conference website
location: # City, Country
---
```

Save the file and submit your addition as a pull request.

### Journals
Fork the repository as for conferences and create a file in the `_journals` directory.
Name the file something like `[year]-[journal-name].md`. If there are many
issues for this journal in the same year either add a letter to the year (`2017b-journal.md`) or
include the issue name in the filename too.
By convention, we name the file in lower-case, using hyphens instead of spaces, and only including
letters and numbers in the name.

Include the following content in the file. Dates should be
in `yyyy-mm-dd` format and surrounded by quotes, e.g. `'2017-04-01'`.

The `date` field is required by Jekyll, but is not used. You can set it
to the same value as `submission_date`, or to the date that the issue
will be published.

```
---
submission_date: # Date that submissions are due
date: # Same as submission_date, or publishing date
journal: # Name of the journal
issue: # Name of this issue
ext_url: # URL to call for articles for this issue
---
```

## Technical information

We have separate pages for each year. This means at the end of each year, we need
to update the `index.html` page for conferences and journals to reflect items for
the current year, and to create a new `year.html` page for the last year.
