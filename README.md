# CNF-DNF-Convertor
Java code to convert every logical formula to conjunctive normal form and disjunctive normal form

## Java code
Use simple names for variables like p, q, r.
#####
Use the following characters for operators
* and: &
* or: |
* negation: ~
* implication: ->
* equivalence: <->

## Remember to put parentheses around each formula
Correct samples: ((p->q)&p) - (~(p->q))|(p&(~q))
#####
Wrong samples: (p->q)&p - ~(p->q) - p&(~q) - (p&~q)
