# Data Dictionary for levinson_2007_particles.csv

These data were collected for an acceptability judgment study included in chapter 3 of:

Levinson, Lisa. (2007). The roots of verbs [PhD Thesis]. New York University.

Acceptability judgments were collected with different orders of verb particles 
in combination with resultative and pseudo-resultative adjectives. 
It was hypothesized that pseudo-resultative secondary predicates would
be more acceptable in combination with particles than resultative
secondary predicates. 

These are the labels used for the relevant conditions in the original
dataset. Labels without "PR" or "RR" do not contain a secondary
predicate. 

| Pseudo-Resultative Verb | Resultative Verb |
|-------------------------|------------------|
| PV-NoPrt-PR             | RV-NoPrt-RR      |
| PV-Prt1-PR              | RV-Prt1-RR       |
| PV-Prt2-PR              | RV-Prt2-RR       |
| PV-DP                   | RV-DP            |
| PV-Prt1                 | RV-Prt1          |
| PV-Prt2                 | RV-Prt2          |

## Key:

| Abbreviation | Meaning                               |
|--------------|---------------------------------------|
| PV           | Particle Verb                         |
| NoPrt        | No particle                           |
| PR           | Pseudo-resultative                    |
| RR           | Resultative                           |
| Prt1         | Particle in 1st position, pre-object  |
| Prt2         | Particle in 2nd position, post-object |
| DP           | Determiner Phrase (object)            |

## Example Sentences:

Pseudo-resultative (licensing) Verbs:

a.  In one minute, Jane braided the ribbons.\
b.  In one minute, Jane braided up the ribbons.\
c.  In one minute, Jane braided the ribbons up.\
d.  In one minute, Jane braided the ribbons tight.\
e.  In one minute, Jane braided up the ribbons tight.\
f.  In one minute, Jane braided the ribbons up tight.

Resultative (licensing) Verbs:

a.  In ten minutes, Mary smoothed the ribbons.\
b.  In ten minutes, Mary smoothed out the ribbons.\
c.  In ten minutes, Mary smoothed the ribbons out.\
d.  In ten minutes, Mary smoothed the ribbons flat.\
e.  In ten minutes, Mary smoothed out the ribbons flat.\
f.  In ten minutes, Mary smoothed the ribbons out flat.

## Variables

| Column | Variable                          |
|--------|-----------------------------------|
| 1      | trial number (overall)            |
| 2      | participant number                |
| 3      | trial start time (Unix timestamp) |
| 4      | trial end time (Unix timestamp)   |
| 5      | condition names                   |
| 6      | condition group                   |
| 7      | item number                       |
| 8      | likert rating (1-7)               |
| 9      | stimulus list number              |
