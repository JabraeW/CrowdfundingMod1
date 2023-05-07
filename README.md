# CrowdfundingMod1
Crowdfunding Analysis Count Ifs:
  =COUNTIFS(Crowdfunding!$G$2:$G$1001,Crowdfunding!G31,Crowdfunding!$D$2:$D$1001,">="&45000,Crowdfunding!$G$2:$G$1001,Crowdfunding!G31,Crowdfunding!$D$2:$D$1001,"<="&49999)
  Stat Analysis:
    The range of values within the successful and unsuccessful campaigns is very large(outliers). Thus, pushing our mean statistic higher and higher. A more reliable measure for both successful and unsuccessful would be the median. 
