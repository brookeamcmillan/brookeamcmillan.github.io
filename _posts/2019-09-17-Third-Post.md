
# 16 Boolean Operators

1. Logical True

The output value is always true, regardless of the input value of p

| P        | T         |
| ---      | ---       |
| T        | T         |
| F        | T         |

2. Logical False

The output value is never true: that is, always false, regardless of the input value of p

| P        | F         |
| ---      | ---       |
| T        | F         |
| F        | F         |

3. Logical Identity

Operation on one logical value p, for which the output value remains p

| P        | P         |
| ---      | ---       |
| T        | T         |
| F        | F         |

4. Logical Negation

The value of true if its operand is false and a value of false if its operand is true

| P        | ¬P        |
| ---      | ---       |
| T        | F         |
| F        | T         |


 1.	Logical NOR              (F F F T)(p, q)	(  NOR ) Operator: p ↓ q, Xpq	
 2.	Converse nonimplication  (F F T F)(p, q)	(  ↚	 ) Operator: p ↚ q, Mpq	
 3.	Negation                 (F F T T)(p, q)	(¬p, ~p) Operator: ¬p, Np, Fpq
 4.	Material nonimplication  (F T F F)(p, q)	(  ↛	 ) Operator: p ↛ q, Lpq	
 5.	Negation                 (F T F T)(p, q)	(¬q, ~q) Operator: ¬q, Nq, Gpq	
 6.	Exclusive disjunction    (F T T F)(p, q)	( XOR )  Operator: p ⊕ q, Jpq	
 7.	Logical NAND             (F T T T)(p, q)	( NAND)	 Operator: p ↑ q, Dpq	
 8.	Logical conjunction      (T F F F)(p, q)	( AND )  Operator: p ∧ q, Kpq	
 9. Logical biconditional    (T F F T)(p, q)	( XNOR)	 Operator: p If and only if q, Epq	
10. Projection function      (T F T F)(p, q)	(  q	)  Operator: q, Hpq	
11. Material implication     (T F T T)(p, q)	(p → q)	 Operator: if p then q, Cpq	
12. Projection function      (T T F F)(p, q)	(  p  )  Operator: p, Ipq	
13. Converse implication     (T T F T)(p, q)	(p ← q)  Operator: p if q, Bpq	
14. Logical disjunction      (T T T F)(p, q)	( OR)    Operator: p ∨ q, Apq	
15. Tautology                (T T T T)(p, q)	( ⊤ )	   Operator: true, Vpq	
16.	Contradiction            (F F F F)(p, q)	( ⊥	)    Operator: false, Opq	

