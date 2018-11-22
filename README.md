# Smallville-Education-Foundation
181122: Documentation for Smallville Education Foundation (SEF) capstone project
Non Profit Capstone Project: Smallville Education Foundation

Organization Overview	1
About Smallville Education Foundation	1
Development Overview	2
Scholar’s Circle - Giving Levels	2
Events	3
Data Visibility and Security	3
Donor Data	4
Donation/Gift Data	4
Other Requirements	5
Reports and Dashboards	5


Organization Overview
About Smallville Education Foundation
Mission: Smallville Education Foundation (SEF) helps the Smallville School District (SSD) sustain and enhance an exceptional public education for all K-8th grade students. Working together with parents, the school district, and community, we provide SSD with financial resources to create a rich and inspiring education for our children beyond what is possible with public funds.

SEF is a 501(c)(3) non-profit public benefit corporation.

The organization is currently using Donor Perfect to track donations and wishes to migrate to Salesforce. 
Development Overview
Smallville Education Foundation raises money during the school year as part of its “Annual Campaign.” Donations are made by individuals and are tracked by family. Donations are made via the following methods:
Check 
Cash
Credit Card
Stock Donations
Trust donations
Matching donations from Employers

Donations made via credit card will come in through a payment processing system that will be integrated with Salesforce (outside the scope of this project).
Scholar’s Circle - Giving Levels
SEF tracks donations for the school year, not calendar year. Donors are assigned to “giving levels” based on their yearly donation.  The following giving levels are considered to be part of the “Scholar’s Circle”:
Innovator:  $20,000 and above
Trustee: $15,000 – $19,999
Superintendent: $10,000 – $14,999
Assistant Superintendent:  $7,500 – $9,999
Principal: $5,000 – $7,499
Scholar: $2,500 – $4,999
As soon as a family reaches one of these “giving levels,” they will be considered a “Scholar’s Circle” family for the remainder of the school year (this distinction must be made so they can be invited to special events, etc.) The following year, they will also be considered “Scholar’s Circle” and will continue to be invited to special events. However, it is important to track their “current” Scholar’s Circle status for the current school year. This is important because development staff needs to monitor these families and ensure they are maintaining their Scholar’s Circle status. 
Note that all donations – including matching donations from employers – count toward the family’s giving level. 
Events
SEC also holds several events that are intended to motivate donors to make donations, and to raise money during the school year:
Read-a-Thon
Students read and collect donations - these are typically made by the student’s family, or collected from extended family, community members, etc.
Donations collected during Read-a-Thon should be marked as READ donations.
Dinner Dance and Auction (donations made at this event are made during the Fund-a-Need portion of the auction, and identified as FAN donations.) 
Donations made during the Fund a Need portion of the auction should be marked as FAN donations.  
Data Visibility and Security
The Smallville district includes 5 schools:
Lincoln Elementary
Hoover Elementary
McKinley Elementary
Washington Elementary
Smallville Intermediate

Each school has a Site Director (SD) who is responsible for development at the individual school. 
For privacy reasons, a Site Director should only have access to donor data for donors at their own school. Also note that some families will have students in an elementary school and the intermediate school – so data must be visible to both SDs. Each family should have an identified “home school” – if a family has students in both an elementary and the intermediate school, this should be the set to the elementary school. Home school will be used for reporting purposes – in order to track fundraising at the school level. 
The VP of Development assists all Site Directors with fundraising efforts across the district, and should have access to all donor data. 
Donor Data
SCE solicits donations primarily from families in the school district. Donations are sometimes made by community members, as well as extended family from outside the community.

SCE needs the ability to track a family - including all adult household members and students (and students’ school and grade).  SEF receives a file from the school district 3 times per year so that new families can be added to the database (as potential donors) and updates to existing student and family data can be made.  See sample file for details. 

On the donor, the SD would like to see the following donation summary information (dollar amounts): 
TYD (based on the current school year) Donation 
READ YTD
FAN YTD
TYD W/OUT MATCHING

In addition, the donor would like to see the home school and a count of students at each school. Students should be listed separately, under the family. 

Donation/Gift Data

For donations, the system needs to track:
Date of Donation 
Type of Donation  
Donation Amount 
Reference/Check Number (text)
Anonymous?
Memo/Note

Other Requirements 
Need to track all communication, including:
Conversations with donors
Calls to donors
Emails to/responses from donors.

Would like ability to send email to donors and select from templates. For example:
Thank you templates
Outreach templates
Event invitation templates.
Reports and Dashboards
Site Directors must stay on top of things like:
# of families who have donated (grouped by Scholar’s Circle giving level)
Families who have not yet donated at same level as previous year

VP of Development and President should be able to view dashboards for the entire organization – and view progress and totals by school.

Organization, as well as Site Directions, set goals - would be nice to have automatic way to track progress toward goals. Goals are set based on:
$ raised
# of families
# of families at Giving Levels
