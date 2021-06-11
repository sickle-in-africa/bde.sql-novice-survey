---
layout: lesson
root: .
---

In the late 1920s and early 1930s,
William Dyer,
Frank Pabodie,
and Valentina Roerich led expeditions to the
[Pole of Inaccessibility](https://en.wikipedia.org/wiki/Pole_of_inaccessibility)
in the South Pacific,
and then onward to Antarctica.
Two years ago,
their expeditions were found in a storage locker at Miskatonic University.
We have scanned and OCR the data they contain,
and we now want to store that information
in a way that will make search and analysis easy.

Three common options for storage are
text files,
spreadsheets,
and databases.
Text files are easiest to create,
and work well with version control,
but then we would have to build search and analysis tools ourselves.
Spreadsheets are good for doing simple analyses,
but they don't handle large or complex data sets well.
Databases, however, include powerful tools for search and analysis,
and can handle large, complex data sets.
These lessons will show how to use a database to explore the expeditions' data.

> ## Learner experience survey
> On completion of the module, *please* complete this survey:
>
> <div align="center"><a href="https://protect-za.mimecast.com/s/BRYGCZ4GJ0iq3vNmUzad87">Learners experience survey link</a></div>
>
> Your feedback will be invaluable to developing the module for future learners!
{: .callout}

> ## Prerequisites
>
> * This lesson requires the Unix shell, plus [SQLite3](http://www.sqlite.org/) or [DB Browser for SQLite](http://sqlitebrowser.org/).
> * Please download the database we will use: [survey.db]({{ page.root }}/files/survey.db)
{: .prereq}

## Acknowledgements
We acknowledge the financial support from the [National Heart, Lung, and Blood Institute](https://www.nhlbi.nih.gov/) of the [National Institutes of Health](https://www.nih.gov/) who funds SickleInAfrica. The views and content expressed on this website do not necessarily reflect the views and opinions of our funders. 

The content of this module was initially developed by the SADaCC team for SickleInAfrica.  

We extend our gratitude to the [Software Carpentry project](https://software-carpentry.org/) who built the website template used by this module and wrote the content. 