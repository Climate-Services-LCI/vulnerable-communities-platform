ReadME Extreme Heat Metadata

Produced by the Climate Services Team at the Governor's Office of Land Use and Climate Innovation

Indicators 
        
  1) Frequency of days over 100 degrees F 
        
  2) Frequency of days over the 98th historical percentile temperature minimum, masked for areas where historical 98th percentile for maximum temperature is > 90 F 

Analysis 

  1) For 100F (Indicator 1), we want to establish a “number of days” threshold using logic from the number of days per month. For example, our time period is 30 years.  If we used exceeding 100F about 1 day a month on average, as a threshold, that would = 90 days. If we used exceeding 100F about 10 days a month on average, as a threshold, that would = 900 days.  

    Score of 2: Over 10 days a month on average (At or above 900 days). 
    
    Score of 1: Between 1-10 days a month on average (At or above 90 days). 
    
    Score of 0: Less than 1 day a month on average (Below 90 days).  

  2) We are analyzing the 98th percentile of minimum daily temperatures, referred to as "98th Temp Min" (Indicator 2), to determine an "expected number of days", based on this 98th percentile. In June-July-August (92 days), over 30 years (2,760 days total), we expect 2% (55 days) to exceed the threshold. 

    Score of 2 (High Exceedance): If the actual number of days above the threshold is at or above 25% of the total possible days (2,760 days * 0.25 = 690 days), it receives a score of 2. 
  
    Score of 1 (Moderate Exceedance): If the actual number of days above the threshold is at or above 10% of the total possible days (2,760 days * 0.10 = 276 days), but below 25%, it receives a score of 1. 
  
    Score of 0 (Low Exceedance): If the actual number of days above the threshold is below 10% of the total possible days (276 days), it receives a score of 0. 

High Medium and Low Classification Scoring for the VCP 

1) After all squares have extracted the values of the scored rasters, the scores of the squares are averaged within the block group.  
2) The block group receives a score (e.g, 1.9333).  
3) The block group is then classified into H, M, L in an equal interval approach: 

If score.... 
  1 - 1.65 (LOW) 
  
  1.65 - 2.35 (MEDIUM) 
  
  2.35 - 3 (HIGH) 
