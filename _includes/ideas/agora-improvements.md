## Agora

### Idea: Improvements for Agora library

#### Description
 
Agora is a library of data structures and algorithms for counting votes in elections. It consists of over 40 algorithms along with testing frameworks, and more features and algorithms are being added at the moment. This year, we have planned to further improve the library. This project has the following subparts.

- __Addition of new algorithms in Agora__ - Enhancement of the Agora library with more algorithms is of the highest priority. Some research is needed to find, explore and study them. Along with this, there is obviously the need to find suitable ways to modify ballot if needed to meet the demands of the algorithms. Some relevant sources are [here](https://www.opavote.com/), [here](http://democratix.dbai.tuwien.ac.at/) and [here](https://docs.google.com/document/d/1kfdvyTSW-X9d8aNaf_h67CzYg1qKJ6CQND2llSG_ae8/edit). Suggested study includes the book “Handbook of Computational Social Choice” by Prof. Felix Brandt and some recent developments in the field can be found [here](http://research.illc.uva.nl/COMSOC/theses.html).

- __Addition of new quotas in Agora__ - New quotas or algorithms to satisfy for electing individuals can be added to the existing library. Some quotas can be found [here](https://docs.google.com/document/d/1kfdvyTSW-X9d8aNaf_h67CzYg1qKJ6CQND2llSG_ae8/edit).

- __New ballot for involving district and party lists in ballot__ - There are some algorithms, mainly the ones involving party lists, [double majority](https://en.wikipedia.org/wiki/Double_majority), [Biproportional apportionment](https://en.wikipedia.org/wiki/Biproportional_apportionment) and [Dual member proportional representation](https://en.wikipedia.org/wiki/Dual-member_proportional_representation) where inclusion of district and party is needed. Suggestions are welcome regarding format of ballot. More information can be found [here](https://docs.google.com/document/d/1kfdvyTSW-X9d8aNaf_h67CzYg1qKJ6CQND2llSG_ae8/edit).

- __Addition of new Scala libraries for better performance__ - Scala libraries like [Spire](https://github.com/non/spire) for representation of Rational class, and [Breeze](https://github.com/scalanlp/breeze) for numerical operations is suggested. Suggestions welcome to include more.

- __Addition of Scrutiny tables and Summary matrices__ - Summary matrices in various methods, mainly summary matrices in Condorcet methods and methods involving comparison matrices and Scrutiny tables in STV using multidimensional lists in Scala as mentioned [here](https://groups.google.com/forum/#!category-topic/aossie-gsoc-2017/agora/gG4TKIAc91g). Also research on Scrutiny tables for other elections suggested (for example, for some Condorcet methods, say Copeland, there can be two types of tables, one denoting the candidate vs candidate winning percentages and the other being each candidates winning vs losing percentages or scores).

- __Methods to resolve ties__ - Some research is needed to ensure all the algorithms come with methods to resolve ties, either in some pre-established way or after discussion with mentors. Ballot modifications might also be needed if needed (say to handle indifferences).


#### Requirements

For this project, we are looking for a student:

- experienced in Scala (or with solid programming skills in other object-oriented and functional programming languages and willing to learn Scala).

- with good text comprehension skills (to understand imprecise specifications of vote counting methods (e.g. in wikipedia))

You don't have to be an expert in all these skills. Some previous experience in related skills and a lot of motivation to learn quickly would suffice.

#### Mentors

Saumo Pal, Bruno Woltzenlogel Paleo

