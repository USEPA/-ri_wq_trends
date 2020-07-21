# Reviewer 1

## Major Comments

1-1. I would like more detail on how the averaging was done for each year. For each parameter, an annual average was calculated for each lake. In theory, Secchi depth and temperature were sampled every week and water samples were collected 3 times per season, May through October. If the monitoring design was followed consistently, then a simple average should be sufficient. However, I know from experience with other state databases that there are often gaps in sampling. If some years were represented with only samples late in the season and others only had samples early in the season, then seasonal trends could be misinterpreted as annual trends. How many samples were required per year to calculate an annual average and were there any additional measures taken to ensure that the data collected over the course of the season was weighted similarly between years (e.g., must have at least one sample in May/June, July/Aug, and Sept/Oct)? I think there should be some rules to this effect. If this is not a concern, please state some statistics showing that the majority (x%) of lake-years included in the analysis adhered to the full sampling schedule.

- **Response:**

1-2. I also had questions regarding the way that interannual data were represented. At least 10 years of data from 1993 to 2016 had to be available for a lake to be included in the analysis (lines 121-122). This is reasonable. However, this is less than half of the years of the entire period of record. In theory, one lake could be analyzed from 1993 to 2002 and another lake from 2007 to 2016. These are not even overlapping periods of record. I think you need to take it one step further and ensure that there are years represented at the beginning and end of this 24-year period. Oliver et al. 2017 did include rules to this effect. I do not think your analytical method is immune to this possible difference in time frame. Again, please describe the time frames of your data set and adjust your rules if you find that you do have a substantial number of lakes with non-overlapping time frames.

- **Response:**

1-3. How did Secchi depth change? Why wasn’t this analyzed?

- **Response:**

1-4. It is unclear how the trends in temperature, TP, chl-a, TN, and TN:TP compare to water quality condition and any standards that might be set in Rhode Island. Tables 1 and 2 give the range of values across lakes and there is clearly a large gradient in trophic status. Following from the comment made in point 8, it would be helpful to better understand the trends observed here in context of water quality condition. If chl-a is rising, is it still relatively low, or is it reaching “polluted/degraded” levels? Do you observe a shift in trophic status in individual lakes? Somehow, try to put the trends or lack of trends observed in the context of how water quality condition is changing over time. Line 312: It is still unclear to me how this analysis of site-specific anomalies is robust to variation in timing of inclusion of given sampling locations.

- **Response:**

1-5. My biggest concern is possibly overstating the lack of trends in TP and TN and the positive trends in temperature and chl-a and then suggesting that temperature, not nutrients, are responsible for increasing chl-a. The authors are somewhat cautious when making this conclusion, but do not fully recognize the limitations of this interpretation. I will try to break my concerns into manageable pieces for the authors to respond to.

- **Response:**

1-5a. I think the title overstates this result. I agree with increasing Chl-a trends, but don’t agree with stable nutrient trends.

- **Response:**

1-5b. I have not read Wasserstein et al. 2016, but agree with the general concept that a specific p-value threshold is not the only weight of evidence for determining whether there is a trend. However, I do not think the authors conclusions about trends for each parameter in the Rhode Island vs. LAGOS datasets are consistent with one another need a more detailed framework laid out ahead of time to understand the more holistic way of interpreting whether there are trends. These are the trends that I interpret differently than do the authors:

- **Response:**

1-5b-i. TN in Rhode Island (Fig 5A) – The p-value is very small and the slope seems reasonably large. I also see more positive means later in the record. I do not think that 1993 and 1994 have an overly strong effect on the trend. Even when you take them out of the analysis, the slope is still 2.5 and p-value is small. Although the annual increase in TN is not large compared to the range of total TN anomalies, I interpret the stats as an increase in TN. In line 247, I disagree with the statement that removing data from 1993 and 1994 weakens the positive trend “considerably”.

- **Response:**

1-5b-ii. TN in Lagos data set (Fig 5B) – the text says that “TN showed a slight positive trend”. Here, the slope is smaller and the p-value is large. I would think that the positive slope is driven by the high TN values in 2013. I think there is more evidence for increasing TN in the Rhode Island data set than the LAGOS data set, but the text reads the opposite.

- **Response:**

1-5b-iii. TP in Rhode Island (Fig 6A) – The authors state that TP does not show a trend over time. I see a positive slope with a marginally significant p-value and more positive means later in the record. I wouldn’t oversell this as a major increasing trend in TP, but I see some evidence for a slight increase in TP.

- **Response:**

1-5b-iv. TP in LAGOS (Fig 6B) – “TP showed a slight decreasing trend”. I disagree. The slope was negative, but at -0.027, so a much smaller magnitude than the positive slope in the Rhode Island data set. The p-value was 0.32 and the graph itself looks like the slope is a horizontal line centered on 0.

- **Response:**

1-5c. To put the magnitude of each slope in context, you could report the slope as a percent of the full range of slopes observed in the data set. Even those trends that are “significant” have a relatively small slope compared to the variability between lakes.

- **Response:**

1-6. This analysis also seems to be saying something about coherence. In some years, there is a wide range of anomalies, meaning that some lakes are much higher than their long-term average at the same time as other lakes are much lower. This seems like an interesting result in and of itself that is not pointed out in the results or discussion. How does the variability in annual anomalies of water quality between lakes compare to that observed in the climate
literature, which traditionally uses this approach?

- **Response:**

1-7. In the discussion (lines 236-237) and in the title, the authors seem to want to conclude that because there were positive trends in temperature and chl-a but not in TP or TN (which I don’t agree as strongly with), that increasing chl-a is likely caused by increasing temperatures and not nutrients. This is certainly interesting if it were the case, but it is well beyond the scope of what can be concluded here.

- **Response:**

1-7a. This study simply lists the direction of trends of 5 parameters, but does not analyze correlations between them.

- **Response:**

1-7b. Even if it had tested correlations between parameters, it is still difficult to reach for causation.

- **Response:**

1-7c. The analysis of mean anomalies over time is interesting, but that simply means that the entire set of lakes in the state shows trends over time. What I’ve learned from reading some of the papers cited by this study and from my own investigations is that lakes near one another can have opposite trends. Processes at the scale of the individual lake and its watershed are important and can have opposite trends in neighboring watersheds. I think this study would benefit by adding an analysis at the individual lake scale to compliment the state scale. I would feel more comfortable with the statement that increasing chl-a may be a result of warming waters, not nutrients, if this was also tested at the lake scale.  One could build a mixed effects model: 

- Chl-a anomaly ~ temperature anomaly + TP anomaly + TN anomaly + lake 

where lake is a random effect that has a unique id for each lake in the study. Years would be replicates. I think it’s possible that you could see a nutrient effect if you examined the data this way. There is a lot of variability between lakes within a year, so while I find the statistical method used in this study interesting, I don’t think it tests of drivers of change.

- **Response:**

1-8. Line 274-275: the authors pose the interesting question about whether lakes of similar trophic state are showing similar trends. I disagree that this test is beyond the scope of the study. I think it is a timely question that would be good to test following the Stoddard et al. paper. It should be relatively easy to test – dividing the lakes into groups of hypereutrophic, eutrophic, mesotrophic, and oligotrophic categories based on their long-term mean TP or chl-a. If there are not enough lakes in each category, with would be interesting to compare a few.

- **Response:**

## Editorial Comments

1-9. Line 64: Better define the spatial scales of the studies referenced in this paragraph. Macro-scale, regional, subregional could be interpreted in different ways. Please be explicit about the geographic region that each study includes.

- **Response:**

1-10. Line 71: I’m not sure why it was surprising that little change in nutrients and chl-a was reported in Oliver et al. 2017? How is this study different from Lottig and Collins? All three use the LAGOS data set. I think it would be helpful to be more specific about both the spatial extent and the results of these studies – particularly when you talk about complexity in discussing the Lottig and Collins papers. Complex just doesn’t explain the patterns very well – please be more specific in describing what complex means in this case.

- **Response:**

1-11. Lines 99 – 102: please delete. Unnecessary.

- **Response:**

1-12. Line 113: capitalize Secchi

- **Response:**

1-13. Line 123: delete approximately. It seems that you are giving specific numbers here.

- **Response:**

1-14. Lines 202-207: The text simply repeats the numbers reported in tables 1 and 2. It would be more interesting to compare the populations at the two scales – in terms of the means and the ranges and the variety of trophic states represented and to also summarize the comparison of trends over time at the two scales.

- **Response:**

1-15. Line 285: “receive feedback” is a vague phrase here. Perhaps you mean that is important for managers and stakeholders to know what the long-term trends are? I think you could also add more references and specific language about why it is important to share results with volunteers.

- **Response:**

1-16. Line 292: I was a little bit confused by this paragraph. Why discuss ways of reducing nutrients when you have not identified increased nutrients as having an increasing trend? There are a lot of leaps made to get to this paragraph – temperature affects chl-a more than nutrients, resultant chl-a and nutrient values are too high, lower nutrients can offset warming temperatures, ways to lower nutrients. Some of the analyses I suggest adding above may better
motivate this paragraph being included in the discussion section.

- **Response:**

# Reviewer 2

## Major Comments

2-1. The paper needs some contextual description of the RI lakes that could be achieved from GIS analysis. For example, what is the distribution of size and depth of the lakes in the data set? What are the land-use area percentages (e.g. agriculture, residential, and forested areas) within the catchment areas of each lake in the data set? A contextual description will be of value to other researchers who may wish to compare these results to other areas. Smaller lakes potentially could show a different warming trend than larger lakes, for example, and therefore knowing a lake size distribution could help qualify the results. Some context on the land-use patterns is also important for understanding the nutrient-level data, for comparing results between study areas, and perhaps shedding some light on why the Rhode Island mean water quality values are less than mean values for the larger, LAGOSNE dataset (p. 11, lines 205-207). At a minimum, an overview description of the lakes that make up the dataset is needed.

- **Response:**

2-2. There should be no reason to rely on “anecdotal evidence” for explaining warming air temperatures over the timeframe of the investigation (p. 14, lines 269-272). There is no source/reference for this claim. Weather station data for RI should be available to assess whether regional climate is warming and to see if it is consistent with the observed increases in lake temperature.

- **Response:**

2-3. Some clarification on the methods is also needed. The authors say that they used the same analytical methods for the LAGOSNE data set as they did for the Rhode Island lakes. Please verify whether the LAGOSNE data represent the same seasonal timeframe (May – October) and lake sample depth (< or = 2m) as the Rhode Island data (as they should for a comparative analysis). Additionally, please state why the LAGOSNE data extend only until 2014 vs. the year 2016 for the RI dataset.

- **Response:**

## Editorial Comments

2-4. p. 6, line 90: Capitalize “States.”

- **Response:**

2-5. p. 10, line 188: Check spelling of “parameter.”

- **Response:**

