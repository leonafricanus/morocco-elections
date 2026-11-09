# Reading guide for the metrics · Morocco elections dashboard 2002–2021 (version 3)

This guide explains how to read every number, chart and table in the dashboard. It does not tell you what to conclude from the results. Every example uses invented numbers, not the dashboard's figures.

Order: the Overview tab first, then one election tab. The five election tabs share the same layout.

When a metric appears in several places, one section explains it and a "Where it appears" line lists the places.

---

## Part 1 · Moving around the page

### 1. Tabs (2002 … 2021, Overview)
- **What it measures**: Nothing. It lets you choose what to look at: one election, or the comparison of the five.
- **How it is calculated**: The small line under each year reads "{party} first · {government}". The party is the one with the most local seats in the dashboard's calculation.
- **Scale and direction**: No scale.
- **How to read it on the page**: Click a year for its detail. Click Overview to compare. The arrow keys move from one tab to the next.
- **Example with invented numbers**: "2030 / P1 first · Smith" reads: in 2030, party P1 has the most local seats in the calculation, and the government that followed is called "Smith".
- **Traps to avoid**:
  - "First" is counted on local seats only. National and regional list seats are not included.
  - The dashboard's calculation can differ from the official result. See sections 15 and 37.
- **Questions to ask yourself**: Am I on one election or on the comparison? Which year am I reading?

---

## Part 2 · The Overview tab

### 2. The chain, from voters to powers
- **What it measures**: The chain orders five stages: voters, election, largest party, head of government, government. It ends with two boxes, "Government powers" and "Monarchy powers". Each link carries one indicator.
- **How it is calculated**: Each link has three parts: the indicator's name, its value, and a verdict. The indicators are:
  ```
  Voters              → Real turnout (pop 18+), latest election          (section 5)
  Election            → Gallagher index, latest election                 (section 9)
  Largest party       → how often it led the government / how often its own leader was appointed
  Head of government  → Gamson ratio of the winner                       (section 29)
  Government          → Sovereignty ministries held by non-partisans, of 6   (section 31)
  ```
- **Scale and direction**: The verdict is one of three words: "strong", "bounded", "weak". "Strong" means the dashboard's author considers that the vote decides at this link. "Bounded" means it decides within limits. "Weak" means the decision is mostly taken elsewhere.
- **How to read it on the page**: Read from top to bottom. Each framed box is a stage. The line on the side is coloured by verdict. Under the verdict you find the indicator's name, then its value in large type.
- **Example with invented numbers**: If the "Election" link reads "Gallagher index: 3.0" with the verdict "strong", you read: the index is 3.0, and the author gave it "strong" under the author's own rule.
- **Traps to avoid**:
  - The verdicts were set by the dashboard's author with the author's own rules. They are not official standards.
  - The first two links use the latest election only, not all five.
  - The sentence in the box under the chain is the author's reading. This guide does not repeat it.
- **Questions to ask yourself**: Which indicator is used at each link? Is the verdict based on one year or several? What would the verdict be with a different cut-off?

### 3. Largest party
- **What it measures**: The party with the most local seats in the dashboard's calculation.
- **How it is calculated**: The dashboard takes each constituency's votes, allocates the seats with the rule in force that year, and adds them up.
  ```
  Largest party = the party with the highest total of local seats
  ```
- **Scale and direction**: Not a number; it is a party name.
- **How to read it on the page**: In the table "The five elections side by side" it is the first row. On an election tab it is the first tile, with its seats and the runner-up underneath.
- **Where it appears**: The tabs, the election tab's headline, the first tile, the Overview table.
- **Example with invented numbers**: P1 has 70 local seats and P2 has 55. The largest party is P1, "P2 second with 55".
- **Traps to avoid**:
  - Counted on local seats only.
  - It is the result of a simulation from the votes. It can differ from the official count.
- **Questions to ask yourself**: Does the largest party change from one year to the next? How far ahead of the runner-up is it?

### 4. Turnout of registered voters
- **What it measures**: Out of every 100 people on the electoral roll, how many voted.
- **How it is calculated**:
  ```
  Turnout of registered voters = voters ÷ registered voters
  ```
- **Scale and direction**: 0% to 100%. A higher value means a larger share of registered people voted.
- **How to read it on the page**: On an election tab it is the second tile. Underneath it says where the registered figure comes from: "from TAFRA" or "estimated". In the Overview it is a table row, and you can chart it with "Chart one KPI".
- **Where it appears**: The election tile, the Overview table, the map, the constituency table, "Morocco in context".
- **Example with invented numbers**: 1,000 registered, 450 voted. Turnout = 450 ÷ 1,000 = 45%.
- **Traps to avoid**:
  - The denominator is registered voters, not all adults. Unregistered people are not counted.
  - In some years the registered figure is an estimate. See section 15.
- **Questions to ask yourself**: Does the value go up or down between years? Is this year's registered figure from the file or estimated?

### 5. Real turnout (share of adults)
- **What it measures**: Out of every 100 people aged 18 or over, how many voted. It counts unregistered adults too.
- **How it is calculated**:
  ```
  Real turnout = voters ÷ population aged 18 and over
  ```
  The adult population comes from the HCP census. The tile says which census is used.
- **Scale and direction**: From 0% upwards, normally below 100%. A higher value means a larger share of adults voted.
- **How to read it on the page**: Third tile on an election tab. A row in the Overview table. The first link of the chain. The "Legitimacy" line of the scorecard, with a benchmark of 0.5 or more (the author's choice).
- **Example with invented numbers**: 2,000 adults, 1,000 registered, 450 voted. Turnout of registered voters = 45%. Real turnout = 450 ÷ 2,000 = 22.5%.
- **Traps to avoid**:
  - The census is not from the election year. If the population grew after the census, the value comes out higher than reality.
  - In a small province the value can exceed 100% when registered voters outnumber the residents counted in the census.
  - Do not compare this value directly with turnout of registered voters. The denominators differ.
- **Questions to ask yourself**: How far apart are this value and turnout of registered voters? Which census is used for this year?

### 6. Registration rate (share of adults)
- **What it measures**: Out of every 100 adults, how many are on the electoral roll.
- **How it is calculated**:
  ```
  Registration rate = registered voters ÷ population aged 18 and over
  ```
- **Scale and direction**: From 0% upwards. A higher value means a larger share of adults is registered.
- **How to read it on the page**: A row in the Overview table. On an election tab it is the tile "of adults are registered" in "Whose vote weighs more". If "estimate" is written underneath, the registered figure is estimated.
- **Example with invented numbers**: 2,000 adults, 1,400 registered. Registration rate = 70%.
- **Traps to avoid**:
  - Same census trap: the census year is not the election year.
  - If registered voters are estimated, this rate is an estimate too.
- **Questions to ask yourself**: Do this rate and real turnout move in the same direction? Is the value built on registered voters from the file or on an estimate?

### 7. Winner's share of local seats
- **What it measures**: The share of all local seats held by the largest party.
- **How it is calculated**:
  ```
  Winner's share = local seats of the largest party ÷ all local seats
  ```
- **Scale and direction**: 0% to 100%. Above 50% means the largest party holds a majority of local seats on its own.
- **How to read it on the page**: In the election tab's headline ("… comes first with …%"). A row in the Overview table. The "Decisive" line of the scorecard, with a benchmark of 0.4 or more (the author's choice).
- **Example with invented numbers**: 300 local seats, the largest party has 90. Share = 30%.
- **Traps to avoid**:
  - It is a share of local seats, not of the whole chamber.
  - A share of seats is not a share of votes. Compare them in section 38.
- **Questions to ask yourself**: Is the share above or below the scorecard benchmark? How far apart are the same party's seat share and vote share?

### 8. Effective number of parties (votes / seats)
- **What it measures**: How many parties carry real weight. It is not the number of registered parties. A very small party counts for almost nothing.
- **How it is calculated**:
  ```
  Effective number = 1 ÷ (sum of the squared shares)
  ```
  Take each party's share (a number between 0 and 1), square it, add them up, and divide 1 by the total. There are two versions: one with vote shares, one with seat shares.
- **Scale and direction**: The minimum is 1 (one party has everything). There is no maximum. A higher value means votes or seats are spread across more parties.
- **How to read it on the page**: Two rows in the Overview table. On an election tab the fourth tile gives the seats version, with the number of parties that win seats underneath. The constituency table has an "Eff. parties" column for each constituency.
- **Example with invented numbers**: Two parties at 50% and 50%: 1 ÷ (0.25 + 0.25) = 2. Three parties at 60%, 30%, 10%: 1 ÷ (0.36 + 0.09 + 0.01) = 2.17.
- **Traps to avoid**:
  - The votes version and the seats version differ. The seats version is usually smaller.
  - In this dashboard the seats version uses local seats only.
  - If a year's file is missing parties, that year's value is affected.
- **Questions to ask yourself**: How far apart are the votes and seats versions? Does the value change between years? How many parties win seats, and what is the effective number?

### 9. Gallagher index
- **What it measures**: How far seat shares are from vote shares. It is an index of "seat–vote distortion".
- **How it is calculated**:
  ```
  Gallagher = square root of ( ½ × sum of (vote share − seat share)² )
  ```
  Shares are in percent. The sum runs over all parties.
- **Scale and direction**: 0 to 100. Zero means every party has the same share of votes and of seats. A higher value means seats and votes are further apart.
- **How to read it on the page**: Fifth tile on an election tab. Underneath it reads "5 or less counts as low"; that is the author's choice. It is also in the Overview table, in the chain, in the scorecard ("Fair" test) and in "Morocco in context".
- **Example with invented numbers**: Two parties. P1: 60% of votes, 70% of seats. P2: 40% of votes, 30% of seats. The gap is 10 for each. Gallagher = square root of (½ × (100 + 100)) = 10.
- **Traps to avoid**:
  - Here the value is computed on local seats only. The figures for other countries in section 33 are for whole chambers.
  - The index says how large the gap is, not who gains or loses from it. For that, see section 38.
  - The cut-off of 5 is not a universal rule.
- **Questions to ask yourself**: Is the value above or below the dashboard's benchmark? Does it change between years, and in which direction? Which parties have the largest gap between votes and seats?

### 10. Pedersen volatility vs previous election
- **What it measures**: How much the parties' vote shares changed between one election and the one before.
- **How it is calculated**:
  ```
  Pedersen = ½ × sum of | party's share now − party's share at the previous election |
  ```
  Shares are in percent. Differences are taken without their sign.
- **Scale and direction**: 0 to 100. Zero means every party kept the same share. 100 means all votes went to parties that did not exist before.
- **How to read it on the page**: A row in the Overview table. The first year has no value because there is no earlier year. In the scorecard it sits under the "Free" test, with a benchmark of 10 or more (the author's choice).
- **Example with invented numbers**: P1 goes from 40% to 30%. P2 goes from 60% to 70%. Pedersen = ½ × (10 + 10) = 10.
- **Traps to avoid**:
  - A new party, a dissolved party, or a merger raises the value even if voters did not change their choice.
  - If a year's file is missing parties, the volatility involving that year is affected.
  - The index measures net change between parties, not how many individuals switched.
- **Questions to ask yourself**: Is the value above or below the benchmark? Are the parties the same in both years? Are both years' files complete?

### 11. Parties winning seats
- **What it measures**: The number of parties that win at least one local seat.
- **How it is calculated**:
  ```
  Count = number of parties with one local seat or more
  ```
- **Scale and direction**: 1 upwards, a whole number. A higher value means seats are spread across more parties.
- **How to read it on the page**: A row in the Overview table. Under the effective-number tile on an election tab. In the scorecard under the "Free" test, with a benchmark of 5 or more (the author's choice).
- **Example with invented numbers**: 12 parties stood, 7 won seats. The value is 7.
- **Traps to avoid**:
  - A party with one seat counts the same as a party with 80. Compare with the effective number in section 8.
  - If the file is missing parties, this count cannot exceed the number of parties in the file.
- **Questions to ask yourself**: How far is this count from the effective number? How many parties are in this year's file?

### 12. Turnout–winner link (ρ) · Fingerprint
- **What it measures**: Whether the constituencies with high turnout are also the ones where the leading party has a high share.
- **How it is calculated**:
  ```
  ρ = Spearman correlation between: turnout in each constituency, and the leading party's share there
  ```
  Spearman ranks the constituencies from lowest to highest on each measure and compares the two rankings.
- **Scale and direction**: −1 to +1. Near +1: constituencies with high turnout are those where the leading party is high. Near −1: the opposite. Near 0: no shared ordering.
- **How to read it on the page**: On an election tab it is the third tile of the constituencies section. The hint underneath ("strongly positive would be a warning sign") is the author's rule. In the scorecard it sits under "Integrity", with a benchmark below 0.3 (the author's choice). The scatter plot (section 45) displays the same thing visually.
- **Example with invented numbers**: Three constituencies. Turnout: 30%, 50%, 70%. Leading party's share: 20%, 30%, 40%. The order is the same in both. ρ = +1.
- **Traps to avoid**:
  - This is a statistical signal, not evidence of anything.
  - A positive link can come from ordinary causes, such as a party being strong in areas that vote a lot.
  - The value refers to the leading party in each constituency, which is not always the same party.
- **Questions to ask yourself**: Is ρ positive or negative? Is it near zero or far from it? Do the dots in the chart rise together or are they scattered?

### 13. Parties needed for a majority
- **What it measures**: The smallest number of parties that must be added together to reach a majority of the chamber, starting with the largest.
- **How it is calculated**:
  ```
  1. Scale each party's local seats so the total equals the whole chamber
  2. Sort the parties from largest to smallest
  3. Add them up until the majority is reached (half the chamber + 1)
  ```
- **Scale and direction**: 1 upwards, a whole number. 1 means the largest party has a majority alone. A higher value means a coalition needs more parties.
- **How to read it on the page**: Sixth tile on an election tab, with the majority and the chamber size underneath. A row in the Overview table. In the scorecard under "Decisive", with a benchmark of 2 or fewer (the author's choice).
- **Example with invented numbers**: A chamber of 100 seats, majority 51. Parties: 30, 25, 20, 15, 10. 30 + 25 = 55. Answer: 2.
- **Traps to avoid**:
  - This is arithmetic. It does not say whether those parties can or want to govern together.
  - National list seats are not counted directly; local seats are scaled up instead.
  - The actual coalition can have a different number of parties. See section 27.
- **Questions to ask yourself**: What is the majority this year? How many parties were in the actual coalition?

### 14. Malapportionment index (MAL %)
- **What it measures**: How far the distribution of seats across provinces is from the distribution of population.
- **How it is calculated**:
  ```
  MAL = ½ × sum of | province's share of seats − province's share of population | × 100
  ```
- **Scale and direction**: 0% to 100%. Zero means every province has seats in proportion to its population. The value reads as "this share of seats is not where the population is".
- **How to read it on the page**: First tile in "Whose vote weighs more". A row in the Overview table. In the scorecard under "Fair", with a benchmark of 5 or less (the author's choice).
- **Example with invented numbers**: Two provinces. The first has 40% of the population and 50% of the seats. The second has 60% of the population and 50% of the seats. MAL = ½ × (10 + 10) = 10%.
- **Traps to avoid**:
  - Population comes from the census, which is not from the election year.
  - Years that use the same census and the same seats get the same value.
  - The index is computed by province, not by constituency.
- **Questions to ask yourself**: Which census is used? Does the value change between years, and why might it not? Which provinces are furthest out? (section 49)

### 15. Registered voters (and the "est." / "estimate" mark)
- **What it measures**: The number of people on the electoral roll.
- **How it is calculated**: In some years the figure is in the results file for each constituency. In other years it is not, and the dashboard estimates it:
  ```
  Registered (estimate) = valid votes ÷ turnout rate
  then rescaled so the national total equals the official figure
  ```
- **Scale and direction**: A number of people. A higher value means more registered voters.
- **How to read it on the page**: Last row of the Overview table. If "est." appears next to it, the figure is estimated. On an election tab a yellow note says so, and the turnout tile reads "registered voters estimated".
- **Example with invented numbers**: A constituency has 9,000 valid votes and a turnout rate of 45%. Estimate = 9,000 ÷ 0.45 = 20,000 registered, before rescaling.
- **Traps to avoid**:
  - The estimate assumes the share of spoiled ballots is the same in every constituency.
  - Every metric that uses registered voters is affected: turnout, registration rate, and the seats when the electoral quotient is based on registered voters.
- **Questions to ask yourself**: Does this year carry "estimate"? Which metrics on this page use registered voters?

### 16. Chart one KPI
- **What it measures**: It draws one metric from the Overview table, one bar per election.
- **How it is calculated**: No new calculation. Same numbers as the table.
- **Scale and direction**: Depends on the metric you pick. The axis starts at 0.
- **How to read it on the page**: Pick the metric from the list. Each horizontal bar is a year. Its colour is that year's colour throughout the page. The value is written at the end of the bar. "n/a" means there is no value for that year.
- **Example with invented numbers**: You pick "Gallagher index". You see five bars: 4, 6, 5, 7, 3. The longest bar is the year with 7.
- **Traps to avoid**:
  - Bar lengths compare only within one metric. Do not compare a bar of a rate with a bar of a count.
  - The years are not evenly spaced in time.
- **Questions to ask yourself**: Does the value rise, fall or stay level? Is one year very different from the rest? Does that year carry a data caveat?

### 17. How the parties moved
- **What it measures**: Each main party's local seats, or share of votes, at each election.
- **How it is calculated**: No new calculation. The parties listed are those with 10 seats or more at least once.
- **Scale and direction**: With "Local seats": a number of seats. With "Share of votes": a rate from 0% to 100%.
- **How to read it on the page**: Each party has a group of bars, one per year. Colour is the year; the legend is under the chart. The value is written at the end of each bar. The "Show" list switches between seats and votes.
- **Example with invented numbers**: P1 has bars of 30, 45, 20. You read: 30 seats in the first year, 45 in the second, 20 in the third.
- **Traps to avoid**:
  - The number of local seats is not the same in every year. Compare shares, not only counts.
  - A party that did not exist in a year appears as zero.
  - In a year with an incomplete file, vote shares are shares of the votes in the file only.
- **Questions to ask yourself**: Is the party rising or falling? Do its seats and votes move by the same amount?

### 18. The five elections in motion
- **What it measures**: The same local seats as section 17, animated from year to year.
- **How it is calculated**: No new calculation. Small parties are grouped as "Others".
- **Scale and direction**: Number of local seats.
- **How to read it on the page**: Press Play to run through the years, or click a year. The year is written in large type. Bars reorder from largest to smallest and change position. Beside them is a half-circle of dots: each dot is a seat (see section 39).
- **Example with invented numbers**: P1 was on the first line with 60, and in the next year it is on the third line with 25.
- **Traps to avoid**:
  - A bar changes position as well as length. Follow the colour and the name.
  - The motion runs between two years. There is no data in between.
- **Questions to ask yourself**: Which party changed rank? Is the change large or small between each pair of years?

### 19. Where the seats went
- **What it measures**: How many seats each party kept between two elections, and how many passed from one party to another.
- **How it is calculated**:
  ```
  In each constituency:
    seats kept = the smaller of the party's seats before and after
    seats lost by some parties are shared among the parties that gained, in proportion to each gain
  then all constituencies are added up
  ```
  When constituencies were redrawn between two years, the same calculation is done on national totals.
- **Scale and direction**: A number of seats. A wider band means more seats.
- **How to read it on the page**: Each column is a year. Each coloured block is a party, and its height is its seats. A band joins a party in one year to a party in the next. The band takes the colour of the party it leaves. A straight band between the same colour is seats kept. Hover over a band for the number. The "≈" mark in the detail means the calculation is national and approximate.
- **Example with invented numbers**: A 3-seat constituency. Before: P1 has 2, P2 has 1. After: P1 has 1, P2 has 1, P3 has 1. Kept: one for P1, one for P2. One seat passes from P1 to P3.
- **Traps to avoid**:
  - This tracks seats, not voters. It does not say who voted for whom.
  - When several parties lose and several gain in the same constituency, the split is approximate and can give fractions.
  - The national calculation is more approximate than the constituency one.
- **Questions to ask yourself**: How many seats did each party keep? Where did a party's new seats come from? Are these two years computed by constituency or nationally?

### 20. One party across the five elections (tiles)
- **What it measures**: One party's path: local seats, rank, vote share, and the number of constituencies where it comes first.
- **How it is calculated**:
  ```
  Rank = the party's position when parties are sorted by local seats
  Of valid votes = the party's votes ÷ all votes
  Constituencies where it comes first = constituencies where it has the most votes
  ```
- **Scale and direction**: Seats: a count. Rank: 1 is first. Share: 0% to 100%. Constituencies: 0 to the total number.
- **How to read it on the page**: Pick the party from the list. One tile appears per year. The large number is local seats. Under it, the year and the rank. Then the vote share and the number of constituencies. "did not stand" means the party has no votes that year.
- **Example with invented numbers**: A tile reads "40 local seats · rank 2 · 18% of valid votes · 12 constituencies where it comes first".
- **Traps to avoid**:
  - "First in the constituency" means the most votes there, not all of its seats.
  - Rank is based on seats, not on votes.
- **Questions to ask yourself**: Do seats and share move together? Does the rank change?

### 21. Party map and province lists
- **What it measures**: The chosen party's vote share in each province, for the chosen year. Also the provinces where it is strongest, and where it gained or lost since the previous election.
- **How it is calculated**:
  ```
  Share in the province = the party's votes in the province ÷ all votes in the province
  Change = share now − share at the previous election   (in points)
  ```
- **Scale and direction**: Share from 0% to 100%. Change in points: positive means the share rose, negative means it fell.
- **How to read it on the page**: Pick the party and the election. The map uses five shades of blue. The legend gives the range of each shade. Provinces are split into five groups of roughly equal size. A grey province means the party has no votes there. Beside the map: "Strongest provinces", "Biggest gains" and "Biggest losses".
- **Example with invented numbers**: In a province the party has 3,000 votes out of 20,000. Share = 15%. At the previous election it was 22%. Change = −7 points.
- **Traps to avoid**:
  - The colour ranges change with each party and each year. The same shade is not the same value on two maps.
  - A province that is large on the map does not necessarily have more people.
  - For the earlier years, the map uses today's provinces, and each one takes the figures of the province it belonged to.
  - This describes places, not people.
- **Questions to ask yourself**: What are the ranges of each colour on this map? Are the dark provinces clustered or scattered? Where did the share change most?

### 22. Same votes, different parliament
- **What it measures**: The seats each party would get if the same votes were counted under two rules: the 2016 rule and the 2021 rule.
- **How it is calculated**:
  ```
  2016 rule: 3% threshold, electoral quotient based on the votes of lists that pass the threshold
  2021 rule: no threshold, electoral quotient based on registered voters
  Change = seats under the 2021 rule − seats under the 2016 rule
  ```
  Seats are allocated constituency by constituency with the largest-remainder method. See section 23.
- **Scale and direction**: The horizontal axis is local seats, starting at 0. A positive change means more seats under the 2021 rule.
- **How to read it on the page**: Choose which year's votes with "Votes of". Each line is a party. It has two dots joined by a line: one for the 2016 rule and one for the 2021 rule (see the legend for colours). The length of the line is the gap. The number beside it is the change. Only parties with 3 seats or more under either rule are listed.
- **Example with invented numbers**: A party has 80 seats under the 2016 rule and 65 under the 2021 rule. The line joins 80 and 65, and "−15" is written beside it.
- **Traps to avoid**:
  - This is a simulation. It assumes voters would have voted the same way under another rule.
  - When registered voters are estimated, the result under the 2021 rule depends on that estimate.
  - The sentence in the box under the chart is generated automatically and carries the author's reading. This guide does not repeat it.
- **Questions to ask yourself**: Which parties have a long line? In which direction? Is the direction the same when you change the year of the votes?

### 23. The largest party under every rule (and the four rules)
- **What it measures**: The local seats of each year's largest party when that year's votes are counted under each of four rules.
- **How it is calculated**: In each constituency:
  ```
  1. Threshold: a list below the threshold is removed
  2. Electoral quotient = base ÷ number of seats in the constituency
  3. Each list gets one seat for every full quotient
  4. Remaining seats go to the lists with the largest remainders
  ```
  The four rules:
  ```
  6% · eligible votes        base = votes of the lists above 6%
  3% · eligible votes        base = votes of the lists above 3%
  0% · registered voters     base = registered voters in the constituency
  0% · valid votes           base = all valid votes (pure proportional)
  ```
- **Scale and direction**: Number of local seats. The figure in brackets is the difference from the rule in force that year.
- **How to read it on the page**: Each row is a year and its largest party. Each column is a rule. The cell marked "in force" is that year's actual rule. The other cells give the count and the difference in brackets.
- **Example with invented numbers**: A constituency with 3 seats and 30,000 registered. Votes: P1 9,000, P2 4,000, P3 2,000. With a quotient on registered voters: 30,000 ÷ 3 = 10,000. No list reaches 10,000. Seats go to the largest remainders: one each. With a quotient on votes (15,000 ÷ 3 = 5,000): P1 gets one full seat, the remainders are 4,000, 4,000 and 2,000, and the two remaining seats go to P1 and P2. Result: P1 two, P2 one.
- **Traps to avoid**:
  - A simulation on the same votes. It does not account for parties and voters behaving differently under another rule.
  - The thresholds of some earlier years are marked "verify" in the notebook.
  - Local seats only.
- **Questions to ask yourself**: Which rule was in force this year? How large is the gap between rules? Does the gap point the same way in every year?

### 24. Scorecard
- **What it measures**: It groups 9 metrics under 5 tests and compares each one with a benchmark.
- **How it is calculated**:
  ```
  Free        Parties winning seats ≥ 5         |  Pedersen volatility ≥ 10
  Fair        Gallagher index ≤ 5                |  Malapportionment MAL ≤ 5
  Integrity   Fingerprint ρ < 0.3                |  Turnout >80% share < 2%
  Decisive    Winner seat share ≥ 0.4            |  Parties needed for majority ≤ 2
  Legitimacy  Real turnout ≥ 0.5
  ```
  The question behind each test: "Free": is there competition? "Fair": are the rules and the districting neutral? "Integrity": are there unusual statistical signals? "Decisive": does winning give the capacity to govern? "Legitimacy": do people take part?
- **Scale and direction**: Each line has one of three answers: ● (the value meets the benchmark), ○ (it does not), n/a (no value).
- **How to read it on the page**: On an election tab: columns "Test", "KPI", "Benchmark", the value, and "Result". In the Overview: one column per year, with the mark and the value in each cell. Read the whole line: the metric, the benchmark, then the mark.
- **Example with invented numbers**: The benchmark is "5 or less". A value of 4.2 gets ●. A value of 5.8 gets ○.
- **Traps to avoid**:
  - The benchmarks are the author's analytical conventions, not universal norms. The page says so under the table.
  - A value very close to the benchmark can flip the mark with a small difference.
  - The mark does not say how far the value is from the benchmark. Look at the number.
  - Do not add up the marks into a single score. The dashboard does not do that.
- **Questions to ask yourself**: How far is the value from the benchmark? Is the mark the same in every year? What would happen if the benchmark moved a little?

### 25. Turnout >80% share
- **What it measures**: The share of constituencies where turnout of registered voters is above 80%.
- **How it is calculated**:
  ```
  Share = constituencies with turnout > 80% ÷ number of constituencies
  ```
  "Outliers" are constituencies whose turnout is more than 2.5 standard deviations from the average.
- **Scale and direction**: 0% to 100%. A higher value means more constituencies with very high turnout.
- **How to read it on the page**: Fourth tile of the constituencies section, with the names of the outliers underneath if there are any. In the scorecard under "Integrity", with a benchmark below 2% (the author's choice).
- **Example with invented numbers**: 100 constituencies, 3 of them with turnout above 80%. Share = 3%.
- **Traps to avoid**:
  - A small constituency can have high turnout for ordinary reasons.
  - When registered voters are estimated, each constituency's turnout rate comes from the file, but its registered figure does not.
  - This is a signal, not evidence.
- **Questions to ask yourself**: Which constituencies are they? Are they the same in each year? How many registered voters do they have?

### 26. Days from election to government
- **What it measures**: The number of days between election day and the day the government is appointed.
- **How it is calculated**:
  ```
  Days = date the government is appointed − election date
  ```
- **Scale and direction**: 0 upwards, in days. A higher value means a longer time before the government is formed.
- **How to read it on the page**: First row of the table "After the vote". On an election tab, the first tile of the government section.
- **Example with invented numbers**: Election on 1 March, government on 15 April. Value = 45 days.
- **Traps to avoid**:
  - The dates are entered by hand.
  - The count runs to the appointment of the whole government, not of its head.
  - The duration alone does not say why it was long or short.
- **Questions to ask yourself**: Are the durations close across governments or different? Which two dates are used?

### 27. Coalition seats, and the winner's share of coalition seats
- **What it measures**: The total seats of the parties in government. And, of that total, how many belong to the largest party.
- **How it is calculated**:
  ```
  Winner's share of the coalition = largest party's seats ÷ coalition seats
  ```
  Here the seats are the official seats of the whole chamber, not the simulation.
- **Scale and direction**: Seats: a count. Share: 0% to 100%. A higher value means the largest party weighs more inside the coalition.
- **How to read it on the page**: Second and third rows of "After the vote". On an election tab, the second tile of the government section, with the share underneath.
- **Example with invented numbers**: The coalition has 200 seats, the largest party has 90 of them. Share = 45%.
- **Traps to avoid**:
  - These figures are official and hand-entered. The figures in other sections are a simulation on local seats. Do not mix them.
  - "to collect" or "—" means the figure is not available.
- **Questions to ask yourself**: Does the coalition exceed the majority by a little or a lot? What is the largest party's share of it?

### 28. Winner's share of government posts (and the two-bar chart)
- **What it measures**: Out of every 100 members of government, how many come from the largest party.
- **How it is calculated**:
  ```
  Share of posts = members of government from the largest party ÷ members of government
  ```
- **Scale and direction**: 0% to 100%. A higher value means the largest party has more members in government.
- **How to read it on the page**: Fourth row of the table. Under the table is a chart with two bars per government. The first is the largest party's share of coalition seats. The second is its share of posts. See the legend for colours. Compare the two lengths.
- **Example with invented numbers**: The government has 30 members, 12 from the largest party. Share = 40%.
- **Traps to avoid**:
  - Each member counts as one, senior minister or junior. See section 30 for the weighted version.
  - A government without a second bar means the count is "to collect".
  - The sentence in the box under the chart is the author's reading.
- **Questions to ask yourself**: Are the two bars the same length? Which one is longer? Is the count available for this government?

### 29. Gamson ratio
- **What it measures**: Whether the largest party received posts in proportion to its seats in the coalition.
- **How it is calculated**:
  ```
  Gamson = largest party's share of posts ÷ largest party's share of coalition seats
  ```
- **Scale and direction**: 0 upwards. 1 means "in proportion to seats". Below 1: its share of posts is smaller than its share of seats. Above 1: the opposite.
- **How to read it on the page**: Fifth row of "After the vote". Third tile of the government section on an election tab. Fourth link of the chain.
- **Example with invented numbers**: The largest party has 50% of coalition seats and 40% of posts. Gamson = 0.40 ÷ 0.50 = 0.8.
- **Traps to avoid**:
  - It counts posts, not their importance.
  - Non-partisan ministers are in the denominator for posts, and not in coalition seats.
  - If either figure is missing, the ratio is empty.
- **Questions to ask yourself**: Is the value above or below 1? How far from 1? How many non-partisan ministers are in this government?

### 30. Weighted Gamson ratio (indicative), and members of government by party
- **What it measures**: The same idea as Gamson, but each post carries a weight according to its importance.
- **How it is calculated**:
  ```
  Weights: sovereignty ministry = 3 · major ministry = 2 · minister = 1 · junior minister = 0.5
  Weighted Gamson = largest party's share of total weight ÷ its share of coalition seats
  ```
- **Scale and direction**: As for Gamson: 1 means "in proportion to seats".
- **How to read it on the page**: Sixth row of "After the vote". On an election tab it is written under the chart "Members of government by party". In that chart each bar is a party and its length is the number of members. The grey bar is "Non-partisan".
- **Example with invented numbers**: Total weight in the government is 40. The largest party holds 12. Weighted share = 30%. Its share of coalition seats is 50%. Weighted Gamson = 0.6.
- **Traps to avoid**:
  - The dashboard states that the ranking of posts (major, minister, junior) is a placeholder. The value is indicative.
  - The weights are the author's choice.
  - The chart is absent for governments whose list has not been entered.
- **Questions to ask yourself**: How far apart are the plain and weighted ratios? Has this government's list been entered?

### 31. Key ministries / sovereignty ministries (held by non-partisans, held by the winner)
- **What it measures**: Out of 6 ministries, how many are held by ministers with no party, and how many by the largest party.
- **How it is calculated**: The six ministries are: Interior, Foreign Affairs, Justice, Islamic Affairs, Defence administration, Secretariat-General of the Government.
  ```
  Held by non-partisans = ministries (of 6) whose minister has no party
  Held by the winner    = ministries (of 6) whose minister is from the largest party
  ```
- **Scale and direction**: 0 to 6. The remainder (6 minus the two) is ministries held by other parties.
- **How to read it on the page**: Two rows of "After the vote". Fourth tile of the government section. Fifth link of the chain. Under the table is "The key ministries": one row per ministry, one column per government, and in each cell the minister's name and affiliation. ● means held by a party. ○ means held by a non-partisan minister. The last row is the total.
- **Example with invented numbers**: Of 6: 4 held by non-partisans, 1 by the largest party, 1 by another party.
- **Traps to avoid**:
  - The list of "key ministries" is the author's choice.
  - The data is entered by hand. Cells marked "(verify)" still need checking.
  - The table gives the minister when the government was appointed. Later reshuffles are not included.
  - The paragraph under the table is the author's reading.
- **Questions to ask yourself**: How many ministries fall under each type? Do the same names recur across governments? How many cells carry "(verify)"?

### 32. Ministers dismissed by the King during the term, and the "to collect" marker
- **What it measures**: The number of ministers removed by royal decision during the government's term.
- **How it is calculated**: A count entered by hand from official communiqués.
- **Scale and direction**: 0 upwards, a whole number.
- **How to read it on the page**: Last row of "After the vote". "to collect" means the figure has not been entered yet. "—" or "n/a" means it cannot be computed because another figure is missing.
- **Example with invented numbers**: A government with "2": two ministers were removed during the term.
- **Traps to avoid**:
  - "to collect" is not zero. Do not read it as "0".
  - The count does not give the reasons.
- **Questions to ask yourself**: Is the figure available for this government? What is its source?

### 33. Morocco in context
- **What it measures**: The same metrics for the latest national election in 14 other countries, alongside Morocco.
- **How it is calculated**: The figures come from three outside sources: International IDEA (turnout), Gallagher's election indices (parties and distortion, whole chamber), and the Economist Intelligence Unit (democracy score). The metrics are:
  ```
  Turnout of registered voters             (section 4)
  Turnout among all adults                 (section 5)
  Effective number of parties (seats)      (section 8)
  Gallagher index                          (section 9)
  Democracy score                          (section 34)
  ```
- **Scale and direction**: Depends on the chosen metric.
- **How to read it on the page**: Pick the "Indicator". Each horizontal bar is a country. Countries are grouped by region, with the region's name in small capitals. Morocco's bar is in a different colour. "n/a" means the source has no figure. Hover for the year and the regime type. Under the chart is "All figures (table)".
- **Example with invented numbers**: You pick "Turnout among all adults". Country A: 70%. Country B: 45%. A's bar is longer.
- **Traps to avoid**:
  - Morocco's figures here come from the outside sources. They differ slightly from the dashboard's own (local seats only, another census).
  - Each country has a different year and a different electoral law. Voting is compulsory in some countries.
  - The countries were chosen by the dashboard's author: two or three per region.
  - The three bullets under the chart are the author's reading. This guide does not repeat them.
- **Questions to ask yourself**: Where does Morocco sit on this metric? Does the order change when the metric changes? Which year is used for each country?

### 34. Democracy score (0 to 10), and regime type
- **What it measures**: An overall score given to each country by the Economist Intelligence Unit.
- **How it is calculated**: The average of five areas (electoral process, functioning of government, political participation, political culture, civil liberties). The scoring is done by the institution's experts.
  ```
  Full democracy: above 8      · Flawed democracy: above 6 to 8
  Hybrid regime: above 4 to 6  · Authoritarian: 4 or below
  ```
- **Scale and direction**: 0 to 10. A higher value means a higher score from this institution.
- **How to read it on the page**: The first choice in the "Indicator" list. The regime type appears in the hover detail and in the table.
- **Example with invented numbers**: A country with 6.5 falls under "Flawed democracy".
- **Traps to avoid**:
  - This is one institution's score. Other indices exist with other methods.
  - The names of the types are the institution's, not the dashboard's.
  - The dashboard read the figures from Wikipedia, not from the original report.
- **Questions to ask yourself**: Who gave this score, and how? Do countries with a similar score have similar election metrics?

### 35. Reading these numbers
- **What it measures**: Nothing. It is a list of caveats about the data.
- **How it is calculated**: Five points: local seats only; the 2002 file is incomplete; registered voters for 2016 and 2021 are estimates; two censuses; government data is hand-coded.
- **Scale and direction**: None.
- **How to read it on the page**: It is the last section of the Overview. Read it before comparing years.
- **Example with invented numbers**: Before comparing a metric that uses registered voters between two years, check whether both years' registered figures are of the same kind (from the file, or estimated).
- **Traps to avoid**:
  - Each caveat affects particular metrics, not everything.
- **Questions to ask yourself**: Which caveat affects the metric I am reading? Does it affect one year or several?

---

## Part 3 · An election tab

### 36. Headline and rule pills
- **What it measures**: The headline gives the largest party and its share of local seats (sections 3 and 7). Under it are two pills: that year's electoral rule, and the number of local seats modelled.
- **How it is calculated**: The rule has two parts: the threshold and the base of the electoral quotient. See section 23.
- **Scale and direction**: None.
- **How to read it on the page**: Read the rule pill before any seat figure. Every seat figure on this tab uses this rule, unless you change it yourself.
- **Example with invented numbers**: "Rule: 4% threshold, quotient on votes of eligible lists · 300 local seats modelled".
- **Traps to avoid**:
  - The number of local seats is not the size of the chamber.
  - The rule changes from one year to another.
- **Questions to ask yourself**: What is this year's threshold? What is the quotient based on?

### 37. The notes in the yellow box
- **What it measures**: Nothing. They are warnings about that year's data.
- **How it is calculated**: There are two kinds. One is on the 2002 tab: the file lists nine parties only. The other is on the years whose registered voters are estimated (section 15).
- **Scale and direction**: None.
- **How to read it on the page**: The box appears under the first tiles. Read it before the numbers.
- **Example with invented numbers**: If a file has 9 parties out of 20, the seats of the 11 missing parties are handed to those 9 in the calculation.
- **Traps to avoid**:
  - When the file is incomplete, every seat and share figure for that year is indicative.
  - Shares are shares of the votes in the file only.
- **Questions to ask yourself**: Does this year carry a warning? Which figures does it affect?

### 38. Votes and seats
- **What it measures**: For each party: its share of valid votes, and its share of local seats.
- **How it is calculated**:
  ```
  Vote share = the party's votes ÷ all votes
  Seat share = the party's seats ÷ all local seats
  Gap = seat share − vote share   (in points)
  ```
- **Scale and direction**: The horizontal axis is in percent and starts at 0%. A positive gap means the seat share is larger than the vote share.
- **How to read it on the page**: Each party has two stacked bars. The grey one is the vote share. The coloured one is the seat share. The number of seats is written at the end of the coloured bar. Hover for votes, seats and the gap. Parties are sorted by seats.
- **Example with invented numbers**: A party has 30% of votes and 40% of seats. The coloured bar is longer. Gap = +10 points.
- **Traps to avoid**:
  - Only parties with seats, or with at least 2% of votes, are listed.
  - Seats come from the simulation, with that year's rule.
  - The vote share is national, while seats are allocated constituency by constituency.
- **Questions to ask yourself**: Which parties have a coloured bar longer than the grey one? Which have the opposite? What is the gap for the largest party?

### 39. The parliament: local seats (the half-circle)
- **What it measures**: The local seats drawn dot by dot, under the rule you choose.
- **How it is calculated**: The same allocation as section 23. Eight parties have their own colour. The rest are grouped as "Others" in grey.
- **Scale and direction**: Each dot = one seat. Number of dots = number of local seats.
- **How to read it on the page**: Parties are ordered from largest to smallest, left to right. The centre gives the year, then the largest party, its seats and its share. Under the chart is the legend: colour, name, count. The "Electoral rule" list redraws the chamber under another rule. The rule marked "in force" is the actual one.
- **Example with invented numbers**: 300 dots. 90 in P1's colour, 75 in P2's colour, and the rest in other colours.
- **Traps to avoid**:
  - The order is by size. Position in the chart carries no political meaning (left, right).
  - Local seats only.
  - When you change the rule, you are looking at a simulation, not at a result that happened.
- **Questions to ask yourself**: How many colours must be added to pass half the dots? What changes when the rule changes?

### 40. Same votes, different rules
- **What it measures**: How many seats each party gains or loses when this year's votes are counted under another rule.
- **How it is calculated**:
  ```
  Change = seats under the chosen rule − seats under the rule in force
  Seats changing hands = sum of the positive changes
  ```
- **Scale and direction**: In seats. Positive: the party gains under the chosen rule. Negative: it loses. Total gains = total losses.
- **How to read it on the page**: Choose the rule with "Compare the rule in force with". The vertical line in the middle is zero. Bars to the right "gain seats". Bars to the left "lose seats". Only parties with a change are listed. The sentence under the chart gives the total. "Seats under every rule (table)" opens a table with the four rules.
- **Example with invented numbers**: P1: −8. P2: +5. P3: +3. Seats changing hands: 8.
- **Traps to avoid**:
  - A simulation on the same votes (see section 23).
  - A party absent from the chart has a change of zero; it has not disappeared.
- **Questions to ask yourself**: Which party has the longest bar? Do large and small parties move in the same direction? How many seats change out of the total?

### 41. What if turnout had been different? (the controls)
- **What it measures**: This is a simulation. You change turnout, choose where and for which parties, and watch the seats being recounted.
- **How it is calculated**: In each constituency concerned:
  ```
  New turnout = actual turnout + change   (kept between 2% and 98%)
  Extra votes = registered × change × (valid votes ÷ voters)
  The extra votes are shared among the chosen parties, in proportion to the votes they already have there
  ```
  Then seats are allocated with that year's rule.
- **Scale and direction**: "Change in turnout" runs from −20 to +30 points. Positive: more voters. Negative: fewer.
- **How to read it on the page**: Three controls. "Change in turnout": a slider. "Where": everywhere, urban provinces, or rural provinces (the number in brackets is the number of constituencies). "Parties concerned": tick boxes. With none ticked, all parties receive votes in proportion to their own. "Reset" puts everything back to zero.
- **Example with invented numbers**: A constituency has 10,000 registered, 40% turnout, and 90% of ballots valid. Change +10 points. New voters: 1,000. Extra valid votes: 900. If you tick P1 and P2, which have 3,000 and 1,000 there, P1 gets 675 and P2 gets 225.
- **Traps to avoid**:
  - "Urban" means a province with 50% or more urban population in the census. It is a label for the whole province.
  - The number of registered voters does not change in the simulation.
  - A party with no votes in a constituency gains nothing there.
  - This is a hypothetical scenario, not a forecast.
- **Questions to ask yourself**: What assumption am I testing? Which constituencies are concerned? Do the parties I ticked stand in all of them?

### 42. What-if results
- **What it measures**: Four figures after the change, and the seats compared with the actual result.
- **How it is calculated**:
  ```
  Turnout of registered voters = new voters ÷ registered
  Real turnout, share of adults = new voters ÷ adults (census)
  Constituencies where votes change = constituencies the change was applied to
  Change in seats = seats in the scenario − actual seats
  ```
- **Scale and direction**: As in sections 4 and 5. Change in seats: positive is a gain, negative a loss.
- **How to read it on the page**: Each tile gives the new figure in large type, with "actual: …" underneath for comparison. Under the tiles is the gains-and-losses chart (as in section 40). Under it, the half-circle of the chamber in the scenario. "No seat changes" means the allocation stayed the same.
- **Example with invented numbers**: Turnout goes from 40% to 46%. Constituencies where votes change: 50. P1: +6 seats. P2: −4. P3: −2.
- **Traps to avoid**:
  - When all parties receive votes in proportion to their own, shares do not move, and seats rarely change. This follows from the calculation itself.
  - "Actual" here is the dashboard's simulation without any change, not the official result.
- **Questions to ask yourself**: How many points of turnout does it take for one seat to change? Does the result change when "Where" changes?

### 43. The map
- **What it measures**: One metric per province, out of five: leading party, leading party's vote share, turnout of registered voters, real turnout, inhabitants per seat.
- **How it is calculated**: The constituencies of each province are added together.
  ```
  Leading party in the province = the one with the most votes there
  Inhabitants per seat = the province's population ÷ its number of seats
  ```
- **Scale and direction**: "Leading party": one colour per party. The others: five shades of blue, from low values to high. The legend gives the range of each shade.
- **How to read it on the page**: Pick the metric with "Show". Hover over a province for the figures. Click it to open its constituencies (section 47). In the "Leading party" legend, the number beside each party is the number of provinces.
- **Example with invented numbers**: In the legend the darkest shade reads "60% – 75%". A province in that shade has a value between 60% and 75%.
- **Traps to avoid**:
  - Area is not population. A province that is large on the map can have few people.
  - The ranges of the shades change with each metric and each year.
  - "Leading party in the province" does not say by how much it leads.
  - For the earlier years, the outlines are today's (see the note under the map).
- **Questions to ask yourself**: What are the ranges of each colour? Are provinces of the same colour clustered? Does the picture change when the metric changes?

### 44. Median margin for the last seat, and constituencies decided by under 1 point
- **What it measures**: In each constituency, the gap between the last list to win a seat and the best list that did not.
- **How it is calculated**:
  ```
  Gap in the constituency = (votes of the last list elected − votes of the best losing list) ÷ valid votes × 100
  Median margin = the value with half the constituencies below it and half above
  Second figure = constituencies with a gap under 1 point ÷ number of constituencies
  ```
- **Scale and direction**: The gap is in percentage points. A lower value means the last seat was decided by a smaller difference. The second figure runs from 0% to 100%.
- **How to read it on the page**: First and second tiles of the constituencies section. The same figure for each constituency is in the table's "Last-seat margin" column.
- **Example with invented numbers**: A constituency has 20,000 valid votes. The last list elected has 3,000 and the best losing list has 2,600. Gap = 400 ÷ 20,000 = 2 points.
- **Traps to avoid**:
  - The median is not the average. It is not pulled by one constituency with a very large gap.
  - The gap is computed on lists with that year's rule, not on candidates.
- **Questions to ask yourself**: Is the median margin large or small compared with one point? Which constituencies have the smallest gap?

### 45. Scatter plot: turnout × leading party's share
- **What it measures**: Each constituency is placed on two measures at once.
- **How it is calculated**: No new calculation. Same numbers as the constituency table.
- **Scale and direction**: Horizontal axis: turnout of registered voters. Vertical axis: vote share of the leading party in the constituency. Both in percent.
- **How to read it on the page**: Each dot is a constituency. The dot's size follows its number of seats. The colour is the year's colour and carries no other meaning. Hover for the name and figures. Click to open the detail. The shape to look for: do the dots rise from left to right, fall, or scatter with no direction? And are some dots far from the rest?
- **Example with invented numbers**: A dot at 70% across and 55% up: a constituency where turnout is 70% and the leading party has 55% of the votes.
- **Traps to avoid**:
  - The axes do not start at 0. Read the numbers on them.
  - The leading party is not the same party for every dot.
  - The caption under the chart reads: "These are signals, not proof."
- **Questions to ask yourself**: Do the dots have a direction? How many dots are far from the group? Are large and small dots in the same area?

### 46. The constituencies table
- **What it measures**: One row per constituency, with eight columns.
- **How it is calculated**:
  ```
  Constituency · Seats · Registered · Turnout (section 4) · First party (most votes)
  Its share · Eff. parties (section 8, on votes) · Last-seat margin (section 44)
  ```
- **Scale and direction**: Depends on each column.
- **How to read it on the page**: Type in the box to find a constituency, a province or a party. Click a column heading to sort. Click again to reverse the order. The province is written under the constituency's name. Beside the box is the number of constituencies listed.
- **Example with invented numbers**: A row reads "Constituency X · 4 · 120,000 · 48% · P1 · 31% · 4.2 · 1.5 pts".
- **Traps to avoid**:
  - The "First party" in a constituency is the one with the most votes, not necessarily the most seats.
  - Registered voters can be estimated.
- **Questions to ask yourself**: What appears when I sort by turnout? By margin? Do the same constituencies come to the top?

### 47. Constituency detail panel
- **What it measures**: Everything about one constituency: seats, registered voters, voters, turnout, each party's votes and seats, and the seats there at each election.
- **How it is calculated**:
  ```
  Share = the party's votes in the constituency ÷ valid votes in the constituency
  Seats won = seats under that year's rule
  ```
- **Scale and direction**: Share from 0% to 100%. Seats: 0 to the constituency's number of seats.
- **How to read it on the page**: It opens when you click a row, a dot or a province. On the side you get: a line of general figures, a chart of shares, a table with votes, share and seats (each ● is a seat), and a table "Seats here at each election". If you click a province with several constituencies, each one opens separately. "Close" or the Escape key closes it.
- **Example with invented numbers**: P1: 9,000 votes, 30%, ●● 2. P2: 6,000 votes, 20%, ● 1.
- **Traps to avoid**:
  - Only parties with 1% or a seat are listed.
  - The table of years lists only the years with a constituency of the same name. Its boundaries may have changed.
  - "(estimated)" beside registered voters means an estimated figure.
- **Questions to ask yourself**: With how many votes was the last seat won? Did the same parties win the seats each year?

### 48. Gap between the most and least populated seat
- **What it measures**: How many times more inhabitants stand behind a seat in the least represented province than in the most represented one.
- **How it is calculated**:
  ```
  Gap = highest (inhabitants per seat) ÷ lowest (inhabitants per seat)
  ```
- **Scale and direction**: 1 upwards, written with "×". 1 means every seat has the same number of inhabitants behind it.
- **How to read it on the page**: Second tile of "Whose vote weighs more".
- **Example with invented numbers**: One province has 120,000 inhabitants per seat, another has 30,000. Gap = 4×.
- **Traps to avoid**:
  - The value depends on two provinces only: the highest and the lowest. One very small province raises it a lot.
  - It says nothing about the other provinces. For those, see sections 14 and 49.
- **Questions to ask yourself**: Which two provinces set this value? How many inhabitants do they have?

### 49. Inhabitants per local seat (the chart)
- **What it measures**: How many inhabitants stand behind each seat, in the six least represented and the six most represented provinces.
- **How it is calculated**:
  ```
  Inhabitants per seat = the province's population (census) ÷ its number of local seats
  ```
- **Scale and direction**: A number of inhabitants. A lower value means each vote weighs more in that province.
- **How to read it on the page**: 12 horizontal bars. The first six, in grey, are the "least represented" (more inhabitants per seat). The next six, in the year's colour, are the "most represented". The value is written at the end of each bar. Hover for population, seats and the urban rate.
- **Example with invented numbers**: A province with 400,000 inhabitants and 4 seats: 100,000 per seat. A province with 40,000 inhabitants and 2 seats: 20,000 per seat.
- **Traps to avoid**:
  - Only 12 provinces are drawn. The others lie in between and are not drawn.
  - Population comes from the census, not from the election year.
  - "Inhabitants" means all inhabitants, not adults or registered voters.
- **Questions to ask yourself**: How far apart are the first and last bars? Do the provinces in the chart have something in common (size, location)?

### 50. Where each party is strong
- **What it measures**: Whether a party's vote share rises or falls with three census indicators: urbanisation, illiteracy, unemployment. The calculation runs across provinces.
- **How it is calculated**:
  ```
  For each party and each indicator: Spearman correlation between
    the party's share in each province   and   the indicator's value in that province
  ```
- **Scale and direction**: −1 to +1. Positive: the party has a higher share in provinces where the indicator is high. Negative: the opposite. Near 0: no shared ordering.
- **How to read it on the page**: Each row is a party, each column an indicator. The cell's colour follows the sign (positive or negative) and darkens as the value moves away from zero. Parties with 5 seats or more are listed.
- **Example with invented numbers**: A party with "+0.60" under "Urbanisation": the more urban provinces are the ones where it has a higher share, in rank order.
- **Traps to avoid**:
  - This describes places, not people. A positive value with illiteracy does not mean illiterate people voted for that party.
  - Correlation is not cause.
  - With the older census, "unemployment" is a proxy (first-time job seekers).
  - The three indicators are linked to one another: urbanisation and illiteracy run in opposite directions in many provinces.
- **Questions to ask yourself**: Is the sign positive or negative? How far from zero is the value? Does the same party keep the same sign across years?

### 51. The government that followed
- **What it measures**: Four tiles about the government formed after that election, and a chart of members by party.
- **How it is calculated**: The same metrics as sections 26, 27, 29, 31 and 30.
- **Scale and direction**: See each section.
- **How to read it on the page**: The tiles in order: days from election to government; coalition seats out of the chamber, with the largest party's share underneath; Gamson ratio; sovereignty ministries held by non-partisans, with the number held by the largest party underneath. "—" or "to collect" means a missing figure.
- **Example with invented numbers**: "45 days · 200 seats out of 400, the largest party holds 45% of them · Gamson 0.8 · 4 of 6".
- **Traps to avoid**:
  - The government figures are official and hand-entered. The rest of the tab is a simulation.
  - The government's "largest party" is the official one. It can differ from the simulation's "largest party" when the file is incomplete.
- **Questions to ask yourself**: Which tiles have a figure and which read "to collect"? Is the largest party here the same as in the tab's headline?

---

## Glossary

| Term | Short explanation |
|---|---|
| Registered voters | People on the electoral roll |
| Voters | People who cast a ballot, including spoiled ones |
| Valid votes | Votes counted for the lists |
| Spoiled ballots | Blank or rejected ballots |
| Turnout | Voters divided by registered voters, or by adults |
| Adults (18+) | Population aged 18 or over, from the census |
| Constituency | The area that elects a set number of members |
| Province / prefecture | The administrative unit containing one or more constituencies |
| Local seats | Constituency seats, excluding national and regional lists |
| Threshold | The minimum share of votes a list needs to enter the allocation |
| Electoral quotient | The number a list must reach to win one full seat |
| Largest remainder | The method that allocates the seats left over |
| Eligible lists | Lists above the threshold |
| Effective number of parties | The number of parties weighted by their size |
| Gallagher index | The gap between vote shares and seat shares |
| Pedersen volatility | How much party shares changed between two elections |
| Malapportionment | The gap between the distribution of seats and of population |
| Correlation (Spearman, ρ) | Whether two measures rank cases in the same order |
| Median | The value with half the cases below and half above |
| Coalition | The parties in government |
| Portfolio / post | A position in government |
| Gamson ratio | Share of posts divided by share of coalition seats |
| Sovereignty / key ministries | The six ministries selected by the dashboard |
| Non-partisan | A minister with no party affiliation |
| Benchmark | The cut-off the dashboard compares against; an analytical choice |
| Simulation | A calculation from the votes under a given rule, not an official result |
| Estimate | A figure computed because the actual one is unavailable |
| Census | The general population census (HCP) |
| to collect | A figure not yet entered |
| n/a | No value |
