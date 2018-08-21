# Athom Homey RF Signal Analyzer

Automatically record & analyze rf signals.

## Information
Predicts a [signal defenition](https://developer.athom.com/docs/apps/tutorial-Signals-Creating%20a%20Signal.html) based on this guide [how to record a signal](https://github.com/athombv/node-homey-433/wiki/How-to-record-a-signal).
The output can be used to create an `Athom Homey` [RF Driver](https://github.com/athombv/node-homey-rfdriver).

## See it in action
*Open in browser:* **[index.html](http://htmlpreview.github.io/?https://github.com/harriedegroot/Athom-Homey-RF-Signal-Analyzer/blob/master/index.html)**.

## Demo signals
Try pasting these demo signals into the `signal recording data` field.

##### From tutorial
```javascript
[[255, 400, 110, 1002, 1100, 111, 108, 1010, 102, 1004, 1089, 109, 1102, 112, 110, 1004, 230]]
```

##### Random remote button
```javascript
[[5532,6043,345,439,676,786,339,413,704,767,351,404,713,757,360,390,715,753,368,393,714,759,361,748,368,751,357,394,721,760,350,405,713,395,723,392,721,752,358,3114],[364,430,687,777,340,415,700,761,357,402,710,754,369,390,715,762,358,393,715,759,362,749,356,756,361,403,717,750,357,395,723,399,714,401,712,759,362,3132],[351,440,677,778,341,414,700,773,347,401,712,758,360,398,715,755,363,393,716,757,363,750,358,758,356,394,720,749,360,405,713,394,714,404,715,748,365,3126],[41,123,62,190,84,21,63,126,85,21,21,52,53,32,42,740,31,103,73,42,21,116,41,31,41,72,31,186,10,602,10,157,10,516],[679,784,333,414,707,757,360,399,714,757,363,392,718,751,363,392,715,759,362,749,357,756,360,393,725,754,361,396,715,395,713,403,719,746,364,3126],[20,115,20,42,42,117,73,327,84,10,41,105,62,31,20,148,31,84,53,31,271,10,62,31,10,52,31,42,359,31,52,31,342],[15959,1445,10,96,32,126,53,84,10,114,52,441,21,357,21,116,42,169,52,176,42,329,31,691,10,73,21,116,21,21,10,95,21,95,53,127,31,53],[5541,6035,344,437,686,777,341,416,695,768,353,402,718,750,361,394,724,750,360,394,714,758,363,748,363,753,362,393,716,760,361,395,715,401,717,394,719,751,363,3126],[353,427,685,777,339,416,702,769,355,393,720,750,367,396,713,750,364,394,716,757,364,749,362,760,354,394,720,756,363,393,719,396,715,401,713,759,350,3096],[356,420,697,767,339,415,709,754,358,404,709,753,358,400,715,759,357,400,712,749,361,760,357,755,351,403,716,753,358,399,715,395,714,404,709,757,363,3132],[357,430,685,777,344,412,704,757,360,394,714,759,360,398,715,749,359,399,721,757,349,756,359,758,360,397,715,749,360,393,722,397,713,395,723,747,360,3114],[41,94,42,93,20,290,30,281,11,41,165,10,30,30,105,21,63,31,290,31,94,83,146,20,290,52,61,62,156,74,74,21,156],[41,42,52,145,4844,6040,350,423,699,772,347,404,709,754,360,399,715,760,354,394,715,757,366,392,720,749,357,761,357,759,362,386,725,754,351,404,719,394,716,403,708,761,355,3114],[345,441,677,788,340,414,697,765,348,405,712,759,361,397,714,754,354,712,759,357,759,351,760,357,399,713,758,361,395,713,404,713,393,723,753,363,3132],[200,20,51,21,72,10,30,51,52,51,195,31,113,21,135,42,93,20,249,10,127,42,168,32,179,10,20,51,10,51,227,10,176,10,93,20,134,52,61,294],[5531,6039,351,432,689,772,341,416,704,758,360,395,713,756,364,392,718,758,358,398,716,754,357,755,363,746,361,399,719,756,362,393,718,394,717,402,708,760,356,3114],[359,421,688,788,331,416,704,768,349,404,713,757,355,395,720,760,358,397,714,753,357,761,356,759,362,394,715,757,359,391,716,395,726,392,723,750,357,3108],[21,53,32,148,31,21,53,10,52,31,147,10,42,21,689,31,440,21,31,31,42,21,10,74,95,42,63,52,42,42,32,228],[1398,31,408,414,704,771,346,403,710,759,359,397,716,749,364,395,714,757,364,393,717,753,359,753,358,760,361,394,717,757,360,391,716,398,714,402,713,759,361,3132],[52,392,10,73,134,222,146,52,10,73,42,42,74,53,63,147,10,138,31,42,62,127,21,346,21,1128,106,52,673,21,85,31,221,21],[115,2210,3194,6054,360,398,716,749,360,404,707,756,364,391,719,753,358,400,715,759,354,393,725,747,365,748,362,759,359,391,713,764,350,405,712,404,713,397,716,759,350,3096],[357,421,689,781,329,417,705,766,348,402,714,759,353,398,717,756,360,392,716,763,353,756,363,747,362,395,714,759,360,398,713,395,714,404,711,752,360,3114],[358,420,686,787,337,414,700,773,347,404,711,760,351,395,724,750,361,395,714,756,363,749,362,755,359,392,722,756,360,390,723,392,712,400,717,753,367,3138],[42,211,10,73,10,43,64,64,21,32,54,231,10,116,31,42,21,333,21,51,31,536,31,20,61,71,31,124,21,154,20,72,31,61,51,103,31,113,10,138],[5516,6039,359,412,696,778,340,411,706,763,354,402,714,749,362,395,724,748,360,398,714,753,368,751,356,760,351,405,715,757,359,390,715,405,715,391,717,759,357,3120],[357,419,695,778,339,414,704,764,348,401,713,760,360,395,713,750,360,403,712,760,356,750,362,750,359,403,709,756,364,394,718,395,714,401,713,759,352,3102],[31,539,10,232,42,150,63,21,74,31,63,63,21,42,21,42,95,53,32,10,10,63,53,126,21,104,63,75,11,200,74,116,32,10,42,94,32,84,53,73,73,42,10,31,106,42,105,84,42,186],[5522,6038,358,423,695,770,347,402,712,761,350,406,713,749,363,399,712,755,359,405,712,758,359,753,358,759,361,396,719,745,361,403,718,394,715,402,710,754,360,3120],[359,432,680,780,340,418,707,757,358,401,714,748,361,394,726,746,361,400,716,760,360,747,360,753,358,402,713,758,358,399,715,395,725,392,719,747,365,3126],[351,438,686,777,342,417,703,758,353,404,719,748,357,401,722,748,362,395,713,759,360,754,357,759,361,396,715,746,361,403,718,396,717,390,722,748,361,3114],[21,232,32,21,418,31,251,63,118,63,32,32,43,42,85,42,438,10,31,10,242,10,666,21,290,31,128,21,63,42,74,42,107,21,300],[5528,6042,353,423,686,776,349,402,715,757,360,391,716,762,358,394,715,759,353,397,719,757,360,757,360,745,369,392,722,745,360,405,712,395,725,393,715,757,364,3138],[357,422,691,781,341,406,704,769,359,393,712,754,359,405,711,758,358,398,716,750,364,749,361,758,356,395,719,755,360,398,714,399,716,392,720,752,358,3114],[42,433,104,199,10,51,31,20,31,73,43,10,95,73,21,238,31,62,31,32,10,136,31,191,10,42,11,106,21,10,10,54],[15992,1781,32,442,21,94,21,63,10,306,31,84,53,232,31,85,10,31,31,72,41,21,62,32,125,21,260,31,299,41,359,52,10,30,40,20,96],[15992,1781,32,442,21,94,21,63,10,306,31,84,53,232,31,85,10,31,31,72,41,21,62,32,125,21,260,31,299,41,359,52,10,30,40,20,96],[5502,6035,341,438,687,776,341,416,704,758,353,402,718,750,362,393,724,750,360,394,719,756,363,748,362,750,360,404,707,756,364,394,720,395,720,390,722,757,362,3132],[361,431,678,781,338,415,705,768,349,404,711,759,356,402,712,760,350,406,714,753,357,759,356,749,363,394,724,747,359,399,716,395,724,392,720,751,358,3114],[347,441,678,778,344,414,706,756,360,394,714,758,361,398,716,760,358,389,722,758,360,745,364,749,361,396,726,755,358,399,712,403,717,394,716,756,360,3120],[5544,6032,349,433,683,777,341,410,706,769,355,390,723,748,361,395,724,747,360,400,714,760,354,758,360,752,358,402,710,757,359,398,715,394,725,392,720,747,365,3126],[358,431,686,777,339,414,703,765,349,404,711,754,360,400,715,750,369,389,720,759,356,748,363,760,354,394,715,757,365,393,718,394,718,401,712,757,362,3132],[359,420,698,768,340,414,710,763,348,404,711,760,351,395,724,750,360,394,722,753,357,760,353,760,358,391,722,752,358,401,712,403,713,399,716,752,358,3114],[51,315,31,164,20,52,73,32,10,63,94,54,116,242,31,135,41,21,42,31,20,157,10,21,31,409,31,209,32,105,10,53,53,63,21,234],[199,103,21,574,4626,6040,355,419,696,778,336,414,708,764,348,405,712,761,350,395,724,750,364,395,718,755,362,748,361,750,364,394,715,756,364,394,718,394,720,401,715,756,352,3102],[10,115,41,21,405,20,42,41,41,21,30,93,82,52,10,72,31,51,20,165,20,103,145,31,176,31,125,83,31,21,199,21,420],[698,767,351,407,706,758,360,394,713,757,366,394,719,749,367,390,722,747,361,753,358,761,356,394,719,758,358,397,713,395,725,393,713,754,359,3114],[358,419,696,776,339,415,706,758,352,404,716,747,360,400,716,753,366,389,722,757,353,760,354,760,351,396,725,750,364,394,716,392,721,399,715,750,360,3114],[5503,6034,341,439,682,778,332,421,699,769,346,403,707,754,369,394,712,760,351,395,723,754,363,746,364,748,362,395,712,758,359,397,716,400,713,399,711,758,360,3120],[363,421,686,788,332,413,705,756,360,394,713,758,359,399,715,750,360,394,724,746,364,749,360,750,364,395,716,757,351,403,717,396,716,390,724,748,362,3120],[10,508,10,105,42,346,63,189,20,346,21,104,85,95,73,20,407,43,42,115,210,42,281,41,31,91,20,71,60,50,20,61,10,10,41,20,62,31,124,21,187],[5523,6032,352,422,693,778,342,411,708,761,352,394,723,749,361,394,719,757,362,393,717,749,367,749,357,749,361,405,715,747,360,400,716,400,716,392,719,758,355,3114],[361,420,687,777,344,412,704,767,349,404,704,758,359,400,714,760,359,391,723,755,360,750,361,751,363,392,713,757,365,396,716,390,723,394,719,751,363,3126],[31,357,42,53,53,441,42,42,42,97,32,253,84,10,32,85,11,73,21,84,32,31,21,220,21,63,31,200,21,558,21,188,41,134,82,51,41,282,52],[198,678,4650,6045,350,425,697,766,350,403,713,756,361,401,717,750,363,393,714,759,361,396,716,756,361,746,362,760,354,394,716,757,364,392,720,394,715,402,712,760,364,3138],[351,433,681,779,332,419,708,757,352,404,712,754,360,405,709,754,359,399,714,753,361,759,356,757,352,397,725,745,360,402,718,396,716,391,715,759,362,3132],[359,419,687,785,336,414,708,763,348,401,712,759,361,398,715,750,364,395,715,756,363,749,361,750,360,394,718,756,364,392,720,395,715,402,715,748,361,3114],[31,474,31,133,10,269,42,209,42,370,135,10,52,175,31,262,21,126,10,52,52,137,21,318,20,242,73,104,41,451,42,127,31],[5521,6040,345,435,686,776,340,412,703,768,350,399,715,753,368,397,716,750,364,395,716,757,361,756,358,753,358,394,715,756,364,396,715,390,722,394,719,758,358,3120],[359,426,696,776,339,413,705,757,361,390,716,759,353,403,710,755,359,395,720,759,351,761,356,759,351,405,715,746,370,390,716,394,725,392,721,754,359,3120],[351,431,688,778,335,425,693,763,358,404,709,754,359,400,716,760,354,394,716,755,364,748,362,749,360,403,713,758,357,394,721,394,716,402,710,754,358,3114]]
```

## Final note ##
The repository is available at: https://github.com/harriedegroot/Athom-Homey-RF-Signal-Analyzer

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=RFE6WKJ4VRB5U&lc=NL&item_name=Harrie%20de%20Groot&item_number=Athom%20Homey%20RF%20Signal%20Analyzer&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted) 
 Did this app help you create a working driver? Consider buying me a :beer:!
