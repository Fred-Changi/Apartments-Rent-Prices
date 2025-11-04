# Apartments-Rent-Prices
In this project I explore the rent prices of different parts of Kenya.

The dataset did not have many issues.

I only had to clear a number of duplicates.

Another issue is that the price was in text form. For example, KSh 120,000.
I managed to convert this into number form by using the formula 
=VALUE(SUBSTITUTE(SUBSTITUTE(C49, "KSh", ""), ",", "" ))

Some of the insights found was that:

Westlands has the apartments with the highest rent.

Nyali has the cheapest apartment available.

3 bdroom houses are the most available.(Options were 0-6)
