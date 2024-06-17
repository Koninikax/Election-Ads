# Election-Ads
Elections Ad spending analysis using Python and how it impacted the voting patterns.
The dataset collected from Meta Ads contains three files:

1. The Advertisers Dataset provides insights into which pages (parties or organizations) spend money on election ads and the volume of ads they run.
   
2. The Locations Dataset shows how much money was spent on ads in different locations, indicating where the campaigns were focusing their efforts.
   
3. The Results Dataset provides actual voting data, showing how many people voted in each area and the percentage of voter turnout.

![newplot](https://github.com/Koninikax/Election-Ads/assets/96631757/42a7d13f-3a68-4a12-9e03-a4a044b67612)

The bar graph shows the total ad spend (in INR) by state. Uttar Pradesh leads significantly with the highest ad spend, followed by Maharashtra and Odisha. States like West Bengal, Tamil Nadu, Andhra Pradesh, and Bihar also show substantial ad expenditures. In contrast, states such as Lakshadweep, Dadra & Nagar Haveli, Daman & Diu, Andaman & Nicobar Islands, and Arunachal Pradesh have the lowest ad spend. It indicates that larger and more populous states tend to spend more on ads, likely reflecting their greater political significance and larger voter base.

![newplot](https://github.com/Koninikax/Election-Ads/assets/96631757/61dedf0d-9459-47e2-b144-e30b4ecf4140)

Lakshadweep has the highest average voter turnout at nearly 80%, followed closely by Tripura and Assam. States like Andhra Pradesh, Sikkim, and West Bengal also show high voter engagement, with turnouts above 70%. On the other end of the spectrum, states such as Bihar, Uttar Pradesh, and Uttarakhand have the lowest average voter turnout, around 50-55%. It indicates significant regional variations in voter participation, with some smaller states and union territories exhibiting higher engagement compared to larger states with higher ad spend.

![newplot](https://github.com/Koninikax/Election-Ads/assets/96631757/8ae970fa-c8f8-4a67-ae8b-05203644178c)

The Bharatiya Janata Party (BJP) has the highest ad spend, accounting for 42.3% of the total. This is followed by the Ama Chinha Sankha Chinha party at 24.5% and the Indian National Congress at 23.7%. Ellorum Nammudan and BJP Odisha have significantly lower ad spends, at 5.19% and 4.27%, respectively. It indicates that BJP dominates in terms of ad spending on Facebook and Instagram ads, with nearly half of the total expenditure, suggesting a significant investment in advertising compared to other parties.

The correlation matrix shows that the relationship between the amount spent (INR) and the percentage of votes polled (%) is very weak and slightly negative, with a correlation coefficient of -0.010688. This indicates that there is virtually no linear relationship between ad spend and voter turnout. In other words, increasing the amount spent on advertising does not significantly affect the percentage of voter turnout.

![newplot](https://github.com/Koninikax/Election-Ads/assets/96631757/b0e230ab-68bd-46a8-aa45-71332432d72a)

It shows that higher ad spending does not necessarily correlate with higher voter turnout. Voter turnout seems to cluster between 60% and 80% across most constituencies, regardless of the ad spend amount, which ranges from 0 to 150 million INR. This suggests that other factors besides ad spend may play a significant role in influencing voter turnout.

![newplot](https://github.com/Koninikax/Election-Ads/assets/96631757/28a633cd-3937-4bd4-b57a-26c16a7f6ef9)

The histogram indicates that most constituencies have ad spends clustered around the 50M and 100M INR marks, with fewer constituencies spending less than 10M INR or more than 150M INR. The box plot highlights that the median ad spend is around 70M INR, with the interquartile range (IQR) spanning from approximately 30M to 110M INR. There are a few outliers, particularly a constituency with an exceptionally high ad spend above 150M INR. This distribution suggests that while the majority of ad spends are concentrated within a certain range, there are notable exceptions with significantly higher expenditures.

![newplot](https://github.com/Koninikax/Election-Ads/assets/96631757/e9bba144-1491-4831-a69a-02cebbeeb547)

There is no consistent trend between ad spend and voter turnout. Election phases 1 and 4 have the highest ad spends, with phase 4 peaking in voter turnout at around 70%. However, phase 1, despite high ad spend, has a lower voter turnout of about 67%. Phases with moderate ad spend (e.g., 2 and 6) have lower voter turnout, while phase 5 has a notably low turnout despite moderate spending.

## Conclusion
Overall, the analyses indicate that higher ad spend does not guarantee higher voter turnout and voter engagement is influenced by various other factors. Larger and more significant states tend to spend more on ads, but this does not necessarily translate to higher voter participation. Political parties, invest heavily in advertising, yet the effectiveness of this spending in increasing voter turnout is questionable.





