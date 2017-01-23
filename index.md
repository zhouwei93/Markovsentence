# welcome to markovsentence project!

Markovian-tweets,consume a text file with sentences and produce a tweet with the style of the input text.

## Function:
1. Markov Sentence Generation
2. input several words , can generate sentences in someone's style.

## Details
1. Write source code using C++, the source code is main.cpp 
2. example.txt store the sentence we would like to translate.
3. We can generate the tweet like this:change the snetence in the example.txt, run the code, input two words 
4. After input words, the code will generate a sentence automaticlly in the original sentence's style.

following is the original sentence:
 After one year from the ratification of this article the manufacture, sale,
 
or transportation of intoxicating liquors within, the importation thereof into,

or the exportation thereof from the United States and all territory subject to

the jurisdiction thereof for beverage purposes is hereby prohibited.

input: one year

output:one year from the United States and all territory subject to the Constitution by the Congress.

## how to use it

firstly, write “g++ main.cpp” in the bash field;

secondly, write “./a.out” in the bash field;

after that , it will print “please input prefix 1:” you can input a word then Enter(eg: shall)

then, it will print"please input prefix 2:" to ask you input another word(eg: be) and Enter;

Finally, you can get the sentence witch begin with these two words from out prepared document.



