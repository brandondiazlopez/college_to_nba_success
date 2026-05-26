# NBA Draft Analysis

Basketball has always been more than just a game for me. I grew up playing through high school, competed on Air Force base teams, and still run rec league now. Off the court I have helped out at camps and done volunteer skills coaching with kids, because passing the game on is just as important as playing it.

The obsession with the numbers side started early. Back in NBA Live 09 I would spend hours running simulations, breaking down player ratings, figuring out why Steve Nash was so effective despite not being the most athletic guy on the floor. But what really got me was the Player DNA feature. The idea that every player had a unique fingerprint of tendencies, strengths, and habits that defined how they played. As a kid I just thought it was cool. Looking back, that was basically an early version of what player tracking analytics does today. Breaking a player down into their core behavioral patterns to understand and predict performance. It just took me a few years to realize the game had already shown me what I wanted to do for a living.

That curiosity about what actually makes a player successful never went away. It just eventually turned into a career in data analytics.

This project is where both worlds meet.

*Photo above taken in New Mexico at a court built for the youth of our church community, where I volunteered teaching kids the game that taught me everything about numbers.*

---

## What this project looks at

Every year teams spend millions evaluating draft prospects. But how much does draft position actually matter once a player gets to the league? This analysis looks at 20 years of NBA draft data (1990 to 2021) to see whether where you get picked predicts whether you will have a successful career.

---

## How success is defined

Rookie contracts are the right benchmark. First round picks get 4-year deals, second round picks get shorter 2-year deals. So success here means a player outlasted their initial contract:

- **First round picks (1 to 30):** 4+ seasons
- **Second round picks (31 to 60):** 3+ seasons

---

## What's in the notebook

- Exploratory analysis of 1,800+ draft picks across 20 years
- Success rate breakdown by lottery, late first round, and second round
- Success rate visualized for every individual pick number
- Random Forest classification model to predict success from draft position
- Confusion matrix and feature importance

**Run it yourself:** [Open in Google Colab](https://colab.research.google.com/drive/1gILH4u_pDTCtQw8ptu8q7JQU4aezxgIw?usp=sharing)

---

## Tools used
Python, pandas, scikit-learn, matplotlib, seaborn

---

**Brandon Diaz-Lopez**
M.S. Data Analytics, UCF 2024
[Portfolio](https://brandondiazlopez.github.io/BrandonDiaz-Lopez2.github.io/) | [LinkedIn](https://www.linkedin.com/in/brandon-diaz-lopez-)
