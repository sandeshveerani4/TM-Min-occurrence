# TM-Min-occurrence
https://turingmachinesimulator.com

name: TM-Min-occurrence
init: q0
accept: qa

q0,a
q1,X,>

q0,b
q2,Y,>

q1,a
q1,a,>

q1,Y
q1,Y,>

q1,X
q1,X,>

q1,_
q5,_,<

q1,b
q2,Y,>

q2,b
q2,b,>

q2,X
q2,X,>

q2,Y
q2,Y,>

q2,_
q3,_,<

q2,a
q1,X,>

q3,Y
q3,Y,<

q3,X
q3,X,<

q3,b
q3,b,<

q3,a
q1,X,>

q3,_
q4,_,>

q4,X
q4,c,>

q4,Y
q4,_,>

q4,_
qa,_,-

q4,a
q4,c,>

q4,b
q4,_,>

q5,Y
q5,c,<

q5,X
q5,_,<

q5,a
q5,_,<

q5,b
q5,c,<

q5,_
qa,_,-
