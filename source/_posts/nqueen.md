---
title: N-Queens Problem
tags:
  - Computing Science
categories:
  - Computing Science
date: 2018-04-13 17:27:00  
---

There is usually no use of sharing the reports i write at the university. Most of them are of small scope that deals with a meta programming. i.e writing software to understand software. 

However recently I've been assigned the n-queen problem as part of one course and it can be of interest to a broader audience. It's in a way the perfect problem.
The problem is trivial to understand and a simple to find an algorithm. To make the program run in parallel and get a decent load balancing is tricky and, since there is no exact known mathematical relationship, a time sink. When you're think you're done however the algorithm can be made stupendously hard when considering that all solution's rotation and mirror image is also a solution. That fact can shave of significant time if correctly implemented but requires, understanably, quite the effort.

It's the perfect linear increase in difficulty that can stimulate both the novice and the tenured doctorate in CS alike. It's also a problem with great history, the greeks couldn't get the answer 
to the 8x8 chessboard which is trivila with todays computing power. Many of Computing sciences greates, including Djikstra, worked on the problem and it's still only solved for n up to 27. Improvments in hardware and software will keep push it's boundaries and keep it relevant for decades to come. 

Here is my implementation, it uses MPI for the parallelisation and thus requires an environment for such.
[source code](https://github.com/Johnstedt/N_Queens_Puzzle "Source Code")
[report](https://drive.google.com/file/d/15_rsGAUqpmeamOLt4QXP4LnkEF9JP1Eb/preview "Report")

<html >

  <iframe src="https://drive.google.com/file/d/15_rsGAUqpmeamOLt4QXP4LnkEF9JP1Eb/preview" type="application/pdf" width="900px" height="1000px" style=" margin-left: -100px">
        This browser does not support PDFs. Please download the PDF to view it: <a href="https://drive.google.com/file/d/15_rsGAUqpmeamOLt4QXP4LnkEF9JP1Eb/preview">Download PDF</a>.</p>
    </iframe>

</html>