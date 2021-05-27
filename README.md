# Gray-codes

What is the Gray Code?


The reflected binary code (RBC), also known just as reflected binary (RB) or Gray code after Frank Gray, is an ordering of the binary numeral system such that two successive values differ in only one bit (binary digit).





An n-bit Gray code is a sequence of n-bit strings constructed according to certain rules. For example,


------------------------------------------------------------------------
n = 1: C(1) = ['0','1'].
n = 2: C(2) = ['00','01','11','10'].
n = 3: C(3) = ['000','001','011','010',´110´,´111´,´101´,´100´].

------------------------------------------------------------------------


Find out the construction rules and write a predicate with the following specification:

------------------------------------------------------------------------

% gray(N,C) :- C is the N-bit Gray code

------------------------------------------------------------------------
