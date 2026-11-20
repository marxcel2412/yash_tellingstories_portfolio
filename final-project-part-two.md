| [Portfolio home](https://marxcel2412.github.io/yash_tellingstories_portfolio/) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) |

# The Two Lives of an Intelligent Building

*Final Project II · Storyboard, draft charts, and user research*

[Start the draft story](#storyboard-and-draft-story) · [Read the interview protocol](#user-research-protocol) · [Interview findings and Part III](#interview-findings)

## Storyboard and draft story

This page is the working storyboard for a scroll-based story about CMU’s Intelligent Workplace. The panels show how the reader moves from the opening question through three comparisons to a closing summary. The charts below use measured data from December 2017 through March 2018.

![Six storyboard panels showing the opening, hourly demand, the lighting-related signal, indoor readings, the monthly check, and the closing evidence summary.](assets/iw-part-ii-storyboard.svg)

### How much does demand drop outside a typical workday?

Above Margaret Morrison Carnegie Hall, CMU’s Intelligent Workplace serves as both a research lab and a place to work. I expected the electricity meter to show a clear drop outside a typical workday. Across the four months of records, median weekday demand was **8.71 kW outside the assumed workday** and **9.26 kW during it**, a difference of about **0.55 kW**.

The comparison uses **8 a.m. to 6 p.m. on weekdays** as a schedule. The records do not include verified occupancy. [See CMU’s photograph of the Intelligent Workplace, credited to Karl Backus](https://www.architecture.cmu.edu/cbpd).

### 1. Follow the meter through a day

![Median weekday and weekend demand by hour. Weekday median demand was 8.71 kW outside assumed work hours and 9.26 kW during them.](assets/iw-demand-profile.png)

*Figure 1. Lines show the median demand at each hour. Bands show the middle 80% of readings. Gray marks the hours outside the assumed weekday schedule. The dotted line is the 5th percentile across all valid hours.*

Follow the solid weekday line from late afternoon into the evening. Demand tapers, then settles near its overnight level. The dashed weekend line is flatter. The meter shows a persistent demand, and identifying the equipment behind it requires a list of the loads connected to the meter.

### 2. Compare demand with a lighting-related reading

![Scatterplots split into weekdays and weekends on the same axes. Higher lighting-related readings generally coincide with higher electricity demand.](assets/iw-demand-lighting.png)

*Figure 2. Each dot is one valid hour. The two panels use the same axes so the weekday and weekend patterns can be compared.*

Higher lighting-related readings generally occur alongside higher demand. The overall correlation is **0.91**. The signal’s definition, its units, and the loads included in the power meter still need verification before I can explain the relationship.

### 3. Look inside the workplace

![Medians and middle-half ranges for raw CO₂ and room-temperature readings across four groups of hourly demand. The groups overlap.](assets/iw-indoor-readings.png)

*Figure 3. Recorded hours are divided into four roughly equal groups by demand. The dots are medians and the whiskers span the middle half of each group.*

Median room-temperature readings rise across the demand groups. Median CO₂ readings dip in the second group before rising in the third and fourth. The ranges overlap. To relate either pattern to people’s experience, I need the sensor locations and units, along with occupancy records.

### 4. See how much the four months differ

![Monthly median electricity demand ranged from 8.69 to 8.85 kW. February had the widest 10th-to-90th-percentile range.](assets/IW_deep_04_winter_spring.png)

*Figure 4. Dots show monthly median demand. Bars show the middle 80% of each month’s readings.*

Monthly medians stay close, from **8.69 to 8.85 kW**, while February has a wider spread. The four months give an early check on the pattern. Comparing seasons would require records from the rest of the year and weather data.

**Closing screen.** The meter kept recording substantial weekday demand outside the assumed workday. A lighting-related reading moved with demand. To explain what was running and why, I would start by checking meter coverage, control schedules, and occupancy.

### From Part I sketches to this draft

| Part I concept | Part II decision |
|---|---|
| [Daily rhythm sketch](assets/iw-sketch-01-daily-rhythm.png) | The sketch anticipated a steep daytime rise. The measured profile shows a modest shift, so it opens the draft with the actual comparison. |
| [Hourly heatmap sketch](assets/iw-sketch-02-weekly-heatmap.png) | The weekday and weekend profile introduces the time pattern first. A calendar-date heatmap could help investigate unusual days later. |
| [Inside the systems sketch](assets/iw-sketch-03-systems.png) | The aligned timelines become a pair of scatterplots for the lighting-related reading and two compact comparisons for indoor readings. |

## User research protocol

**Goal.** Test whether a first-time reader can identify the central comparison, interpret the charts, and describe what the records establish about building operation.

**Target audience and recruitment.** Recruit at least three CMU students with different levels of familiarity with building data. Aim for two without building-science training and one who has encountered building or sustainability data. Ask people who have not worked on the project. Record broad descriptions such as “student, unfamiliar with building data.”

**Session.** Allow 10–15 minutes per person. Use the draft story above and show it in order. Ask for a think-aloud first, then use the follow-up questions. Take anonymous notes on what readers say and do. Ask permission before recording a quotation and omit identifying details from any notes posted here.

**Opening script.** “I’m testing how clearly this draft explains electricity demand at a campus workplace. Please read it at your own pace and tell me what you notice, what you expect next, or where you get stuck. You can skip any question. Is it okay if I take anonymous notes?”

| When | Question or task | What to note |
|---|---|---|
| After the opening | In your own words, what is this story about? What do you expect to see next? | First takeaway and expectations. |
| At the daily profile | Point to an hour outside the assumed workday. How does weekday demand there compare with the daytime? What do the lines and shaded areas mean to you? | Whether the reader uses the lines, bands, or schedule shading correctly. |
| At the scatterplots | What changes as you read from left to right? What, if anything, would you conclude about the lights? | Whether the reader sees an association or treats the chart as proof of a cause. |
| At the indoor charts | What do you notice about the lowest- and highest-demand groups? What would you need to know to interpret this as someone using the space? | Whether the reader notices the spread and asks about units, occupancy, or comfort. |
| At the close | What would you tell a friend about the building after reading this? Which part would you change or remove? | Final takeaway, confusing spots, and what kept the reader interested. |

## Interview findings

Part II interview findings are pending. The storyboard above is the version prepared for testing.

## Design changes to test for Part III

These are candidate revisions to evaluate with readers during the interviews.

| What to listen for | Candidate revision |
|---|---|
| Readers treat the assumed schedule as proof of when the building is empty. | Put “schedule assumption” directly beside the shading and repeat the occupancy limitation at the opening. |
| Readers struggle to compare the 8.71 and 9.26 kW figures with the daily profile. | Add a short annotation pointing to the evening and overnight segment. |
| Readers take the scatterplots as evidence that the lights cause the change. | Add a plain-language annotation explaining the relationship and naming the missing meter information. |
| Readers lose the thread at the indoor or monthly comparison. | Move the less useful comparison into a short evidence note after the main story. |

## Sources and AI acknowledgment

- Historical Intelligent Workplace building-management-system exports, December 2017 through March 2018. [Cleaned hourly data](data/IW_hourly_Dec2017_Mar2018.csv) · [Preparation and quality checks](final-project-part-one#how-i-prepared-the-hourly-data).
- Carnegie Mellon University, [Center for Building Performance and Diagnostics](https://www.architecture.cmu.edu/cbpd). Building context and linked photograph.

I chose the Intelligent Workplace as the case study, obtained permission to use the data, and developed the original concepts. I used ChatGPT to help process and check the hourly data, develop the draft figures, and draft this storyboard, page text, and interview protocol.

[Back to the portfolio](https://marxcel2412.github.io/yash_tellingstories_portfolio/)
