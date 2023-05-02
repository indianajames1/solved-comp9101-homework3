Download Link: https://assignmentchef.com/product/solved-comp9101-homework3
<br>



<ol>

 <li>After the success of your latest research project in mythical DNA, you have gained the attention of a most diabolical creature: Medusa. Medusa has snakes instead of hair. Each of her snakes’ DNA is represented by an uppercase string of letters. Each letter is one of S, N, A, K or E. Your extensive research shows that a snake’s venom level depends on its DNA. A snake has venom level x if its DNA:

  <ul>

   <li>has exactly 5x letters</li>

   <li>begins with x copies of the letter S</li>

   <li>then has x copies of the letter N</li>

   <li>then has x copies of the letter A • then has x copies of the letter K</li>

   <li>ends with x copies of the letter E.</li>

  </ul></li>

</ol>

For example, a snake with venom level 1 has DNA SNAKE, while a snake that has venom level 3 has DNA SSSNNNAAAKKKEEE. If a snake’s DNA does not fit the format described above, it has a venom level of 0. Medusa would like your help making her snakes venomous, by deleting zero or more letters from their DNA. Given a snake’s DNA, can you work out the maximum venom level this snake could have? Your algorithm should run in time <em>O</em>(<em>n</em>log<em>n</em>)

<em>Hint: Combine binary search with greedy.</em>

<ol start="2">

 <li>Paper. Scissors. The rules are simple. The game is contested by two people over <em>N </em>rounds. During each round, you and your opponent simultaneously throw either Rock, Paper or Scissors. Rock beats Scissors, Scissors beats Paper, and Paper beats Rock. If your throw beats your opponent’s, you gain one point. Conversely, if their throw beats yours, you lose one point. Your opponent is very predictable. You know that they will throw Rock in the first <em>R<sub>a </sub></em>rounds, throw Paper in the next <em>P<sub>a </sub></em>rounds, then finally throw Scissors in the last <em>S<sub>a </sub></em>rounds, where <em>R<sub>a </sub></em>+ <em>P<sub>a </sub></em>+ <em>S<sub>a </sub></em>= <em>N</em>. You have</li>

</ol>

1

to throw Rock in <em>R<sub>b </sub></em>rounds, Paper in <em>P<sub>b </sub></em>rounds, and Scissors in <em>S<sub>b </sub></em>rounds, where <em>R<sub>b </sub></em>+ <em>P<sub>b </sub></em>+ <em>S<sub>b </sub></em>= <em>N</em>. However, as you are an experienced player, you may throw these in any order you like. At the beginning of the game, you start with 0 points. How should you play to maximise the number of points you can finish with?

<ol start="3">

 <li>You are given a time schedule of arrivals <em>a<sub>i </sub></em>and departures <em>d<sub>i </sub></em>of <em>n </em>trains, so 1 ≤ <em>i </em>≤ <em>n</em>, during each 24 hour period (note: a train can arrive before the midnight and leave after midnight; each train arrives and departs at the same time every day). You need to find the minimum number of platforms so that each train can stay at a platform without interfering with other arrivals and departures.</li>

 <li>You are given a set of <em>n </em>jobs where each job <em>i </em>has a deadline <em>d<sub>i </sub></em>≥ 1 and profit <em>p<sub>i </sub>&gt; </em> Only one job can be scheduled at a time. Each job takes 1 unit of time to complete. We earn the profit if and only if the job is completed by its deadline. The task is to find the subset of jobs that maximises profit. Your algorithm should run in time <em>O</em>(<em>n</em><sup>2</sup>).</li>

 <li>You have to produce and deliver <em>N </em> You need to deliver <em>W<sub>i </sub></em>kilograms of chemical <em>C<sub>i</sub></em>. Production of each chemical takes one day, and your factory can produce only one chemical at any time. However, all of the chemicals evaporate, and at the end of each day you loose <em>p </em>percent of the amount you had at the end of the previous day, so you need to produce more than what you need to deliver. Schedule the production of the chemicals so that the total extra weight of all chemicals needed to produce to compensate for the evaporation loss is as small as possible.</li>

</ol>

<em>Hint: First determine how much of a chemical is left after k many days and then compute how much of it has ben lost, and then apply greedy</em>