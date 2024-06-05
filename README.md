# Overview

<img src="photo-wzr.jpg" alt="photo" width="200"/>

I am Zhuoran Wei, a master's student at the Institute of Parallel and Distributed Systems (IPADS), Shanghai Jiao Tong University.
Currently, I am working on the application of formal verification in database systems under the supervision of [Prof. Zhaoguo Wang](https://ipads.se.sjtu.edu.cn/pub/members/zhaoguo_wang).

# Projects

## SQLSolver

[Github repo](https://github.com/SJTU-IPADS/SQLSolver)

SQLSolver is an automated prover for the equivalence of SQL queries.
Compared to prior provers, it can support more SQL features and has a stronger verification capability:
for example, SQLSolver can verify the equivalence of all 232 query pairs from the Calcite test suite, while only 121 of them can be proved by prior provers.
I contributed to the implementation and refactoring of SQLSolver.

## SQLRuleGen

SQLRuleGen automatically extracts rewrite rules from equivalent SQL queries.
It does not need to enumerate rules in an exhaustive manner like prior work (e.g. WeTune).
I was responsible for the implementation of SQLRuleGen.

## AtomFS

AtomFS is the first formally-verified concurrent file system with fine-grained locking.
I took part in writing liveness proof in Coq.

# Education

- 2022.09 - now, M.S., School of Software, Shanghai Jiao Tong University, Advisor: Zhaoguo Wang
- 2017.09 - 2021.06, B.S., School of Software, Shanghai Jiao Tong University

# Contact

Email: zrway43@gmail.com
