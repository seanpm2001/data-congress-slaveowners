# Congress slaveowners

## About this story
[More than 1,700 congressmen once enslaved Black people. This is who they were, and how they shaped the nation.](https://www.washingtonpost.com/history/interactive/2022/congress-slaveowners-names-list/)

The Washington Post has compiled the first database of slaveholding members of Congress by examining thousands of pages of census records and historical documents.

## Methodology

To create this database, The Washington Post researched more than 5,500 members of Congress — every single member born before 1840 — meaning he had reached 21 by the time the last census before the Civil War was conducted in 1860. The Post found more than 1,700 people who served in Congress and owned human beings at some point in their lives. In the early decades of America’s history as an independent country, more than half of all congressmen voting on the laws forming the country’s framework were enslavers.

To create the database, The Washington Post reviewed 18th- and 19th-century census records, which have been digitized and made available through the National Archives and Ancestry.com, as well as other documents, including wills, journal articles and plantation records. 

Washington Post reporter Julie Zauzmer Weil confirmed that the person listed in the census was in fact the member of Congress using available evidence such as age, place of birth, middle name, family relationships and profession. Men who represented U.S. territories are listed in this database under the state that territory eventually became; for example, delegates from Orleans Territory are listed under Louisiana.

But we couldn’t reach a conclusion on 677 additional members of Congress. That’s where you come in. If you have any evidence about any congressman or found any errors, please visit [this page to help us identify members of Congress who enslaved people](https://www.washingtonpost.com/history/interactive/2022/submit-congress-enslaved-database/).

## About the data
This database of every person elected to Congress who was born before 1840 was created based on Washington Post research and data from these two datasets:

•	[Biographical directory of the United States Congress](https://bioguide.congress.gov/)

•	[congress-legislators](https://github.com/unitedstates/congress-legislators)

## Folders of note in this repo
•	data/congress_slaveowners.csv - Download the data used in this story.

## Data dictionary
Variables that can be found in the data:

* `bioguide`: Member's unique identification number within the Biographical Directory of the United States Congress.
* `name`: Name of the member of Congress.
* `positions`: Member's position/s held in Congress.
* `date_of_birth`: Date of birth of this member.
* `states_served`: States where this member served at any point.
* `congresses_served`: Sessions of Congress that this member was a part of at any point.
* `start_date`: First day in Congress.
* `end_date`: Last day in Congress.
* `is_slaveholder`: Describes if this member of Congress was identified as a slaveowner.
  * `true`: This member was a slaveowner.
  * `false`: This member was not identified as a slaveowner.
  * `unknown`: There is not enough evidence to determine if this member was a slaveowner or not.

## Changelog

Database published on Monday, January 10, 2022.

We are soliciting [help and feedback from readers](https://www.washingtonpost.com/history/interactive/2022/submit-congress-enslaved-database/) and we will update the data in this repository as we verify new evidence that comes to light.

## Licensing

This data is published under an [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license](https://creativecommons.org/licenses/by-nc-sa/4.0/)