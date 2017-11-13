## rake_nltk.py

Forked from https://github.com/sujitpal/mlia-examples/blob/master/src/salary_pred/rake_nltk.py specifically to update that code ...

* SOURCE:
  * http://sujitpal.blogspot.ca/2013/03/implementing-rake-algorithm-with-nltk.html
  * https://github.com/sujitpal/mlia-examples/blob/master/src/salary_pred/rake_nltk.py
  * [Adapted by author Sujit Pal from: https://github.com/aneesha/RAKE | https://github.com/aneesha/RAKE/blob/master/rake.py]

* Additionally modified by [Victoria Stuart](https://github.com/victoriastuart) on Nov 13, 2017:
  * Py2 --> Py3
  * other edits ...

* Input:
```
text1 = "Compatibility of systems of linear constraints over the set of natural numbers. Criteria of compatibility of a system of linear Diophantine equations, strict inequations, and nonstrict inequations are considered. Upper bounds for components of a minimal set of solutions and algorithms of construction of minimal generating sets of solutions for all types of systems are given. These criteria and the corresponding algorithms for constructing a minimal supporting set of solutions can be used in solving all the considered types of systems and systems of mixed types."
```
* Output (print statements included, to follow that output):
```
(py35) [victoria@victoria nltk-rake]$ P nltk-rake-py3.py 
[P: python]

text1:
 Compatibility of systems of linear constraints over the set of natural numbers. Criteria of compatibility of a system of linear Diophantine equations, strict inequations, and nonstrict inequations are considered. Upper bounds for components of a minimal set of solutions and algorithms of construction of minimal generating sets of solutions for all types of systems are given. These criteria and the corresponding algorithms for constructing a minimal supporting set of solutions can be used in solving all the considered types of systems and systems of mixed types. 


phrase list:
 [['compatibility'], ['systems'], ['linear', 'constraints'], ['set'], ['natural', 'numbers'], ['criteria'], ['compatibility'], ['system'], ['linear', 'diophantine', 'equations'], ['strict', 'inequations'], ['nonstrict', 'inequations'], ['considered'], ['upper', 'bounds'], ['components'], ['minimal', 'set'], ['solutions'], ['algorithms'], ['construction'], ['minimal', 'generating', 'sets'], ['solutions'], ['types'], ['systems'], ['given'], ['criteria'], ['corresponding', 'algorithms'], ['constructing'], ['minimal', 'supporting', 'set'], ['solutions'], ['used'], ['solving'], ['considered', 'types'], ['systems'], ['systems'], ['mixed', 'types']] 

----------
Phrase 1:
phrase: ['compatibility']
 * cumulative word freq for word "compatibility": 1
   word degree[word] (cumulative): 1
----------
Phrase 2:
phrase: ['systems']
 * cumulative word freq for word "systems": 1
   word degree[word] (cumulative): 1
----------
Phrase 3:
phrase: ['linear', 'constraints']
 * cumulative word freq for word "linear": 1
   word degree[word] (cumulative): 2
 * cumulative word freq for word "constraints": 1
   word degree[word] (cumulative): 2
----------
Phrase 4:
phrase: ['set']
 * cumulative word freq for word "set": 1
   word degree[word] (cumulative): 1
----------
Phrase 5:
phrase: ['natural', 'numbers']
 * cumulative word freq for word "natural": 1
   word degree[word] (cumulative): 2
 * cumulative word freq for word "numbers": 1
   word degree[word] (cumulative): 2
----------
Phrase 6:
phrase: ['criteria']
 * cumulative word freq for word "criteria": 1
   word degree[word] (cumulative): 1
----------
Phrase 7:
phrase: ['compatibility']
 * cumulative word freq for word "compatibility": 2
   word degree[word] (cumulative): 2
----------
Phrase 8:
phrase: ['system']
 * cumulative word freq for word "system": 1
   word degree[word] (cumulative): 1
----------
Phrase 9:
phrase: ['linear', 'diophantine', 'equations']
 * cumulative word freq for word "linear": 2
   word degree[word] (cumulative): 5
 * cumulative word freq for word "diophantine": 1
   word degree[word] (cumulative): 3
 * cumulative word freq for word "equations": 1
   word degree[word] (cumulative): 3
----------
Phrase 10:
phrase: ['strict', 'inequations']
 * cumulative word freq for word "strict": 1
   word degree[word] (cumulative): 2
 * cumulative word freq for word "inequations": 1
   word degree[word] (cumulative): 2
----------
Phrase 11:
phrase: ['nonstrict', 'inequations']
 * cumulative word freq for word "nonstrict": 1
   word degree[word] (cumulative): 2
 * cumulative word freq for word "inequations": 2
   word degree[word] (cumulative): 4
----------
Phrase 12:
phrase: ['considered']
 * cumulative word freq for word "considered": 1
   word degree[word] (cumulative): 1
----------
Phrase 13:
phrase: ['upper', 'bounds']
 * cumulative word freq for word "upper": 1
   word degree[word] (cumulative): 2
 * cumulative word freq for word "bounds": 1
   word degree[word] (cumulative): 2
----------
Phrase 14:
phrase: ['components']
 * cumulative word freq for word "components": 1
   word degree[word] (cumulative): 1
----------
Phrase 15:
phrase: ['minimal', 'set']
 * cumulative word freq for word "minimal": 1
   word degree[word] (cumulative): 2
 * cumulative word freq for word "set": 2
   word degree[word] (cumulative): 3
----------
Phrase 16:
phrase: ['solutions']
 * cumulative word freq for word "solutions": 1
   word degree[word] (cumulative): 1
----------
Phrase 17:
phrase: ['algorithms']
 * cumulative word freq for word "algorithms": 1
   word degree[word] (cumulative): 1
----------
Phrase 18:
phrase: ['construction']
 * cumulative word freq for word "construction": 1
   word degree[word] (cumulative): 1
----------
Phrase 19:
phrase: ['minimal', 'generating', 'sets']
 * cumulative word freq for word "minimal": 2
   word degree[word] (cumulative): 5
 * cumulative word freq for word "generating": 1
   word degree[word] (cumulative): 3
 * cumulative word freq for word "sets": 1
   word degree[word] (cumulative): 3
----------
Phrase 20:
phrase: ['solutions']
 * cumulative word freq for word "solutions": 2
   word degree[word] (cumulative): 2
----------
Phrase 21:
phrase: ['types']
 * cumulative word freq for word "types": 1
   word degree[word] (cumulative): 1
----------
Phrase 22:
phrase: ['systems']
 * cumulative word freq for word "systems": 2
   word degree[word] (cumulative): 2
----------
Phrase 23:
phrase: ['given']
 * cumulative word freq for word "given": 1
   word degree[word] (cumulative): 1
----------
Phrase 24:
phrase: ['criteria']
 * cumulative word freq for word "criteria": 2
   word degree[word] (cumulative): 2
----------
Phrase 25:
phrase: ['corresponding', 'algorithms']
 * cumulative word freq for word "corresponding": 1
   word degree[word] (cumulative): 2
 * cumulative word freq for word "algorithms": 2
   word degree[word] (cumulative): 3
----------
Phrase 26:
phrase: ['constructing']
 * cumulative word freq for word "constructing": 1
   word degree[word] (cumulative): 1
----------
Phrase 27:
phrase: ['minimal', 'supporting', 'set']
 * cumulative word freq for word "minimal": 3
   word degree[word] (cumulative): 8
 * cumulative word freq for word "supporting": 1
   word degree[word] (cumulative): 3
 * cumulative word freq for word "set": 3
   word degree[word] (cumulative): 6
----------
Phrase 28:
phrase: ['solutions']
 * cumulative word freq for word "solutions": 3
   word degree[word] (cumulative): 3
----------
Phrase 29:
phrase: ['used']
 * cumulative word freq for word "used": 1
   word degree[word] (cumulative): 1
----------
Phrase 30:
phrase: ['solving']
 * cumulative word freq for word "solving": 1
   word degree[word] (cumulative): 1
----------
Phrase 31:
phrase: ['considered', 'types']
 * cumulative word freq for word "considered": 2
   word degree[word] (cumulative): 3
 * cumulative word freq for word "types": 2
   word degree[word] (cumulative): 3
----------
Phrase 32:
phrase: ['systems']
 * cumulative word freq for word "systems": 3
   word degree[word] (cumulative): 3
----------
Phrase 33:
phrase: ['systems']
 * cumulative word freq for word "systems": 4
   word degree[word] (cumulative): 4
----------
Phrase 34:
phrase: ['mixed', 'types']
 * cumulative word freq for word "mixed": 1
   word degree[word] (cumulative): 2
 * cumulative word freq for word "types": 3
   word degree[word] (cumulative): 5

[('minimal generating sets', 8.666666666666666), ('linear diophantine equations', 8.5), ('minimal supporting set', 7.666666666666666), ('minimal set', 4.666666666666666), ('linear constraints', 4.5), ('nonstrict inequations', 4.0), ('upper bounds', 4.0), ('strict inequations', 4.0), ('natural numbers', 4.0), ('mixed types', 3.666666666666667), ('corresponding algorithms', 3.5), ('considered types', 3.166666666666667), ('set', 2.0), ('types', 1.6666666666666667), ('considered', 1.5), ('algorithms', 1.5), ('solutions', 1.0), ('components', 1.0), ('constructing', 1.0), ('compatibility', 1.0), ('given', 1.0), ('systems', 1.0), ('system', 1.0), ('criteria', 1.0), ('construction', 1.0), ('solving', 1.0), ('used', 1.0)]

(py35) [victoria@victoria nltk-rake]$ 

# ----------------------------------------------------------------------------
# Calculation of score for top-ranked phrase 'minimal generating sets':
# [see, e.g.: https://codelingo.wordpress.com/2017/05/26/keyword-extraction-using-rake/]

minimal:
         freq: 1 + 1 + 1
       degree: 2 + 3 + 3
  score (d/f): (2 + 3 + 3) / (1 + 1 + 1) = 8/3 =  2.6667

generating:
         freq: 1
       degree: 3
  score (d/f): 3 / 1  = 3

sets:
         freq: 1
       degree: 3
  score (d/f): 3 / 1 = 3

score('minimal generating sets') = 2.6667 + 3 + 3 = 8.6667

```
