# Daura LGA Outreach Follow-Up Note
## Comparing Who Came and Who Stayed Home to Plan the Next Outreach

This repository presents a side-by-side analysis of an immunization outreach in Daura LGA, Katsina State. Using Excel-based pivot tables and formula-driven comparison, records from 30 attendees, 40 non-attending households and 3 outreach staff were analyzed to show what holds each group back and what the outreach in-charge could do next. The findings are summarized in a one-page decision note.

**This project uses synthetic practice data. No real households or programme results are involved.**

## About the Data

* Attendee and staff records come from a provided practice dataset.
* The non-attender survey of 40 households was generated for this demonstration, and its patterns were designed, not discovered.
* Because of this, the insights below show how the method works. They are not findings about Daura.

## Key Insights (Illustrative)

* Among attendees, lack of information was named most in Kusugu (5 of 15, against 2 of 15 in Sarkin Yara). Among households that stayed home, the information gap sits in Sarkin Yara, where 8 of 20 never heard about the outreach, against 4 of 20 in Kusugu.
* Most households that missed the outreach still want to come. Of the 12 that never heard, 10 said Yes or Maybe to attending next time, and 34 of all 40 households said Yes or Maybe.
* The two groups ask for different things. Attendees most often asked for shorter waiting time (10 of 29 who answered), and 7 of 29 waited over an hour. Non-attending households most often asked for a closer service point (9 of 40), and 14 of 40 asked for a closer point or a home visit.
* Households that stayed home live farther away, with a median of 3.65 km and 45 minutes of travel, against 2.3 km and 33 minutes for attendees.
* Community health workers and community leaders reached most of the non-attending households that did hear about the outreach (17 of 28, or 61%).
* Only 3 staff records exist and none are from Sarkin Yara, so the staff view is a hint, not a finding.

## Tool Used

Microsoft Excel: pivot tables, live formulas and side-by-side comparison tables.

## Methodology

* **Data Structure:** Attendee, non-attender and staff records were organized on separate sheets, with a data dictionary for the non-attender survey.
* **Pivot Summaries:** Pivot tables summarized each group by community, barrier or reason, how people heard, and the service or help they asked for.
* **Side-by-Side Comparison:** A comparison sheet built on live formulas puts both groups next to each other, so every figure traces back to the records.
* **Grouping:** Barriers named by attendees and reasons named by non-attenders were mapped to common groups, as documented on the Notes sheet.
* **Handling Extremes and Small Groups:** Medians were used for distance and travel time because one attendee record has an extreme travel time of 295 minutes. Counts are shown beside percentages because the groups are small.
* **Decision Note:** The findings were turned into a one-page note with three recommended actions, each linked to its supporting numbers and a progress check for the next outreach round.

## Repository Structure

* **Decision Note:** One-page PDF for the outreach in-charge.
* **Data and Analysis (Excel Workbooks):**
   * Side-by-side workbook: Comparison, Notes, Attendees, NonAttendees and Staff sheets
   * Attendee pivot summaries
   * Non-attender survey, pivot summaries and data dictionary

## Limits

The data shows what goes together, not what causes what. Percentages are based on small groups, so read the counts alongside them.
