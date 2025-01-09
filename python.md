# PostgreSQL Interview Questions & Answers

## Questions

| No. | Questions                                                                                                                                                                                                                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|     | **Behavioural Questions**                                                                                                                                                                                                            |
| 1   | [What are the _key features_ of _Python_?](#what-are-the-key-features-of-python)                                                                                                                                                     |
| 2   | [How is _Python_ executed?](#how-is-python-executed)                                                                                                                                                                                 |
| 3   | [What is _PEP 8_ and why is it important?](#what-is-pep-8-and-why-is-it-important)                                                                                                                                                   |
| 4   | [How is memory allocation and garbage collection handled in _Python_?](#how-is-memory-allocation-and-garbage-collection-handled-in-python)                                                                                           |
| 5   | [What are the _built-in data types_ in _Python_?](#what-are-the-built-in-data-types-in-python)                                                                                                                                       |
| 6   | [Explain the difference between a _mutable_ and _immutable_ object.](#explain-the-difference-between-a-mutable-and-immutable-object)                                                                                                 |
| 7   | [How do you _handle exceptions_ in _Python_?](#how-do-you-handle-exceptions-in-python)                                                                                                                                               |
| 8   | [What is the difference between _list_ and _tuple_?](#what-is-the-difference-between-list-and-tuple)                                                                                                                                 |
| 9   | [How do you create a _dictionary_ in _Python_?](#how-do-you-create-a-dictionary-in-python)                                                                                                                                           |
| 10  | [What is the difference between _==_ and _is operator_ in _Python_?](#what-is-the-difference-between--and-is-operator-in-python)                                                                                                     |
| 11  | [How does a _Python function_ work?](#how-does-a-python-function-work)                                                                                                                                                               |
| 12  | [What is a _lambda function_, and where would you use it?](#what-is-a-lambda-function-and-where-would-you-use-it)                                                                                                                    |
| 13  | [Explain _\*args_ and _\*\*kwargs_ in _Python_.](#explain-args-and-kwargs-in-python)                                                                                                                                                 |
| 14  | [What are _decorators_ in _Python_?](#what-are-decorators-in-python)                                                                                                                                                                 |
| 15  | [How can you create a _module_ in _Python_?](#how-can-you-create-a-module-in-python)                                                                                                                                                 |
| 16  | [Given two arrays, write a Python function to return the intersection of the two?](#given-two-arrays-write-a-python-function-to-return-the-intersection-of-the-two)                                                                  |
| 17  | [Given an array, find all the duplicates in this array?](#given-an-array-find-all-the-duplicates-in-this-array)                                                                                                                      |
| 18  | [Given an integer array, return the maximum product of any three numbers in the array?](#given-an-integer-array-return-the-maximum-product-of-any-three-numbers-in-the-array)                                                        |
| 19  | [Given an integer array, find the sum of the largest contiguous subarray within the array?](#given-an-integer-array-find-the-sum-of-the-largest-contiguous-subarray-within-the-array)                                                |
| 20  | [Define tuples and lists in Python. What are the major differences between them?](#define-tuples-and-lists-in-python-what-are-the-major-differences-between-them)                                                                    |
| 21  | [Compute the Euclidean Distance Between Two Series?](#compute-the-euclidean-distance-between-two-series)                                                                                                                             |
| 22  | [Given an integer n and an integer K, output a list of all the combination of k numbers chosen from 1 to n.](#given-an-integer-n-and-an-integer-k-output-a-list-of-all-the-combination-of-k-numbers-chosen-from-1-to-n)              |
| 23  | [Write a function to generate N samples from a normal distribution and plot them on the histogram.](#write-a-function-to-generate-n-samples-from-a-normal-distribution-and-plot-them-on-the-histogram)                               |
| 24  | [What is the difference between apply and applymap function in pandas?](#what-is-the-difference-between-apply-and-applymap-function-in-pandas)                                                                                       |
| 25  | [Given a string, return the first recurring character in it, or “None” if there is no recurring character.](#given-a-string-return-the-first-recurring-character-in-it-or-none-if-there-is-no-recurring-character)                   |
| 26  | [Given a positive integer X, return an integer that is a factorial of X using recursion.](#given-a-positive-integer-x-return-an-integer-that-is-a-factorial-of-x-using-recursion)                                                    |
| 27  | [Given an m-by-n matrix with positive integers, determine the length of the longest increasing path.](#given-an-m-by-n-matrix-with-positive-integers-determine-the-length-of-the-longest-increasing-path)                            |
| 28  | [Explain what Flask is and its benefits.](#explain-what-flask-is-and-its-benefits)                                                                                                                                                   |
| 29  | [What is the difference between lists, arrays, and sets in Python, and when should you use each of them?](#what-is-the-difference-between-lists-arrays-and-sets-in-python-and-when-should-you-use-each-of-them)                      |
| 30  | [Converting an Integer into Decimals](#converting-an-integer-into-decimals)                                                                                                                                                          |
| 31  | [Converting a String of Integers into Decimals](#converting-a-string-of-integers-into-decimals)                                                                                                                                      |
| 32  | [Reversing a String using an Extended Slicing Technique](#reversing-a-string-using-an-extended-slicing-technique)                                                                                                                    |
| 33  | [Counting Vowels in a Given Word](#counting-vowels-in-a-given-word)                                                                                                                                                                  |
| 34  | [Counting Consonants in a Given Word](#counting-consonants-in-a-given-word)                                                                                                                                                          |
| 35  | [Counting the Number of Occurrences of a Character in a String](#counting-the-number-of-occurrences-of-a-character-in-a-string)                                                                                                      |
| 36  | [Writing Fibonacci Series](#writing-fibonacci-series)                                                                                                                                                                                |
| 37  | [Finding the Maximum Number in a List](#finding-the-maximum-number-in-a-list)                                                                                                                                                        |
| 38  | [Finding the Minimum Number in a List](#finding-the-minimum-number-in-a-list)                                                                                                                                                        |
| 39  | [Finding the Middle Element in a List](#finding-the-middle-element-in-a-list)                                                                                                                                                        |
| 40  | [Converting a List into a String](#converting-a-list-into-a-string)                                                                                                                                                                  |
| 41  | [Adding Two List Elements Together](#adding-two-list-elements-together)                                                                                                                                                              |
| 42  | [Comparing Two Strings for Anagrams](#comparing-two-strings-for-anagrams)                                                                                                                                                            |
| 43  | [Checking for Palindrome Using Extended Slicing Technique](#checking-for-palindrome-using-extended-slicing-technique)                                                                                                                |
| 44  | [Counting the White Spaces in a String](#counting-the-white-spaces-in-a-string)                                                                                                                                                      |
| 45  | [Counting Digits, Letters, and Spaces in a String](#counting-digits-letters-and-spaces-in-a-string)                                                                                                                                  |
| 46  | [Counting Special Characters in a String](#counting-special-characters-in-a-string)                                                                                                                                                  |
| 47  | [Removing All Whitespace in a String](#removing-all-whitespace-in-a-string)                                                                                                                                                          |
| 48  | [Building a Pyramid in Python](#building-a-pyramid-in-python)                                                                                                                                                                        |
| 49  | [Randomizing the Items of a List in Python](#randomizing-the-items-of-a-list-in-python)                                                                                                                                              |
|     | [Top Python Theoritical Interview Questions and Answers](#top-python-theoritical-interview-questions-and-answers)                                                                                                                    |
| 50  | [Explain Python?](#explain-python)                                                                                                                                                                                                   |
| 51  | [What are the distinct features of Python?](#what-are-the-distinct-features-of-python)                                                                                                                                               |
| 52  | [What is Python path?](#what-is-python-path)                                                                                                                                                                                         |
| 53  | [What are the supported standard data types in Python?](#what-are-the-supported-standard-data-types-in-python)                                                                                                                       |
| 54  | [Define tuples in Python?](#define-tuples-in-python)                                                                                                                                                                                 |
| 55  | [What are the positive and negative indices?](#what-are-the-positive-and-negative-indices)                                                                                                                                           |
| 56  | [What can be the length of the identifier in Python?](#what-can-be-the-length-of-the-identifier-in-python)                                                                                                                           |
| 57  | [Define Pass statement in Python?](#define-pass-statement-in-python)                                                                                                                                                                 |
| 58  | [What are the limitations of Python?](#what-are-the-limitations-of-python)                                                                                                                                                           |
| 59  | [Do runtime errors exist in Python? Give an example?](#do-runtime-errors-exist-in-python-give-an-example)                                                                                                                            |
| 60  | [Why do we need a break in Python?](#why-do-we-need-a-break-in-python)                                                                                                                                                               |
| 61  | [Why do we need a continue in Python?](#why-do-we-need-a-continue-in-python)                                                                                                                                                         |
| 62  | [Can we use a break and continue together in Python? How?](#can-we-use-a-break-and-continue-together-in-python-how)                                                                                                                  |
| 63  | [Does Python support an intrinsic do-while loop?](#does-python-support-an-intrinsic-do-while-loop)                                                                                                                                   |
| 64  | [How many ways can be applied for applying reverse string?](#how-many-ways-can-be-applied-for-applying-reverse-string)                                                                                                               |
| 65  | [What are the different stages of the Life Cycle of a Thread?](#what-are-the-different-stages-of-the-life-cycle-of-a-thread)                                                                                                         |
| 66  | [What is the purpose of relational operators in Python?](#what-is-the-purpose-of-relational-operators-in-python)                                                                                                                     |
| 67  | [What are assignment operators in Python?](#what-are-assignment-operators-in-python)                                                                                                                                                 |
| 68  | [Why do we need membership operators in Python?](#why-do-we-need-membership-operators-in-python)                                                                                                                                     |
| 69  | [How are identity operators different than the membership operators?](#how-are-identity-operators-different-than-the-membership-operators)                                                                                           |
| 70  | [Describe how multithreading is achieved in Python?](#describe-how-multithreading-is-achieved-in-python)                                                                                                                             |
| 71  | [What is Inheritance in Python?](#what-is-inheritance-in-python)                                                                                                                                                                     |
| 72  | [What are the different types of inheritance?](#what-are-the-different-types-of-inheritance)                                                                                                                                         |
| 73  | [Explain memory managed in Python?](#explain-memory-managed-in-python)                                                                                                                                                               |
| 74  | [What are Python decorators?](#what-are-python-decorators)                                                                                                                                                                           |
| 75  | [What do you understand by the process of compilation and linking in Python?](#what-do-you-understand-by-the-process-of-compilation-and-linking-in-python)                                                                           |
| 76  | [What is the map() function used for in Python?](#what-is-the-map-function-used-for-in-python)                                                                                                                                       |
| 77  | [How will you distinguish between NumPy and SciPy?](#how-will-you-distinguish-between-numpy-and-scipy)                                                                                                                               |
| 78  | [What is the lambda function?](#what-is-the-lambda-function)                                                                                                                                                                         |
| 80  | [Differentiate between list and tuple?](#differentiate-between-list-and-tuple)                                                                                                                                                       |
| 81  | [What is the // operator? What is its use?](#what-is-the--operator-what-is-its-use)                                                                                                                                                  |
| 82  | [What is monkey patching in Python?](#what-is-monkey-patching-in-python)                                                                                                                                                             |
| 83  | [What is the split function used for?](#what-is-the-split-function-used-for)                                                                                                                                                         |
| 84  | [Explain the Dogpile effect?](#explain-the-dogpile-effect)                                                                                                                                                                           |
| 85  | [What is a pass in Python?](#what-is-a-pass-in-python)                                                                                                                                                                               |
| 86  | [Define slicing in Python.](#define-slicing-in-python)                                                                                                                                                                               |
| 87  | [What are docstring?](#what-are-docstring)                                                                                                                                                                                           |
| 88  | [What is [::-1] used for?](#what-is--1-used-for)                                                                                                                                                                                     |
| 89  | [Define Python Iterators](#define-python-iterators)                                                                                                                                                                                  |
| 90  | [How are comments written in Python?](#how-are-comments-written-in-python)                                                                                                                                                           |
| 91  | [How to capitalize the first letter of string?](#how-to-capitalize-the-first-letter-of-string)                                                                                                                                       |
| 92  | [What is, not and in operators?](#what-is-not-and-in-operators)                                                                                                                                                                      |
| 93  | [How are files deleted in Python?](#how-are-files-deleted-in-python)                                                                                                                                                                 |
| 94  | [Does Python support multiple inheritances?](#does-python-support-multiple-inheritances)                                                                                                                                             |
| 95  | [What does the method object() do?](#what-does-the-method-object-do)                                                                                                                                                                 |
| 96  | [What is pep 8?](#what-is-pep-8)                                                                                                                                                                                                     |
| 97  | [What is namespace in Python?](#what-is-namespace-in-python)                                                                                                                                                                         |
| 98  | [Is indentation necessary in Python?](#is-indentation-necessary-in-python)                                                                                                                                                           |
| 99  | [Explain 'Everything in Python is an object'.](#explain-everything-in-python-is-an-object)                                                                                                                                           |
| 100 | [What is mutable and immutable objects/data types in Python?](#what-is-mutable-and-immutable-objectsdata-types-in-python)                                                                                                            |
| 101 | [What is the difference between list and tuples in Python?](#what-is-the-difference-between-list-and-tuples-in-python)                                                                                                               |
| 102 | [How is memory managed in Python?](#how-is-memory-managed-in-python)                                                                                                                                                                 |
| 103 | [Explain exception handling in Python.](#explain-exception-handling-in-python)                                                                                                                                                       |
| 104 | [Explain some changes in Python 3.8.](#explain-some-changes-in-python-38)                                                                                                                                                            |
| 105 | [Explain Python Design Patterns.](#explain-python-design-patterns)                                                                                                                                                                   |
| 106 | [How would you load a large data file in Python?](#how-would-you-load-a-large-data-file-in-python)                                                                                                                                   |
| 107 | [Explain Generators and use case of it.](#explain-generators-and-use-case-of-it)                                                                                                                                                     |
| 108 | [Is there a sequence in defining exceptions in except block for exception handling?](#is-there-a-sequence-in-defining-exceptions-in-except-block-for-exception-handling)                                                             |
| 109 | [Explain Closures in Python.](#explain-closures-in-python)                                                                                                                                                                           |
| 110 | [How to make a chain of function decorators?](#how-to-make-a-chain-of-function-decorators)                                                                                                                                           |
| 111 | [Three different ways to fetch every 3rd item of a list.](#three-different-ways-to-fetch-every-3rd-item-of-a-list)                                                                                                                   |
| 112 | [What is MRO in Python? How does it work?](#what-is-mro-in-python-how-does-it-work)                                                                                                                                                  |
| 113 | [What is monkey patching? How to use it in Python?](#what-is-monkey-patching-how-to-use-it-in-python)                                                                                                                                |
| 114 | [What is the difference between staticmethod and classmethod?](#what-is-the-difference-between-staticmethod-and-classmethod)                                                                                                         |
| 115 | [What is the purpose of the single underscore “\_” variable in Python?](#what-is-the-purpose-of-the-single-underscore--variable-in-python)                                                                                           |
| 116 | [What's the difference between a Python module and a Python package?](#whats-the-difference-between-a-python-module-and-a-python-package)                                                                                            |
| 117 | [What is a global interpreter lock (GIL)?](#what-is-a-global-interpreter-lock-gil)                                                                                                                                                   |
| 118 | [Which is faster, list comprehension or for loop?](#which-is-faster-list-comprehension-or-for-loop)                                                                                                                                  |
| 119 | [Explain Singleton class and its uses?](#explain-singleton-class-and-its-uses)                                                                                                                                                       |
| 120 | [Explain Meta Classes in Python.](#explain-meta-classes-in-python)                                                                                                                                                                   |
| 121 | [Best way to concatenate n number of strings together into one.](#best-way-to-concatenate-n-number-of-strings-together-into-one)                                                                                                     |
| 122 | [Explain briefly about map() and lambda() functions.](#explain-briefly-about-map-and-lambda-functions)                                                                                                                               |
| 123 | [Explain Abstract Classes and its uses.](#explain-abstract-classes-and-its-uses)                                                                                                                                                     |
| 124 | [Explain object creation process in detail. Which method is called first?](#explain-object-creation-process-in-detail-which-method-is-called-first)                                                                                  |
| 125 | [Difference between a class variable and instance variable.](#difference-between-a-class-variable-and-instance-variable)                                                                                                             |
| 126 | [Explain the concept behind dictionary in Python.](#explain-the-concept-behind-dictionary-in-python)                                                                                                                                 |
| 127 | [Difference between an expression and a statement in Python.](#difference-between-an-expression-and-a-statement-in-python)                                                                                                           |
| 128 | [Explain threading in Python.](#explain-threading-in-python)                                                                                                                                                                         |
| 129 | [Can set have lists as elements?](#can-set-have-lists-as-elements)                                                                                                                                                                   |
| 130 | [Is method overloading possible in Python?](#is-method-overloading-possible-in-python)                                                                                                                                               |
| 131 | [Explain inheritance in Python.](#explain-inheritance-in-python)                                                                                                                                                                     |
| 132 | [Explain method resolution order for multiple inheritance.](#explain-method-resolution-order-for-multiple-inheritance)                                                                                                               |
| 133 | [What can be used as keys in a dictionary?](#what-can-be-used-as-keys-in-a-dictionary)                                                                                                                                               |
| 134 | [Explain shallow and deep copy in Python.](#explain-shallow-and-deep-copy-in-python)                                                                                                                                                 |
| 135 | [Why does Python generate a .pyc file even when it is an interpreted language?](#why-does-python-generate-a-pyc-file-even-when-it-is-an-interpreted-language)                                                                        |
| 136 | [How private variables are declared in Python?](#how-private-variables-are-declared-in-python)                                                                                                                                       |
| 137 | [Difference between an array and list.](#difference-between-an-array-and-list)                                                                                                                                                       |
| 138 | [What is an iterator? How is an iterator different from a generator?](#what-is-an-iterator-how-is-an-iterator-different-from-a-generator)                                                                                            |
| 139 | [How do you define a dict where several keys have the same value?](#how-do-you-define-a-dict-where-several-keys-have-the-same-value)                                                                                                 |
| 140 | [What are the different types of namespaces in Python?](#what-are-the-different-types-of-namespaces-in-python)                                                                                                                       |
| 141 | [How can you access an attribute of the parent class bypassing the attribute with the same name in derived class?](#how-can-you-access-an-attribute-of-the-parent-class-bypassing-the-attribute-with-the-same-name-in-derived-class) |
| 142 | [Evaluation of boolean expressions.](#evaluation-of-boolean-expressions)                                                                                                                                                             |
| 143 | [Difference between multiprocessing and multithreading.](#difference-between-multiprocessing-and-multithreading)                                                                                                                     |
| 144 | [How to merge two dictionaries together?](#how-to-merge-two-dictionaries-together)                                                                                                                                                   |
| 145 | [Explain the below code.](#explain-the-below-code)                                                                                                                                                                                   |
| 146 | [Example filter with lambda expression.](#example-filter-with-lambda-expression)                                                                                                                                                     |
| 147 | [Explain context managers.](#explain-context-managers)                                                                                                                                                                               |
| 148 | [What is Python? List some popular applications of Python in the world of technology.](#what-is-python-list-some-popular-applications-of-python-in-the-world-of-technology)                                                          |
| 149 | [What are the benefits of using Python language as a tool in the present scenario?](#what-are-the-benefits-of-using-python-language-as-a-tool-in-the-present-scenario)                                                               |
| 150 | [Is Python a compiled language or an interpreted language?](#is-python-a-compiled-language-or-an-interpreted-language)                                                                                                               |
| 151 | [What does the ‘#’ symbol do in Python?](#what-does-the-symbol-do-in-python)                                                                                                                                                         |
| 152 | [What is the difference between a Mutable datatype and an Immutable data type?](#what-is-the-difference-between-a-mutable-datatype-and-an-immutable-data-type)                                                                       |
| 153 | [How are arguments passed by value or by reference in Python?](#how-are-arguments-passed-by-value-or-by-reference-in-python)                                                                                                         |
| 154 | [What is the difference between a Set and Dictionary?](#what-is-the-difference-between-a-set-and-dictionary)                                                                                                                         |
| 155 | [What is List Comprehension? Give an Example.](#what-is-list-comprehension-give-an-example)                                                                                                                                          |
| 156 | [What is a lambda function?](#what-is-a-lambda-function)                                                                                                                                                                             |
| 157 | [What is a pass in Python?](#what-is-a-pass-in-python)                                                                                                                                                                               |
| 158 | [What is the difference between / and // in Python?](#what-is-the-difference-between--and--in-python)                                                                                                                                |
| 159 | [How is Exceptional handling done in Python?](#how-is-exceptional-handling-done-in-python)                                                                                                                                           |
| 160 | [What is swapcase function in Python?](#what-is-swapcase-function-in-python)                                                                                                                                                         |
| 161 | [Can we Pass a function as an argument in Python?](#can-we-pass-a-function-as-an-argument-in-python)                                                                                                                                 |
| 162 | [What are \*args and \*\*kwargs?](#what-are-args-and-kwargs)                                                                                                                                                                         |
| 163 | [Is Indentation Required in Python?](#is-indentation-required-in-python)                                                                                                                                                             |
| 164 | [What is Scope in Python?](#what-is-scope-in-python)                                                                                                                                                                                 |
| 165 | [What is docstring in Python?](#what-is-docstring-in-python)                                                                                                                                                                         |
| 166 | [What is a dynamically typed language?](#what-is-a-dynamically-typed-language)                                                                                                                                                       |
| 167 | [What is a break, continue, and pass in Python?](#what-is-a-break-continue-and-pass-in-python)                                                                                                                                       |
| 168 | [What are Built-in data types in Python?](#what-are-built-in-data-types-in-python)                                                                                                                                                   |
| 169 | [How do you floor a number in Python?](#how-do-you-floor-a-number-in-python)                                                                                                                                                         |
| 170 | [What is the difference between xrange and range functions?](#what-is-the-difference-between-xrange-and-range-functions)                                                                                                             |
| 171 | [What is Dictionary Comprehension? Give an Example.](#what-is-dictionary-comprehension-give-an-example)                                                                                                                              |
| 172 | [Is Tuple Comprehension? If yes, how, and if not why?](#is-tuple-comprehension-if-yes-how-and-if-not-why)                                                                                                                            |
| 173 | [Differentiate between List and Tuple.](#differentiate-between-list-and-tuple)                                                                                                                                                       |
| 174 | [What is the difference between a shallow copy and a deep copy?](#what-is-the-difference-between-a-shallow-copy-and-a-deep-copy)                                                                                                     |
| 175 | [Which sorting technique is used by sort() and sorted() functions of Python?](#which-sorting-technique-is-used-by-sort-and-sorted-functions-of-python)                                                                               |
| 176 | [What are Decorators?](#what-are-decorators)                                                                                                                                                                                         |
| 177 | [How do you debug a Python program?](#how-do-you-debug-a-python-program)                                                                                                                                                             |
| 178 | [What are Iterators in Python?](#what-are-iterators-in-python)                                                                                                                                                                       |
| 179 | [What are Generators in Python?](#what-are-generators-in-python)                                                                                                                                                                     |
| 180 | [Does Python support multiple Inheritance?](#does-python-support-multiple-inheritance)                                                                                                                                               |
| 181 | [What is Polymorphism in Python?](#what-is-polymorphism-in-python)                                                                                                                                                                   |
| 182 | [Define encapsulation in Python?](#define-encapsulation-in-python)                                                                                                                                                                   |
| 183 | [How do you do data abstraction in Python?](#how-do-you-do-data-abstraction-in-python)                                                                                                                                               |
| 184 | [How is memory management done in Python?](#how-is-memory-management-done-in-python)                                                                                                                                                 |
| 185 | [How to delete a file using Python?](#how-to-delete-a-file-using-python)                                                                                                                                                             |
| 186 | [What is slicing in Python?](#what-is-slicing-in-python)                                                                                                                                                                             |
| 187 | [What is a namespace in Python?](#what-is-a-namespace-in-python)                                                                                                                                                                     |
| 188 | [What is a zip function?](#what-is-a-zip-function)                                                                                                                                                                                   |
| 189 | [What are Pickling and Unpickling?](#what-are-pickling-and-unpickling)                                                                                                                                                               |
| 190 | [What is monkey patching in Python?](#what-is-monkey-patching-in-python)                                                                                                                                                             |
| 191 | [What is **init**() in Python?](#what-is-init-in-python)                                                                                                                                                                             |
| 192 | [Write a code to display the current time?](#write-a-code-to-display-the-current-time)                                                                                                                                               |
| 193 | [What are Access Specifiers in Python?](#what-are-access-specifiers-in-python)                                                                                                                                                       |
| 194 | [What are unit tests in Python?](#what-are-unit-tests-in-python)                                                                                                                                                                     |
| 195 | [Python Global Interpreter Lock (GIL)?](#python-global-interpreter-lock-gil)                                                                                                                                                         |
| 196 | [What are Function Annotations in Python?](#what-are-function-annotations-in-python)                                                                                                                                                 |
| 197 | [What are Exception Groups in Python?](#what-are-exception-groups-in-python)                                                                                                                                                         |
| 198 | [What is Python Switch Statement?](#what-is-python-switch-statement)                                                                                                                                                                 |
| 199 | [What is Walrus Operator?](#what-is-walrus-operator)                                                                                                                                                                                 |
| 200 | [Difference between for loop and while loop in Python.](#difference-between-for-loop-and-while-loop-in-python)                                                                                                                       |
|     | [NumPy Interview Questions.](#numpy-interview-questions)                                                                                                                                                                             |
| 201 | [What is NumPy?](#what-is-numpy)                                                                                                                                                                                                     |
| 202 | [How do I create a NumPy array?](#how-do-i-create-a-numpy-array)                                                                                                                                                                     |
| 203 | [What are the main features of Numpy?](#what-are-the-main-features-of-numpy)                                                                                                                                                         |
| 204 | [How do you calculate the dot product of two NumPy arrays?](#how-do-you-calculate-the-dot-product-of-two-numpy-arrays)                                                                                                               |
| 205 | [How do I access elements in a NumPy array?](#how-do-i-access-elements-in-a-numpy-array)                                                                                                                                             |
| 206 | [What is the difference between a shallow copy and a deep copy in NumPy?](#what-is-the-difference-between-a-shallow-copy-and-a-deep-copy-in-numpy)                                                                                   |
| 207 | [How do you reshape a NumPy array?](#how-do-you-reshape-a-numpy-array)                                                                                                                                                               |
| 208 | [How to perform element-wise operations on NumPy arrays?](#how-to-perform-element-wise-operations-on-numpy-arrays)                                                                                                                   |
| 209 | [Define the var function in NumPy.](#define-the-var-function-in-numpy)                                                                                                                                                               |
| 210 | [Define the min and max function in NumPy.](#define-the-min-and-max-function-in-numpy)                                                                                                                                               |
| 211 | [How to generate random numbers with NumPy?](#how-to-generate-random-numbers-with-numpy)                                                                                                                                             |
| 212 | [What is the purpose of NumPy in Python?](#what-is-the-purpose-of-numpy-in-python)                                                                                                                                                   |
| 213 | [How can you create a NumPy array from a Python list?](#how-can-you-create-a-numpy-array-from-a-python-list)                                                                                                                         |
| 214 | [How can you access elements in a NumPy array based on specific conditions?](#how-can-you-access-elements-in-a-numpy-array-based-on-specific-conditions)                                                                             |
| 215 | [What are some common data types supported by NumPy?](#what-are-some-common-data-types-supported-by-numpy)                                                                                                                           |
| 216 | [How can you concatenate two NumPy arrays vertically?](#how-can-you-concatenate-two-numpy-arrays-vertically)                                                                                                                         |
| 217 | [What is the significance of the random module in NumPy?](#what-is-the-significance-of-the-random-module-in-numpy)                                                                                                                   |
| 218 | [How can you generate random numbers following a normal distribution using NumPy?](#how-can-you-generate-random-numbers-following-a-normal-distribution-using-numpy)                                                                 |
| 219 | [What is Matrix Inversion in NumPy?](#what-is-matrix-inversion-in-numpy)                                                                                                                                                             |
| 220 | [Define the mean function in NumPy.](#define-the-mean-function-in-numpy)                                                                                                                                                             |
| 220 | [Convert a multidimensional array to 1D array.](#convert-a-multidimensional-array-to-1d-array)                                                                                                                                       |
| 221 | [Write a NumPy code snippet to create an array of zeros.](#write-a-numpy-code-snippet-to-create-an-array-of-zeros)                                                                                                                   |
| 222 | [How can you identify outliers in a NumPy array?](#how-can-you-identify-outliers-in-a-numpy-array)                                                                                                                                   |
| 223 | [How do you remove missing or null values from a NumPy array?](#how-do-you-remove-missing-or-null-values-from-a-numpy-array)                                                                                                         |
| 224 | [What is the difference between slicing and indexing in NumPy?](#what-is-the-difference-between-slicing-and-indexing-in-numpy)                                                                                                       |
| 225 | [How do you compute the Fourier transform of a signal using NumPy?](#how-do-you-compute-the-fourier-transform-of-a-signal-using-numpy)                                                                                               |
| 226 | [How can you create an array with same values.](#how-can-you-create-an-array-with-same-values)                                                                                                                                       |
| 227 | [How can you modify the data type of a NumPy array?](#how-can-you-modify-the-data-type-of-a-numpy-array)                                                                                                                             |
| 228 | [What is a masked array in NumPy.](#what-is-a-masked-array-in-numpy)                                                                                                                                                                 |
| 229 | [What are some of the limitations of NumPy.](#what-are-some-of-the-limitations-of-numpy)                                                                                                                                             |
| 230 | [How do you sort a NumPy array in ascending or descending order?](#how-do-you-sort-a-numpy-array-in-ascending-or-descending-order)                                                                                                   |
| 231 | [How to use NumPy with Matplotlib?](#how-to-use-numpy-with-matplotlib)                                                                                                                                                               |
| 232 | [What is the use of diag() square matrix?](#what-is-the-use-of-diag-square-matrix)                                                                                                                                                   |
| 233 | [How are NumPy Arrays better than Lists in Python?](#how-are-numpy-arrays-better-than-lists-in-python)                                                                                                                               |
| 234 | [What is negative indexing in NumPy arrays?](#what-is-negative-indexing-in-numpy-arrays)                                                                                                                                             |
| 235 | [Can you create a plot in NumPy?](#can-you-create-a-plot-in-numpy)                                                                                                                                                                   |
| 236 | [Discuss uses of vstack() and hstack() functions?](#discuss-uses-of-vstack-and-hstack-functions)                                                                                                                                     |
| 237 | [How does NumPy handle numerical exceptions?](#how-does-numpy-handle-numerical-exceptions)                                                                                                                                           |
| 238 | [What is the significance of the random module in NumPy?](#what-is-the-significance-of-the-random-module-in-numpy)                                                                                                                   |
| 239 | [How to Get the eigen values of a matrix.](#how-to-get-the-eigen-values-of-a-matrix)                                                                                                                                                 |
| 240 | [How to Calculate the determinant of a matrix using NumPy?](#how-to-calculate-the-determinant-of-a-matrix-using-numpy)                                                                                                               |
| 241 | [Find a matrix or vector norm using NumPy.](#find-a-matrix-or-vector-norm-using-numpy)                                                                                                                                               |
| 242 | [How to compare two NumPy arrays?](#how-to-compare-two-numpy-arrays)                                                                                                                                                                 |
| 243 | [Calculate the QR decomposition of a given matrix using NumPy.](#calculate-the-qr-decomposition-of-a-given-matrix-using-numpy)                                                                                                       |
| 244 | [How to filter out integers from float NumPy array.](#how-to-filter-out-integers-from-float-numpy-array)                                                                                                                             |
| 245 | [Define a polynomial function.](#define-a-polynomial-function)                                                                                                                                                                       |
| 246 | [What are ndarrays in NumPy?](#what-are-ndarrays-in-numpy)                                                                                                                                                                           |
| 247 | [What are the main features that make NumPy unique.](#what-are-the-main-features-that-make-numpy-unique)                                                                                                                             |
| 248 | [What is the difference between shape and size attributes of NumPy array.](#what-is-the-difference-between-shape-and-size-attributes-of-numpy-array)                                                                                 |
| 249 | [What are some important differences between the standard Python sequences and NumPy arrays?](#what-are-some-important-differences-between-the-standard-python-sequences-and-numpy-arrays)                                           |
| 250 | [What are Universal functions in NumPy?](#what-are-universal-functions-in-numpy)                                                                                                                                                     |
| 251 | [What are the difference between ndarray and array in NumPy.](#what-are-the-difference-between-ndarray-and-array-in-numpy)                                                                                                           |
| 252 | [How would you convert a pandas dataframe into NumPy array.](#how-would-you-convert-a-pandas-dataframe-into-numpy-array)                                                                                                             |
| 253 | [Explain vectorization in NumPy.](#explain-vectorization-in-numpy)                                                                                                                                                                   |
| 254 | [How would you reverse a numpy array?](#how-would-you-reverse-a-numpy-array)                                                                                                                                                         |
| 255 | [How do you remove missing or null values from a NumPy array?](#how-do-you-remove-missing-or-null-values-from-a-numpy-array)                                                                                                         |
| 256 | [What is the difference between slicing and indexing in NumPy?](#what-is-the-difference-between-slicing-and-indexing-in-numpy)                                                                                                       |
| 257 | [How do you create a masked array in NumPy, and what is its purpose?](#how-do-you-create-a-masked-array-in-numpy-and-what-is-its-purpose)                                                                                            |
| 258 | [What are some common techniques for normalizing data in a NumPy array?](#what-are-some-common-techniques-for-normalizing-data-in-a-numpy-array)                                                                                     |
| 259 | [How do you remove missing or null values from a NumPy array?](#how-do-you-remove-missing-or-null-values-from-a-numpy-array)                                                                                                         |
| 261 | [What is difference between NumPy and Pandas?](#what-is-difference-between-numpy-and-pandas)                                                                                                                                         |
| 262 | [Why NumPy is faster than list?](#why-numpy-is-faster-than-list)                                                                                                                                                                     |
| 263 | [How do you check for an empty (zero Element) array?](#how-do-you-check-for-an-empty-zero-element-array)                                                                                                                             |
| 264 | [What is the procedure to count the number of times a given value appears in an array of integers?](#what-is-the-procedure-to-count-the-number-of-times-a-given-value-appears-in-an-array-of-integers)                               |
| 265 | [How can you sort an array in NumPy?](#how-can-you-sort-an-array-in-numpy)                                                                                                                                                           |
| 266 | [How can you find the maximum or minimum value of an array in NumPy?](#how-can-you-find-the-maximum-or-minimum-value-of-an-array-in-numpy)                                                                                           |
| 267 | [How slicing and indexing can be used for data cleaning?](#how-slicing-and-indexing-can-be-used-for-data-cleaning)                                                                                                                   |
| 268 | [What is the difference between using the shape and size attributes of a NumPy array?](#what-is-the-difference-between-using-the-shape-and-size-attributes-of-a-numpy-array)                                                         |
| 269 | [What is a NumPy array and how is it different from a NumPy matrix?](#what-is-a-numpy-array-and-how-is-it-different-from-a-numpy-matrix)                                                                                             |
| 270 | [How can you find the unique elements in an array in NumPy?](#how-can-you-find-the-unique-elements-in-an-array-in-numpy)                                                                                                             |
| 271 | [What is _NumPy_, and why is it important in _Machine Learning_?](#what-is-numpy-and-why-is-it-important-in-machine-learning)                                                                                                        |
| 272 | [Explain how _NumPy arrays_ are different from _Python lists_.](#explain-how-numpy-arrays-are-different-from-python-lists)                                                                                                           |
| 273 | [What are the main _attributes_ of a _NumPy ndarray_?](#what-are-the-main-attributes-of-a-numpy-ndarray)                                                                                                                             |
| 274 | [How do you create a _NumPy array_ from a regular _Python list_?](#how-do-you-create-a-numpy-array-from-a-regular-python-list)                                                                                                       |
| 275 | [Explain the concept of _broadcasting_ in _NumPy_.](#explain-the-concept-of-broadcasting-in-numpy)                                                                                                                                   |
| 276 | [What are the _data types_ supported by _NumPy arrays_?](#what-are-the-data-types-supported-by-numpy-arrays)                                                                                                                         |
| 277 | [How do you inspect the _shape_ and _size_ of a _NumPy array_?](#how-do-you-inspect-the-shape-and-size-of-a-numpy-array)                                                                                                             |
| 278 | [What is the difference between a _deep copy_ and a _shallow copy_ in _NumPy_?](#what-is-the-difference-between-a-deep-copy-and-a-shallow-copy-in-numpy)                                                                             |
| 279 | [How do you perform _element-wise operations_ in _NumPy_?](#how-do-you-perform-element-wise-operations-in-numpy)                                                                                                                     |
| 280 | [What are _universal functions_ (_ufuncs_) in _NumPy_?](#what-are-universal-functions-ufuncs-in-numpy)                                                                                                                               |
| 281 | [How do you perform _matrix multiplication_ using _NumPy_?](#how-do-you-perform-matrix-multiplication-using-numpy)                                                                                                                   |
| 282 | [Explain how to _invert a matrix_ in _NumPy_.](#explain-how-to-invert-a-matrix-in-numpy)                                                                                                                                             |
| 283 | [How do you calculate the _determinant_ of a _matrix_?](#how-do-you-calculate-the-determinant-of-a-matrix)                                                                                                                           |
| 284 | [What is the use of the `_axis_` parameter in _NumPy functions_?](#what-is-the-use-of-the-axis-parameter-in-numpy-functions)                                                                                                         |
| 285 | [How do you _concatenate_ two _arrays_ in _NumPy_?](#how-do-you-concatenate-two-arrays-in-numpy)                                                                                                                                     |
|     | [Selenium Interview Question?](#selenium-interview-question)                                                                                                                                                                         |
| 286 | [What is Selenium?](#what-is-selenium)                                                                                                                                                                                               |
| 287 | [What are the Selenium suite components?](#what-are-the-selenium-suite-components)                                                                                                                                                   |
| 288 | [Mention the advantages of using Selenium as an automation tool.](#mention-the-advantages-of-using-selenium-as-an-automation-tool)                                                                                                   |
| 289 | [What is test automation or automation testing?](#what-is-test-automation-or-automation-testing)                                                                                                                                     |
| 290 | [What are the advantages of automation testing?](#what-are-the-advantages-of-automation-testing)                                                                                                                                     |
| 291 | [What is Selenese? How is it classified?](#what-is-selenese-how-is-it-classified)                                                                                                                                                    |
| 292 | [What is the difference between Selenium 2.0 and Selenium 3.0?](#what-is-the-difference-between-selenium-20-and-selenium-30)                                                                                                         |
| 293 | [What are the testing types supported by Selenium?](#what-are-the-testing-types-supported-by-selenium)                                                                                                                               |
| 294 | [What are the different types of annotations which are used in Selenium?](#what-are-the-different-types-of-annotations-which-are-used-in-selenium)                                                                                   |
| 295 | [What are the types of Web locating strategies?](#what-are-the-types-of-web-locating-strategies)                                                                                                                                     |
| 296 | [What are the types of waits supported by WebDriver?](#what-are-the-types-of-waits-supported-by-webdriver)                                                                                                                           |
| 297 | [Mention the types of navigation commands.](#mention-the-types-of-navigation-commands)                                                                                                                                               |
| 298 | [What is the Difference Between driver.close() and driver.quit() Commands?](#what-is-the-difference-between-driverclose-and-driverquit-commands)                                                                                     |
| 299 | [Differentiate Between Manual Testing and Automated Testing.](#differentiate-between-manual-testing-and-automated-testing)                                                                                                           |
| 300 | [What is an Absolute XPath and Relative XPath?](#what-is-an-absolute-xpath-and-relative-xpath)                                                                                                                                       |
| 301 | [What are the limitations of Selenium testing?](#what-are-the-limitations-of-selenium-testing)                                                                                                                                       |
| 302 | [What is the same-origin policy and how is it handled?](#what-is-the-same-origin-policy-and-how-is-it-handled)                                                                                                                       |
| 303 | [What makes Selenium such a widely used testing tool? Give reasons.](#what-makes-selenium-such-a-widely-used-testing-tool-give-reasons)                                                                                              |
| 304 | [Why is it advised to select Selenium as a testing tool for web applications or systems?](#why-is-it-advised-to-select-selenium-as-a-testing-tool-for-web-applications-or-systems)                                                   |
| 305 | [What is an exception test in Selenium?](#what-is-an-exception-test-in-selenium)                                                                                                                                                     |
| 306 | [How to wait until a web page has been loaded completely in Selenium?](#how-to-wait-until-a-web-page-has-been-loaded-completely-in-selenium)                                                                                         |
| 307 | [What is Selenium WebDriver?](#what-is-selenium-webdriver)                                                                                                                                                                           |
| 308 | [Is Selenium WebDriver a library?](#is-selenium-webdriver-a-library)                                                                                                                                                                 |
| 309 | [Which browsers/drivers are supported by Selenium Webdriver?](#which-browsersdrivers-are-supported-by-selenium-webdriver)                                                                                                            |
| 310 | [Explain Selenium 4 and why it is different from other Selenium versions?](#explain-selenium-4-and-why-it-is-different-from-other-selenium-versions)                                                                                 |
| 311 | [What will happen if I execute this command? driver.get](#what-will-happen-if-i-execute-this-command-driverget)                                                                                                                      |
| 312 | [What is an alternative option to driver.get() method to open an URL in Selenium Web Driver?](#what-is-an-alternative-option-to-driverget-method-to-open-an-url-in-selenium-web-driver)                                              |
| 313 | [Is it possible to test APIs or web services using Selenium Webdriver?](#is-it-possible-to-test-apis-or-web-services-using-selenium-webdriver)                                                                                       |
| 314 | [Mention different ways of locating an element in Selenium?](#mention-different-ways-of-locating-an-element-in-selenium)                                                                                                             |
| 315 | [How can we move to the nth-child element using XPath?](#how-can-we-move-to-the-nth-child-element-using-xpath)                                                                                                                       |
| 316 | [How to type text in an input box using Selenium?](#how-to-type-text-in-an-input-box-using-selenium)                                                                                                                                 |
| 317 | [How to scroll down a page using JavaScript?](#how-to-scroll-down-a-page-using-javascript)                                                                                                                                           |
| 318 | [How to click on a hyperlink in Selenium?](#how-to-click-on-a-hyperlink-in-selenium)                                                                                                                                                 |
| 319 | [How to assert the title of a webpage?](#how-to-assert-the-title-of-a-webpage)                                                                                                                                                       |
| 320 | [How to mouse hover over a web element?](#how-to-mouse-hover-over-a-web-element)                                                                                                                                                     |
| 321 | [How to retrieve CSS properties of an element?](#how-to-retrieve-css-properties-of-an-element)                                                                                                                                       |
| 322 | [What is POM?](#what-is-pom)                                                                                                                                                                                                         |
| 323 | [Can Captcha be automated?](#can-captcha-be-automated)                                                                                                                                                                               |
| 324 | [How does Selenium handle Windows-based pop-ups?](#how-does-selenium-handle-windows-based-pop-ups)                                                                                                                                   |
| 325 | [How to take screenshots in WebDriver?](#how-to-take-screenshots-in-webdriver)                                                                                                                                                       |
| 326 | [Why do testers choose Selenium over QTP?](#why-do-testers-choose-selenium-over-qtp)                                                                                                                                                 |
| 327 | [What are the data-driven framework and keyword-driven framework?](#what-are-the-data-driven-framework-and-keyword-driven-framework)                                                                                                 |
| 328 | [What is the difference between getwindowhandles() and getwindowhandle()?](#what-is-the-difference-between-getwindowhandles-and-getwindowhandle)                                                                                     |
| 329 | [What is a Selenium Maven project?](#what-is-a-selenium-maven-project)                                                                                                                                                               |
| 330 | [What is an Object Repository?](#what-is-an-object-repository)                                                                                                                                                                       |
| 331 | [How do you Locate Elements using XPath?](#how-do-you-locate-elements-using-xpath)                                                                                                                                                   |
| 332 | [How can you Handle Multiple Windows in Selenium?](#how-can-you-handle-multiple-windows-in-selenium)                                                                                                                                 |
| 333 | [Explain Implicit and Explicit waits in Selenium.](#explain-implicit-and-explicit-waits-in-selenium)                                                                                                                                 |
| 334 | [List the Difference Between Close and Quit Commands.](#list-the-difference-between-close-and-quit-commands)                                                                                                                         |
| 335 | [How can we submit a form in Selenium?](#how-can-we-submit-a-form-in-selenium)                                                                                                                                                       |
| 336 | [How to delete cookies in Selenium?](#how-to-delete-cookies-in-selenium)                                                                                                                                                             |
| 337 | [How do you work with frames in Selenium?](#how-do-you-work-with-frames-in-selenium)                                                                                                                                                 |
| 338 | [Discuss the importance of Cross-Browser Testing in Selenium.](#discuss-the-importance-of-cross-browser-testing-in-selenium)                                                                                                         |
| 339 | [What are the challenges of Parallel Execution in Selenium?](#what-are-the-challenges-of-parallel-execution-in-selenium)                                                                                                             |
| 340 | [How to integrate Selenium with Jenkins for Continuous Integration?](#how-to-integrate-selenium-with-jenkins-for-continuous-integration)                                                                                             |
| 341 | [What is the purpose of the Page Factory in Selenium?](#what-is-the-purpose-of-the-page-factory-in-selenium)                                                                                                                         |
| 342 | [Describe the Significance of TestNG in Selenium.](#describe-the-significance-of-testng-in-selenium)                                                                                                                                 |
| 343 | [How do you handle Synchronization in Selenium WebDriver?](#how-do-you-handle-synchronization-in-selenium-webdriver)                                                                                                                 |
| 344 | [What are the Benefits of using Selenium Grid or Selenium Tool Suite?](#what-are-the-benefits-of-using-selenium-grid-or-selenium-tool-suite)                                                                                         |
| 345 | [Explain the Purpose of the 'assert' statement in Selenium.](#explain-the-purpose-of-the-assert-statement-in-selenium)                                                                                                               |
| 346 | [What are the limitations of Selenium testing?](#what-are-the-limitations-of-selenium-testing)                                                                                                                                       |
| 347 | [Differentiate between WebDriver and WebElement.](#differentiate-between-webdriver-and-webelement)                                                                                                                                   |
| 348 | [How do You Perform Database Testing Using Selenium?](#how-do-you-perform-database-testing-using-selenium)                                                                                                                           |
| 349 | [Discuss the Role of the Cucumber Framework in Selenium.](#discuss-the-role-of-the-cucumber-framework-in-selenium)                                                                                                                   |
| 350 | [What are the Considerations for Headless Browser Testing in Selenium?](#what-are-the-considerations-for-headless-browser-testing-in-selenium)                                                                                       |
| 351 | [Examine the Challenges and Solutions of Handling Dynamic Tables.](#examine-the-challenges-and-solutions-of-handling-dynamic-tables)                                                                                                 |
| 352 | [How to Capture Screenshots in Selenium?](#how-to-capture-screenshots-in-selenium)                                                                                                                                                   |
| 353 | [What are the Benefits of Using a Data-Driven Framework in Selenium?](#what-are-the-benefits-of-using-a-data-driven-framework-in-selenium)                                                                                           |
| 354 | [Explain the concept of Object Repository in Selenium.](#explain-the-concept-of-object-repository-in-selenium)                                                                                                                       |
| 355 | [How can you Perform Mouse Hover Actions in Selenium?](#how-can-you-perform-mouse-hover-actions-in-selenium)                                                                                                                         |
|     | [Panda Interview Questions?](#panda-interview-questions)                                                                                                                                                                             |
| 356 | [What are Pandas?](#what-are-pandas)                                                                                                                                                                                                 |
| 357 | [What are the Different Types of Data Structures in Pandas?](#what-are-the-different-types-of-data-structures-in-pandas)                                                                                                             |
| 358 | [List Key Features of Pandas.](#list-key-features-of-pandas)                                                                                                                                                                         |
| 359 | [What is Series in Pandas?](#what-is-series-in-pandas)                                                                                                                                                                               |
| 360 | [What are the Different Ways to Create a Series?](#what-are-the-different-ways-to-create-a-series)                                                                                                                                   |
| 361 | [How can we Create a Copy of the Series?](#how-can-we-create-a-copy-of-the-series)                                                                                                                                                   |
| 362 | [What is a DataFrame in Pandas?](#what-is-a-dataframe-in-pandas)                                                                                                                                                                     |
| 363 | [What are the Different Ways to Create a DataFrame in Pandas?](#what-are-the-different-ways-to-create-a-dataframe-in-pandas)                                                                                                         |
| 364 | [How to Read Data into a DataFrame from a CSV file?](#how-to-read-data-into-a-dataframe-from-a-csv-file)                                                                                                                             |
| 365 | [How to Access the First Few Rows of a DataFrame?](#how-to-access-the-first-few-rows-of-a-dataframe)                                                                                                                                 |
| 366 | [What is Reindexing in Pandas?](#what-is-reindexing-in-pandas)                                                                                                                                                                       |
| 367 | [How to Select a Single Column of a DataFrame?](#how-to-select-a-single-column-of-a-dataframe)                                                                                                                                       |
| 368 | [How to Rename a Column in a DataFrame?](#how-to-rename-a-column-in-a-dataframe)                                                                                                                                                     |
| 369 | [How to Add an Index, Row, or Column to an Existing DataFrame?](#how-to-add-an-index-row-or-column-to-an-existing-dataframe)                                                                                                         |
| 370 | [How to Delete an Index, Row, or Column from an Existing DataFrame?](#how-to-delete-an-index-row-or-column-from-an-existing-dataframe)                                                                                               |
| 371 | [How to Set the Index in a Panda DataFrame?](#how-to-set-the-index-in-a-panda-dataframe)                                                                                                                                             |
| 372 | [How to Reset the Index of a DataFrame?](#how-to-reset-the-index-of-a-dataframe)                                                                                                                                                     |
| 373 | [How to Find the Correlation Using Pandas?](#how-to-find-the-correlation-using-pandas)                                                                                                                                               |
| 374 | [How to Iterate Over a DataFrame in Pandas?](#how-to-iterate-over-a-dataframe-in-pandas)                                                                                                                                             |
| 375 | [What are the Important Conditions to Keep in Mind Before Iterating?](#what-are-the-important-conditions-to-keep-in-mind-before-iterating)                                                                                           |
| 376 | [What is Categorical Data and How is it Represented in Pandas?](#what-is-categorical-data-and-how-is-it-represented-in-pandas)                                                                                                       |
| 377 | [How Can a DataFrame be Converted to an Excel File?](#how-can-a-dataframe-be-converted-to-an-excel-file)                                                                                                                             |
| 378 | [What is Multi-Indexing in Pandas?](#what-is-multi-indexing-in-pandas)                                                                                                                                                               |
| 379 | [How to Select Specific Data-Types to Include or Exclude in the DataFrame?](#how-to-select-specific-data-types-to-include-or-exclude-in-the-dataframe)                                                                               |
| 380 | [How to Convert a DataFrame into a Numpy Array?](#how-to-convert-a-dataframe-into-a-numpy-array)                                                                                                                                     |
| 381 | [How to Split a DataFrame According to a Boolean Criterion?](#how-to-split-a-dataframe-according-to-a-boolean-criterion)                                                                                                             |
| 382 | [What is Time Series in Pandas?](#what-is-time-series-in-pandas)                                                                                                                                                                     |
| 383 | [What is Time Delta in Pandas?](#what-is-time-delta-in-pandas)                                                                                                                                                                       |
| 384 | [What is Data Aggregation in Pandas?](#what-is-data-aggregation-in-pandas)                                                                                                                                                           |
| 385 | [Difference Between merge() and concat()](#difference-between-merge-and-concat)                                                                                                                                                      |
| 386 | [Difference Between map(), applymap(), and apply()](#difference-between-map-applymap-and-apply)                                                                                                                                      |
| 387 | [Difference Between pivot_table() and groupby()](#difference-between-pivot-table-and-groupby)                                                                                                                                        |
| 388 | [How Can We Use Pivot and Melt Data in Pandas?](#how-can-we-use-pivot-and-melt-data-in-pandas)                                                                                                                                       |
| 389 | [How to Convert a String to Datetime in Pandas?](#how-to-convert-a-string-to-datetime-in-pandas)                                                                                                                                     |
| 390 | [What is the Significance of Pandas Describe Command?](#what-is-the-significance-of-pandas-describe-command)                                                                                                                         |
| 391 | [How to Compute Mean, Median, Mode, Variance, Standard Deviation, and Various Quantile Ranges in Pandas?](#how-to-compute-mean-median-mode-variance-standard-deviation-and-various-quantile-ranges-in-pandas)                        |
| 392 | [How to Make Label Encoding Using Pandas?](#how-to-make-label-encoding-using-pandas)                                                                                                                                                 |
| 393 | [How to Make Onehot Encoding Using Pandas?](#how-to-make-onehot-encoding-using-pandas)                                                                                                                                               |
| 394 | [How to Make a Boxplot Using Pandas?](#how-to-make-a-boxplot-using-pandas)                                                                                                                                                           |
| 395 | [How to Make a Distribution Plot Using Pandas?](#how-to-make-a-distribution-plot-using-pandas)                                                                                                                                       |
| 396 | [How to Sort a DataFrame?](#how-to-sort-a-dataframe)                                                                                                                                                                                 |
| 397 | [How to Check and Remove Duplicate Values in Pandas?](#how-to-check-and-remove-duplicate-values-in-pandas)                                                                                                                           |
| 398 | [How to Create a New Column Based on Existing Columns?](#how-to-create-a-new-column-based-on-existing-columns)                                                                                                                       |
| 399 | [How to Handle Missing Data in Pandas?](#how-to-handle-missing-data-in-pandas)                                                                                                                                                       |
| 400 | [What is groupby() Function in Pandas?](#what-is-groupby-function-in-pandas)                                                                                                                                                         |
| 401 | [What are loc and iloc Methods in Pandas?](#what-are-loc-and-iloc-methods-in-pandas)                                                                                                                                                 |
| 402 | [How to Merge Two DataFrames?](#how-to-merge-two-dataframes)                                                                                                                                                                         |
| 403 | [Difference Between iloc() and loc()](#difference-between-iloc-and-loc)                                                                                                                                                              |
| 404 | [Difference Between join() and merge()](#difference-between-join-and-merge)                                                                                                                                                          |
| 405 | [Difference Between interpolate() and fillna()](#difference-between-interpolate-and-fillna)                                                                                                                                          |

## Answers

# 100 Core Python Interview Questions

<div>
<p align="center">
<a href="https://devinterview.io/questions/web-and-mobile-development/">
<img src="https://firebasestorage.googleapis.com/v0/b/dev-stack-app.appspot.com/o/github-blog-img%2Fweb-and-mobile-development-github-img.jpg?alt=media&token=1b5eeecc-c9fb-49f5-9e03-50cf2e309555" alt="web-and-mobile-development" width="100%">
</a>
</p>

#### You can also find all 100 answers here 👉 [Devinterview.io - Python](https://devinterview.io/questions/web-and-mobile-development/python-interview-questions)

<br>

1. ## What are the _key features_ of _Python_?

**Python** is a versatile and popular programming language known for its simplicity, **elegant syntax**, and a vast ecosystem of libraries. Let's look at some of the key features that make Python stand out.

### Key Features of Python

#### 1. Interpreted and Interactive

Python uses an interpreter, allowing developers to run code **line-by-line**, making it ideal for rapid prototyping and debugging.

#### 2. Easy to Learn and Read

Python's **clean, readable syntax**, often resembling plain English, reduces the cognitive load for beginners and experienced developers alike.

#### 3. Cross-Platform Compatibility

Python is versatile, running on various platforms, such as Windows, Linux, and macOS, without requiring platform-specific modifications.

#### 4. Modular and Scalable

Developers can organize their code into modular packages and reusabale functions.

#### 5. Rich Library Ecosystem

The Python Package Index (PyPI) hosts over 260,000 libraries, providing solutions for tasks ranging from web development to data analytics.

#### 6. Exceptionally Versatile

From web applications to scientific computing, Python is equally proficient in diverse domains.

#### 7. Memory Management

Python seamlessly allocates and manages memory, shielding developers from low-level tasks, such as memory deallocation.

#### 8. Dynamically Typed

Python infers the data type of a variable during execution, easing the declartion and manipulation of variables.

#### 9. Object-Oriented

Python supports object-oriented paradigms, where everything is an **object**, offering attributes and methods to manipulate data.

#### 10. Extensible

With its C-language API, developers can integrate performance-critical tasks and existing C modules with Python.
<br>

**[⬆ Back to Top](#questions)**

2. ## How is _Python_ executed?

**Python** source code is processed through various steps before it can be executed. Let's explore the key stages in this process.

### Compilation & Interpretation

Python code goes through both **compilation** and **interpretation**.

- **Bytecode Compilation**: High-level Python code is transformed into low-level bytecode by the Python interpreter with the help of a compiler. Bytecode is a set of instructions that Python's virtual machine (PVM) can understand and execute.
- **On-the-fly Interpretation**: The PVM reads and executes bytecode instructions in a step-by-step manner.

This dual approach known as "compile and then interpret" is what sets Python (and certain other languages) apart.

### Bytecode versus Machine Code Execution

While some programming languages compile directly to machine code, Python compiles to bytecode. This bytecode is then executed by the Python virtual machine. This extra step of bytecode execution **can make Python slower** in certain use-cases when compared to languages that compile directly to machine code.

The advantage, however, is that bytecode is platform-independent. A Python program can be run on any machine with a compatible PVM, ensuring cross-platform support.

### Source Code to Bytecode: Compilation Steps

1. **Lexical Analysis**: The source code is broken down into tokens, identifying characters and symbols for Python to understand.
2. **Syntax Parsing**: Tokens are structured into a parse tree to establish the code's syntax and grammar.
3. **Semantic Analysis**: Code is analyzed for its meaning and context, ensuring it's logically sound.
4. **Bytecode Generation**: Based on the previous steps, bytecode instructions are created.

### Just-In-Time (JIT) Compilation

While Python typically uses a combination of interpretation and compilation, **JIT** boosts efficiency by selectively compiling parts of the program that are frequently used or could benefit from optimization.

JIT compiles sections of the program to machine code on-the-fly. This direct machine code generation for frequently executed parts can significantly speed up those segments, blurring the line between traditional interpreters and compilers.

### Code Example: Disassembly of Bytecode

```python
import dis

def example_func():
    return 15 * 20

# Disassemble to view bytecode instructions
dis.dis(example_func)
```

Disassembling code using Python's `dis` module can reveal the underlying bytecode instructions that the PVM executes. Here's the disassembled output for the above code:

```plaintext
  4           0 LOAD_CONST               2 (300)
              2 RETURN_VALUE
```

<br>

**[⬆ Back to Top](#questions)**

3. ## What is _PEP 8_ and why is it important?

**PEP 8** is a style guide for Python code that promotes code consistency, readability, and maintainability. It's named after Python Enhancement Proposal (PEP), the mechanism used to propose and standardize changes to the Python language.

PEP 8 is not a set-in-stone rule book, but it provides general guidelines that help developers across the Python community write code that's visually consistent and thus easier to understand.

### Key Design Principles

PEP 8 emphasizes:

- **Readability**: Code should be easy to read and understand, even by someone who didn't write it.
- **Consistency**: Codebase should adhere to a predictable style so there's little cognitive load in reading or making changes.
- **One Way to Do It**: Instead of offering multiple ways to write the same construct, PEP 8 advocates for a single, idiomatic style.

### Base Rules

- **Indentation**: Use 4 spaces for each level of logical indentation.
- **Line Length**: Keep lines of code limited to 79 characters. This number is a guideline; longer lines are acceptable in certain contexts.
- **Blank Lines**: Use them to separate logical sections but not excessively.

### Naming Styles

- **Class Names**: Prefer `CamelCase`.
- **Function and Variable Names**: Use `lowercase_with_underscores`.
- **Module Names**: Keep them short and in `lowercase`.

### Documentation

- Use triple quotes for documentation strings.
- Comments should be on their own line and explain the reason for the following code block.

### Whitespace Usage

- **Operators**: Surround them with a single space.
- **Commas**: Follow them with a space.

### Example: Directory Walker

Here is the `PEP8` compliant code:

```python
import os

def walk_directory(path):
    for dirpath, dirnames, filenames in os.walk(path):
        for filename in filenames:
            file_path = os.path.join(dirpath, filename)
            print(file_path)

walk_directory('/path/to/directory')
```

<br>

**[⬆ Back to Top](#questions)**

4. ## How is memory allocation and garbage collection handled in _Python_?

In Python, **both memory allocation** and **garbage collection** are handled discretely.

### Memory Allocation

- The "heap" is the pool of memory for storing objects. The Python memory manager allocates and deallocates this space as needed.

- In latest Python versions, the `obmalloc` system is responsible for small object allocations. This system preallocates small and medium-sized memory blocks to manage frequently created small objects.

- The `allocator` abstracts the system-level memory management, employing memory management libraries like `Glibc` to interact with the operating system.

- Larger blocks of memory are primarily obtained directly from the operating system.

- **Stack** and **Heap** separation is joined by "Pool Allocator" for internal use.

### Garbage Collection

Python employs a method called **reference counting** along with a **cycle-detecting garbage collector**.

#### Reference Counting

- Every object has a reference count. When an object's count drops to zero, it is immediately deallocated.

- This mechanism is swift, often releasing objects instantly without the need for garbage collection.

- However, it can be insufficient in handling **circular references**.

#### Cycle-Detecting Garbage Collector

- Python has a separate garbage collector that periodically identifies and deals with circular references.

- This is, however, a more time-consuming process and is invoked less frequently than reference counting.

### Memory Management in Python vs. C

Python handles memory management quite differently from languages like C or C++:

- In Python, the developer isn't directly responsible for memory allocations or deallocations, reducing the likelihood of memory-related bugs.

- The memory manager in Python is what's known as a **"general-purpose memory manager"** that can be slower than the dedicated memory managers of C or C++ in certain contexts.

- Python, especially due to the existence of a garbage collector, might have memory overhead compared to C or C++ where manual memory management often results in minimal overhead is one of the factors that might contribute to Python's sometimes slower performance.

- The level of memory efficiency isn't as high as that of C or C++. This is because Python is designed to be convenient and easy to use, often at the expense of some performance optimization.
  <br>

**[⬆ Back to Top](#questions)**

5. ## What are the _built-in data types_ in _Python_?

Python offers numerous **built-in data types** that provide varying functionalities and utilities.

### Immutable Data Types

#### 1. int

Represents a whole number, such as 42 or -10.

#### 2. float

Represents a decimal number, like 3.14 or -0.01.

#### 3. complex

Comprises a real and an imaginary part, like 3 + 4j.

#### 4. bool

Represents a boolean value, True or False.

#### 5. str

A sequence of unicode characters enclosed within quotes.

#### 6. tuple

An ordered collection of items, often heterogeneous, enclosed within parentheses.

#### 7. frozenset

A set of unique, immutable objects, similar to sets, enclosed within curly braces.

#### 8. bytes

Represents a group of 8-bit bytes, often used with binary data, enclosed within brackets.

#### 9. bytearray

Resembles the 'bytes' type but allows mutable changes.

#### 10. NoneType

Indicates the absence of a value.

### Mutable Data Types

#### 1. list

A versatile ordered collection that can contain different data types and offers dynamic sizing, enclosed within square brackets.

#### 2. set

Represents a unique set of objects and is characterized by curly braces.

#### 3. dict

A versatile key-value paired collection enclosed within braces.

#### 4. memoryview

Points to the memory used by another object, aiding efficient viewing and manipulation of data.

#### 5. array

Offers storage for a specified type of data, similar to lists but with dedicated built-in functionalities.

#### 6. deque

A double-ended queue distinguished by optimized insertion and removal operations from both its ends.

#### 7. object

The base object from which all classes inherit.

#### 8. types.SimpleNamespace

Grants the capability to assign attributes to it.

#### 9. types.ModuleType

Represents a module body containing attributes.

#### 10. types.FunctionType

Defines a particular kind of function.
<br>

**[⬆ Back to Top](#questions)**

6. ## Explain the difference between a _mutable_ and _immutable_ object.

Let's look at the difference between **mutable** and **immutable** objects.

### Key Distinctions

- **Mutable Objects**: Can be modified after creation.
- **Immutable Objects**: Cannot be modified after creation.

### Common Examples

- **Mutable**: Lists, Sets, Dictionaries
- **Immutable**: Tuples, Strings, Numbers

### Code Example: Immutability in Python

Here is the Python code:

```python
# Immutable objects (int, str, tuple)
num = 42
text = "Hello, World!"
my_tuple = (1, 2, 3)

# Trying to modify will raise an error
try:
    num += 10
    text[0] = 'M'  # This will raise a TypeError
    my_tuple[0] = 100  # This will also raise a TypeError
except TypeError as e:
    print(f"Error: {e}")

# Mutable objects (list, set, dict)
my_list = [1, 2, 3]
my_dict = {'a': 1, 'b': 2}

# Can be modified without issues
my_list.append(4)
del my_dict['a']

# Checking the changes
print(my_list)  # Output: [1, 2, 3, 4]
print(my_dict)  # Output: {'b': 2}
```

### Benefits & Trade-Offs

**Immutability** offers benefits such as **safety** in concurrent environments and facilitating **predictable behavior**.

**Mutability**, on the other hand, often improves **performance** by avoiding copy overhead and redundant computations.

### Impact on Operations

- **Reading and Writing**: Immutable objects typically favor **reading** over **writing**, promoting a more straightforward and predictable code flow.

- **Memory and Performance**: Mutability can be more efficient in terms of memory usage and performance, especially concerning large datasets, thanks to in-place updates.

Choosing between the two depends on the program's needs, such as the required data integrity and the trade-offs between predictability and performance.
<br>

**[⬆ Back to Top](#questions)**

7. ## How do you _handle exceptions_ in _Python_?

**Exception handling** is a fundamental aspect of Python, and it safeguards your code against unexpected errors or conditions. Key components of exception handling in Python include:

### Components

- **Try**: The section of code where exceptions might occur is placed within a `try` block.

- **Except**: Any possible exceptions that are `raised` by the `try` block are caught and handled in the `except` block.

- **Finally**: This block ensures a piece of code always executes, regardless of whether an exception occurred. It's commonly used for cleanup operations, such as closing files or database connections.

### Generic Exception Handling vs. Handling Specific Exceptions

It's good practice to **handle** specific exceptions. However, a more **general** approach can also be taken. When doing the latter, ensure the general exception handling is at the end of the chain, as shown here:

```python
try:
    risky_operation()
except IndexError:  # Handle specific exception types first.
    handle_index_error()
except Exception as e:  # More general exception must come last.
    handle_generic_error()
finally:
    cleanup()
```

### Raising Exceptions

Use this mechanism to **trigger and manage** exceptions under specific circumstances. This can be particularly useful when building custom classes or functions where specific conditions should be met.

**Raise** a specific exception:

```python
def divide(a, b):
    if b == 0:
        raise ZeroDivisionError("Divisor cannot be zero")
    return a / b

try:
    result = divide(4, 0)
except ZeroDivisionError as e:
    print(e)
```

**Raise a general exception**:

```python
def some_risky_operation():
    if condition:
        raise Exception("Some generic error occurred")
```

### Using `with` for Resource Management

The `with` keyword provides a more efficient and clean way to handle resources, like files, ensuring their proper closure when operations are complete or in case of any exceptions. The resource should implement a `context manager`, typically by having `__enter__` and `__exit__` methods.

Here's an example using a file:

```python
with open("example.txt", "r") as file:
    data = file.read()
# File is automatically closed when the block is exited.
```

### Silence with `pass`, `continue`, or `else`

There are times when not raising an exception is appropriate. You can use `pass` or `continue` in an exception block when you want to essentially ignore an exception and proceed with the rest of your code.

- **`pass`**: Simply does nothing. It acts as a placeholder.

  ```python
  try:
      risky_operation()
  except SomeSpecificException:
      pass
  ```

- **`continue`**: This keyword is generally used in loops. It moves to the next iteration without executing the code that follows it within the block.

  ````python
  for item in my_list:
      try:
          perform_something(item)
      except ExceptionType:
          continue
      ```

  ````

- **`else` with `try-except` blocks**: The `else` block after a `try-except` block will only be executed if no exceptions are raised within the `try` block

  ```python
  try:
      some_function()
  except SpecificException:
      handle_specific_exception()
  else:
      no_exception_raised()
  ```

### Callback Function: `ExceptionHook`

Python 3 introduced the better handling of uncaught exceptions by providing an optional function for printing stack traces. The `sys.excepthook` can be set to match any exception in the module as long as it has a `hook` attribute.

Here's an example for this test module:

```python
# test.py
import sys

def excepthook(type, value, traceback):
    print("Unhandled exception:", type, value)
    # Call the default exception hook
    sys.__excepthook__(type, value, traceback)

sys.excepthook = excepthook

def test_exception_hook():
    throw_some_exception()
```

When run, calling `test_exception_hook` will print "Unhandled exception: ..."

_Note_: `sys.excepthook` will not capture exceptions raised as the result of interactive prompt commands, such as SyntaxError or KeyboardInterrupt.
<br>

**[⬆ Back to Top](#questions)**

8. ## What is the difference between _list_ and _tuple_?

**Lists** and **Tuples** in Python share many similarities, such as being sequences and supporting indexing.

However, these data structures differ in key ways:

### Key Distinctions

- **Mutability**: Lists are mutable, allowing you to add, remove, or modify elements after creation. Tuples, once created, are immutable.

- **Performance**: Lists are generally slower than tuples, most apparent in tasks like iteration and function calls.

- **Syntax**: Lists are defined with square brackets `[]`, whereas tuples use parentheses `()`.

### When to Use Each

- **Lists** are ideal for collections that may change in size and content. They are the preferred choice for storing data elements.

- **Tuples**, due to their immutability and enhanced performance, are a good choice for representing fixed sets of related data.

### Syntax

#### List: Example

```python
my_list = ["apple", "banana", "cherry"]
my_list.append("date")
my_list[1] = "blackberry"
```

#### Tuple: Example

```python
my_tuple = (1, 2, 3, 4)
# Unpacking a tuple
a, b, c, d = my_tuple
```

<br>

**[⬆ Back to Top](#questions)**

9. ## How do you create a _dictionary_ in _Python_?

**Python dictionaries** are versatile data structures, offering key-based access for rapid lookups. Let's explore various data within dictionaries and techniques to create and manipulate them.

### Key Concepts

- A **dictionary** in Python contains a collection of `key:value` pairs.
- **Keys** must be unique and are typically immutable, such as strings, numbers, or tuples.
- **Values** can be of any type, and they can be duplicated.

### Creating a Dictionary

You can use several methods to create a dictionary:

1. **Literal Definition**: Define key-value pairs within curly braces { }.

2. **From Key-Value Pairs**: Use the `dict()` constructor or the `{key: value}` shorthand.

3. **Using the `dict()` Constructor**: This can accept another dictionary, a sequence of key-value pairs, or named arguments.

4. **Comprehensions**: This is a concise way to create dictionaries using a single line of code.

5. **`zip()` Function**: This creates a dictionary by zipping two lists, where the first list corresponds to the keys, and the second to the values.

### Examples

#### Dictionary Literal Definition

Here is a Python code:

```python
# Dictionary literal definition
student = {
    "name": "John Doe",
    "age": 21,
    "courses": ["Math", "Physics"]
}
```

#### From Key-Value Pairs

Here is the Python code:

```python
# Using the `dict()` constructor
student_dict = dict([
    ("name", "John Doe"),
    ("age", 21),
    ("courses", ["Math", "Physics"])
])

# Using the shorthand syntax
student_dict_short = {
    "name": "John Doe",
    "age": 21,
    "courses": ["Math", "Physics"]
}
```

#### Using `zip()`

Here is a Python code:

```python
keys = ["a", "b", "c"]
values = [1, 2, 3]

zipped = zip(keys, values)
dict_from_zip = dict(zipped) # Result: {"a": 1, "b": 2, "c": 3}
```

#### Using `dict()` Constructor

Here is a Python code:

```python
# Sequence of key-value pairs
student_dict2 = dict(name="Jane Doe", age=22, courses=["Biology", "Chemistry"])

# From another dictionary
student_dict_combined = dict(student, **student_dict2)
```

<br>

**[⬆ Back to Top](#questions)**

10. ## What is the difference between _==_ and _is operator_ in _Python_?

Both the **`==`** and **`is`** operators in Python are used for comparison, but they function differently.

- The **`==`** operator checks for **value equality**.
- The **`is`** operator, on the other hand, validates **object identity**,

In Python, every object is unique, identifiable by its memory address. The **`is`** operator uses this memory address to check if two objects are the same, indicating they both point to the exact same instance in memory.

- **`is`**: Compares the memory address or identity of two objects.
- **`==`**: Compares the content or value of two objects.

While **`is`** is primarily used for **None** checks, it's generally advisable to use **`==`** for most other comparisons.

### Tips for Using Operators

- **`==`**: Use for equality comparisons, like when comparing numeric or string values.
- **`is`**: Use for comparing membership or when dealing with singletons like **None**.
  <br>

**[⬆ Back to Top](#questions)**

11. ## How does a _Python function_ work?

**Python functions** are the building blocks of code organization, often serving predefined tasks within modules and scripts. They enable reusability, modularity, and encapsulation.

### Key Components

- **Function Signature**: Denoted by the `def` keyword, it includes the function name, parameters, and an optional return type.
- **Function Body**: This section carries the core logic, often comprising conditional checks, loops, and method invocations.
- **Return Statement**: The function's output is determined by this statement. When None is specified, the function returns by default.
- **Local Variables**: These variables are scoped to the function and are only accessible within it.

### Execution Process

When a function is called:

1. **Stack Allocation**: A stack frame, also known as an activation record, is created to manage the function's execution. This frame contains details like the function's parameters, local variables, and **instruction pointer**.

2. **Parameter Binding**: The arguments passed during the function call are bound to the respective parameters defined in the function header.

3. **Function Execution**: Control is transferred to the function body. The statements in the body are executed in a sequential manner until the function hits a return statement or the end of the function body.

4. **Return**: If a return statement is encountered, the function evaluates the expression following the `return` and hands the value back to the caller. The stack frame of the function is then popped from the call stack.

5. **Post Execution**: If there's no `return` statement, or if the function ends without evaluating any return statement, `None` is implicitly returned.

### Local Variable Scope

- **Function Parameters**: These are a precursor to local variables and are instantiated with the values passed during function invocation.
- **Local Variables**: Created using an assignment statement inside the function and cease to exist when the function execution ends.
- **Nested Scopes**: In functions within functions (closures), non-local variables - those defined in the enclosing function - are accessible but not modifiable by the inner function, without using the `nonlocal` keyword.

### Global Visibility

If a variable is not defined within a function, the Python runtime will look for it in the global scope. This behavior enables functions to access and even modify global variables.

### Avoiding Side Effects

Functions offer a level of encapsulation, potentially reducing side effects by ensuring that data and variables are managed within a controlled environment. Such containment can help enhance the robustness and predictability of a codebase. As a best practice, minimizing the reliance on global variables can lead to more maintainable, reusable, and testable code.
<br>

**[⬆ Back to Top](#questions)**

12. ## What is a _lambda function_, and where would you use it?

A **Lambda function**, or **lambda**, for short, is a small anonymous function defined using the `lambda` keyword in Python.

While you can certainly use named functions when you need a function for something in Python, there are places where a lambda expression is more suitable.

### Distinctive Features

- **Anonymity**: Lambdas are not given a name in the traditional sense, making them suited for one-off uses in your codebase.
- **Single Expression Body**: Their body is limited to a single expression. This can be an advantage for brevity but a restriction for larger, more complex functions.
- **Implicit Return**: There's no need for an explicit `return` statement.
- **Conciseness**: Lambdas streamline the definition of straightforward functions.

### Common Use Cases

- **Map, Filter, and Reduce**: Functions like `map` can take a lambda as a parameter, allowing you to define simple transformations on the fly. For example, doubling each element of a list can be achieved with `list(map(lambda x: x*2, my_list))`.
- **List Comprehensions**: They are a more Pythonic way of running the same `map` or `filter` operations, often seen as an alternative to lambdas and `map`.
- **Sorting**: Lambdas can serve as a custom key function, offering flexibility in sort orders.
- **Callbacks**: Often used in events where a function is needed to be executed when an action occurs (e.g., button click).
- **Simple Functions**: For functions that are so basic that giving them a name, especially in more procedural code, would be overkill.

### Notable Limitations

- **Lack of Verbose Readability**: Named functions are generally preferred when their intended use is obvious from the name. Lambdas can make code harder to understand if they're complex or not used in a recognizable pattern.
- **No Formal Documentation**: While the function's purpose should be apparent from its content, a named function makes it easier to provide direct documentation. Lambdas would need a separate verbal explanation, typically in the code or comments.
  <br>

**[⬆ Back to Top](#questions)**

13. ## Explain _\*args_ and _\*\*kwargs_ in _Python_.

In Python, `*args` and `**kwargs` are often used to pass a variable number of arguments to a function.

`*args` collects a variable number of positional arguments into a **tuple**, while `**kwargs` does the same for keyword arguments into a **dictionary**.

Here are the key features, use-cases, and their respective code examples.

### **\*args**: Variable Number of Positional Arguments

- **How it Works**: The name `*args` is a convention. The asterisk (\*) tells Python to put any remaining positional arguments it receives into a tuple.

- **Use-Case**: When the number of arguments needed is uncertain.

#### Code Example: "\*args"

```python
def sum_all(*args):
    result = 0
    for num in args:
        result += num
    return result

print(sum_all(1, 2, 3, 4))  # Output: 10
```

### **\*\*kwargs**: Variable Number of Keyword Arguments

- **How it Works**: The double asterisk (\*\*) is used to capture keyword arguments and their values into a dictionary.

- **Use-Case**: When a function should accept an arbitrary number of keyword arguments.

#### Code Example: "\*\*kwargs"

```python
def print_values(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")

# Keyword arguments are captured as a dictionary
print_values(name="John", age=30, city="New York")
# Output:
# name: John
# age: 30
# city: New York
```

<br>

**[⬆ Back to Top](#questions)**

14. ## What are _decorators_ in _Python_?

In Python, a **decorator** is a design pattern and a feature that allows you to modify functions and methods dynamically. This is done primarily to keep the code clean, maintainable, and DRY (Don't Repeat Yourself).

### How Decorators Work

- Decorators wrap a target function, allowing you to execute custom code before and after that function.
- They are typically **higher-order functions** that take a function as an argument and return a new function.
- This paradigm of "functions that modify functions" is often referred to as **metaprogramming**.

### Common Use Cases

- **Authorization and Authentication**: Control user access.
- **Logging**: Record function calls and their parameters.
- **Caching**: Store previous function results for quick access.
- **Validation**: Verify input parameters or function output.
- **Task Scheduling**: Execute a function at a specific time or on an event.
- **Counting and Profiling**: Keep track of the number of function calls and their execution time.

### Using Decorators in Code

Here is the Python code:

```python
from functools import wraps

# 1. Basic Decorator
def my_decorator(func):
    @wraps(func)  # Ensures the original function's metadata is preserved
    def wrapper(*args, **kwargs):
        print('Something is happening before the function is called.')
        result = func(*args, **kwargs)
        print('Something is happening after the function is called.')
        return result
    return wrapper

@my_decorator
def say_hello():
    print('Hello!')

say_hello()

# 2. Decorators with Arguments
def decorator_with_args(arg1, arg2):
    def actual_decorator(func):
        @wraps(func)
        def wrapper(*args, **kwargs):
            print(f'Arguments passed to decorator: {arg1}, {arg2}')
            result = func(*args, **kwargs)
            return result
        return wrapper
    return actual_decorator

@decorator_with_args('arg1', 'arg2')
def my_function():
    print('I am decorated!')

my_function()
```

### Decorator Syntax in Python

The `@decorator` syntax is a convenient shortcut for:

```python
def say_hello():
    print('Hello!')
say_hello = my_decorator(say_hello)
```

### Role of **functools.wraps**

When defining decorators, particularly those that return functions, it is good practice to use `@wraps(func)` from the `functools` module. This ensures that the original function's metadata, such as its name and docstring, is preserved.
<br>

**[⬆ Back to Top](#questions)**

15. ## How can you create a _module_ in _Python_?

You can **create** a Python module through one of two methods:

- **Define**: Begin with saving a Python file with `.py` extension. This file will automatically function as a module.

- **Create a Blank Module**: Start an empty file with no extension. Name the file using the accepted module syntax, e.g., `__init__ `, for it to act as a module.

Next, use **import** to access the module and its functionality.

### Code Example: Creating a `math_operations` Module

#### Module Definition

Save the below `math_operations.py` file :

```python
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    return x / y
```

#### Module Usage

You can use `math_operations` module by using import as shown below:

```python
import math_operations

result = math_operations.add(4, 5)
print(result)

result = math_operations.divide(10, 5)
print(result)
```

Even though it is not required in the later **versions of Python**, you can also use statement `from math_operations import *` to import all the members such as functions and classes at once:

```python
from math_operations import *  # Not recommended generally due to name collisions and readability concerns

result = add(3, 2)
print(result)
```

### Best Practice

Before submitting the code, let's make sure to follow the **Best Practice**:

- **Avoid Global Variables**: Use a `main()` function.
- **Guard Against Code Execution on Import**: To avoid unintended side effects, use:

```python
if __name__ == "__main__":
    main()
```

This makes sure that the block of code following `if __name__ == "__main__":` is only executed when the module is run directly and not when imported as a module in another program.
<br>

**[⬆ Back to Top](#questions)**

16. ## Given two arrays, write a python function to return the intersection of the two?

### For example, X = [1,5,9,0] and Y = [3,0,2,9] it should return [9,0]

Answer:

```
set(X).intersect (set(Y))
```

**[⬆ Back to Top](#questions)**

17. ## Given an array, find all the duplicates in this array?

### For example: input: [1,2,3,1,3,6,5] output: [1,3]

Answer:

```
set1=set()
res=set()
for i in list:
  if i in set1:
    res.add(i)
  else:
    set1.add(i)
print(res)
```

**[⬆ Back to Top](#questions)**

18. ## Given an integer array, return the maximum product of any three numbers in the array?

Answer:

```
import heapq

def max_three(arr):
    a = heapq.nlargest(3, arr) # largerst 3 numbers for postive case
    b = heapq.nsmallest(2, arr) # for negative case
    return max(a[2]*a[1]*a[0], b[1]*b[0]*a[0])
```

**[⬆ Back to Top](#questions)**

19. ## Given an integer array, find the sum of the largest contiguous subarray within the array.

### For example, given the array A = [0,-1,-5,-2,3,14] it should return 17 because of [3,14]. Note that if all the elements are negative it should return zero.

```
def max_subarray(arr):
  n = len(arr)
  max_sum = arr[0] #max
  curr_sum = 0
  for i in range(n):
    curr_sum += arr[i]
    max_sum = max(max_sum, curr_sum)
    if curr_sum <0:
      curr_sum  = 0
  return max_sum

```

**[⬆ Back to Top](#questions)**

20. ## Define tuples and lists in Python What are the major differences between them?

Answer:

Lists:
In Python, a list is created by placing elements inside square brackets [], separated by commas. A list can have any number of items and they may be of different types (integer, float, string, etc.). A list can also have another list as an item. This is called a nested list.

1. Lists are mutable
2. Lists are better for performing operations, such as insertion and deletion.
3. Lists consume more memory
4. Lists have several built-in methods

Tuples:
A tuple is a collection of objects which ordered and immutable. Tuples are sequences, just like lists. The differences between tuples and lists are, the tuples cannot be changed unlike lists and tuples use parentheses, whereas lists use square brackets.

1. Tuples are immutable
2. Tuple data type is appropriate for accessing the elements
3. Tuples consume less memory as compared to the list
4. Tuple does not have many built-in methods.

- Mutable = we can change, add, delete and modify stuff
- Immutable = we cannot change, add, delete and modify stuff

**[⬆ Back to Top](#questions)**

21. ## Compute the Euclidean Distance Between Two Series?

```

```

**[⬆ Back to Top](#questions)**

22. ## Given an integer n and an integer K, output a list of all the combination of k numbers chosen from 1 to n

### For example, if n=3 and k=2, return [1,2],[1,3],[2,3]

Answer

```
from itertools import combinations
def find_combintaion(k,n):
    list_num = []
    comb = combinations([x for x in range(1, n+1)],k)
    for i in comb:
        list_num.append(i)
    print("(K:{},n:{}):".format(k,n))
    print(list_num,"\n")
```

**[⬆ Back to Top](#questions)**

23. ## Write a function to generate N samples from a normal distribution and plot them on the histogram

Answer:
Using bultin Libraries:

```
import numpy as np
import matplotlib.pyplot as plt

x = np.random.randn((N,))
plt.hist(x)
```

From scratch:
![Alt_text](https://github.com/youssefHosni/Data-Science-Interview-Questions/blob/main/Figures/Python%20questions%208.png)

**[⬆ Back to Top](#questions)**

24. ## What is the difference between apply and applymap function in pandas?

Answer:

Both the methods only accept callables as arguments but what sets them apart is that applymap is defined on dataframes and works element-wise. While apply can be defined on data frames as well as series and can work row/column-wise as well as element-wise. In terms of use case, applymap is used for transformations while apply is used for more complex operations and aggregations. Applymap only returns a dataframe while apply can return a scalar value, series, or dataframe.

**[⬆ Back to Top](#questions)**

25. ## Given a string, return the first recurring character in it, or “None” if there is no recurring character.

### Example: input = "pythoninterviewquestion" , output = "n"

Answer:

```
input_string = "pythoninterviewquestion"

def first_recurring(input_str):

  a_str = ""
  for letter in input_str:
    a_str = a_str + letter
    if a_str.count(letter) > 1:
      return letter
  return None

first_recurring(input_string)

```

**[⬆ Back to Top](#questions)**

26. ## Given a positive integer X, return an integer that is a factorial of X using recursion

### Given a positive integer X return an integer that is a factorial of X. If a negative integer is provided, return -1. Implement the solution by using a recursive function.

Answer:

```
def factorial(x):
    # Edge cases
    if x < 0: return -1
    if x == 0: return 1

    # Exit condition - x = 1
    if x == 1:
        return x
    else:
        # Recursive part
        return x * factorial(x - 1)
```

**[⬆ Back to Top](#questions)**

27. ## Given an m-by-n matrix with positive integers, determine the length of the longest increasing path

### For example, consider the input matrix:

```c
        [ 1 2 3 ]

        [ 4 5 6 ]

        [ 7 8 9 ]

        The answer should be 5 since the longest path would be 1-2-5-6-9
```

Answer:

```
MAX = 10

def Longest_Increasing_Path(dp, mat, n, m, x, y):

    # If value not calculated yet.
    if (dp[x][y] < 0):
        result = 0

        #  // If reach bottom right cell, return 1
        if (x == n - 1 and y == m - 1):
            dp[x][y] = 1
            return dp[x][y]

        # If reach the corner
        # of the matrix.
        if (x == n - 1 or y == m - 1):
            result = 1

        # If value greater than below cell.
        if (x + 1 < n and mat[x][y] < mat[x + 1][y]):
            result = 1 + LIP(dp, mat, n,
                            m, x + 1, y)

        # If value greater than left cell.
        if (y + 1 < m and mat[x][y] < mat[x][y + 1]):
            result = max(result, 1 + LIP(dp, mat, n,
                                        m, x, y + 1))
        dp[x][y] = result
    return dp[x][y]

# Wrapper function
def wrapper(mat, n, m):
    dp = [[-1 for i in range(MAX)]
            for i in range(MAX)]
    return Longest_Increasing_Path(dp, mat, n, m, 0, 0)
```

**[⬆ Back to Top](#questions)**

28. ## Explain what Flask is and its benefits

Answer:

Flask is a web framework. This means flask provides you with tools, libraries, and technologies that allow you to build a web application. This web application can be some web pages, a blog, a wiki, or go as big as a web-based calendar application or a commercial website.

Benefits of Flask:

- Scalable
  Flask’s status as a microframework means that it can be used to grow a tech project such as a web app very quickly.

- Flexible
  It allows the project to be rearranged and moved around. Also makes sure that the project structure does not collapse when a part is altered.

- Easy to negotiate
  At its core, the microframework is easy to understand for web developers also giving them more control over their code and what is possible.

- Lightweight
  Certain parts of a design of a tool/framework might need assembling and reassembling and do not rely on a large number of extensions to function which gives web developers a certain level of control. Further, Flask also supports modular programming, which is where its functionality can be split into several interchangeable modules and each module acts as an independent entity and executes a part of the functionality.

**[⬆ Back to Top](#questions)**

29. ## What is the difference between lists, arrays, and sets in Python, and when should you use each of them

Answer:

All three are data structures that can store sequences of data. but with some differences.

List denoted by [ ], set by { } , and array/tuple by ( )

𝐋𝐢𝐬𝐭: built-in data type in Python that helps store data in sequence with a very rich API that allows insertion removal retrieval and expansion. one of its benefits is that it allows the use of many data types in the same lists as it can store string, integers, floats of any other derived objects. one of its cons that are very slow if it will be used in numerical computation.

𝐀𝐫𝐫𝐚𝐲: on the other hand array can only store a single data type like integers only, float only, or any derived object only. but unlike lists, it's very efficient in terms of speed and memory usage (NumPy is one of the best libraries that implements array operations as it's a very rich library that solves many problems in numerical computation like vectorization, broadcasting, ...etc).

𝐒𝐞𝐭: it's also a built-in data type in Python and can store more that data types. but it does not allow for the existence of duplicates and if there are duplicates it only uses one of them. provide a lot of methods like unions, diffs, and intersections.

**[⬆ Back to Top](#questions)**

30. ## Converting an Integer into Decimals

```python
import decimal
integer = 10
print(decimal.Decimal(integer))
print(type(decimal.Decimal(integer)))

> 10
> <class 'decimal.Decimal'>

```

**[⬆ Back to Top](#questions)**

31. ## Converting a String of Integers into Decimals

```python
import decimal
string = '12345'
print(decimal.Decimal(string))
print(type(decimal.Decimal(string)))

> 12345
> <class 'decimal.Decimal'>

```

**[⬆ Back to Top](#questions)**

32. ## Reversing a String using an Extended Slicing Technique

```python
string = "Python Programming"
print(string[::-1])

> gnimmargorP nohtyP

```

**[⬆ Back to Top](#questions)**

33. ## Counting Vowels in a Given Word

```python
vowel = ['a', 'e', 'i', 'o', 'u']
word = "programming"
count = 0
for character in word:
    if character in vowel:
        count += 1
print(count)

> 3
```

**[⬆ Back to Top](#questions)**

34. ## Counting Consonants in a Given Word

```python
vowel = ['a', 'e', 'i', 'o', 'u']
word = "programming"
count = 0
for character in word:
    if character not in vowel:
        count += 1
print(count)

> 8
```

**[⬆ Back to Top](#questions)**

35. ## Counting the Number of Occurrences of a Character in a String

```python
word = "python"
character = "p"
count = 0
for letter in word:
    if letter == character:
        count += 1
print(count)

> 1
```

**[⬆ Back to Top](#questions)**

36. ## Writing Fibonacci Series

```python
fib = [0,1]
# Range starts from 0 by default
for i in range(5):
    fib.append(fib[-1] + fib[-2])

# Converting the list of integers to string
print(', '.join(str(e) for e in fib))

> 0, 1, 1, 2, 3, 5, 8

```

**[⬆ Back to Top](#questions)**

37. ## Finding the Maximum Number in a List

```python
numberList = [15, 85, 35, 89, 125]

maxNum = numberList[0]
for num in numberList:
    if maxNum < num:
        maxNum = num
print(maxNum)

> 125

```

**[⬆ Back to Top](#questions)**

38. ## Finding the Minimum Number in a List

```python
numberList = [15, 85, 35, 89, 125, 2]

minNum = numberList[0]
for num in numberList:
    if minNum > num:
        minNum = num
print(minNum)

> 2

```

**[⬆ Back to Top](#questions)**

39. ## Finding the Middle Element in a List

```python
numList = [1, 2, 3, 4, 5]
midElement = int((len(numList)/2))

print(numList[midElement])

> 3
```

**[⬆ Back to Top](#questions)**

40. ## Converting a List into a String

```python
lst = ["P", "Y", "T", "H", "O", "N"]
string = ''.join(lst)

print(string)
print(type(string))

> PYTHON
> <class 'str'>
```

**[⬆ Back to Top](#questions)**

41. ## Adding Two List Elements Together

```python
lst1 = [1, 2, 3]
lst2 = [4, 5, 6]

res_lst = []
for i in range(0, len(lst1)):
    res_lst.append(lst1[i] + lst2[i])
print(res_lst)

> [5, 7, 9]

```

**[⬆ Back to Top](#questions)**

42. ## Comparing Two Strings for Anagrams

```python
str1 = "Listen"
str2 = "Silent"

str1 = list(str1.upper())
str2 = list(str2.upper())
str1.sort(), str2.sort()

if(str1 == str2):
    print("True")
else:
    print("False")

> True

```

**[⬆ Back to Top](#questions)**

43. ## Checking for Palindrome Using Extended Slicing Technique

```python
str1 = "Kayak".lower()
str2 = "kayak".lower()

if(str1 == str2[::-1]):
    print("True")
else:
    print("False")

> True

```

**[⬆ Back to Top](#questions)**

44. ## Counting the White Spaces in a String

```python
string = "P r ogramm in g "
print(string.count(' '))

> 5
```

**[⬆ Back to Top](#questions)**

45. ## Counting Digits, Letters, and Spaces in a String

```python
# Importing Regular Expressions Library
import re

name = 'Python is 1'

digitCount = re.sub("[^0-9]", "", name)
letterCount = re.sub("[^a-zA-Z]", "", name)
spaceCount = re.findall("[ \n]", name)

print(len(digitCount))
print(len(letterCount))
print(len(spaceCount))

> 1
> 8
> 2
```

**[⬆ Back to Top](#questions)**

46. ## Counting Special Characters in a String

```python
# Importing Regular Expressions Library
import re
spChar = "!@#$%^&*()"

count = re.sub('[\w]+', '', spChar)
print(len(count))

> 10
```

**[⬆ Back to Top](#questions)**

47. ## Removing All Whitespace in a String

```python
import re

string = "C O D E"
spaces = re.compile(r'\s+')
result = re.sub(spaces, '', string)
print(result)

```

**[⬆ Back to Top](#questions)**

48. ## Building a Pyramid in Python

```python
floors = 3
h = 2*floors-1
for i in range(1, 2*floors, 2):
    print('{:^{}}'.format('*'*i, h))

>  *
  ***
 *****

```

**[⬆ Back to Top](#questions)**

49. ## Randomizing the Items of a List in Python

```python

from random import shuffle

lst = ['Python', 'is', 'Easy']
shuffle(lst)
print(lst)

> ['Easy', 'is', 'Python']


```

**[⬆ Back to Top](#questions)**

# Top Python Theoritical Interview Questions and Answers

50. ## Explain Python?

Python is a highly comprehensive, interactive, and object-oriented scriptwriting language. It was developed to make the content highly readable among net surfers. Python makes use of various English keywords other than just punctuations.

**[⬆ Back to Top](#questions)**

51. ## What are the distinct features of Python?

- Structured and functional programmings are supported.
- It can be compiled to byte-code for creating larger applications.
- Develops high-level dynamic data types.
- Supports checking of dynamic data types.
- Applies automated garbage collection.
- It could be used effectively along with Java, COBRA, C, C++, ActiveX, and COM.

**[⬆ Back to Top](#questions)**

52. ## What is Python path?

A Python path tells the Python interpreter to locate the module files that can be imported into the program. It includes the Python source library directory and source code directory.

**[⬆ Back to Top](#questions)**

53. ## What are the supported standard data types in Python?

The supported standard data types in Python include the following.

- List
- Number
- String
- Dictionary
- Tuples

**[⬆ Back to Top](#questions)**

54. ## Define tuples in Python?

Tuples is a sequence data type in Python. The number of values in tuples are separated by commas.

**[⬆ Back to Top](#questions)**

55. ## What are the positive and negative indices?

In the positive indices are applied the search beings from left to the right. In the case of the negative indices, the search begins from right to left. For example, in the array list of size n the positive index, the first index is 0, then comes 1 and until the last index is n-1. However, in the negative index, the first index is -n, then -(n-1) until the last index will be -1

**[⬆ Back to Top](#questions)**

56. ## What can be the length of the identifier in Python?

The length of the identifier in Python can be of any length. The longest identifier will violate from PEP – 8 and PEP – 20.

**[⬆ Back to Top](#questions)**

57. ## Define Pass statement in Python?

A Pass statement in Python is used when we cannot decide what to do in our code, but we must type something for making syntactically correct.

**[⬆ Back to Top](#questions)**

58. ## What are the limitations of Python?

There are certain limitations of Python, which include the following:

- It has design restrictions.
- It is slower when compared with C and C++ or Java.
- It is inefficient in mobile computing.
- It consists of an underdeveloped database access layer.

**[⬆ Back to Top](#questions)**

59. ## Do runtime errors exist in Python? Give an example?

Yes, runtime errors exist in Python. For example, if you are duck typing and things look like a duck, then it is considered as a duck even if that is just a flag or stamp or any other thing. The code, in this case, would be A Run-time error. For example, Print “Hackr io”, then the runtime error would be the missing parenthesis that is required by print ( ).

**[⬆ Back to Top](#questions)**

60. ## Why do we need a break in Python?

Break helps in controlling the Python loop by breaking the current loop from execution and transfer the control to the next block.

**[⬆ Back to Top](#questions)**

61. ## Why do we need a continue in Python?

A continue also helps in controlling the Python loop but by making jumps to the next iteration of the loop without exhausting it.

**[⬆ Back to Top](#questions)**

62. ## Can we use a break and continue together in Python? How?

Break and continue can be used together in Python. The break will stop the current loop from execution, while jump will take to another loop.

**[⬆ Back to Top](#questions)**

63. ## Does Python support an intrinsic do-while loop?

No Python does not support an intrinsic do-while loop.

**[⬆ Back to Top](#questions)**

64. ## How many ways can be applied for applying reverse string?

There are five ways in which the reverse string can be applied which include the following.

- Loop
- Recursion
- Stack
- Extended Slice Syntax
- Reversed

**[⬆ Back to Top](#questions)**

65. ## What are the different stages of the Life Cycle of a Thread?

The different stages of the Life Cycle of a Thread can be stated as follows.
Stage 1: Creating a class where we can override the run method of the Thread class.
Stage 2: We make a call to start() on the new thread. The thread is taken forward for scheduling purposes.
Stage 3: Execution takes place wherein the thread starts execution, and it reaches the running state.
Stage 4: Thread wait until the calls to methods including join() and sleep() takes place.
Stage 5: After the waiting or execution of the thread, the waiting thread is sent for scheduling.
Stage 6: Running thread is done by executing the terminates and reaches the dead state.

**[⬆ Back to Top](#questions)**

66. ## What is the purpose of relational operators in Python?

The purpose of relational operators in Python is to compare values.

**[⬆ Back to Top](#questions)**

67. ## What are assignment operators in Python?

The assignment operators in Python can help in combining all the arithmetic operators with the assignment symbol.

**[⬆ Back to Top](#questions)**

68. ## Why do we need membership operators in Python?

We need membership operators in Python with the purpose to confirm if the value is a member in another or not.

**[⬆ Back to Top](#questions)**

69. ## How are identity operators different than the membership operators?

Unlike membership operators, the identity operators compare the values to find out if they have the same value or not.

**[⬆ Back to Top](#questions)**

70. ## Describe how multithreading is achieved in Python?

Even though Python comes with a multi-threading package, if the motive behind multithreading is to speed the code then using the package is not the go-to option.

The package has something called the GIL or Global Interpreter Lock, which is a construct. It ensures that one and only one of the threads execute at any given time. A thread acquires the GIL and then do some work before passing it to the next thread.

This happens so fast that to a user it seems that threads are executing in parallel. Obviously, this is not the case as they are just taking turns while using the same CPU core. Moreover, GIL passing adds to the overall overhead to the execution.

Hence, if you intend to use the threading package for speeding up the execution, using the package is not recommended.

**[⬆ Back to Top](#questions)**

71. ## What is Inheritance in Python?

Inheritance enables a class to acquire all the members of another class. These members can be attributes, methods, or both. By providing reusability, inheritance makes it easier to create as well as maintain an application.

The class which acquires is known as the child class or the derived class. The one that it acquires from is known as the superclass or base class or the parent class

**[⬆ Back to Top](#questions)**

72. ## What are the different types of inheritance?

- Single Inheritance – A single derived class acquires from on single superclass.
- Multi-Level Inheritance – At least 2 different derived classes acquire from two distinct base classes.
- Hierarchical Inheritance – A number of child classes acquire from one superclass
- Multiple Inheritance – A derived class acquires from several superclasses.

**[⬆ Back to Top](#questions)**

73. ## Explain memory managed in Python?

Python private heap space takes place of memory management in Python. It contains all Python objects and data structures. The interpreter is responsible to take care of this private heap and the programmer does not have access to it. The Python memory manager is responsible for the allocation of Python heap space for Python objects. The programmer may access some tools for the code with the help of the core API. Python also provides an inbuilt garbage collector, which recycles all the unused memory and frees the memory and makes it available to heap space.

**[⬆ Back to Top](#questions)**

74. ## What are Python decorators?

A specific change made in Python syntax to alter the functions easily are termed as Python decorators.

**[⬆ Back to Top](#questions)**

75. ## What do you understand by the process of compilation and linking in Python?

In order to compile new extensions without any error, compiling and linking is used in Python. Linking initiates only and only when the compilation is complete.

In the case of dynamic loading, the process of compilation and linking depends on the style that is provided with the concerned system. In order to provide dynamic loading of the configuration setup files and rebuilding the interpreter, the Python interpreter is used.

**[⬆ Back to Top](#questions)**

76. ## What is the map() function used for in Python?

The map() function applies a given function to each item of an iterable. It then returns a list of the results. The value returned from the map() function can then be passed on to functions to the likes of the list() and set().

Typically, the given function is the first argument and the iterable is available as the second argument to a map() function. Several tables are given if the function takes in more than one arguments.

**[⬆ Back to Top](#questions)**

77. ## How will you distinguish between NumPy and SciPy?

Typically, NumPy contains nothing but the array data type and the most basic operations, such as basic element-wise functions, indexing, reshaping, and sorting. All the numerical code resides in SciPy.

As one of NumPy’s most important goals is compatibility, the library tries to retain all features supported by either of its predecessors. Hence, NumPy contains a few linear algebra functions despite the fact that these more appropriately belong to the SciPy library.

SciPy contains fully-featured versions of the linear algebra modules available to NumPy in addition to several other numerical algorithms.

**[⬆ Back to Top](#questions)**

78. ## What is the lambda function?

An anonymous function is known as a lambda function. This function can have only one statement but can have any number of parameters.

**[⬆ Back to Top](#questions)**

80. ## Differentiate between list and tuple?

Tuple is not mutable it can be hashed eg. key for dictionaries. On the other hand, lists are mutable.

**[⬆ Back to Top](#questions)**

81. ## What is the // operator? What is its use?

The // is a Floor Divisionoperator used for dividing two operands with the result as quotient displaying digits before the decimal point. For instance, 10//5 = 2 and 10.0//5.0 = 2.0.

**[⬆ Back to Top](#questions)**

82. ## What is monkey patching in Python?

The dynamic modifications made to a class or module at runtime are termed as monkey patching in Python

**[⬆ Back to Top](#questions)**

83. ## What is the split function used for?

The split function breaks the string into shorter strings using the defined separator. It returns the list of all the words present in the string.

**[⬆ Back to Top](#questions)**

84. ## Explain the Dogpile effect?

The event when the cache expires and websites are hit by multiple requests made by the client at the same time. Using a semaphore lock prevents the Dogpile effect. In this system when value expires, the first process acquires the lock and starts generating new value.

**[⬆ Back to Top](#questions)**

85. ## What is a pass in Python?

No-operation Python statement refers to pass. It is a place holder in the compound statement, where there should have a blank left or nothing written there.

**[⬆ Back to Top](#questions)**

86. ## Define slicing in Python.

Slicing refers to the mechanism to select the range of items from sequence types like lists, tuples, strings

**[⬆ Back to Top](#questions)**

87. ## What are docstring?

Docstring is a Python documentation string, it is a way of documenting Python functions, classes and modules.

**[⬆ Back to Top](#questions)**

88. ## What is [::-1] used for?

[::-1] reverses the order of an array or a sequence. However, the original array or the list remains unchanged.

**[⬆ Back to Top](#questions)**

89. ## Define Python Iterators

Group of elements, containers or objects that can be traversed.

**[⬆ Back to Top](#questions)**

90. ## How are comments written in Python?

Comments in Python start with a # character, they can also be written within docstring(String within triple quotes)

**[⬆ Back to Top](#questions)**

91. ## How to capitalize the first letter of string?

Capitalize() method capitalizes the first letter of the string, and if the letter is already capital it returns the original string

**[⬆ Back to Top](#questions)**

92. ## What is, not and in operators?

Operators are functions that take two or more values and returns the corresponding result.

- is: returns true when two operands are true
- not: returns inverse of a boolean value
- in: checks if some element is present in some sequence.

**[⬆ Back to Top](#questions)**

93. ## How are files deleted in Python?

To delete a file in Python:

- Import OS module
- Use os.remove() function

**[⬆ Back to Top](#questions)**

94. ## Does Python supports multiple inheritances?

Yes, in Python a class can be derived from more than one parent class.

**[⬆ Back to Top](#questions)**

95. ## What does the method object() do?

The method returns a featureless object that is base for all classes. This method does not take any parameters.

**[⬆ Back to Top](#questions)**

96. ## What is pep 8?

Python Enhancement Proposal or pep 8 is a set of rules that specify how to format Python code for maximum readability.

**[⬆ Back to Top](#questions)**

97. ## What is namespace in Python?

A naming system used to make sure that names are unique to avoid naming conflicts refers to as Namespace.

**[⬆ Back to Top](#questions)**

98. ## Is indentation necessary in Python?

Indentation is required in Python if not done properly the code is not executed properly and might throw errors. Indentation is usually done using four space characters.

Question: Define a function in Python
Answer: A block of code that is executed when it is called is defined as a function. Keyword def is used to define a Python function.

Question: Define self in Python
Answer: An instance of a class or an object is self in Python. It is included as the first parameter. It helps to differentiate between the methods and attributes of a class with local variables.

**[⬆ Back to Top](#questions)**

# Python Interview Preparation

99. ## Explain 'Everything in Python is an object'.

What's an object? An object in a object-oriented programming language is an entity that contains data along with some methods for operations related to that data. <br>
Everything from numbers, lists, strings, functions and classes are python objects.

```python
>>> a = 10.5
>>> a.is_integer() # Float type has is_integer() method cause a is an object of float class
False
>>> type(a)
<class 'float'>
>>> def func()
....    pass
>>> type(func)
<class 'function'>
>>> # like functions, classes are also objects of 'type' class
```

Look at the below example

```python
>>> var = 'Tom' # Object 'Tom' is created in memory and name 'var' is binded to it.
>>> var = 'Harry' # Another object is created however note that name 'var' is now binded to 'Harry' but 'Tom' is still somewhere in memory and is unaffected.
```

Ref: [Nina Zakharenko - Memory Management in Python - The Basics - PyCon 2016](https://www.youtube.com/watch?v=F6u5rhUQ6dU)

**[⬆ Back to Top](#questions)**

100. ## What is mutable and immutable objects/data types in Python?

Mutation generally refers to 'change'. So when we say that an object is mutable or immutable we meant to say that the value of object can/cannot change. <br>
When an object is created in Python, it is assigned a type and an id. An object/data type is mutable if with the same id, the value of the object changes after the object is created.

##

<b>Mutable objects in Python</b>
-- Objects that can change after creation. Lists, byte arrays, sets, and dictionaries.

```python
>>> list_var = [17, 10]
>>> list_var
[17, 10]
>>> id(list_var)
2289772854208
>>> list_var += [17]
>>> list_var
[17, 10, 17]
>>> id(list_var) # ID of the object didn't change.
2289772854208
```

##

<b>Immutable objects in Python</b>
-- Numeric data types, strings, bytes, frozen sets, and tuples.

```python
>>> # Example of tuples
>>> tuple_var = (17,)
>>> tuple_var
(17,)
>>> id(tuple_var)
1753146091504
>>> tuple_var += (10,)
>>> tuple_var
(17,10)
>>> id(tuple_var) # ID changes when made changes in object.
1753153466880
```

##

<b>Mutable objects and functon arguments</b>

```python
def sample_func(sample_arg):
    sample_agr.append(10)
    # No need to return the obj since it is utilizing the same memory block

sample_list = [7, 8, 9]
sample_func(sample_list)
print(sample_list) # [7, 8, 9, 10]
```

**[⬆ Back to Top](#questions)**

101. ## What is the difference between list and tuples in Python?

|    Parameter    |               List                |                   Tuples                    |
| :-------------: | :-------------------------------: | :-----------------------------------------: |
|     Syntax      |  Square brackets or list keyword  | Round brackets/parenthesis or tuple keyword |
|     Nature      |              Mutable              |                  Immutable                  |
| Item Assignment |             Possible              |                Not Possible                 |
|   Reusablity    |              Copied               |                 Not Copied                  |
|   Performance   |         Relatively slower         |              Relatively faster              |
|     Memory      | Large-Extra than the element size |            Fixed to element size            |

Note: It is not required for tuples to have parenthesis, one can also define tuple `python a = 2, 3, 4 `

### Memory Allocation of Tuple and List

Tuple does not allot any extra memory during construction because it will be immutable so does not have to worry about addition of elements.

```python
>>> tuple_var = tuple()
>>> tuple_var.__sizeof__() # take 24 bytes for empty tuple
24
>>> tuple_var = (1,2) # additional 8 bytes for each integer element
>>> tuple_var.__sizeof__()
40
```

List over-allocates memory otherwise list.append would be an O(n) operation.

```python
>>> list_var = list()
>>> list_var.__sizeof__() # take 40 bytes for empty list
40
>>> list_var.append(1)
>>> list_var.__sizeof__() # append operation allots extra memory size considering future appends
72
>>> list_var
[1]
>>> list_var.append(2)
>>> list_var.__sizeof__() # size remains same since list has space available
72
>>> list_var
[1,2]
```

### Reusablity

Tuple literally assigns the same object to the new variable while list basically copies all the elements of the existing list.

```python
>>> # List vs Tuples | Reused vs. Copied
>>> old_list = [1,2]
>>> old_list.append(3)
>>> old_list
[1, 2, 3]
>>> id(old_list)
2594206915456
>>> old_list.__sizeof__()
88

>>> # Copying list
>>> new_list = list(old_list)
>>> new_list
[1, 2, 3]
>>> id(new_list) # new id so new list is created
2594207110976
>>> new_list.__sizeof__() # size is also not same as old_list
64

>>> Tuple Copy
>>> old_tuple = (1,2)
>>> id(old_tuple)
2594206778048
>>> old_tuple.__sizeof__()
40
>>> new_tuple = tuple(old_tuple)
>>> id(new_tuple) # same id as old_tuple
2594206778048
>>> new_tuple.__sizeof__() # also same size as old_tuple since it is refering to old_tuple
40
```

### Performance-Speed

Tuples and List takes almost same time in indexing, but for construction, tuple destroys list. See example, 'List vs Tuple'.

**[⬆ Back to Top](#questions)**

102. ## How is memory managed in Python?

Unlike other programming languages, python stores references to an object after it is created. For example, an integer object 17 might have two names(variables are called names in python) a and b. The memory manager in python keeps track of the reference count of each object, this would be 2 for object 17. Once the object reference count reaches 0, object is removed from memory. <br>
The reference count

- increases if an object is assigned a new name or is placed in a container, like tuple or dictionary.
- decreases when the object's reference goes out of scope or when name is assigned to another object.
  Python's garbage collector handles the job of removing objects & a programmer need not to worry about allocating/de-allocating memory like it is done in C.

```python
>>> import sys
>>> sys.getrefcount(17)
>>> 11
>>> a = 17
>>> b = 17
>>> a is b
>>> True
>>> sys.getrefcount(17)
>>> 13 # addition of two
```

**[⬆ Back to Top](#questions)**

103. ## Explain exception handling in Python.

Exception handling is the way by which a programmer can control an error within the program without breaking out the flow of execution.

```python
try:
    # Part which might cause an error
except TypeError:
    # What happens when error occurs | In this case what happens what a TypeError occurs
else:
    # what happens if there is no exception | Optional
finally:
    # Executed after try and except| always executed | Optional
```

Examples :- TypeError, ValueError, ImportError, KeyError, IndexError, NameError, PermissionError, EOFError, ZeroDivisionError, StopIteration

**[⬆ Back to Top](#questions)**

104. ## Explain some changes in Python 3.8

Positional arguments representation

```python
def sum(a,b,/,c=10):
    return a+b+c
sum(10,12,c=12)
```

F String can also do operations

```python
a,b = 10, 12
f"Sum of a and b is {a+b}"
f"Value of c is {(c := a+b)}"
```

**[⬆ Back to Top](#questions)**

105. ## Explain Python Design Patterns.

Ref: https://www.youtube.com/watch?v=o1FZ_Bd4DSM

**[⬆ Back to Top](#questions)**

106. ## How would you load large data file in Python?

The best way is to load data in chunks, Pandas provides option to define chunk size while loading any file.

```python
for chunk in pd.read_csv(file.csv, chunksize=1000):
    process(chunk)

pd.read_csv('file.csv', sep='\t', iterator=True, chunksize=1000)
```

Another way is to use context manager.

```python
with open("log.txt") as infile:
    for line in infile:
        do_something_with(line)
```

**[⬆ Back to Top](#questions)**

107. ## Explain Generators and use case of it.

A function or method which uses the yield statement is called a generator function. Such a function, when called, always returns an iterator object which can be used to execute the body of the function: calling the iterator’s iterator.\_\_next\_\_()method will cause the function to execute until it provides a value using the yield statement. <br>
When the function executes a return statement or falls off the end, a StopIteration exception is raised and the iterator will have reached the end of the set of values to be returned. Note that a generator can have n numbers of yield statements

#### Use Case

Generators are good for calculating large sets of results where you don't know if you are going to need all results, or where you don't want to allocate the memory for all results at the same time.

```python
# Search function as generator, effective for returning some set as result with functionality like 'Load 10 more items'
def search_result(keyword):
    while keyword in dataset:
        yield matched_data

search_object = search_result('keyword')
# type(search_function)  --> <class 'generator'>

search_object.__next__()
```

Note: You can only iterate over a generator once, if you try to loop over it second time it will return nothing. Generators also do not store all the values in memory, they generate the values on the fly

```python
mygenerator = (x*x for x in range(3))
```

When you call a generator function, the code you have written in the function body does not run. The function only returns the generator object.
Example: https://github.com/baliyanvinay/Python-Advanced/blob/main/Generator.py

**[⬆ Back to Top](#questions)**

108. ## Is there a sequence in defining exceptions in except block for exception handling?

Yes can be defined in a tuple. From left to right will be executed based on the exception raised.

```python
try:
    pass
except (TypeError, IndexError, RuntimeError) as error:
    pass
```

**[⬆ Back to Top](#questions)**

109. ## Explain Closures in Python

A closure is a functionality in Python where some data is memorized in the memory for lazy execution. Decorators heavily rely on the concept of closure. <br>
To create a closure in python:-

1. There must be a nested function(function within a enclosing/outer function)
2. The nested function must refer to a value defined in the enclosing function
3. The enclosing function must return(not call it) the nested function.

```python
def enclosing_function(defined_value):
    def nested_function():
        return defined_value+some_operation
    return nested_function

closure_function = enclosing_function(20)
closure_function() # returns 20+some_operation
```

Objects are data with methods attached, closures are functions with data attached.

**[⬆ Back to Top](#questions)**

110. ## How to make a chain of function decorators?

```python
def make_bold(fn):
    def wrapped():
        return "<b>" + fn() + "</b>"
    return wrapped

def make_italic(fn):
    def wrapped():
        return "<i>" + fn() + "</i>"
    return wrapped

@make_bold
@make_italic
def index():
    return "hello world"

print(index())
## returns "<b><i>hello world</i></b>"

```

**[⬆ Back to Top](#questions)**

111. ## Three different ways to fetch every 3rd item of a list

Using index jump

```python
>>> example_list = [0,1,2,3,4,5,6]
>>> example_list = [::3] # returns [0,3,6]
```

Using list comphrehension

```python
>>> [x for x in example_list if example_list.index(x)%3==0]
>>> [0,3,6]
```

Using while loop

```python
i = 0
while i < len(example_list):
    print(example_list[i])
    i += 3
```

**[⬆ Back to Top](#questions)**

112. ## What is MRO in Python? How does it work?

Method Resolution Order (MRO) is the order in which Python looks for a method in a hierarchy of classes. Especially it plays vital role in the context of multiple inheritance as single method may be found in multiple super classes.

```python
class A:
    def process(self):
        print('A')

class B(A):
    pass

class C(A):
    def process(self):
        print('C')

class D(B,C):
    pass

obj = D()
obj.process()
# D -> B -> C -> A -> object
```

Note: a class can't be called before its superclass in resolving MRO. Super Class has to be called after derived class

**[⬆ Back to Top](#questions)**

113. ## What is monkey patching? How to use it in Python?

Monkey patching refers to the practice of dynamically modifying or extending code at runtime, typically to change the behavior of existing classes, modules, or functions.

Monkey patching can be useful in several scenarios:

1. Testing: It allows to replace parts of code during testing with mock objects or functions.
2. Hotfixes: In situations where you can't immediately deploy a fix to production code, monkey patching can be used as a temporary solution to address critical issues without waiting for a formal release cycle.
3. Extending functionality: It enables to add new features or alter the behavior of existing code without modifying the original source. This can be useful when working with third-party libraries or legacy code that you can't modify directly.

```python
# Original module
class OriginalClass:
    def method(self):
        return "Original method"

# Monkey patching
def new_method(self):
    return "Patched method"

# Patching the class method
OriginalClass.method = new_method
# Using the patched code
obj = OriginalClass()
print(obj.method())  # Output: "Patched method"
```

**[⬆ Back to Top](#questions)**

114. ## What is the difference between staticmethod and classmethod?

| Parameter |                 Class Method                  |            Static Method            |
| :-------: | :-------------------------------------------: | :---------------------------------: |
| Decorator |                 @classmethod                  |            @staticmethod            |
| Use Case  | More widely used as a factory method to class |      Acts as utility functions      |
|   Scope   |      Bound to the classs and not objects      | Also bound to class and not objects |
| Behaviour |       Can modify the state of the class       |      Can't access class state       |
| Parameter |         Takes cls as first parameter          |        No specific parameter        |

```python
class Circle:
    no_of_circles = 0
    def __init__(self, radius):
        self.radius = radius
        Circle.no_of_circles += 1

    @staticmethod
    def square(num):
        return num**2

    @classmethod
    def getCircleCount(cls):
        return cls.no_of_circles
```

**[⬆ Back to Top](#questions)**

115. ## What is the purpose of the single underscore “\_” variable in Python?

Python automatically stores the value of last expression in interpreter in single underscore.

```python
>>> 78 + 89
167
>>> _
167
```

Single underscore used in unpacking to ignore value(s).

```python
>>> a, _, b = (1, 12, 2)
>>> a, *_, b = (1, 12, 13, 14, 15, 16, 2) # only want first and last value
>>> a, *x, b = (1, 12, 13, 14, 15, 16, 2) # note that any other name can also be used
>>> _ # returns a list of elements
[12, 13, 14, 15, 16]
```

It is most commonly used in loops where we are not interested in the value returned by the iterator.

```python
for _ in range(5):
    print('Some operations')
```

Note that it is entirely the convention to use single underscore in all these ways to avoid having defined extra variable for such operations.

**[⬆ Back to Top](#questions)**

116. ## What's the difference between a Python module and a Python package?

#### Module

The module is a Python file that contains collections of functions and global variables and with having a .py extension file.

### Package

The package is a directory having collections of modules. This directory contains Python modules and also having **init**.py file by which the interpreter interprets it as a Package.

**[⬆ Back to Top](#questions)**

117. ## What is a global interpreter lock (GIL)?

Ref: https://www.geeksforgeeks.org/what-is-the-python-global-interpreter-lock-gil/

**[⬆ Back to Top](#questions)**

118. ## Which is faster, list comprehension or for loop?

List comprehensions are generally faster than 'a for loop' because of the implementation of both. One key difference is that 'for loop' generally rounds up more than one statement/operation as compared to 'list comprehension' which has to perform single operation on all the elements. For example, creating a list or update in an existing list is faster when done using list comprehension.

**[⬆ Back to Top](#questions)**

119. ## Explain Singleton class and its uses?

Refer to [Python Advanced : Design Patterns](https://github.com/baliyanvinay/Python-Advanced/tree/main/Design%20Patterns)

**[⬆ Back to Top](#questions)**

120. ## Explain Meta Classes in Python.

In Python everything is an object, even a class is an object. As a result, a class also must have a type. All classes in Python are of 'type' type. Even the class of 'type' is 'type'. So 'type' is the meta class in Python and to create custom meta class, you would need to inherit from 'type'.<br>

### Use Case of Meta Class

A meta class is the class of a class. A class is an instance of a metaclass. A metaclass is most commonly used as a class-factory. When you create an object by calling the class, Python creates a new class (when it executes the 'class' statement) by calling the metaclass.<br>

```python
>>> type(17) # <class 'int'>
>>> type(int) # <class 'type'>
>>> str.__class__ # <class 'type'>
>>> type.__class__ # <class 'type'>
```

### Meta Class call

The metaclass is called with the

- name: name of the class,
- bases: tuple of the parent class (for inheritance, can be empty) and
- attributes: dictionary containing attributes names and values.

```python
def init(self, make):
    self.make = make

# type(name, bases, attrs)
>>> Car = type('Car', (object,), {'__init__': init, '__repr__': lambda self: self.make,  'wheels': 4})
>>> seltos = Car('Kia')
>>> seltos # Kia
```

Ref: [Stack Overflow : Meta Classes](https://stackoverflow.com/questions/100003/what-are-metaclasses-in-python)

**[⬆ Back to Top](#questions)**

121. ## Best way to concatenate n number of strings together into one.

The best way of appending a string to a string variable is to use + or +=. This is because it's readable and fast. However in most of the codebases we see use of append and join when joining strings together, this is done for readablity and cleaner code. Sometimes it is more important to have code readablity to actually understand the operation.

```python
first_name = 'Max '
last_name = 'Verstappen'
full_name = first_name + last_name
# using join string method
full_name = ''.join( (first_name, last_name) ) # takes in tuple of string in case of multiple values
```

**[⬆ Back to Top](#questions)**

122. ## Explain briefly about map() and lambda() functions.

### map(function, iterable)

Map function returns an iterator that applies function to every item in the iterable. In case multiple iterables are passed, the iterator stops when the shortest iterable is exhausted.

```python
def custom_power(x, y):
    return x**y

values = [1,2,3,4]
powers = [2,1,2]
map_iterator = map(custom_power, values, powers) # will skip the power of 4
print(list(map_iterator)) # [1,2,9]
```

### lambda parameters: expression

Lambda expression yields an anonymous function object. Note that functions created with lambda expressions cannot contain statements or annotations. For example, can't assign variables in lambda definition.

```python
>>> # lambda [parameter list] : expression
>>> list(map(lambda x: x+10, [1,2,3])) # [11,12,13]
>>> func =  lambda x: x+10 # <function <lambda> at 0x7fdb99e9c310>
>>> func(25) # returns 35
>>> lambda : 'hello' # with no parameter
```

**[⬆ Back to Top](#questions)**

123. ## Explain Abstract Classes and its uses.

An abstract class can be considered as a blueprint for other classes. It allows you to create a set of methods that must be created within any child classes built from the abstract class. Or in more general terms, a class which contains one or more abstract methods is called an abstract class.<br>
By default Python does not provide abstract class, ABC module of Python can be used to define an abstract class.

### Abstract Method

Abstract method is a method that has a declaration but does not have an implementation. This ensures that any class built from this class will have to implement the method.

```python
from abc import ABC, abstractmethod
class DB_PLugin(ABC):
    @abstractmethod
    def add_source(self):
        pass
```

**[⬆ Back to Top](#questions)**

124. ## Explain object creation process in detail. Which method is called first?

When an object of a class is created or a class is instantiated, the \_\_new\_\_() method of class is called. This particular method is resposible for returning a new class object. It can be overriden to implement object creational restrictions on class. <br>

- The constructor of the class is \_\_new\_\_() and
- the initializer of the class is \_\_init**(). <br>
  Initializer is called right after the constructor, if the constructor has not returned a class object, the initializer call is useless. <br>
  Note that the reason \_\_init**() could use class object(self) to initialize is because when the code flow reaches \_\_init\_\_() the object of the class is already created.

**[⬆ Back to Top](#questions)**

125. ## Difference between a class variable and instance variable.

|  Parameter  |                       Class Variable                        |              Instance Variable               |
| :---------: | :---------------------------------------------------------: | :------------------------------------------: |
| Declaration | Inside class definition but outside of any instance methods | Inside constructor method i.e., \_\_init\_\_ |
|    Scope    |                  Shared across all objects                  |         Tied to the object instance          |
|  Behaviour  |        Any change is reflected across all instances         |       Change limited to instances only       |
|   Access    |                      cls.variable_name                      |              self.variable_name              |

```python
class Car:
    total_cars, wheels = 0, 4
    def __init__(self, engine_power):
        self.engine_power =  engine_power
        Car.total_cars += 1 # incremented anytime a new car is added.

kia_sonet = Car(120)
print(kia_sonet.wheels) # returns 4
kia_sonet.wheels += 1 # extra wheel
print(kia_sonet.wheels) # returns 5

print(Car.total_cars) # returns 1
print(Car.wheels) # returns 4 not 5
Car.wheel = 6 # two extra wheels

print(kia_sonet.wheels) # returns 6 now
```

Example: https://github.com/baliyanvinay/Python-Advanced/blob/main/Class%20Variables.py

**[⬆ Back to Top](#questions)**

126. ## Explain the concept behind dictionary in Python

- A dictionary consists of a collection of key-value pairs. Each key-value pair maps the key to its associated value.
- A key can appear in a dictionary only once. Duplicate keys are not allowed
- Using a key twice in initial dict definition will override the first entry
- Key must be of a type that is immutable. Values can be anything

```python
>>> dict_sample_01 = {1: 12, 2: 14, 1: 16}
>>> dict_sample_02 # {1: 16, 2: 14}
>>> dict_sample_02 = dict.fromkeys('123')
>>> dict_sample_02 # {'1': None, '2': None, '3': None}
```

**[⬆ Back to Top](#questions)**

127. ## Difference between an expression and a statement in Python

A statement is a complete line of code that performs some action, while an expression is any section of the code that evaluates to a value. An expression is also a statement. Note that lambda function in Python only accepts expressions.

**[⬆ Back to Top](#questions)**

128. ## Explain threading in Python

**[⬆ Back to Top](#questions)**

129. ## Can set have lists as elements?

You can't add a list to a set because lists are mutable, meaning that you can change the contents of the list after adding it to the set. You can however add tuples to the set, because you cannot change the contents of a tuple. <br>
The objects have to be hashable so that finding, adding and removing elements can be done faster than looking at each individual element every time you perform these operations. <br>
Some unhashable datatypes:

- list: use tuple instead
- set: use frozenset instead

**[⬆ Back to Top](#questions)**

130. ## Is method overloading possible in Python?

Yes method overloading is possible in Python. It can be achived using different number of arguments.

```python
def increment(value, by=1):
   return value+by

# calling function
increment(5) # returns 6
increment(5, 2) # return 7
```

**[⬆ Back to Top](#questions)**

131. ## Explain inheritance in Python.

![Inheritance in Python](https://github.com/baliyanvinay/Python-Interview-Preparation/blob/main/Inheritance.png)

**[⬆ Back to Top](#questions)**

132. ## Explain method resolution order for multiple inheritance

**[⬆ Back to Top](#questions)**

133. ## What can be used as keys in dictionary?

Any immutable object type can be used as dictionary key even functions and classes can also be used as dictionary keys.

**[⬆ Back to Top](#questions)**

#### Why can't list or another dict(mutable object) be used as key in dictionary?

Dict implementation reduces the average complexity of dictionary lookups to O(1) by requiring that key objects provide a "hash" function. Such a hash function takes the information in a key object and uses it to produce an integer, called a hash value. This hash value is then used to determine which "bucket" this (key, value) pair should be placed into. Mutuable objects like list or dict cannot provide a valid /**hash** method.

134. ## Explain shallow and deep copy in Python

For collections that are mutable or contain mutable items, a copy is sometimes needed so one can change one copy without changing the other. <br>
Python follows a pattern of compiling the original source to byte codes, then interpreting the byte codes on a virtual machine. The .pyc file generated contains byte code.

```python
>>> import copy
>>> sample_1 = [1,2,3]
>>> id(sample_1)
139865052152768
>>> sample_2 = sample_1
>>> id(sample_2)
139865052152768
>>> sample_3 = copy.copy(sample_1)
>>> id(sample_3)
139865052236736
```

- A shallow copy constructs a new compound object and then (to the extent possible) inserts references into it to the objects found in the original.
- A deep copy constructs a new compound object and then, recursively, inserts copies into it of the objects found in the original.

Ref: [Python Docs Copy](https://docs.python.org/3/library/copy.html)

**[⬆ Back to Top](#questions)**

135. ## Why Python generates a .pyc file even when it is an interpreted language?

.pyc files are created by the Python interpreter when a .py file is imported, and they contain the "compiled bytecode" of the imported module/program, the idea being that the "translation" from source code to bytecode (which only needs to be done once) can be skipped on subsequent imports if the .pyc is newer than the corresponding .py file, thus speeding startup a little. But it's still interpreted.

**[⬆ Back to Top](#questions)**

136. ## How private varibles are declared in Python?

Python does not have anything called private member however by convention two underscore before a variable or function makes it private.

```python
class XSpecial:
    normal_var = 10
    __private_var = 17

>>> special_obj = XSpecial()
>>> special_obj.normal_var
>>> special_obj.__private_var # AttributeError
```

**[⬆ Back to Top](#questions)**

137. ## Difference between an array and list

|                       List                        |                             Array                              |
| :-----------------------------------------------: | :------------------------------------------------------------: |
|   Can contain elements of different data types    |     Contains homogeneous elements only i.e. same data type     |
|                 No need to import                 |               Need to import via numpy or array                |
|    Preferred for short sequence of data items     | Preferred for large sequence of data items i.e., data analysis |
| Can't perform airthmetic operations on whole list |                Great for airthmetic operations                 |

**[⬆ Back to Top](#questions)**

138. ## What is an iterator? How is iterator is different from a generator?

An iterator is an object that implements /**next**, which is expected to return the next element of the iterable object, and raise a StopIteration exception when no more elements are available.

### Differnce between iterator and generator

|                                Iterator                                 |                    Generator                     |
| :---------------------------------------------------------------------: | :----------------------------------------------: |
|                 Class is used to implement an iterator                  |    Function is used to implement a generator     |
|                Iterator uses iter() and next() functions                |           Generator uses yield keyword           |
|                    Every iterator is not a generator                    |          Every generator is an iterator          |
| Saves the states of local variables every time ‘yield’ pauses execution | An iterator does not make use of local variables |
|                            Memory efficient                             |       More memory allocated than iterator        |

**[⬆ Back to Top](#questions)**

139. ## How do you define a dict where several keys has same value?

```python
products = {}
products.update(
    dict.keys(['Apple','Mango','Oranges'], 20)
)
products.update(
    dict.keys(['Pizza','Kind Pizza','Bad Pizza'], 30)
)
```

**[⬆ Back to Top](#questions)**

140. ## What are different types of namespaces in Python?

Namespace is a way to implement scope. In Python, each package, module, class, function and method function owns a "namespace" in which variable names are resolved. Plus there's a global namespace that's used if the name isn't in the local namespace.<br>
Each variable name is checked in the local namespace (the body of the function, the module, etc.), and then checked in the global namespace.

### Types of Namespaces

- <b>Local Namespace: </b>The local namespace for a function is created when the function is called, and deleted when the function returns or raises an exception that is not handled within the function.
- <b>Global Namespace: </b>The global namespace for a module is created when the module definition is read in; normally, module namespaces also last until the interpreter quits.
- <b>Built-in Namespace: </b>The namespace containing the built-in names is created when the Python interpreter starts up, and is never deleted.

**[⬆ Back to Top](#questions)**

141. ## How can you access attribute of parent class bypassing the attribute with the same name in derived class?

```python
class Parent:
    variable = 12

class Derived(Parent):
    variable = 10

Parent.variable # returns 12
```

**[⬆ Back to Top](#questions)**

142. ## Evaulation of boolean expressions

- The expression x and y first evaluates x; if x is false, its value is returned; otherwise, y is evaluated and the resulting value is returned.
- The expression x or y first evaluates x; if x is true, its value is returned; otherwise, y is evaluated and the resulting value is returned.

```python
x = 'Some Value'
y = 24
z = False
x or y # returns x
z or y # returns y
x and y # returns y
z and x # returns z
```

**[⬆ Back to Top](#questions)**

143. ## Difference between multiprocessing and multithreading

The threading module uses threads, the multiprocessing module uses processes. The difference is that threads run in the same memory space, while processes have separate memory. This makes it a bit harder to share objects between processes with multiprocessing. Since threads use the same memory, precautions have to be taken or two threads will write to the same memory at the same time.

- Multithreading is concurrent and is used for IO-bound tasks
- Multiprocessing achieves true parallelism and is used for CPU-bound tasks
  Use Multithreading if most of your task involves waiting on API-calls, because why not start up another request in another thread while you wait, rather than have your CPU sit idly by.

**[⬆ Back to Top](#questions)**

144. ## How to merge two dictionaries together?

```python
first_dict = {'name': 'Tom', 'age': 44}
second_dict = {'occupation': 'actor', 'nationality': 'British'}
# merging
final_dict = {**first_dict, **second_dict}
```

In case any key is repeated in both dictionaries, the second key will hold supremacy.

**[⬆ Back to Top](#questions)**

145. ## Explain the below code

```python
def func(sample_list=[]):
    sample_list.append(12)
    # print(id(sample_list))
    return sample_list

print(func()) # [12]
print(func()) # [12,12]
```

Since list is mutualable type of data structure, the first time func is called, the list is empty, but when the same function is called twice, the list already has an item. We cans sure of the that by printing the id of the sample_list used in the first, on each subsquent call to the function, the id will return the same value.

**[⬆ Back to Top](#questions)**

146. ## Example filter with lambda expression.

### filter

filter(function, iterable) # function must return True or False

```python
input_list = ['Delhi', 'Mumbai', 'Noida', 'Gurugram']
to_match = 'Gurugram'

matched_list = list(filter(lambda item: item == to_match, input_list))
matched_list # ['Gurugram']
```

For every single item in the input_list, the condition is checked in the lambda function which returns either True or False.

**[⬆ Back to Top](#questions)**

147. ## Explain context managers.

- A context manager in Python is a protocol implemented using the with statement.
- It allows you to perform setup and teardown operations around a block of code.
- Commonly used to manage resources like files, database connections, locks, etc.

```python
class MyContextManager:
    def __enter__(self):
        # Perform setup operations
        return self

    def __exit__(self, exc_type, exc_value, traceback):
        # Perform cleanup operations

# Using the context manager
with MyContextManager() as cm:
    # Code inside the context
```

**[⬆ Back to Top](#questions)**

148. ## What is Python? List some popular applications of Python in the world of technology.

Python is a widely-used general-purpose, high-level programming language. It was created by Guido van Rossum in 1991 and further developed by the Python Software Foundation. It was designed with an emphasis on code readability, and its syntax allows programmers to express their concepts in fewer lines of code.
It is used for:

- System Scripting
- Web Development
- Game Development
- Software Development
- Complex Mathematics

**[⬆ Back to Top](#questions)**

149. ## What are the benefits of using Python language as a tool in the present scenario?

The following are the benefits of using Python language:

- Object-Oriented Language
- High-Level Language
- Dynamically Typed language
- Extensive support for Machine Learning Libraries
- Presence of third-party modules
- Open source and community development
- Portable and Interactive
- Portable across Operating systems

**[⬆ Back to Top](#questions)**

150. ## Is Python a compiled language or an interpreted language?

Actually, Python is a partially compiled language and partially interpreted language. The compilation part is done first when we execute our code and this will generate byte code internally this byte code gets converted by the Python virtual machine(p.v.m) according to the underlying platform(machine+operating system).

**[⬆ Back to Top](#questions)**

151. ## What does the ‘#’ symbol do in Python?

‘#’ is used to comment on everything that comes after on the line.

**[⬆ Back to Top](#questions)**

152. ## What is the difference between a Mutable datatype and an Immutable data type?

Mutable data types can be edited i.e., they can change at runtime. Eg – List, Dictionary, etc.
Immutable data types can not be edited i.e., they can not change at runtime. Eg – String, Tuple, etc.

**[⬆ Back to Top](#questions)**

153. ## How are arguments passed by value or by reference in Python?

In Python, arguments are passed by object reference (also called “pass by assignment”). This means that functions receive references to the same objects:

Mutable objects (like lists or dictionaries) can be modified within the function.
Immutable objects (like integers or strings) cannot be changed and reassigning them inside the function doesn’t affect the original object.

**[⬆ Back to Top](#questions)**

154. ## What is the difference between a Set and Dictionary?

The set is unordered collection of unique items that is iterable and mutable. A dictionary in Python is an ordered collection of data values, used to store data values like a map.

**[⬆ Back to Top](#questions)**

155. ## What is List Comprehension? Give an Example.

List comprehension is a syntax construction to ease the creation of a list based on existing iterable.

For Example:

```python

my_list = [i for i in range(1, 10)]

```

**[⬆ Back to Top](#questions)**

156. ## What is a lambda function?

A lambda function is an anonymous function. This function can have any number of parameters but, can have just one statement. For Example:

```python

a = lambda x, y : x*y
print(a(7, 19))

```

**[⬆ Back to Top](#questions)**

157. ## What is a pass in Python?

Pass means performing no operation or in other words, it is a placeholder in the compound statement, where there should be a blank left and nothing has to be written there.

**[⬆ Back to Top](#questions)**

158. ## What is the difference between / and // in Python?

/ represents precise division (result is a floating point number) whereas // represents floor division (result is an integer). For Example:

```python
5//2 = 2
5/2 = 2.5
```

**[⬆ Back to Top](#questions)**

159. ## How is Exceptional handling done in Python?

There are 3 main keywords i.e. try, except, and finally which are used to catch exceptions and handle the recovering mechanism accordingly. Try is the block of a code that is monitored for errors. Except block gets executed when an error occurs.

The beauty of the final block is to execute the code after trying for an error. This block gets executed irrespective of whether an error occurred or not. Finally, block is used to do the required cleanup activities of objects/variables.

**[⬆ Back to Top](#questions)**

160. ## What is swapcase function in Python?

It is a string’s function that converts all uppercase characters into lowercase and vice versa. It is used to alter the existing case of the string. This method creates a copy of the string which contains all the characters in the swap case. For Example:

string = "GeeksforGeeks"
string.swapcase() ---> "gEEKSFORgEEKS"

**[⬆ Back to Top](#questions)**

161. ## Can we Pass a function as an argument in Python?

Yes, Several arguments can be passed to a function, including objects, variables (of the same or distinct data types), and functions. Functions can be passed as parameters to other functions because they are objects. Higher-order functions are functions that can take other functions as arguments.

To read more, refer to the article: Passing function as an argument in Python

**[⬆ Back to Top](#questions)**

162. ## What are \*args and \*\*kwargs?

To pass a variable number of arguments to a function in Python, use the special syntax \*args and \**kwargs in the function specification. Both are to send a variable-length argument list. The syntax *args is used to pass a non-keyworded, variable-length argument list.

**[⬆ Back to Top](#questions)**

163. ## Is Indentation Required in Python?

Yes, indentation is required in Python. A Python interpreter can be informed that a group of statements belongs to a specific block of code by using Python indentation. Indentations make the code easy to read for developers in all programming languages but in Python, it is very important to indent the code in a specific order.

**[⬆ Back to Top](#questions)**

164. ## What is Scope in Python?

The location where we can find a variable and also access it if required is called the scope of a variable.

- Python Local variable: Local variables are those that are initialized within a function and are unique to that function. It cannot be accessed outside of the function.
- Python Global variables: Global variables are the ones that are defined and declared outside any function and are not specified to any function.
- Module-level scope: It refers to the global objects of the current module accessible in the program.
- Outermost scope: It refers to any built-in names that the program can call. The name referenced is located last among the objects in this scope.

**[⬆ Back to Top](#questions)**

165. ## What is docstring in Python?

Python documentation strings (or docstrings) provide a convenient way of associating documentation with Python modules, functions, classes, and methods.

- Declaring Docstrings: The docstrings are declared using ”’triple single quotes”’ or “””triple double quotes””” just below the class, method, or function declaration. All functions should have a docstring.
- Accessing Docstrings: The docstrings can be accessed using the **doc** method of the object or using the help function.

**[⬆ Back to Top](#questions)**

166. ## What is a dynamically typed language?

Typed languages are the languages in which we define the type of data type and it will be known by the machine at the compile-time or at runtime. Typed languages can be classified into two categories:

- Statically typed languages: In this type of language, the data type of a variable is known at the compile time which means the programmer has to specify the data type of a variable at the time of its declaration.
- Dynamically typed languages: These are the languages that do not require any pre-defined data type for any variable as it is interpreted at runtime by the machine itself. In these languages, interpreters assign the data type to a variable at runtime depending on its value.

**[⬆ Back to Top](#questions)**

167. ## What is a break, continue, and pass in Python?

The break statement is used to terminate the loop or statement in which it is present. After that, the control will pass to the statements that are present after the break statement, if available.

Continue is also a loop control statement just like the break statement. continue statement is opposite to that of the break statement, instead of terminating the loop, it forces to execute the next iteration of the loop.

Pass means performing no operation or in other words, it is a placeholder in the compound statement, where there should be a blank left and nothing has to be written there.

**[⬆ Back to Top](#questions)**

168. ## What are Built-in data types in Python?

The following are the standard or built-in data types in Python:

-**Numeric**: The numeric data type in Python represents the data that has a numeric value. A numeric value can be an integer, a floating number, a Boolean, or even a complex number.

- **Sequence Type**: The sequence Data Type in Python is the ordered collection of similar or different data types. There are several sequence types in Python:
  - Python String
  - Python List
  - Python Tuple
  - Python range
- **Mapping Types**: In Python, hashable data can be mapped to random objects using a mapping object. There is currently only one common mapping type, the dictionary, and mapping objects are mutable.
  - Python Dictionary
- **Set Types**: In Python, a Set is an unordered collection of data types that is iterable, mutable, and has no duplicate elements. The order of elements in a set is undefined though it may consist of various elements.

**[⬆ Back to Top](#questions)**

169. ## How do you floor a number in Python?

The Python math module includes a method that can be used to calculate the floor of a number.

- floor() method in Python returns the floor of x i.e., the largest integer not greater than x.
- Also, The method ceil(x) in Python returns a ceiling value of x i.e., the smallest integer greater than or equal to x.

**[⬆ Back to Top](#questions)**

170. ## What is the difference between xrange and range functions?

range() and xrange() are two functions that could be used to iterate a certain number of times in for loops in Python.

- In Python 3, there is no xrange, but the range function behaves like xrange.
- In Python 2
  - range() – This returns a range object, which is an immutable sequence type that generates the numbers on demand.
  - xrange() – This function returns the generator object that can be used to display numbers only by looping. The only particular range is displayed on demand and hence called lazy evaluation.

**[⬆ Back to Top](#questions)**

171. ## What is Dictionary Comprehension? Give an Example

Dictionary Comprehension is a syntax construction to ease the creation of a dictionary based on the existing iterable.

For Example: my_dict = {i:i+7 for i in range(1, 10)}

**[⬆ Back to Top](#questions)**

172. ## Is Tuple Comprehension? If yes, how, and if not why?

```python
(i for i in (1, 2, 3))
```

Tuple comprehension is not possible in Python because it will end up in a generator, not a tuple comprehension.

**[⬆ Back to Top](#questions)**

173. ## Differentiate between List and Tuple?

Let’s analyze the differences between List and Tuple:

**List**

- Lists are Mutable datatype.
- Lists consume more memory
- The list is better for performing operations, such as insertion and deletion.
- The implication of iterations is Time-consuming

**Tuple**

- Tuples are Immutable datatype.
- Tuple consumes less memory as compared to the list
- A Tuple data type is appropriate for accessing the elements
- The implication of iterations is comparatively Faster

**[⬆ Back to Top](#questions)**

174. ## What is the difference between a shallow copy and a deep copy?

Shallow copy is used when a new instance type gets created and it keeps values that are copied whereas deep copy stores values that are already copied.

A shallow copy has faster program execution whereas a deep copy makes it slow.

**[⬆ Back to Top](#questions)**

175. ## Which sorting technique is used by sort() and sorted() functions of python?

Python uses the Tim Sort algorithm for sorting. It’s a stable sorting whose worst case is O(N log N). It’s a hybrid sorting algorithm, derived from merge sort and insertion sort, designed to perform well on many kinds of real-world data.

**[⬆ Back to Top](#questions)**

176. ## What are Decorators?

Decorators are a very powerful and useful tool in Python as they are the specific change that we make in Python syntax to alter functions easily.

**[⬆ Back to Top](#questions)**

177. ## How do you debug a Python program?

By using this command we can debug a Python program:

```bash
$ python -m pdb python-script.py
```

**[⬆ Back to Top](#questions)**

178. ## What are Iterators in Python?

In Python, iterators are used to iterate a group of elements, containers like a list. Iterators are collections of items, and they can be a list, tuples, or a dictionary. Python iterator implements **itr** and the next() method to iterate the stored elements. We generally use loops to iterate over the collections (list, tuple) in Python.

**[⬆ Back to Top](#questions)**

179. ## What are Generators in Python?

In Python, the generator is a way that specifies how to implement iterators. It is a normal function except that it yields expression in the function. It does not implement **itr** and **next** method and reduces other overheads as well.

If a function contains at least a yield statement, it becomes a generator. The yield keyword pauses the current execution by saving its states and then resumes from the same when required.

**[⬆ Back to Top](#questions)**

180. ## Does Python supports multiple Inheritance?

Python does support multiple inheritances, unlike Java. Multiple inheritances mean that a class can be derived from more than one parent class.

**[⬆ Back to Top](#questions)**

181. ## What is Polymorphism in Python?

Polymorphism means the ability to take multiple forms. Polymorphism allows different classes to be treated as if they are instances of the same class through a common interface. This means that a method in a parent class can be overridden by a method with the same name in a child class, but the child class can provide its own specific implementation. This allows the same method to operate differently depending on the object that invokes it. Polymorphism is about overriding, not overloading; it enables methods to operate on objects of different classes, which can have their own attributes and methods, providing flexibility and reusability in the code.

**[⬆ Back to Top](#questions)**

182. ## Define encapsulation in Python?

Encapsulation means binding the code and the data together. A Python class is an example of encapsulation.

**[⬆ Back to Top](#questions)**

183. ## How do you do data abstraction in Python?

Data Abstraction is providing only the required details and hides the implementation from the world. It can be achieved in Python by using interfaces and abstract classes.

**[⬆ Back to Top](#questions)**

184. ## How is memory management done in Python?

Python uses its private heap space to manage the memory. Basically, all the objects and data structures are stored in the private heap space. Even the programmer can not access this private space as the interpreter takes care of this space. Python also has an inbuilt garbage collector, which recycles all the unused memory and frees the memory and makes it available to the heap space.

**[⬆ Back to Top](#questions)**

185. ## How to delete a file using Python?

We can delete a file using Python by following approaches:

- os.remove()
- os.unlink()

**[⬆ Back to Top](#questions)**

186. ## What is slicing in Python?

Python Slicing is a string operation for extracting a part of the string, or some part of a list. With this operator, one can specify where to start the slicing, where to end, and specify the step. List slicing returns a new list from the existing list.

```bash
Syntax: Lst[ Initial : End : IndexJump ]
```

**[⬆ Back to Top](#questions)**

187. ## What is a namespace in Python?

A namespace is a naming system used to make sure that names are unique to avoid naming conflicts.

Advanced Python Interview Questions & Answers 42. What is PIP?
PIP is an acronym for Python Installer Package which provides a seamless interface to install various Python modules. It is a command-line tool that can search for packages over the internet and install them without any user interaction.

**[⬆ Back to Top](#questions)**

188. ## What is a zip function?

Python zip() function returns a zip object, which maps a similar index of multiple containers. It takes an iterable, converts it into an iterator and aggregates the elements based on iterables passed. It returns an iterator of tuples.

**[⬆ Back to Top](#questions)**

189. ## What are Pickling and Unpickling?

The Pickle module accepts any Python object and converts it into a string representation and dumps it into a file by using the dump function, this process is called pickling. While the process of retrieving original Python objects from the stored string representation is called unpickling.

**[⬆ Back to Top](#questions)**

190. ## What is monkey patching in Python?

In Python, the term monkey patch only refers to dynamic modifications of a class or module at run-time.

```python
# g.py

class GeeksClass:
def function(self):
print "function()"

import m
def monkey_function(self):
print "monkey_function()"

m.GeeksClass.function = monkey_function
obj = m.GeeksClass()
obj.function()
```

**[⬆ Back to Top](#questions)**

191. ## What is **init**() in Python?

The **init**() method in Python is equivalent to constructors in OOP terminology. It is a reserved method in Python classes and is called automatically whenever a new object is instantiated. This method is used to initialize the object’s attributes with values. While **init**() initializes the object, it does not allocate memory. Memory allocation for a new object is handled by the **new**() method, which is called before **init**().

**[⬆ Back to Top](#questions)**

192. ## Write a code to display the current time?

```python

import time

currenttime= time.localtime(time.time())
print (“Current time is”, currenttime)
```

**[⬆ Back to Top](#questions)**

193. ## What are Access Specifiers in Python?

Python uses the ‘\_’ symbol to determine the access control for a specific data member or a member function of a class. A Class in Python has three types of Python access modifiers:

- Public Access Modifier: The members of a class that are declared public are easily accessible from any part of the program. All data members and member functions of a class are public by default.

- Protected Access Modifier: The members of a class that are declared protected are only accessible to a class derived from it. All data members of a class are declared protected by adding a single underscore ‘\_’ symbol before the data members of that class.

- Private Access Modifier: The members of a class that are declared private are accessible within the class only, the private access modifier is the most secure access modifier. Data members of a class are declared private by adding a double underscore ‘\_\_’ symbol before the data member of that class.

**[⬆ Back to Top](#questions)**

194. ## What are unit tests in Python?

Unit Testing is the first level of software testing where the smallest testable parts of the software are tested. This is used to validate that each unit of the software performs as designed. The unit test framework is Python’s xUnit style framework. The White Box Testing method is used for Unit testing.

**[⬆ Back to Top](#questions)**

195. ## Python Global Interpreter Lock (GIL)?

Python Global Interpreter Lock (GIL) is a type of process lock that is used by Python whenever it deals with processes. Generally, Python only uses only one thread to execute the set of written statements. The performance of the single-threaded process and the multi-threaded process will be the same in Python and this is because of GIL in Python. We can not achieve multithreading in Python because we have a global interpreter lock that restricts the threads and works as a single thread.

**[⬆ Back to Top](#questions)**

196. ## What are Function Annotations in Python?

Function Annotation is a feature that allows you to add metadata to function parameters and return values. This way you can specify the input type of the function parameters and the return type of the value the function returns.

Function annotations are arbitrary Python expressions that are associated with various parts of functions. These expressions are evaluated at compile time and have no life in Python’s runtime environment. Python does not attach any meaning to these annotations. They take life when interpreted by third-party libraries, for example, mypy.

**[⬆ Back to Top](#questions)**

197. ## What are Exception Groups in Python?

The latest feature of Python 3.11, Exception Groups. The ExceptionGroup can be handled using a new except* syntax. The * symbol indicates that multiple exceptions can be handled by each except\* clause.

ExceptionGroup is a collection/group of different kinds of Exception. Without creating Multiple Exceptions we can group together different Exceptions which we can later fetch one by one whenever necessary, the order in which the Exceptions are stored in the Exception Group doesn’t matter while calling them.

```python
try:
raise ExceptionGroup('Example ExceptionGroup', (
TypeError('Example TypeError'),
ValueError('Example ValueError'),
KeyError('Example KeyError'),
AttributeError('Example AttributeError')
))
except* TypeError:
...
except* ValueError as e:
...
except\* (KeyError, AttributeError) as e:
```

**[⬆ Back to Top](#questions)**

198. ## What is Python Switch Statement

From version 3.10 upward, Python has implemented a switch case feature called “structural pattern matching”. You can implement this feature with the match and case keywords. Note that the underscore symbol is what you use to define a default case for the switch statement in Python.

Note: Before Python 3.10 Python doesn’t support match Statements.

```python

match term:
case pattern-1:
action-1
case pattern-2:
action-2
case pattern-3:
action-3
case \_:
action-default

```

**[⬆ Back to Top](#questions)**

199. ## What is Walrus Operator?

The Walrus Operator allows you to assign a value to a variable within an expression. This can be useful when you need to use a value multiple times in a loop, but don’t want to repeat the calculation.

The Walrus Operator is represented by the `:=` syntax and can be used in a variety of contexts including while loops and if statements.

Note: Python versions before 3.8 doesn’t support Walrus Operator.

```python

names = ["Jacob", "Joe", "Jim"]
​
if (name := input("Enter a name: ")) in names:
print(f"Hello, {name}!")
else:
print("Name not found.")

```

**[⬆ Back to Top](#questions)**

# NumPy Interview Questions.

200. ## Difference between for loop and while loop in Python

The “for” Loop is generally used to iterate through the elements of various collection types such as List, Tuple, Set, and Dictionary. Developers use a “for” loop where they have both the conditions start and the end. Whereas, the “while” loop is the actual looping feature that is used in any other programming language. Programmers use a Python while loop where they just have the end conditions.

**[⬆ Back to Top](#questions)**

201. ## What is NumPy?

The Python package NumPy, which stands for "Numerical Python," is the basis for numerical and scientific computing. It offers support for arrays, matrices, and a variety of mathematical operations that can effectively operate on these arrays. In the Python environment, NumPy is a fundamental library for manipulating and analyzing data. It also used in many additional libraries that are used in data science, machine learning areas.

**[⬆ Back to Top](#questions)**

202. ## How do I create a NumPy array?

We can create NumPy arrays using various methods. Here are some common ways to create NumPy arrays:

- Using np. array()
- np.zeros()
- np.ones()
- np.full()
- np.arange()
- np.linspace()

**[⬆ Back to Top](#questions)**

203. ## What are the main features of Numpy?

Here are some main features of the NumPy.

- Arrays
- Efficiency
- Mathematical Functions
- Broadcasting
- Integration with other libraries
- Multi-dimensional arrays
- Indexing and Slicing
- Memory Management

**[⬆ Back to Top](#questions)**

204. ## How do you calculate the dot product of two NumPy arrays?

Calculating the dot product of two NumPy arrays we used numpy.dot() function and we also used the @ operator:

Using numpy.dot() function:

```python
numpy.dot(a, b)
```

a: The first input array (NumPy array).
b: The second input array (NumPy array).

Using the @ operator

```python
a @ b
```

Both methods will return the dot product of the two arrays as a scalar value.

**[⬆ Back to Top](#questions)**

205. ## How do I access elements in a NumPy array?

In NumPy, we can access elements in an array by indexing and slicing. Here's we can do it:

**Slicing**: You can also access a range of elements using slicing. Slicing allows you to extract a subset of the array based on the indices or ranges you provide.

**Boolean indexing**: Boolean indexing is used to access elements based on a condition. it help us when we want to select elements that meet the critiria.

**[⬆ Back to Top](#questions)**

206. ## What is the difference between a shallow copy and a deep copy in NumPy?

In numPy we have two ways to copy an array. shallow copy and deep copy are two most used methods used in numpy to copy an array. Here is the main difference between both of them.

| **Aspect**            | **Shallow Copy**                                                                                | **Deep Copy**                                                                                |
| --------------------- | ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| **Definition**        | A new array that is a view of the original array's data.                                        | A completely new and independent array that does not share any data with the original array. |
| **Data Reference**    | The new array references the same data as the original array, so there's no actual duplication. | The data is duplicated, creating a separate copy in memory.                                  |
| **Impact of Changes** | Changes made in the original array will also be reflected in the shallow copy, and vice versa.  | Changes made in the original array do not affect the deep copy, and vice versa.              |

**[⬆ Back to Top](#questions)**

207. ## How do you reshape a NumPy array?

We can reshape a NumPy array by using the reshape() method or the np.reshape() function. it help us to change the dimensions of the array and keep all the elements constant.

Using the reshape() method:

```python
array1= original_array.reshape(new_shape)
```

Using the np.reshape() function:

```python
array1 = np.reshape(original_array, new_shape)
```

In both cases, original_array is the existing NumPy array you want to reshape, and new_shape is a tuple specifying the desired shape of the new array.

**[⬆ Back to Top](#questions)**

208. ## How to perform element-wise operations on NumPy arrays?

To perform element-wise operations on NumPy arrays, you can use standard arithmetic operators.NumPy automatically applies these operations element-wise when you use them with arrays of the same shape.

```python
import numpy as np

# Create two NumPy arrays

array1 = np.array([1, 2, 3, 4, 5])
array2 = np.array([6, 7, 8, 9, 10])

# Perform element-wise operations

result_addition= array1 + array2
result_subtract = array1 - array2
result_multiply = array1 \* array2
result_divide = array1 / array2
result_power = np.power(array1, 2)
```

**[⬆ Back to Top](#questions)**

209. ## Define the var function in NumPy.

In NumPy, the var function is used to compute the variance of elements in an array or along a specified axis. Variance is a measure of the spread or dispersion of data points.

```python
np.var(a, axis=None, dtype=None)
```

a: The input array for which you want to calculate the variance.
axis: Axis or axes along which the variance is computed. If not specified, the variance is calculated for the whole array. It can be an integer or a tuple of integers to specify multiple axes.
dtype: The data type for the returned variance. If not specified, the data type is inferred from the input array.

**[⬆ Back to Top](#questions)**

210. ## Define the min and max function in NumPy.

In NumPy, you can use the min() and max() functions to find the minimum and maximum values in a NumPy array, respectively.

**np.min() Function:**

The np.min() function calculates the minimum value in a NumPy array along a specified axis or for the entire array.

```python
np.min(a, axis=None)
```

a: The input array in which you want to find the minimum value.
axis: Axis or axes along which the minimum value is computed. If not specified, the minimum is calculated for the whole array. It can be an integer or a tuple of integers to specify multiple axes.

**np.max() Function:**

The np.max() function calculates the maximum value in a NumPy array along a specified axis or for the entire array.

```python
np.max(a, axis=None)

a: The input array in which you want to find the maximum value.
axis (optional): Axis or axes along which the maximum value is computed. If not specified, the maximum is calculated for the whole array.
```

**[⬆ Back to Top](#questions)**

211. ## How to generate random numbers with NumPy?

NumPy provides a wide range of functions for generating random numbers. You can generate random numbers from various probability distributions, set seeds for reproducibility, and more. Here are some common ways to generate random numbers with NumPy:

**Using np.random.rand()**

Generating a Random Float between 0 and 1 using np.random.rand()

```python
random_float = np.random.rand()
```

**Using np.random.randint()**

Generating a Random Integer within a Range using np.random.randint().

```python
random_integer = np.random.randint()
```

**Using np.random.randn()**

```python
random_float = np.random.rand()
```

**Using np.random.seed()**

We can set a seed using np.random.seed() to ensure that the generated random numbers are reproducible.

```python
np.random.seed(seed_value)
```

**[⬆ Back to Top](#questions)**

212. ## What is the purpose of NumPy in Python?

NumPy (Numerical Python) is a fundamental library in Python for scientific computing and data analysis. it is the main purpose for providing support for large and multi-dimensional arrays and matrices.

**[⬆ Back to Top](#questions)**

213. ## How can you create a NumPy array from a Python list?

We can create a NumPy array from a Python list using the np.array() constructor provided by NumPy.

```python
python_list = [1, 2, 3, 4, 5]

# Convert the Python list to a NumPy array

numpy_array = np.array(python_list)
```

- Create a list that containing the elements we want to convert into NumPy array.
- Use the np.array() constructor to create a NumPy array from the Python list. Pass python_list as the argument to the np.array() function.

**[⬆ Back to Top](#questions)**

214. ## How can you access elements in a NumPy array based on specific conditions?

We can access elements in a NumPy array based on specific conditions using boolean indexing. Boolean indexing allows us to create true and false values based on a condition.

```python
arr = np.array([1, 2, 3, 4, 5])

# Define a condition (boolean mask)

condition = (arr > some_value)

# Use the condition to access elements

selected_elements = arr[condition]
```

- Create a NumPy array arr or use an existing array.
- Define a condition by creating a boolean mask. Replace some_value with your specific condition. For each element in the array, a logical expression that results in True or False should be used as the condition.
- Use the boolean mask (condition) to access elements from the array arr. The result, selected_elements, will be an array containing only the elements that satisfy the condition.

**[⬆ Back to Top](#questions)**

215. ## What are some common data types supported by NumPy?

In NumPy there are so many data types that are used to specify the type of data which stored in array. This data type provide control that how data stored in memory during operations.Some common data types supported by NumPy include:

- int
- float
- complex
- bool
- object
- datetime

**[⬆ Back to Top](#questions)**

216. ## How can you concatenate two NumPy arrays vertically?

We can concatenate two NumPy arrays vertically (along the rows) using the np.vstack() function or the np.concatenate() function with the axis parameter set to 0. Here's how to do it with both methods:

**Method 1: Using np.vstack()**

```python
array= np.vstack((array1, array2))
```

**Method 2: Using np.concatenate() with axis**

```python
array= np.concatenate((array1, array2), axis=0)
```

**[⬆ Back to Top](#questions)**

217. ## What is the significance of the random module in NumPy?

Here's a brief explanation of the significance of the random module in Python:

- Random Number Generation
- Random Sequences
- Probability Distributions
- Random Choices

**[⬆ Back to Top](#questions)**

218. ## How can you generate random numbers following a normal distribution using NumPy?

We can generate random numbers following a normal distribution (Gaussian distribution) using NumPy's random module. NumPy provides several functions for this purpose, with different options for specifying the mean and standard deviation of the distribution. The most commonly used function is numpy.random.normal.

**[⬆ Back to Top](#questions)**

219. ## What is Matrix Inversion in NumPy?

Matrix inversion in NumPy refers to the process of finding the inverse of a square matrix. The identity matrix is produced when multiplying the original matrix by the inverse of the matrix. In other words, if A is a square matrix and A^(-1) is its inverse, then A \* A^(-1) = I, where I is the identity matrix.

NumPy provides a convenient function called numpy.linalg.inv() to compute the inverse of a square matrix. Here's how you can use it:

```python
# Define a square matrix

A = np.array([[a11, a12, ...],
              [a21, a22, ...],
              [..., ..., ...]])

# Calculate the inverse of the matrix

A_inverse = np.linalg.inv(A)
```

**[⬆ Back to Top](#questions)**

220. ## Define the mean function in NumPy.

The arithmetic mean (average) in NumPy can be calculated using numpy.mean(). This method tallies elements in an array, whether it be along a specified axis or the whole array, if no axis is explicitly mentioned. The summation of all elements is then divided by the overall number of elements, which provides the average.

```python
numpy.mean(a, axis=None)
```

a: The input array for which you want to calculate the mean.

axis : The axis or axes along which the mean is computed. If not specified, the mean is calculated over the entire array.

**[⬆ Back to Top](#questions)**

220. ## Convert a multidimensional array to 1D array.

You can convert a multidimensional array to a 1D array (also known as flattening the array) in NumPy using various methods. Two common methods are using for the Convert a multidimensional array to 1D array.

**Using flatten():**

```python
# Create a multidimensional array

multidimensional_array = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])

# Use the flatten() method to convert it to a 1D array

one_dimensional_array = multidimensional_array.flatten()
```

**Using ravel():**

```python
# Create a multidimensional array

multidimensional_array = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])

# Use the ravel() method to convert it to a 1D array

one_dimensional_array = multidimensional_array.ravel()
```

Both of these methods will flatten the multidimensional array into a 1D array. The primary difference between them is that flatten() returns a new copy of the array, while ravel() returns a flattened view of the original array whenever possible. If you modify the elements in the flattened view obtained from ravel().

**[⬆ Back to Top](#questions)**

221. ## Write a NumPy code snippet to create an array of zeros.

With the help of numpy.zeros() function we can create an array of zeros in numpy. it help us to specify the shape and data type of the resulting array.

```python
# Create a 1D array of zeros with a specified length (e.g., 5)

zeros_1d = np.zeros(5)
```

**[⬆ Back to Top](#questions)**

222. ## How can you identify outliers in a NumPy array?

Identifying and removing outliers in a NumPy array involves several steps. Outliers are data points that significantly deviate from the majority of the data and can adversely affect the results of data analysis. Here's a general approach to identify and remove outliers:

**Identifying Outliers:**

- Calculate Descriptive Statistics: Compute basic statistics like the mean and standard deviation of the array to understand the central tendency and spread of the data.
- Define a Threshold:
- Decide on a threshold where data points are considered outliers.

**[⬆ Back to Top](#questions)**

223. ## How do you remove missing or null values from a NumPy array?

Removing missing or null values from NumPy array we can use boolean indexing or the numpy.isnan() function to create a mask that identifies the missing values.

```python
mask = np.isnan(my_array)

# Use the mask to filter out missing values

filtered_array = my_array[mask]
```

**[⬆ Back to Top](#questions)**

224. ## What is the difference between slicing and indexing in NumPy?

In NumPy, both slicing and indexing are fundamental operations for accessing and manipulating elements in arrays, but there are some main difference are avialable.

| **Aspect**     | **Slicing**                                                                                                               | **Indexing**                                                                                                                            |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **Definition** | The process of extracting a portion or a subset of elements from a NumPy array by specifying a range or slice of indices. | The process of accessing individual elements or subsets of elements from a NumPy array using specific indices or index values.          |
| **Purpose**    | Used to create a new array that contains a contiguous subset of elements from the original array.                         | Used to retrieve a single element or access multiple elements at specific positions.                                                    |
| **Syntax**     | Involves using a colon `:` inside square brackets to specify a range of indices.                                          | Typically involves using square brackets `[]` and providing one or more index values (separated by commas for multidimensional arrays). |

In summary, indexing is used to access individual or specific elements from an array, while slicing is used to create a new array that contains a contiguous subset of elements from the original array based on a specified range of indices.

**[⬆ Back to Top](#questions)**

225. ## How do you compute the Fourier transform of a signal using NumPy?

To compute the Fourier transform of a signal using NumPy we will use numpy.fft module that provides functions for various types of Fourier transforms. for computing the Fourier transform of a signal we use the Fast Fourier Transform (FFT) algorithm. Here's a step-by-step guide on how to do it.

```python
t = np.linspace(0, 1, 1000, endpoint=False) # Time vector
signal = np.sin(2 _ np.pi _ 5 \* t)

# Compute the FFT of the signal

fft_result = np.fft.fft(signal)
```

**[⬆ Back to Top](#questions)**

226. ## How can you create array with same values.

We can create a NumPy array with the same values using various functions and methods depending on your specific needs. Here are a few common approaches:

**Using numpy.full():**

You can use the numpy.full() function to create an array filled with a specific value. This function takes two arguments: the shape of the array and the fill value.

```python
# Create a 1D array with 5 elements, all set to 7

arr = np.full(5, 7)
```

**Using Broadcasting:**

If you want to create an array of the same value repeated multiple times, you can use broadcasting with NumPy.

```python
# Create a 1D array with 5 elements, all set to 7

arr = 7 \* np.ones(5)

# Create a 2D array with dimensions 3x4, all elements set to 2.0

arr_2d = 2.0 \* np.ones((3, 4))
```

You can also create an array with the same values using a list comprehension and then converting it to a NumPy array.

```python
# Create a 1D array with 5 elements, all set to 7

arr = np.array([7] \* 5)

# Create a 2D array with dimensions 3x4, all elements set to 2.0

arr*2d = np.array([[2.0] * 4] \_ 3)
```

**[⬆ Back to Top](#questions)**

227. ## How can you modify the data type of a NumPy array?

We can modify the data type of a NumPy array using the astype() method or by directly assigning a new data type to the dtype attribute. Here's how you can do it:

**Using the astype() method:**

You can use the astype() method to create a new array with the desired data type while leaving the original array unchanged.

```python
new_array = original_array.astype(float)
```

**Directly assigning a new data type to the dtype attribute:**

You can also modify the data type of a NumPy array in place by assigning a new data type directly to the dtype attribute.

```python
# Create a NumPy array with the original data type (e.g., int)

original_array = np.array([1, 2, 3, 4, 5])

# Change the data type of the original array to float

original_array.dtype = float
```

**[⬆ Back to Top](#questions)**

228. ## What is a masked array in NumPy.

A masked array in NumPy is a special type of array that includes an additional Boolean mask, which marks certain elements as invalid or masked. This allows you to work with data that has missing or invalid values without having to modify the original data. Masked arrays are particularly useful when dealing with real-world datasets that may have missing or unreliable data points.

**[⬆ Back to Top](#questions)**

229. ## What are some of the limitations of NumPy.

NumPy is a powerful library for numerical and scientific computing in Python but it have some limitations depending on some requirements. Here are some of the limitations of NumPy.

- Homogeneous Data Types
- Memory Usage
- Single-threaded
- Limited Support for Missing Data
- Limited Support for Labeling Data
- Limited Support for Advanced Statistics
- Performance Overheads for Small Arrays
- Limited Support for GPU Acceleration
- Complex Installation for Some Platforms
- Limited Support for Distributed Computing

**[⬆ Back to Top](#questions)**

230. ## How do you sort a NumPy array in ascending or descending order?

To arrange a NumPy array in both ascending and descending order we use numpy.sort() to create an ascending one and numpy.argsort() for a descending one. Here’s how to do it:

**Ascending Order:**

You can use the sort function that numpy offers to sort your array in ascending order. The function will return a new sorted array, while still leaving the original array unchanged.

```python
# Create a NumPy array

my_array = np.array([3, 1, 2, 4, 5])

# Sort the array in ascending order

sorted_array = np.sort(my_array)
```

**Sorting in Descending Order:**

To sort a NumPy array in descending order, you can use the numpy.argsort() function to obtain the indices that would sort the array in ascending order and then reverse those indices to sort in descending order.

```python
# Create a NumPy array

my_array = np.array([3, 1, 2, 4, 5])

# Get the indices to sort the array in ascending order

ascending_indices = np.argsort(my_array)
```

**[⬆ Back to Top](#questions)**

231. ## How to use NumPy with Matplotlib?

NumPy provides powerful array manipulation capabilities, and Matplotlib is a popular library for creating various types of plots and charts. Here's how you can use NumPy with Matplotlib:

```python
x = np.linspace(0, 2 \* np.pi, 100)
y = np.sin(x)

# Create a basic line plot

plt.plot(x, y)
```

**[⬆ Back to Top](#questions)**

232. ## What is the use of diag() square matrix ?

The diag() function in NumPy is used to extract or manipulate the diagonal elements of a square matrix (a matrix with the same number of rows and columns). It can serve various purposes in matrix operations and linear algebra. Here are some common uses of the diag() function:

**[⬆ Back to Top](#questions)**

233. ## How are NumPy Arrays better than Lists in Python?

NumPy arrays offer several advantages over Python lists when it comes to numerical and scientific computing. Here are some key reasons why NumPy arrays are often preferred:

- Performance
- Vectorization
- Broadcasting
- Multidimensional Arrays
- Memory Management
- Standardization

**[⬆ Back to Top](#questions)**

234. ## what is negative indexing in NumPy arrays?

Negative­ indexing in NumPy arrays allows individuals to access ele­ments from the end of an array by using ne­gative integers as indice­s. This feature offers a conve­nient way to retrieve­ elements re­lative to the array's end, without the­ need for precise­ knowledge of its length. In NumPy, -1 corre­sponds to the last eleme­nt, -2 refers to the se­cond-to-last element, and so forth.

**[⬆ Back to Top](#questions)**

235. ## Can you create a plot in NumPy?

Using NumPy and Matplotlib together, you can create a simple plot. NumPy is primarily a library for numerical computations with arrays, while Matplotlib is a popular Python library for creating various plots and charts. To create a plot, first import NumPy and Matplotlib, then use the functions from both libraries.

```python
# Create any sample data using NumPy

x = np.linspace(0, 2 * np.pi, 100) #generate 100 points between 0 and 2*pi
y = np.sin(x) #compute the sine of each point
plt.plot(x,y,label = 'Sine Wave') #plotting the sine wave
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.legend()
plt.grid(True)
#show the plot
plt.show()
```

**[⬆ Back to Top](#questions)**

236. ## Discuss uses of vstack() and hstack() functions?

The vstack() and hstack() functions in NumPy are used to stack or concatenate arrays vertically and horizontally, respectively. These functions are essential for combining arrays in different dimensions and are widely used in various data processing and manipulation tasks. Here's a discussion of their uses:

**vstack() (Vertical Stack):**

np.vstack() is used to vertically stack or concatenate arrays along the vertical axis (axis 0). This means that it stacks arrays on top of each other.

It is commonly used when you want to combine arrays with the same number of columns (i.e., the same number of features or variables) but different rows (i.e., different data points).

**hstack() (Horizontal Stack):**

np.hstack() is used to horizontally stack or concatenate arrays along the horizontal axis (axis 1). This means that it stacks arrays side by side.

It is commonly used when we want to combine arrays with the same number of rows.

**[⬆ Back to Top](#questions)**

237. ## How does NumPy handle numerical exceptions?

NumPy handles numerical exceptions, such as overflow, underflow, and invalid mathematical operations, in a way that ensures stability and well-defined behavior in numerical computations.

NumPy's handling of numerical exceptions is designed to provide predictable behavior in numerical computations while adhering to standard conventions and IEEE 754 rules. It allows users to work with exceptional cases and maintain control over error handling when needed.

**[⬆ Back to Top](#questions)**

238. ## What is the significance of the random module in NumPy?

The random module in NumPy is a powerful and essential component for generating random numbers and performing various random processes in scientific computing, simulations, statistics, and machine learning. Here are some significant aspects of the random module in NumPy.

**[⬆ Back to Top](#questions)**

239. ## How to Get the eigen values of a matrix.

With the help of np.eigvals() method, we can get the eigen values of a matrix by using np.eigvals() method.

```python
np.eigvals(matrix)
```

**[⬆ Back to Top](#questions)**

240. ## How to Calculate the determinant of a matrix using NumPy?

The Determinant of a square matrix is a unique number that can be derived from a square matrix. Using the numpy.linalg.det() method, NumPy gives us the ability to determine the determinant of a square matrix.

```python
numpy.linalg.det(array)
```

**[⬆ Back to Top](#questions)**

241. ## Find a matrix or vector norm using NumPy.

We employ the numpy.linalg.norm() method of the NumPy Python library to determine a matrix or vector norm. Depending on the value of its parameters, this function returns either one of the seven matrix norms or one of the infinite vector norms.

```python
numpy.linalg.norm(x, ord=None, axis=None)
```

**[⬆ Back to Top](#questions)**

242. ## How to compare two NumPy arrays?

Here, we'll concentrate on the array comparison performed with NumPy. When two NumPy arrays are compared, the presence of the same element at each corresponding index indicates whether the arrays are comparable.

Method 1: We generally use the == operator to compare two NumPy arrays to generate a new array object. Call ndarray.all() with the new array object as ndarray to return True if the two NumPy arrays are equivalent.

Method 2: **Using array_equal()**

This array_equal() function checks if two arrays have the same elements and same shape.

```python
numpy.array_equal(arr1, arr2)
```

**[⬆ Back to Top](#questions)**

243. ## Calculate the QR decomposition of a given matrix using NumPy.

A matrix's decomposition into the form "A=QR," where Q is an orthogonal matrix and R is an upper-triangular matrix, is known as QR factorization. With the aid of numpy, we can determine the QR decomposition of a given matrix.linalg.qr().

```python
numpy.linalg.qr(a, mode=’reduced’)
```

a : matrix(M,N) which needs to be factored.

mode : it is optional.

**[⬆ Back to Top](#questions)**

244. ## How to filter out integers from float NumPy array.

The aim is to remove integers from an array that contains float and integers using a numpy array. Let's look at a couple approaches to completing a task.

- Using astype(int)
- Using np.equal() and np.mod()
- Using np.isclose()
- Using round()

**[⬆ Back to Top](#questions)**

245. ## Define a polynomial function.

Using NumPy's numpy.poly1d class, you can define polynomial functions. Using the coefficients of a polynomial, we can create a new function using this class. In NumPy, define a polynomial function as follows:

```python
numpy.poly1d(arr, root, var)
```

**[⬆ Back to Top](#questions)**

246. ## What are ndarrays in NumPy?

An ndarray (short for "N-dimensional array") is a fundamental data structure used in NumPy (Numerical Python) for effectively storing and manipulating data, particularly numerical data. It offers a multidimensional, homogeneous array with a variety of capabilities for mathematical and array-oriented operations and is the fundamental building block of the NumPy library.

**[⬆ Back to Top](#questions)**

247. ## What are the main features that make NumPy unique.

Due to a number of distinguishing characteristics, NumPy (Numerical Python) is a distinctive and crucial library in the Python ecosystem for numerical and scientific computing.

The ndarray (N-dimensional array), a very effective, homogeneous, and multi-dimensional data structure, is introduced by NumPy. An ndarray's same data types enable for memory-efficient storage and mathematical operations that are optimised.

**[⬆ Back to Top](#questions)**

248. ## What is the difference between shape and size attributes of NumPy array.

Shape and size attributes of an array give information about the dimension of the array but there are some differences.

| **Aspect**           | **Shape**                                                                                                                                                                                   | **Size**                                                                                                                                                                        |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Definition**       | The array's dimensions are represented by a tuple that the shape attribute returns. The size of the array along each axis or dimension is represented by an individual member of the tuple. | The attribute `size` gives the total number of elements in the array, regardless of its shape. It provides a single integer value representing the size of the flattened array. |
| **Details Provided** | Gives details about the array's dimensions, including the number of rows, columns, and other dimensions.                                                                                    | Provides the total count of elements in the array.                                                                                                                              |
| **Result**           | Represented by a tuple, where each element corresponds to the size along a specific dimension.                                                                                              | Calculated as the product of all elements in the shape tuple.                                                                                                                   |
| **For 1D Arrays**    | A single element serves as the array's length in the shape tuple.                                                                                                                           | Represents the overall element count in the array.                                                                                                                              |

**[⬆ Back to Top](#questions)**

249. ## What are some important differences between the standard Python sequences and NumPy arrays?

The key distinctions between NumPy arrays and common Python sequences (such as lists and tuples) make NumPy arrays the best option for numerical and scientific computing. Here are some significant variations:

While NumPy arrays are homogeneous and require that every member have the same data type, Python sequences can hold items of various data types. In NumPy, this homogeneity enables effective storage and optimised operations.

**[⬆ Back to Top](#questions)**

250. ## What are Universal functions in NumPy?

The core building block of NumPy (Numerical Python), universal functions, or "ufuncs," allow for effective element-wise operations on ndarrays (N-dimensional arrays). Ufuncs in NumPy are functions that work on ndarray items, allowing you to efficiently and vectorizely carry out operations like exponentiation, trigonometry, and more.

**[⬆ Back to Top](#questions)**

251. ## What are the difference between ndarray and array in NumPy.

The terms "ndarray" and "array" in NumPy essentially refer to the same object: a multi-dimensional array object that makes it possible to effectively conduct mathematical operations on data. While "array" is a more casual term that is frequently used in everyday speech and documentation to refer to NumPy arrays, "ndarray" is the official term used within NumPy. Both terms refer to the same data structure that NumPy uses for effective numerical computations.

**ndarray**

- The official NumPy word for a multi-dimensional array is "ndarray".
- In particular, it alludes to the NumPy array object.
- You generate "ndarray" objects when you use NumPy functions or constructors to create arrays, such as np.array(), np.zeros(), or np.ones().

**array**

- While it is not the official nomenclature, the word "array" is frequently used informally to refer to NumPy arrays.
- In reality, when people use the word "array" in relation to NumPy, they often mean "ndarray."

**[⬆ Back to Top](#questions)**

252. ## How would you convert a pandas dataframe into NumPy array.

You can use the DataFrame's.values attribute to convert a Pandas DataFrame into a NumPy array.

```python
import pandas as pd
import numpy as np

# Create a Pandas DataFrame (replace this with your actual DataFrame)

data = {'A': [1, 2, 3], 'B': [4, 5, 6]}
df = pd.DataFrame(data)

# Convert the DataFrame to a NumPy array

numpy_array = df.values
```

**[⬆ Back to Top](#questions)**

253. ## Explain vectorization in NumPy.

In NumPy, the term "vectorization" refers to the capacity to carry out element-wise operations on whole arrays or sizable sections of arrays without the use of explicit Python loops. You can perform a single action on the entire array or a sizable section of it all at once rather than iterating through each element in an array one at a time. This idea is comparable to how operations on vectors or matrices operate in linear algebra.

**[⬆ Back to Top](#questions)**

254. ## How would you reverse a numpy array?

We can reverse a NumPy array using the [::-1] slicing technique.

```python
import numpy as np

# Create a NumPy array (replace this with your array)

original_array = np.array([1, 2, 3, 4, 5])

# Reverse the array

reversed_array = original_array[::-1]

print(reversed_array)
```

**[⬆ Back to Top](#questions)**

255. ## How do you remove missing or null values from a NumPy array?

Unlike Pandas DataFrames, NumPy arrays do not by default support missing or null values. However, you may achieve a similar feature by filtering out missing or null data using a masked array or a boolean mask.

Using Masked array:

```python
import numpy as np

# Create a NumPy array with missing values (NaN)

arr = np.array([1.0, 2.0, np.nan, 4.0, 5.0])

# Create a masked array where missing values are masked

masked_arr = np.ma.masked_invalid(arr)

# Access only non-missing values

clean_data = masked_arr.compressed()

print(clean_data)
```

**[⬆ Back to Top](#questions)**

256. ## What is the difference between slicing and indexing in NumPy?

**Indexing**

- In NumPy, the term "indexing" refers to the process of choosing particular elements or groups of elements from an array according to their precise places, generally by using integers or boolean masks.
- You can use it to access and change individual items or particular elements at predetermined locations in the array.
- When you wish to locate and change or remove particular values in the array based on their positions, indexing might be handy for focused data cleaning operations.
- For instance, indexing can be used to set specific items to NaN (not-a-number) for missing data or to replace all negative values with zeros.

**Slicing**

- Using a range of indices or a boolean mask, slicing entails extracting a continuous portion of an array.
- It enables you to build an array from a portion of the original data, which is helpful for extracting particular rows or columns.
- When you want to filter and extract rows or columns that fit specific criteria or when you only want to work with a section of the data, slicing is useful for cleaning the data.
- Slicing, for instance, can be used to choose rows that meet particular criteria, such as all rows where values in a particular column are greater than a predetermined threshold.

**[⬆ Back to Top](#questions)**

257. ## How do you create a masked array in NumPy, and what is its purpose?

The np.ma.masked_array() function in NumPy is used to build a masked array. It is useful when dealing with data when some numbers are regarded as "masked" or "invalid" and ought to be left out of calculations. When dealing with missing data or poor data quality, masked arrays are very helpful since they let you conduct operations while disregarding the masked values.

```python
import numpy as np

# Create a NumPy array with some missing or invalid values (e.g., -999)

data = np.array([1, 2, -999, 4, -999, 6])

# Create a masked array where -999 is considered masked (invalid)

masked_data = np.ma.masked_array(data, mask=(data == -999))
```

In conclusion, a masked array in NumPy is a useful tool for working with data that contains blank or incorrect values. It enables you to perform operations on legitimate data while excluding masked numbers, guaranteeing that the data used in your calculations and analysis is accurate.

**[⬆ Back to Top](#questions)**

258. ## What are some common techniques for normalizing data in a NumPy array?

Data analysis and machine learning frequently utilize normalization, a preprocessing method, to scale data to a standard range, usually between 0 and 1, or with a mean of 0 and a standard deviation of 1. Many machine learning algorithms can perform better with the aid of normalized data, which also ensures that features with various scales contribute equally to the study.

Some common technique are:

- Min-Max Scaling
- Z-Score Normalization (Standardization)
- Log Transformation
- Box-Cox Transformation
- Robust Scaling

**[⬆ Back to Top](#questions)**

259. ## How do you remove missing or null values from a NumPy array?

Unlike Pandas DataFrames, NumPy arrays do not by default support missing or null values. However, you may deal with missing values in NumPy arrays by either filtering them out or by replacing them with suitable values.

Replacing Missing values:

```python
import numpy as np

# Create a NumPy array with missing values

arr = np.array([1, 2, -999, 4, -999, 6])

# Replace -999 with a specific value

arr[arr == -999] = 0
Q60 Create a two 2-D array. Plot it using matplotlib.
import NumPy
print(“Printing Original array”)
sampleArray = NumPy.array([[34,43,73],[82,22,12],[53,94,66]])
print (sampleArray)
print(“Array after deleting column 2 on axis 1”)
sampleArray = NumPy.delete(sampleArray , 1, axis = 1)
print (sampleArray)
arr = NumPy.array([[10,10,10]])
print(“Array after inserting column 2 on axis 1”)
sampleArray = NumPy.insert(sampleArray , 1, arr, axis = 1)
print (sampleArray)
```

**[⬆ Back to Top](#questions)**

261. ## What is difference between NumPy and Pandas?

The main goal of NumPy is to enable huge, multi-dimensional arrays and matrices while also offering a range of mathematical operations that may be used effectively to these arrays. It serves as the basis for Python's numerical computations.

On the other hand, Pandas is based on NumPy and intended for data analysis and manipulation. Series and DataFrame, two fundamental data structures that are effective for managing structured data types like spreadsheets and SQL tables, are introduced. With its high-level features, Pandas makes data cleaning, transformation, and analysis simple. It is also frequently used for data exploration and manipulation jobs.

In conclusion, NumPy and Pandas are both crucial Python tools for data analysis, but NumPy concentrates on numerical computing using arrays, while Pandas is an expert in data manipulation and analysis with

**[⬆ Back to Top](#questions)**

262. ## Why NumPy is faster than list?

The following justifies why Python Lists are slower than NumPy Arrays:

Due to its uniform data type storage, which enables best memory consumption and effective vectorized operations, NumPy is quicker than lists. Compared to Python's interpreted code, NumPy offers faster execution because it is implemented in C. It makes use of parallel processing capabilities and well optimized numerical algorithms to speed up numerical computations. Its memory management guarantees improved cache locality and utilization. The combination of NumPy with compiled languages also improves performance for computationally demanding jobs.

**[⬆ Back to Top](#questions)**

263. ## How do you check for an empty (zero Element) array?
     If the variable is an array, you can use the size attribute to determine whether the array is empty. The variable might, however, be of the list or sequence type in which case len() can be used. The size attribute is the best technique to look for a zero element.

```python
> > > a = NumPy.zeros((1,0))
> > > a.size
 0
 whereas
> > > len(a)
 1
```

**[⬆ Back to Top](#questions)**

264. ## What is the procedure to count the number of times a given value appears in an array of integers?

The bincount() function can be used to count the instances of a given value. It should be noted that the bincount() function takes boolean expressions or positive integers as arguments. Integers that are negative cannot be used.

Implement NumPy.bincount().

```python
arr = NumPy.array([0, 5, 4, 0, 4, 4, 3, 0, 0, 5, 2, 1, 1, 9])
NumPy.bincount(arr)
```

**[⬆ Back to Top](#questions)**

265. ## How can you sort an array in NumPy?

The sort function in NumPy can be used to sort an array. This function arranges the members of an array in ascending order while altering the array already in use. As a result, it sorts the array itself rather than returning a new sorted array.

```python
import numpy as np

# Create an unsorted array

arr = np.array([3, 2, 1])

# Sort the array

arr.sort()

# Print the sorted array

print(arr)
```

**[⬆ Back to Top](#questions)**

266. ## How can you find the maximum or minimum value of an array in NumPy?

Using the max and min functions, you may determine an array's maximum or minimum value in NumPy. These operations accept an array as an input and output the array's maximum or minimum value.

```python
import numpy as np

# Create an array

arr = np.array([3, 2, 1])

# Find the maximum value of the array

max_value = np.max(arr)

# Find the minimum value of the array

min_value = np.min(arr)

# Print the maximum and minimum values

print(max_value)
print(min_value)
```

**[⬆ Back to Top](#questions)**

267. ## how slicing and indexing can be used for data cleaning?

In this example, negative values are located and replaced with zeros using indexing, and a new array with more than two members is created using slicing. Both indexing and slicing are useful methods for cleaning data because they let you modify or filter data based on particular criteria or target particular data points for modification.

```python
import numpy as np

# Sample NumPy array

data = np.array([1, 2, -1, 4, 5, -2, 7])

# Indexing: Replace negative values with zeros

data[data < 0] = 0

# Slicing: Extract elements greater than 2

subset = data[data > 2]
```

**[⬆ Back to Top](#questions)**

268. ## What is the difference between using the shape and size attributes of a NumPy array?

A tuple that describes the size of the array along each dimension is the shape attribute of a NumPy array. For instance, an array of the shape (3, 4) has 3 rows and 4 columns. The array's dimensions can be found by using the form attribute, or the array can be reshaped by altering the sizes of the individual dimensions.

```python
import numpy as np

# Create a NumPy array

arr = np.array([[1, 2, 3, 4], [5, 6, 7, 8], [9, 10, 11, 12]])

# Get the shape of the array

shape = arr.shape
print(shape) # Output: (3, 4)

# Access the individual dimensions

num_rows = shape[0]
num_cols = shape[1]
print(num_rows)
print(num_cols)
```

A NumPy array's size attribute gives the total number of elements in the array. This is just the sum of the array's various dimensions' sizes. For instance, an array with the shape (3, 4) has 3 \* 4 = 12 elements overall.

```python
import numpy as np

# Create a NumPy array

arr = np.array([[1, 2, 3, 4], [5, 6, 7, 8], [9, 10, 11, 12]])

# Get the size of the array

size = arr.size
print(size) # Output: 12

# Calculate the size manually

num_rows = arr.shape[0]
num_cols = arr.shape[1]
size = num_rows \* num_cols
print(size)
```

**[⬆ Back to Top](#questions)**

269. ## What is a NumPy array and how is it different from a NumPy matrix?

In a contiguous block of memory, NumPy arrays are data structures that hold values of the same data type. Similar to Python lists, they may hold values of any data type and are more effective for some tasks. Shape, size, and dtype are a few useful properties of umPy arrays. The array's size along each dimension is specified by a tuple that the shape attribute returns. The array's total number of elements is returned by the size attribute. The data type of each element in the array is returned by the dtype property.

- A additional data type called a matrix, a subclass of the array data type, is also included in NumPy. Similar to a NumPy array, a NumPy matrix includes a few more properties that make it more practical for linear algebra operations.
- Arrays employ the element-wise _ operator, whereas matrices contain a distinct _ operator for matrix multiplication.
- Additionally, matrices provide attributes for inverse and transpose, respectively.

**[⬆ Back to Top](#questions)**

270. ## How can you find the unique elements in an array in NumPy?

Apply the unique function from the NumPy module to identify the unique elements in an array in NumPy. This function returns the array's unique elements in sorted order, along with a count of how many times each element occurred.

```python
import numpy as np
array = np.array([1, 2, 3, 1, 2, 3, 3, 4, 5, 6, 7, 5])
unique, counts = np.unique(array, return_counts=True)
print(unique)
print(counts)
```

The unique items of the input array array are contained in this example's output arrays unique and counts, along with a count of each element.

271. ## What is _NumPy_, and why is it important in _Machine Learning_?

**NumPy** (Numerical Python) is a fundamental library in Python for numerical computations. It's a versatile tool primarily used for its advanced **multi-dimensional array support**.

### Key Features

- **Task-Specific Modules**: NumPy offers a rich suite of mathematical functions in areas such as linear algebra, Fourier analysis, and random number generation.

- **Performance and Speed**:

  - Enables vectorized operations.
  - Many of its core functions are implemented in `C` for optimized performance.
  - It uses contiguous blocks of memory, providing efficient caching and reducing overhead during processing.

- **Broadcasting**: NumPy allows combining arrays of different shapes during arithmetic operations, facilitating streamlined computation.

- **Linear Algebra**: It provides essential linear algebra operations, including matrix multiplication and decomposition methods.

### NumPy Arrays

- **Homogeneity**: NumPy arrays are homogeneous, meaning they contain elements of the same data type.
- **Shape Flexibility**: Arrays can be reshaped for specific computations without data duplication.
- **Simple Storage**: They use efficient memory storage and can be created from regular Python lists.

### Performance Benchmarks

1. **Contiguous Memory**: NumPy arrays ensure that all elements in a multi-dimensional array are stored in contiguous memory blocks, unlike basic Python lists.

2. **No Type Checking**: NumPy arrays are specialized for numerical data, so they don't require dynamic type checks during operations.

3. **Vectorized Computing**: NumPy obviates the need for manual looping, making computations more efficient.

### Code Example: NumPy and Efficiency

Here is the Python code:

```python
# Using Python Lists
python_list1 = [1, 2, 3, 4, 5]
python_list2 = [6, 7, 8, 9, 10]
result = [a + b for a, b in zip(python_list1, python_list2)]

# Using NumPy Arrays
import numpy as np
np_array1 = np.array([1, 2, 3, 4, 5])
np_array2 = np.array([6, 7, 8, 9, 10])
result = np_array1 + np_array2
```

In the above example, both cases opt for element-wise addition, yet the NumPy version is more concise and efficient.
<br>

**[⬆ Back to Top](#questions)**

272. ## Explain how _NumPy arrays_ are different from _Python lists_.

**NumPy arrays** and **Python lists** are both versatile **data structures**, but they have distinct advantages and use-cases that set them apart.

### Key Distinctions

#### Storage Mechanism

- **Lists**: These are general-purpose and can store various data types. Items are often stored contiguously in memory, although the list object itself is an array of references, allowing flexibility in item sizes.
- **NumPy Arrays**: These are designed for homogeneous data. Elements are stored in a contiguous block of memory, making them more memory-efficient and offering faster element access.

#### Underlying Optimizations

- **Lists**: Are not specialized for numerical operations and tends to be slower for such tasks. They are dynamic in size, allowing for both append and pop.
- **NumPy Arrays**: Are optimized for numerical computations and provide vectorized operations, which can dramatically improve performance. Array size is fixed upon creation.

### Performance Considerations

- **Memory Efficiency**: NumPy arrays can be more memory-efficient, especially for large datasets, because they don't need to store type information for each individual element.
- **Element-Wise Operations**: NumPy's vectorized operations can be orders of magnitude faster than traditional Python loops, which are used for element-wise operations on lists.
- **Size Flexibility**: Lists can grow and shrink dynamically, which may lead to extra overhead. NumPy arrays are more memory-friendly in this regard.

#### Use in Machine Learning

- **Python Lists**: Typically used for general data-handling tasks, such as reading in data before converting it to NumPy arrays.
- **NumPy Arrays**: The foundational data structure for numerical data in Python. Most numerical computing libraries, including TensorFlow and scikit-learn, work directly with NumPy arrays.
  <br>

**[⬆ Back to Top](#questions)**

273. ## What are the main _attributes_ of a _NumPy ndarray_?

A NumPy `ndarray` is a multi-dimensional array that offers efficiency in numerical operations. Much of its strength comes from its **resilience with large datasets** and **agility in mathematical computations**.

### Main Attributes

- **Shape**: A tuple representing the size of each dimension.
- **Data Type (dtype)**: The type of data stored as elements in the array.
- **Strides**: The number of bytes to "jump" in memory to move from one element to the next in each dimension.

### NumPy Examples:

#### Shape Attribute

```python
import numpy as np

# 1D Array
v = np.array([1, 2, 3])
print(v.shape)  # Output: (3,)

# 2D Array
m = np.array([[1, 2, 3], [4, 5, 6]])
print(m.shape)  # Output: (2, 3)
```

#### Data Type Attribute

```python
import numpy as np

arr_int = np.array([1, 2, 3])
print(arr_int.dtype)  # Output: int64

arr_float = np.array([1.0, 2.5, 3.7])
print(arr_float.dtype)  # Output: float64
```

#### Strides Attribute

The **strides** attribute defines how many bytes one must move in memory to go to the next element along each dimension of the array. If **`x.strides = (10,1)`**, this means that:

- Moving one element in the last dimension, we move **1** byte in memory --- as it is a **float64**.
- Moving one element in the first dimension, we move **10** bytes in memory.

```python
import numpy as np

x = np.array([[1, 2, 3], [4, 5, 6]], dtype=np.int16)
print(x.strides)  # Output: (6, 2)
```

<br>

**[⬆ Back to Top](#questions)**

274. ## How do you create a _NumPy array_ from a regular _Python list_?

### Problem Statement

The task is to create a **NumPy array** from a standard Python list.

### Solution

Several routes exist to transform a standard Python list into a NumPy array. Regardless of the method, it's crucial to have the `numpy` package installed.

#### Using `numpy.array()`

This is the most straightforward method.

#### Implementation

Here, I demonstrate how to convert a basic Python list to a NumPy array with `numpy.array()`. While it works for most cases, be cautious with nested lists as they have significant differences in behavior compared to Python lists.

#### Code

Here's the Python code:

```python
import numpy as np

python_list = [1, 2, 3]

numpy_array = np.array(python_list)
print(numpy_array)
```

#### Output

The output displays the NumPy array `[1 2 3]`.

#### Using `numpy.asarray()`

This is another method to convert a Python list into a NumPy array. The difference from `numpy.array()` is primarily in how it handles inputs like other NumPy arrays and nested lists.

#### When to Use `numpy.asarray()`

The function `numpy.asarray()` is beneficial when you're uncertain whether the input is a NumPy array or a list. It converts non-array types to arrays but leaves already existing NumPy arrays unchanged.

#### Using `numpy.fromiter()`

This method is useful when you have an iterable and want to create a NumPy array from its elements. An important point to consider is that the iterable is consumed as part of the array-creation process.

#### Using `numpy.arange()` and `numpy.linspace()`

If your intention is to create sequences of numbers, such as equally spaced data for plotting, NumPy offers specialized methods.

- `numpy.arange(start, stop, step)` generates an array with numbers between `start` and `stop`, using `step` as the increment.
- `numpy.linspace(start, stop, num)` creates an array with `num` equally spaced elements between `start` and `stop`.
  <br>

**[⬆ Back to Top](#questions)**

275. ## Explain the concept of _broadcasting_ in _NumPy_.

**Broadcasting** in NumPy is a powerful feature that enables efficient operations on arrays of different shapes without explicit array replication. It works by duplicating the elements along different axes and then carrying out the operation through these 'virtual' repetitions.

### Broadcasting Mechanism

1. **Axes Alignment**: Arrays with fewer dimensions are padded with additional axes on their leading side to match the shape of the other array.

2. **Compatible Dimensions**: For two arrays to be broadcast-compatible, at each axis, their sizes are either equal or one of them is 1.

### Example: Adding Scalars to Arrays

When adding a scalar to an array, it's as if the scalar is broadcast to match the shape of the array before the addition:

```python
import numpy as np

arr = np.array([1, 2, 3])
scalar = 10
result = arr + scalar

print(result)  # Outputs: [11, 12, 13]
```

### Visual Representation

The example below demonstrates what happens at each step of the **three-dimensional** array addition `arr` + `addition_vector`:

```python
import numpy as np

arr = np.array(
    [
        [[1, 2, 3], [4, 5, 6]],
        [[7, 8, 9], [10, 11, 12]]
    ]
)

addition_vector = np.array([1, 10, 100])
sum_result = arr + addition_vector

print(f"Array:\n{arr}\n\nAddition Vector:\n{addition_vector}\n\nResult:\n{sum_result}")
```

The broadcasting process, along with the output, is visually depicted in the code.

### Real-world Application: Visualizing Multidimensional Data

NumPy broadcasting is invaluable in applications where visualizing or analyzing **multidimensional named data** is essential, permitting easy manipulations without resorting to loops or explicit data copying.

For instance, matching a three-dimensional RGB image (represented by a 3D NumPy array) with a 1D intensity array prior to modifying the image's pixels is simplified through broadcasting.
<br>

**[⬆ Back to Top](#questions)**

276. ## What are the _data types_ supported by _NumPy arrays_?

**NumPy** deals with a variety of data types, which it refers to as **dtypes**.

### NumPy Data Types

NumPy data types build upon the primitive types offered by the machine:

1. **Basic Types**: `int`, `float`, and `bool`.
2. **Floating Point Types**: `np.float16`, `np.float32`, and `np.float64`.

3. **Complex Numbers**: `np.complex64` and `np.complex128`.
4. **Integers**: `np.int8`, `np.int16`, `np.int32`, and `np.int64`, along with their unsigned variants.
5. **Boolean**: Represents `True` or `False`.

6. **Strings**: `np.str_`.

7. **Datetime64**: Date and time data with time zone information.

8. **Object**: Allows any data type.
9. **Categories and Structured Arrays**: Specialized for categorical data and structured records.

**NumPy** enables you to define arrays with the specific data types:

```python
import numpy as np

my_array = np.array([1, 2, 3])  # Defaults to int64
float_array = np.array([1.5, 2.5, 3.5], dtype=np.float16)
bool_array = np.array([True, False, True], dtype=np.bool)

# Specifying the dtype of string
str_array = np.array(['cat', 'dog', 'elephant'], dtype=np.str_)
```

<br>

**[⬆ Back to Top](#questions)**

277. ## How do you inspect the _shape_ and _size_ of a _NumPy array_?

You can examine the **shape** and **size** of a NumPy array using two key attributes: `shape` and `size`.

### Code Example: Shape and Size Attributes

Here is the Python code:

```python
import numpy as np

# Create a 2D array
arr = np.array([[1, 2, 3], [4, 5, 6]])

# Access shape and size attributes
shape = arr.shape
size = arr.size

print("Shape:", shape)  # Outputs: (2, 3)
print("Size:", size)    # Outputs: 6
```

<br>

**[⬆ Back to Top](#questions)**

278. ## What is the difference between a _deep copy_ and a _shallow copy_ in _NumPy_?

In NumPy, you can create **shallow** and **deep** copies using the `.copy()` method.

Each type of copy preserves ndarray data in a different way, impacting their link to the original array and potential impact of one on the other.

### Shallow Copy

A shallow copy creates a new array object, but it does not duplicate the actual **data**. Instead, it points to the data of the original array. Modifying the shallow copy will affect the original array and vice versa.

The shallow copy is a view of the original array. You can create it either by calling `.copy()` method on an array or using a slice operation.

Here is an example:

```python
import numpy as np

original = np.array([1, 2, 3])
shallow = original.copy()

# Modifying the shallow copy
shallow[0] = 100  # Modifications do not affect the original
print(shallow)  # [100, 2, 3]
print(original)  # [1, 2, 3]

# Modifying the original
original[1] = 200
print(shallow)  # [100, 200, 3]  # The shallow copy is affected
print(original)  # [1, 200, 3]
```

### Deep Copy

A deep copy creates a new array as well as creates separate copies of arrays and their data. **Modifying a deep copy does not affect the original array**, and vice versa.

In NumPy, you can achieve a deep copy using the same `.copy()` method but with the `order='K'` parameter, or by using `np.array(array, copy=True)`. Here is an example:

```python
import numpy as np

# For a 1D array:
original_deep = np.array([1, 2, 3], copy=True)  # This creates a deep copy
original_deep[0] = 100  # Modifications do not affect the original
print(original_deep)  # [100, 2, 3]
print(original)  # [1, 2, 3]

# For a 2D array:
original_2d = np.array([[1, 2], [3, 4]])
deep_2d = original_2d.copy(order='K')  # Deep copy with 'K'
deep_2d[0, 0] = 100
print(deep_2d)  # [[100, 2], [3, 4]]
print(original_2d)  # [[1, 2], [3, 4]]
```

<br>

**[⬆ Back to Top](#questions)**

279. ## How do you perform _element-wise operations_ in _NumPy_?

**Element-wise operations** in NumPy use broadcasting to efficiently apply a single operation to multiple elements in a NumPy array.

### Key Functions

- **Basic Math Functions**: `np.add()`, `np.subtract()`, `np.multiply()`, `np.divide()`, `np.power()`, `np.mod()`
- **Trigonometric Functions**: `np.sin()`, `np.cos()`, `np.tan()`, `np.arcsin()`, `np.arccos()`, `np.arctan()`
- **Rounding**: `np.round()`, `np.floor()`, `np.ceil()`, `np.trunc()`
- **Exponents and Logarithms**: `np.exp()`, `np.log()`, `np.log10()`
- **Other Elementary Functions**: `np.sqrt()`, `np.cbrt()`, `np.square()`
- **Absolute and Sign Functions**: `np.abs()`, `np.sign()`
- **Advanced Array Operations**: `np.dot()`, `np.inner()`, `np.outer()`

### Example: Basic Math Operations

Here is the Python code:

```python
import numpy as np

# Generating the arrays
arr1 = np.array([1, 2, 3, 4])
arr2 = np.array([5, 6, 7, 8])

# Element-wise addition
print(np.add(arr1, arr2))  # Output: [ 6  8 10 12]

# Element-wise subtraction
print(np.subtract(arr1, arr2))  # Output: [-4 -4 -4 -4]

# Element-wise multiplication
print(np.multiply(arr1, arr2))  # Output: [ 5 12 21 32]

# Element-wise division
print(np.divide(arr2, arr1))  # Output: [5.         3.         2.33333333 2.        ]

# Element-wise power
print(np.power(arr1, 2))  # Output: [ 1  4  9 16]

# Element-wise modulo
print(np.mod(arr2, arr1))  # Output: [0 0 1 0]
```

<br>

**[⬆ Back to Top](#questions)**

280. ## What are _universal functions_ (_ufuncs_) in _NumPy_?

In **NumPy**, a **Universal Function** (ufunc) is a function that operates element-wise on **ndarrays**, optimizing performance.

Whether it's a basic arithmetic operation, advanced math function, or a comparison, ufuncs are designed to process data fast.

### Key Features

- **Element-Wise Operation**: Ufuncs process each element in an ndarray individually. This technique reduces the need for explicit loops in Python, leading to enhanced efficiency.

- **Broadcasting**: Ufuncs integrate seamlessly with **NumPy's broadcasting rules**, making them versatile.

- **Code Optimization**: These functions utilize low-level array-oriented operations for optimized execution.

- **Type Conversion**: You can specify the data type for output ndarray, or let NumPy determine the optimal type automatically for you.

- **Multi-Threaded Execution**: Ufuncs are highly compatible with multi-threading to expedite computation.

### Ufunc Categories

1. **Unary Ufuncs**: Operate on a single ndarray.

   Example: $\exp(5)$

2. **Binary Ufuncs**: Perform operations between two distinct arrays.

   Example: $10 + \cos(\text{{arr1}})$

### Code Example: Unique Advantages of Using Ufuncs

- Ufuncs Empower Faster Computing:

  - Regex and String Operations: Ufuncs are quicker and more efficient compared to list comprehension and string methods.
  - Set Operations: Ufuncs enable rapid union, intersection, and set difference with ndarrays.

- Enhanced NumPy Functions:
  - Log and Exponential Functions: NumPy provides faster and more accurate methods than standard Python math functions.
  - Trigonometric Functions: Ufuncs are vectorized, offering faster calculations for arrays of angles.
  - Special Functions: NumPy features an array of special mathematical functions, including Bessel functions and gamma functions, optimized for array computations.

```python
import numpy as np

arr = np.array([1, 2, 3])

# Using ".prod()" reduces redundancy and accelerates functional operation.
result = arr.prod()
print(result)

# Accessing unique elements via ufunc "np.unique" is more streamlined and quicker.
unique_elements = np.unique(arr)
print(unique_elements)
```

<br>

**[⬆ Back to Top](#questions)**

281. ## How do you perform _matrix multiplication_ using _NumPy_?

### Problem Statement

The task is to explain how to perform **matrix multiplication** using **NumPy**.

### Solution

NumPy's `np.dot()` function or the `@` operator is used for both **matrix multiplication** and **dot product**.

#### Matrix Multiplication

Two matrices are multiplied using the `np.dot()` function.

- $C = A \times B$ where $A$ is a $2 \times 3$ matrix and $B$ is a $3 \times 2$ matrix.

$$
C = \begin{bmatrix} A_{11} & A_{12} & A_{13} \\ A_{21} & A_{22} & A_{23} \end{bmatrix} \times \begin{bmatrix} B_{11} & B_{12} \\ B_{21} & B_{22} \\ B_{31} & B_{32} \end{bmatrix}
$$

$$
C = \begin{bmatrix} A_{11} \times B_{11} + A_{12} \times B_{21} + A_{13} \times B_{31} & A_{11} \times B_{12} + A_{12} \times B_{22} + A_{13} \times B_{32} \\ A_{21} \times B_{11} + A_{22} \times B_{21} + A_{23} \times B_{31} & A_{21} \times B_{12} + A_{22} \times B_{22} + A_{23} \times B_{32} \end{bmatrix}
$$

#### Broadcasting in NumPy

NumPy has a built-in capability, known as **broadcasting**, for performing operations on arrays of different shapes. If the shapes of two arrays are not compatible for an element-wise operation, NumPy uses broadcasting to make the shapes compatible.

#### Implementation

Here is the Python code using NumPy:

```python
import numpy as np

A = np.array([[1, 2, 3], [4, 5, 6]])
B = np.array([[7, 8], [9, 10], [11, 12]])

# Matrix Multiplication
C = np.dot(A, B)
# The result is: [[ 58  64] [139 154]]
```

<br>

**[⬆ Back to Top](#questions)**

282. ## Explain how to _invert a matrix_ in _NumPy_.

### Problem Statement

The goal is to **invert a matrix** using NumPy.

### Solution

In NumPy, you can use the `numpy.linalg.inv` function to find the inverse of a matrix.

#### Conditions:

1. The matrix must be square, i.e., it should have an equal number of rows and columns.
2. The matrix should be non-singular (have a non-zero determinant).

#### Algorithm Steps:

1. Import NumPy: `import numpy as np`
2. Define the matrix: `A = np.array([[4, 7], [2, 6]])`
3. Compute the matrix inverse: `A_inv = np.linalg.inv(A)`

#### Implementation

Here's the complete Python code:

```python
import numpy as np

# Define the matrix
A = np.array([[4, 7], [2, 6]])

# Compute the matrix inverse
A_inv = np.linalg.inv(A)
print(A_inv)
```

The output for the given matrix `A` is:

```
[[ 0.6 -0.7]
 [-0.2  0.4]]
```

<br>

**[⬆ Back to Top](#questions)**

283. ## How do you calculate the _determinant_ of a _matrix_?

### Problem Statement

The **determinant** of a matrix is a scalar value that can be derived from the elements of a **square matrix**.

Calculating the determinant of a matrix is a fundamental operation in linear algebra, with applications in finding the **inverse of a matrix**, solving systems of linear equations, and more.

### Solution

#### Method 1: Numerical Calculation

For a numeric $n \times n$ matrix, the determinant is calculated using **Laplace's expansion** along rows or columns. This method is computationally expensive, with a time complexity of $O(n!)$.

#### Method 2: Matrix Decomposition

An alternative, more efficient approach involves using **matrix decomposition** methods such as **LU decomposition** or **Cholesky decomposition**. However, these methods are more complex and are not commonly used for determinant calculation alone.

#### Method 3: NumPy Function

The most convenient and efficient method, especially for large matrices, is to make use of the `numpy.linalg.det` function, which internally utilizes LU decomposition.

#### Implementation

Here is Python code:

```python
import numpy as np

# Define the matrix
A = np.array([[1, 2], [3, 4]])

# Calculate the determinant
det_A = np.linalg.det(A)
print("Determinant of A:", det_A)
```

#### Output

```
Determinant of A: -2.0
```

### Key Insight

The determinant of a matrix is crucial in various areas of mathematics and engineering, including linear transformations, volume scaling factors, and the characteristic polynomial of a matrix, often used in Eigenvalues and Eigenvectors calculations.
<br>

**[⬆ Back to Top](#questions)**

284. ## What is the use of the _axis_ parameter in _NumPy functions_?

The `_axis_` parameter in **NumPy** enables operations to be carried out along a specific axis of a multi-dimensional array, providing more granular control over results.

### Functions with `_axis_` Parameter

Many NumPy functions incorporate the `_axis_` parameter to modify behavior based on the specified axis value.

### Common Functions

- **Math Operations**: Functions such as `mean`, `sum`, `std`, and `min` perform element-wise operations or aggregations, allowing you to focus on specific axes.

- **Array Manipulation**: `concatenate`, `split`, and others enable flexible array operations while considering the specified axis.

- **Numerical Analysis**: Functions like `trapezoid` and `Simpsons` provide integration along a specific axis, especially useful for multi-dimensional datasets.

### Practical Examples

#### Mean Calculation

Suppose you have the following dataset representing quiz scores:

```python
import numpy as np

# Quiz scores for five students across four quizzes
scores = np.array([[8, 6, 7, 9],
                   [4, 7, 6, 8],
                   [3, 5, 9, 2],
                   [4, 6, 2, 8],
                   [5, 2, 7, 9]])
```

You can calculate the mean scores for each quiz with:

```python
# axis=0 calculates the mean along the first dimension (students)
quiz_means = np.mean(scores, axis=0)
```

#### Splitting Arrays

Consider you want to separate a dataset into two based on a specific criterion. You can do this using `split`:

```python
# Assign students into two groups based on the mean quiz score
group1, group2 = np.split(scores, [2], axis=1)
```

In this case, it splits the `scores` array into two arrays at column index 2, resulting in `group1` containing scores from the first two quizzes and `group2` from the last two quizzes.

#### Integration over Multi-dimensional Arrays

NumPy provides functions to integrate arrays along different axes. For example, using the `trapz` function can calculate the area under the curve represented by the array:

```python
# Define a 2D array representing a surface
surface = np.array([[1, 2, 3, 4],
                    [2, 3, 4, 5]])

# Perform integration along axis 0
area_under_curve = np.trapz(surface, axis=0)
```

<br>

**[⬆ Back to Top](#questions)**

285. ## How do you _concatenate_ two _arrays_ in _NumPy_?

### Problem Statement

The task is to combine two $\text{NumPy}$ arrays. Concatenation can occur **horizontally** (column-wise) or **vertically** (row-wise).

### Solution

In `NumPy`, we can concatenate arrays using the `numpy.concatenate()`, `numpy.hstack()`, or `numpy.vstack()` functions.

#### Key Points

- `numpy.concatenate()`: Combines arrays along a specified **axis**.
- `numpy.hstack()`: Stacks arrays horizontally.
- `numpy.vstack()`: Stacks arrays vertically.

Let's explore these methods in more detail.

#### Implementation

Here is the Python code:

```python
import numpy as np

# Sample arrays
arr1 = np.array([[1, 2], [3, 4]])
arr2 = np.array([[5, 6], [7, 8]])

# Concatenation along rows (vertically)
print(np.concatenate((arr1, arr2), axis=0))  # Output: [[1 2] [3 4] [5 6] [7 8]]

# Concatenation along columns (horizontally)
print(np.concatenate((arr1, arr2), axis=1))  # Output: [[1 2 5 6] [3 4 7 8]]

# Stacking horizontally
print(np.hstack((arr1, arr2)))  # Output: [[1 2 5 6] [3 4 7 8]]

# Stacking vertically
print(np.vstack((arr1, arr2)))  # Output: [[1 2] [3 4] [5 6] [7 8]]
```

<br>

**[⬆ Back to Top](#questions)**

# Selenium Interview Question

286. ## What is Selenium?

Selenium is a widely used tool for testing web-based applications that checks if they are doing as expected. It is a prominent preference amongst testers for cross-browser testing and is viewed as one of the most reliable systems for web application automation evaluation.

Selenium is also platform-independent, so it can provide distributed testing using the Selenium Network. Selenium is a powerful tool for controlling web browsers through programs and performing browser automation. It is functional for all browsers, works on all major OS and its scripts are written in various languages.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240529151025/Selenium-features-.webp" alt="Selenium features" width = "50%" height="50%">

**[⬆ Back to Top](#questions)**

287. ## What are the Selenium suite components?

Here are four major Components of Selenium

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240529180052/Components-of-Selenium-660.webp" alt="Selenium features" width = "50%" height="50%">

1. Selenium IDE

Selenium IDE serves as an innovative toolkit for web testing, allowing users to record interactions with web applications. Selenium-IDE was initially created by "Shinya Kasatani" in 2006. Selenium IDE also helps to simplify the testing process. It is a friendly space for testers and developers to team up. This helps everyone quickly share important testing information and results, making things work better and feel accomplished.

2. Selenium RC (Remote control)

Selenium Remote Control (RC) was one of the earliest Selenium tools, preceding WebDriver. It allowed testers to write automated web application tests in various programming languages like Java, C#, Python, etc. The key feature of Selenium RC was its ability to interact with web browsers using a server, which acted as an intermediary between the testing code and the browser.

3. Selenium Web Driver

Selenium WebDriver is a robust open-source framework for automating web browsers, primarily aimed at easing the testing and verification of web applications. As an important part of the Selenium suite, WebDriver offers a programming interface to interact with web browsers, allowing developers and testers to automate browser actions seamlessly.

4. Selenium GRID

Selenium Grid is a server that allows tests to use web browser instances running on remote machines. With Selenium Grid, one server acts as the hub. Tests contact the hub to obtain access to browser instances.

**[⬆ Back to Top](#questions)**

288. ## Mention the advantages of using Selenium as an automation tool.

Selenium mainly used among the automation tools due to its unique benefits, including with being the open-source framework, it will be supporting multiple languages and platforms, and offering easy compatibility with the various browsers, providing flexible frameworks for many more use of the same, It will benefit in enabling reusability, and improving the integrated and parallel test execution.

**[⬆ Back to Top](#questions)**

289. ## What is test automation or automation testing?

Automated Testing means using special software for tasks that people usually do when checking and testing a software product. Nowadays, many software projects use automation testing from start to end, especially in agile and DevOps methods

**[⬆ Back to Top](#questions)**

290. ## What are the advantages of automation testing?

- Simplifies Test Case Execution: Automation testing can be left virtually unattended and thus it allows monitoring of the results at the end of the process. Thus, simplifying the overall test execution and increasing the efficiency of the application.

- Improves Reliability of Tests: Automation testing ensures that there is equal focus on all the areas of the testing, thus ensuring the best quality end product.

- Increases amount of test coverage: Using automation testing, more test cases can be created and executed for the application under test. Thus, resulting in higher test coverage and the detection of more bugs. This allows for the testing of more complex applications and more features can be tested.

- Minimizing Human Interaction: In automation testing, everything is automated from test case creation to execution thus there are no changes for human error due to neglect. This reduces the necessity for fixing glitches in the post-release phase.

- Saves Time and Money: The initial investment for automation testing is on the higher side but it is cost-efficient and time-efficient in the long run. This is due to the reduction in the amount of time required for test case creation and execution which contributes to the high quality of work.

- Earlier detection of defects: Automation testing documents the defects, thus making it easier for the development team to fix the defect and give a faster output. The earlier the defect is identified, the more easier and cost-efficient it is to fix the defects.

**[⬆ Back to Top](#questions)**

291. ## What is Selenese? How is it classified?

Selenese are the sets of commands that are used in Selenium ide to perform various operations on the web. It is majorly used to develop coding scripts in Selenium IDE. The element locator helps Selenium to decide which HTML element a command will refer to.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240530150634/Selenium-commands.webp" alt="Selenium features" width = "50%" height="50%">

- **Actions**: Actions are selenium IDE commands that control the status of an application.
- **Accessors**: Accessors are the selenium commands that are used to check the state of the application and store the result in a variable.
- **Assertions**: Assertions are the selenium commands that enable the testers to check/verify the status of an application.

**[⬆ Back to Top](#questions)**

292. ## What is the difference between Selenium 2.0 and Selenium 3.0?

Selenium 2.0 streamlined creating automated tests for web applications by combining the original Selenium project with the WebDriver project. While Selenium Remote Control (RC) became outdated after the merge, it was still supported for a while to ensure existing tests wouldn't break.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240530152019/selenium2.webp" alt="Selenium features" width = "50%" height="50%">

Building upon Selenium 2.0, Selenium 3.0 brought a range of improvements. It seamlessly worked with older tests while completely removing reliance on Selenium RC. This new version also squashed bugs and made everything more reliable.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240530152214/selenium3.webp" alt="Selenium features" width = "50%" height="50%">

In short, Selenium 3.0 took the strengths of Selenium 2.0, fixed its issues, and made it even better for automating web tests.

**[⬆ Back to Top](#questions)**

293. ## What are the testing types supported by Selenium?

Selenium is a powerful tool for automated web application testing, supporting various testing types to ensure the quality and functionality of your web applications.

Selenium supports the Regression testing and Functional testing and the following key insight of the same.

Regression testing - Regression Testing is the process of testing the modified parts of the code and the parts that might get affected due to the modifications to ensure that no new errors have been introduced in the software after the modifications have been made.

The step involve in the Regression testing which are:

- Identify relevant test cases from existing suites.
- Prioritize test cases based on criticality and priority.
- Execute selected test cases to detect regressions.
- Analyze the test results for failures.
- Report identified defects in bug tracking system.
- Maintain regression test suites as needed.
- Automate regression tests for efficiency.
- Repeat regression testing after each software update.

Functional testing: Functional testing is defined as a type of testing that verifies that each function of the software application works in conformance with the requirement and specification.

The step involve in the Functional testing which are:

- Identify test input: This step involves identifying the functionality that needs to be tested. This can vary from testing the usability functions, and main functions to error conditions.
- Compute expected outcomes: Create input data based on the specifications of the function and determine the output based on these specifications.
- Execute test cases: This step involves executing the designed test cases and recording the output.
- Compare the actual and expected output: In this step, the actual output obtained after executing the test cases is compared with the expected output to determine the amount of deviation in the results.

**[⬆ Back to Top](#questions)**

294. ## What are the different types of annotations which are used in Selenium?

These are the types of TestNG Annotations

- @BeforeSuite - Is executed before the execution of all the test cases inside a TestNG Suite. This annotation allows developers to specify various actions to be taken before the execution of all the test cases inside a TestNG Suite.
- @AfterSuite - This annotation allows developers to specify various actions to be taken after the execution of all the test cases inside a TestNG Suite.
- @BeforeTest - This annotation allows developers to specify various actions to be taken before the execution of all the @test annotated methods inside a TestNG Suite.
- @AfterTest - This annotation allows developers to specify various actions to be taken after the execution of all the @test annotated methods inside a TestNG Suite.
- @BeforeClass - This annotation allows developers to specify various actions to be taken before all the methods of the current class start their execution.
- @AfterClass - This annotation allows developers to specify various actions to be taken after all the methods of the current class finish their execution.
- @BeforeMethod - This annotation allows developers to specify various actions to be taken before test methods are run.
- @AfterMethod - This annotation allows developers to specify various actions to be taken after test methods are run.
- @BeforeGroups - This annotation allows developers to specify various actions to be taken before all the methods of the current group within a class finish their execution.
- @AfterGroups - This annotation allows developers to specify various actions to be taken after all the test methods belonging to a specified group have been run.

**[⬆ Back to Top](#questions)**

295. ## What are the types of Web locating strategies?

Here are the 7 locating strategies:

- **Locating By ID** - Id is a locator which is present under the By class. Id locator which is unique for every element in the DOM page that’s why an ID can uniquely identify an element.

Syntax:

```python
element=driver.find_element(By.ID, “element_id”)
```

- **Locating By Class Name** - The class attribute is one of the most commonly used in attribute in HTML .The class attribute allows multiple elements on a webpage to share a common styling. While classes can be shares with other elements , each element class value should be unique within its scope.

Syntax:

```python
element=driver.find_element(By.CLASS_NAME, “element_class_name”)
```

- **Locating By Name** - The name attribute of an HTML element is an identifier like a label . Unlike id ,class the name attribute doesn’t necessarily unique within a web page. They are often used for naming form elements and is used in HTML forms to handle form controls such as input fields , radio button etc.

Syntax:

```python
element=driver.find_element(By.NAME, “element_name”)
```

- **Locating By Tag Name** - Every element in HTML document is identified by a TAG NAME. Tag Name are used to define the purpose and type of an element in a webpage.

Syntax:

```python
element=driver.find_element(By.TAG_NAME, “element_tag_name”)
```

- **Locating By CSS Selector** - CSS Selectors are the patterns that used to select and style HTML elements in web development. CSS selectors allows us to target elements in a web page by their attributes ,position and hierarchy on a web page.

Syntax:

```python
driver.find_element(By.CSS_SELECTOR, “element_css_selector”)
```

- **Locating By XPath-**

XPath (XML Path Language) is a powerful and one of the best locating strategy in Selenium for identifying elements on a web page. XPath is a language used for navigating and querying XML documents but its widely used in web scrapping and automation.

Syntax-

```python
element=driver.find_element(By.XPATH, “element_xpath”)
```

- **Locating By Link Text And Partial Link Text** - Link Texts as the name suggests are primarily used to locate anchor tags ‘<a>’ elements on a webpage . Anchor tags are primarily used for hyperlinks (those which navigate us to different page or resource on a website).

Syntax:

```python
element = driver.find_element(By.LINK_TEXT, “element_link_text”)
```

**[⬆ Back to Top](#questions)**

296. ## What are the types of waits supported by WebDriver?

Selenium WebDriver provides three types of waits
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240530154934/Types-of-Waits.webp" alt="Selenium features" width = "50%" height="50%">

- Implicit Waits - An implicit wait tells WebDriver to poll the DOM for a certain amount of time when trying to find any element (or elements) not immediately available.
- Explicit Waits - Explicit wait allows you to wait for a certain condition to be met before proceeding with the next steps in the test script. Unlike implicit wait, direct wait waits for a certain condition to be fulfilled within a certain time This is only used for certain elements where a condition is expected.
- Fluent Wait - Fluent Expectation is an enhancement to Explicit A wait that provides wait conditions over more flexibility and control. It is also known as Fluent Wait. It allows you to specify the maximum time to wait for a condition and the frequency of checking the condition.

**[⬆ Back to Top](#questions)**

297. ## Mention the types of navigation commands

The Navigation Command provides four methods: to(), back(), forward(), and refresh(). These methods allow the WebDriver to perform the following operations:

- to() Command: Loads a new web page in the current browser window. It accepts a string parameter that specifies the URL of the web page to be loaded.
- back() Command: Moves back one step in the browser’s history stack. It does not accept any parameters and does not return anything.
- forward() Command: Moves forward one step in the browser’s history stack. It does not accept any parameters and does not return anything.
- refresh() Command: Reloads the current web page in the browser window. It does not accept any parameters and does not return anything.

**[⬆ Back to Top](#questions)**

298. ## What is the Difference Between driver.close() and driver.quit() Commands.

| Parameters                          | `driver.close()`                      | `driver.quit()`                                  |
| ----------------------------------- | ------------------------------------- | ------------------------------------------------ |
| **Execution Scope**                 | Window/Tab-specific                   | Session-specific                                 |
| **Effect on WebDriver Session**     | Doesn’t terminate                     | Terminates along with windows                    |
| **Resource Release**                | Closes a specific window/tab in focus | Terminates WebDriver and associated windows/tabs |
| **Effect on Active Window/Tab**     | Closes the active window/tab          | Closes the active window/tab                     |
| **Impact on Multiple Windows/Tabs** | Doesn’t affect                        | Closes all windows/tabs                          |

**[⬆ Back to Top](#questions)**

299. ## Differentiate Between Manual Testing and Automated Testing.

The Differentiate Between Manual Testing and Automated Testing are as follows:

| Parameters                | Manual Testing                                                      | Automation Testing                                                       |
| ------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **Definition**            | In manual testing, the test cases are executed by the human tester. | In automated testing, the test cases are executed by the software tools. |
| **Processing Time**       | Manual testing is time-consuming.                                   | Automation testing is faster than manual testing.                        |
| **Resources Requirement** | Manual testing takes up human resources.                            | Automation testing takes up automation tools and trained employees.      |
| **Exploratory Testing**   | Exploratory testing is possible in manual testing.                  | Exploratory testing is not possible in automation testing.               |
| **Framework Requirement** | Manual testing doesn’t use frameworks.                              | Automation testing uses frameworks like Data Driven.                     |

**[⬆ Back to Top](#questions)**

300. ## What is an Absolute XPath and Relative XPath?

**Absolute XPath**

- An XPath Absolute Path is like giving the full address to find a specific location in an XML document.
- It begins from the root (main) node or starts with a '/' symbol.
- To create an absolute path, you list every parent node in the hierarchy until you reach the desired node.
- It's like providing the complete route to get to a particular point in the XML structure.

**Relative XPath**

- A relative path in XPath is like giving directions from your current location to a specific place without starting from the very beginning.
- You don't have to describe the whole journey from the starting point; instead, you begin from where you currently are.
- This makes it simpler to find and pinpoint things in an XML document without having to spell out the entire path from the root.

**[⬆ Back to Top](#questions)**

301. ## What are the limitations of Selenium testing?

- No dedicated support: Selenium is open-source, so it lacks official tech support for user issues.
- Web applications only: Selenium is mainly for web apps. testing mobile or desktop apps requires extra tools like Appium.
- No image testing: Selenium does not support testing images directly.
- No built-in reports or management: It needs tools like TestNG or JUnit for test reporting and management.
- Programming knowledge needed: Some basic programming skills are required to use Selenium effectively.

**[⬆ Back to Top](#questions)**

302. ## What is the same-origin policy and how is it handled?

The Same Origin Policy is a security feature in browsers that allows a script on one webpage to access content on another webpage only if both have the same origin (same URL scheme, hostname, and port). This policy helps prevent malicious scripts on one page from accessing sensitive data on a different page.

For example, a JavaScript application on google.com can access all pages within Google’s domain (like google.com/login or google.com/mail) but cannot access pages on other domains (like yahoo.com).

To work around this policy, Selenium RC introduced a server that acts as a proxy, making it seem as if Selenium and the web application are from the same origin. This enables Selenium to test applications more flexibly across domains.

**[⬆ Back to Top](#questions)**

303. ## What makes Selenium such a widely used testing tool? Give reasons.

- Easy to Use: Selenium is user-friendly as it's developed in JavaScript, making it accessible and versatile.
- Browser Compatibility: It supports testing on major browsers like Firefox, Opera, Chrome, and Safari.
- Language Flexibility: Test scripts can be written in multiple languages like Java, Python, Perl, and PHP.
- Platform Independent: Selenium works on different operating systems, including Windows, Linux, and macOS.
- Third-Party Integration: Selenium integrates with tools like JUnit and TestNG for better test management and reporting.

**[⬆ Back to Top](#questions)**

304. ## Why is it advised to select Selenium as a testing tool for web applications or systems?

- Open-Source and Free: Selenium is a portable, open-source tool available at no cost.
- Cross-Platform Support: Compatible with Linux, Unix, macOS, and Windows operating systems.
- Browser Compatibility: Works with popular browsers like Chrome, Opera, Safari, and Internet Explorer.
- Multi-Language Support: Allows scripting in languages like Java, Python, JavaScript, Perl, Ruby, and more.
- Mobile Testing: Supports testing on iPhone, Android, and Blackberry applications.
- Integration with Build Tools: Easily integrates with frameworks like ANT and Maven for code compilation.
- Resource-Efficient: Uses minimal CPU and RAM, making script execution efficient.

**[⬆ Back to Top](#questions)**

305. ## What is an exception test in Selenium?

In Selenium, an exception test is used when you expect a specific exception to occur during a test. If a test case is designed to throw a particular exception, you can use the @Test annotation in TestNG and specify the expected exception type in its parameters. This way, the test will pass only if that exception is thrown.

Here's a simple example:

```python
import org.testng.annotations.Test;

public class ExceptionTestExample {

    @Test(expectedExceptions = ArithmeticException.class)
    public void testDivideByZero() {
        int result = 10 / 0; // This line will throw an ArithmeticException
    }

}
```

In this example, the test will pass because an ArithmeticException is expected when dividing by zero. If no exception or a different exception is thrown, the test will fail.

**[⬆ Back to Top](#questions)**

306. ## How to wait until a web page has been loaded completely in Selenium?

In Selenium, you can use two main types of waits to ensure elements load before interacting with them:

- Implicit Wait: Sets a basic wait time for all elements. Selenium will wait for this time before throwing an error if an element isn’t found.
- Explicit Wait: Waits for a specific element or condition to be met, like waiting for a button to appear. This type of wait is more precise.

These waits help manage delays in loading, making tests more reliable.

**[⬆ Back to Top](#questions)**

307. ## What is Selenium WebDriver?

Selenium WebDriver is a robust open-source framework for automating web browsers, primarily aimed at easing the testing and verification of web applications. As an important part of the Selenium suite, WebDriver offers a programming interface to interact with web browsers, allowing developers and testers to automate browser actions seamlessly.

Refer More: Selenium Webdriver

**[⬆ Back to Top](#questions)**

308. ## Is Selenium WebDriver a library?

Selenium WebDriver is not a library.

**[⬆ Back to Top](#questions)**

309. ## Which browsers/drivers are supported by Selenium Webdriver?

Selenium WebDriver works with several popular browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

This makes it flexible for testing across different browser environments.

**[⬆ Back to Top](#questions)**

310. ## Explain Selenium 4 and why it is different from other Selenium versions?

Selenium 4 is the latest version of the Selenium testing tool, which bringing new features and improvements over older versions. It offers better support for modern web testing needs, with updated browser compatibility, enhanced debugging, and user-friendly updates for testers.

**[⬆ Back to Top](#questions)**

311. ## What will happen if I execute this command? driver.get

This command tells the Selenium WebDriver to open the given URL in the web browser.

**[⬆ Back to Top](#questions)**

312. ## What is an alternative option to driver.get() method to open an URL in Selenium Web Driver?

Another way to open a URL in Selenium WebDriver is by using the driver.navigate().to() method instead of driver.get().

**[⬆ Back to Top](#questions)**

313. ## Is it possible to test APIs or web services using Selenium Webdriver?

No, Selenium WebDriver cannot be used to test APIs or web services because it is specifically designed for testing web-based applications.

314. ## Mention different ways of locating an element in Selenium?

The various ways of locating an element in Selenium are: by ID, by name, by classname, by tagname, by link text, by partial link text, by CSS selector, and by XPath.

**[⬆ Back to Top](#questions)**

315. ## How can we move to the nth-child element using XPath?

You can select the nth-child element using XPath with the following expression: (//parent-element/\*)[n].

Related Testing Interview Guides

- Manual Testing
- API Testing
- Automation Testing
- SQL
- Database Testing

**[⬆ Back to Top](#questions)**

316. ## How to type text in an input box using Selenium?

1. **Clicking a Link by Full Text:**

```python
driver.findElement(By.linkText("Menu")).click();
```

This command locates a link on the page with the exact text "Today’s deals" and clicks it, redirecting the user to the linked page.

2. **Clicking a Link by Partial Text:**

```python
driver.findElement(By.partialLinkText("marks")).click();
```

Here, the command finds a link that contains the word "Service" in its text (even if it's part of a longer text) and clicks it.

**Another Example Using Partial Link Text:**

```python
driver.findElement(By.partialLinkText("price")).click();
```

This would locate and click on a link containing "Discount," even if the full text of the link is "Best Discounts Today."

**[⬆ Back to Top](#questions)**

317. ## How to scroll down a page using JavaScript?

Purpose of scrollBy(): The scrollBy() method allows you to scroll a webpage by a specified number of pixels.

General Syntax:

```python
executeScript("window.scrollBy(x-pixels, y-pixels)");
```

- x-pixels: Horizontal scroll amount (0 if you don’t want horizontal scrolling).
- y-pixels: Vertical scroll amount (positive values scroll down, negative values scroll up).

Example Code:

First, create a JavaScript executor object:

```python
JavascriptExecutor js = (JavascriptExecutor) driver;
```

Open the desired webpage:

```python
driver.get("https://www.google.com");
```

Scroll down the page by 1000 pixels:

```python
js.executeScript("window.scrollBy(0, 1000)");
```

This command scrolls the page vertically down by 1000 pixels.

**[⬆ Back to Top](#questions)**

318. ## How to click on a hyperlink in Selenium?

Using linkText:

```python
driver.findElement(By.linkText("Contact Us")).click();
```

This command searches for a link on the webpage that says "Contact Us." When it finds the link, it clicks on it, and the user is taken to the Contact Us page where they can find information to get in touch with support.

Using partialLinkText:

```python
driver.findElement(By.partialLinkText("About")).click();
```

This command looks for any link that has the word "About" in its text. It could be something like "About Us" or "About Our Company." When it finds a link containing "About," it clicks on it, redirecting the user to the About page for more information about the company

**[⬆ Back to Top](#questions)**

319. ## How to assert the title of a webpage?

Open the GeeksforGeeks website, get the title, and compare it with the expected title.

```python
// Step 1: Open the GeeksforGeeks website
driver.get("https://www.geeksforgeeks.org/");

// Step 2: Get the title of the webpage and store it in a variable
String actualTitle = driver.getTitle();

// Step 3: Set the expected title
String expectedTitle = "GeeksforGeeks - A Computer Science Portal for Geeks";

// Step 4: Check if the titles match
if(actualTitle.equalsIgnoreCase(expectedTitle)) {
System.out.println("Title Matched");
} else {
System.out.println("Title didn't match");
}

// Alternatively, using Assert
Assert.assertEquals(actualTitle, expectedTitle);
```

**[⬆ Back to Top](#questions)**

320.  ## How to mouse hover over a web element?

```python
// Create an instance of the Actions class
Actions action = new Actions(driver);

// Hover over the web element
action.moveToElement(driver.findElement(By.id("id_of_element"))).perform();
```

- Actions Class: Create an instance of the Actions class to handle complex mouse and keyboard actions.
- moveToElement(): Use this method to specify the web element you want to hover over, identified by its ID.
- perform(): Call this method to execute the hover action.

This will perform moving the mouse pointer over the specified element.

**[⬆ Back to Top](#questions)**

321. ## How to retrieve CSS properties of an element?

To retrieve CSS properties of an element in Selenium WebDriver, you can use the getCssValue() method. Here’s a simple step-by-step method:

- Find the Element: Use a locator to identify the web element (e.g., By.id(), By.className()).
- Use getCssValue(): Call the getCssValue("property-name") method on the found element to get the value of the desired CSS property.

```python
// Retrieve the background color of an element with ID "header"

String backgroundColor = driver.findElement(By.id("header")).getCssValue("background-color");
```

This code finds the element with ID "header" and retrieves its background color. You can replace "background-color" with any other CSS property name to get its value.

**[⬆ Back to Top](#questions)**

322. ## What is POM?

POM is a design pattern which is commonly used in Selenium for Automating the Test Cases. This design pattern can be used with any kind of framework like keyword-driven, Data-driven, hybrid framework, etc.

**[⬆ Back to Top](#questions)**

323. ## Can Captcha be automated?

No, Selenium cannot automate Captcha. Captcha is designed to prevent bots from accessing sensitive information. Since Captcha requires human input to verify that a user is not a bot, an automation test engineer must manually enter the Captcha while Selenium can fill in the other fields automatically.

**[⬆ Back to Top](#questions)**

324. ## How does Selenium handle Windows-based pop-ups

Selenium is mainly used for testing web applications and doesn’t support Windows features on its own. However, you can use third-party tools like AutoIT or Robot to work with pop-ups and other Windows-based

**[⬆ Back to Top](#questions)**

325. ## How to take screenshots in WebDriver?

**Step 1**. Take a screenshot and store it in a file format

**Step 2**. Copy screenshot to a location using CopyFile method

```python
FileUtils.copyFile(File, new File(“location where you want to save the image” +FileName+ “.jpeg”));
```

**Step 3**. Create a border around the element: Using the JavaScript executor, we can create a border around the desired element.

```python
JavascriptExecutor js = (JavascriptExecutor) driver; js.executeScript(“arguments[0].style.border = ‘3px solid red'”, Element);
```

**[⬆ Back to Top](#questions)**

326. ## Why do testers choose Selenium over QTP?

Selenium is a free and open-source tool for automated testing, while QTP (Quick Test Professional) is a paid tool that requires a significant investment. Selenium works with many programming languages and can run on different operating systems.

**[⬆ Back to Top](#questions)**

327. ## What are the data-driven framework and keyword-driven framework?

A data-driven framework is a type of test automation framework that keeps the test data separate from the test scripts. This means testers can create automated tests that can work with different sets of data without changing the test code itself.

**[⬆ Back to Top](#questions)**

328. ## What is the difference between getwindowhandles() and getwindowhandle()?

The `getWindowHandle()` method gives you a unique ID for the current browser window. In contrast, the `getWindowHandles()` method returns a list of unique IDs for all the browser windows that WebDriver has opened.

**[⬆ Back to Top](#questions)**

329. ## What is a Selenium Maven project?

A Selenium Maven project is a software project that uses Maven to handle the project's dependencies (like libraries needed for testing) and to manage the build process (how the project is compiled and packaged). This makes it easier to organize and run Selenium tests efficiently.

**[⬆ Back to Top](#questions)**

330. ## What is an Object Repository?

An Object Repository is a central place where testers keep all the web elements used in automated tests, like buttons, text boxes, and links. This makes it easier to manage and use these elements in the testing framework, allowing for better organization and reusability in test scripts.

**[⬆ Back to Top](#questions)**

331. ## How do you Locate Elements using XPath?

1. **Absolute XPath**: Absolute XPath uses the root element of the HTML/XML code and is followed by all the elements that are necessary to reach the desired element. It starts with the forward slash ‘/’. Generally, Absolute XPath is not recommended because in the future any of the web elements when added or removed then Absolute XPath changes.

Example:

```python
/html[1]/body[1]/div[6]/div[1]/div[3]/div[1]/div[1]/div[1]/div[3]/ul[1]/li[2]/a[1]
```

  <img src="https://media.geeksforgeeks.org/wp-content/uploads/20190622160820/Absolute_Xpath.png" alt="" width="50%">

2. **Relative XPath**; In this, XPath begins with the double forward slash ‘//’ which means it can search the element anywhere on the web page. Generally, Relative Xpath is preferred as they are not complete paths from the Root node.

Example:

```python
//input[@id = 'fakebox-input']
```

  <img src="https://media.geeksforgeeks.org/wp-content/uploads/20190622144100/xpath_Example-e1561194841410.png" alt="" width="50%">

**[⬆ Back to Top](#questions)**

332. ## How can you Handle Multiple Windows in Selenium?

Sometimes when we click on a particular web element it opens a new window. To locate the web elements on the new window webpage, we need to shift the focus of selenium from the current page (main page) to the new page. We will try to shift the focus of selenium from one window to another new window. Here we will use the Chrome browser for which we require ChromeDriver you can download it from the official site of Selenium.

To get the IDs of different windows

```python
import java.util.Set;
import org.openqa.selenium.By;
import org.openqa.selenium.JavascriptExecutor;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class GFGIDsOfWindows {

    public static void main(String[] args) throws InterruptedException {
        // Set the path for the ChromeDriver executable
        System.setProperty("webdriver.chrome.driver", "path/to/chromedriver.exe");

        // Create an instance of ChromeDriver
        WebDriver driver = new ChromeDriver();

        // Open the GeeksforGeeks website
        driver.get("https://www.geeksforgeeks.org/");

        // Maximize the browser window
        driver.manage().window().maximize();

        // Delete all cookies
        driver.manage().deleteAllCookies();

        // Scroll down to locate an element
        JavascriptExecutor js = (JavascriptExecutor) driver;
        js.executeScript("window.scrollBy(0, 200)");

        // Click on the 'Courses at GeeksforGeeks' link
        driver.findElement(By.xpath("(//span[text()='Courses at GeeksforGeeks'])[2]")).click();

        // Wait for a moment to allow the new page to load
        Thread.sleep(2000);

        // Click on a specific course (Data Structures and Algorithms)
        driver.findElement(By.xpath("(//h4[text()='Data Structures and Algorithms - Self Paced'])[1]")).click();

        // Get the ID of the main (parent) window
        String parentId = driver.getWindowHandle();
        System.out.println("Parent Window ID: " + parentId);

        // Get the IDs of all open windows (child windows)
        Set<String> windowIds = driver.getWindowHandles();

        // Print the IDs of all windows
        for (String id : windowIds) {
            System.out.println("Window ID: " + id);
        }

        // Optionally, you can switch back to the parent window if needed
        driver.switchTo().window(parentId);

        // Close the browser
        driver.quit();
    }

}
```

Here you can observe the IDs of windows are different.

```bash
CDwindow-EA925E71098EEFBB80858BE787CED1A5 (ID of main window)
CDwindow-C9078346729F1D0CF8AF12E938CE49DD (ID of new window)
```

**[⬆ Back to Top](#questions)**

333. ## Explain Implicit and Explicit waits in Selenium.

| Implicit Cursors                                                                | Explicit Cursors                                                                |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| Implicit cursors are automatically created when select statements are executed. | Explicit cursors need to be defined explicitly by the user by providing a name. |
| They are capable of fetching a single row at a time.                            | Explicit cursors can fetch multiple rows.                                       |
| Closes automatically after execution.                                           | Need to close after execution.                                                  |
| They are more vulnerable to errors such as Data errors, etc.                    | They are less vulnerable to errors (Data errors, etc.).                         |
| Provides less programmatic control to the users.                                | The user/Programmer has the entire control.                                     |

**[⬆ Back to Top](#questions)**

334. ## List the Difference Between Close and Quit Commands.

| Parameters                          | `driver.close()`                      | `driver.quit()`                                  |
| ----------------------------------- | ------------------------------------- | ------------------------------------------------ |
| **Execution Scope**                 | Window/Tab-specific                   | Session-specific                                 |
| **Effect on WebDriver Session**     | Doesn’t terminate                     | Terminates along with windows                    |
| **Resource Release**                | Closes a specific window/tab in focus | Terminates WebDriver and associated windows/tabs |
| **Effect on Active Window/Tab**     | Closes the active window/tab          | Closes the active window/tab                     |
| **Impact on Multiple Windows/Tabs** | Doesn’t affect                        | Closes all windows/tabs                          |

**[⬆ Back to Top](#questions)**

335. ## How can we submit a form in Selenium?

These is how We can submit a form in Selenium:

1. Create a Form

We will create the Form which we will be using to try submitting it from the Selenium script.

2. Code to Submit a Form

we will try to get the fields in which all the data will be entered. To get the field we can find it using Id, Class, or CSS Selector. In the following code blocks, we will find the fields using ID and the submit button will be tracked using the CSS Selector.

```python
// Import necessary libraries
import org.openqa.selenium.Alert;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

public class Main {
public static void main(String[] args) {
// Set the path to the ChromeDriver executable
System.setProperty("webdriver.chrome.driver", "path/to/chromedriver.exe");

        // Initialize WebDriver
        WebDriver driver = new ChromeDriver();

        // Navigate to the desired webpage
        driver.get("your-webpage-url"); // Replace with your actual webpage URL

        // Find the input fields using ID
        WebElement firstName = driver.findElement(By.id("FirstName"));
        WebElement dob = driver.findElement(By.id("DOB"));
        WebElement email = driver.findElement(By.id("Email"));
        WebElement inputNumber = driver.findElement(By.id("inputNumber"));
        WebElement maleRadioButton = driver.findElement(By.id("Male"));

        // Fill out the form
        firstName.sendKeys("Ram");
        dob.sendKeys("19-01-2001");
        email.sendKeys("ram@example.com");
        inputNumber.sendKeys("1234567890");
        maleRadioButton.click();

        // Click the submit button using CSS Selector
        driver.findElement(By.cssSelector("button[type='submit']")).click();

        // Switch to alert and get alert text
        Alert alert = driver.switchTo().alert();
        String alertText = alert.getText();

        // Check if the alert is open
        if (alertText != null) {
            System.out.println("Alert is open, and the content is: " + alertText);
            // Optionally accept the alert if needed
            // alert.accept();
        } else {
            System.out.println("No alert found.");
        }

        // Quit the browser
        driver.quit();
    }

}
```

Output:

Below is the output of the code in which the Chrome browser loads and is redirected to the form. And quickly fills in the details and submits the form. We can see that the alert box opens up and the details are shown in the console window.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20231105173706/Untitled-video---Made-with-Clipchamp-(1).gif" alt="" width="50%" >

**[⬆ Back to Top](#questions)**

336. ## How to delete cookies in Selenium?

Method 1: Using the deleteAllCookies() command:

Python:

```python
driver.manage().deleteAllCookies()
```

Java:

```java
driver.manage().deleteAllCookies()
```

JavaScript:

```javascript
await driver.manage().deleteAllCookies();
```

Method 2: Going to the browser's settings:

Opening your browser's settings menu and manually emptying the cookie jar.

Steps:

- Open the settings page: Type driver.get("chrome://settings/clearBrowserData")
- Find the "Clear Data" button: Use your browser's developer tools to pinpoint it (like a treasure map!).
- Click the button: This will make all the cookies disappear.

**[⬆ Back to Top](#questions)**

337. ## How do you work with frames in Selenium?

1. **Finding the Frame:**

Right-click check: Right-click on the part of the page you think is a frame. If you see options like "This Frame," "View Frame Source," or "Reload Frame," it's a frame!
Code search: Look for `<iframe>` tags in the website's code to find all the frames.

2. **Stepping Inside the Frame:**

- Use a special code: Use driver.switchTo().frame() to step inside the frame. You can tell it which frame you want by:
  - Its order on the page (like first, second, etc.)
  - Its name or ID
  - Finding it like any other element on the page

3. Do Your Thing:

- Once you're inside, you can work with elements inside the frame just like you would normally.

4. Stepping Back Out:

- When you're done, use driver.switchTo().defaultContent() to step back out to the main page.

For more refer -Frames in Selenium

**[⬆ Back to Top](#questions)**

338. ## Discuss the importance of Cross-Browser Testing in Selenium.

**Ensures Consistent User Experience**:

- Different browsers use varying rendering engines, leading to potential inconsistencies in website appearance and functionality. Cross-browser testing with Selenium helps identify and fix these issues, ensuring a smooth and consistent user experience across all major browsers.

**Reaches Wider Audience**:

- By testing on multiple browsers, you cater to a larger audience who use diverse platforms and devices. This expands your reach and avoids alienating users due to browser-specific compatibility issues.

**Improves Quality and Reduces Risk**:

- Early detection and fixing of cross-browser issues prevent bugs and glitches from reaching production, enhancing overall website quality and reducing the risk of user frustration and potential financial losses.

**Boosts Search Engine Optimization (SEO)**:

- Search engines consider website compatibility across different browsers as a ranking factor. By ensuring flawless cross-browser performance, you improve your website's SEO and visibility in search results.

**Benefits of using Selenium for Cross-Browser Testing**:

- Automation: Selenium automates repetitive testing tasks across various browsers, saving time and effort compared to manual testing.
- Flexibility: It supports multiple programming languages and integrates with various testing frameworks, offering flexibility for development teams.
- Open-Source: Its open-source nature makes it cost-effective and accessible to developers of all levels.

For more refer -Cross-Browser Testing

**[⬆ Back to Top](#questions)**

339. ## What are the challenges of Parallel Execution in Selenium?

Parallel execution in Selenium brings many benefits, like faster test execution and improved test coverage, but it also comes with its own set of challenges:

**Test Dependencies**:

- Data isolation: Tests that share data or rely on specific states can interfere with each other when running in parallel. Careful test design and data management are crucial.
- Test order dependencies: Some tests might need to run in a specific order due to logical dependencies. Parallel execution might disrupt this order.

**Resource Management**:

- WebDriver limitations: Not all WebDrivers support parallel execution. For example, EdgeDriver requires special handling.
- Resource contention: Running multiple browser instances simultaneously can strain your machine's resources (CPU, memory, network). Consider using grid-based solutions or cloud services for larger-scale testing.
- Test stability: Parallelization can introduce flakiness in tests due to unforeseen interactions between tests.

**Other Challenges**:

- Synchronization issues: Tests might access shared resources, leading to race conditions and unpredictable behavior. Proper synchronization mechanisms are needed.
- Debugging difficulties: Identifying the root cause of failures in parallel execution can be complex due to multiple test interactions. Logging and reporting tools are helpful.
- Test environment setup: Setting up and managing multiple test environments for parallel execution can be complex and time-consuming.

**[⬆ Back to Top](#questions)**

340. ## How to integrate Selenium with Jenkins for Continuous Integration?

1. Setting Up Jenkins:

- Install necessary plugins: Install plugins like "Pipeline", "Git", and any relevant browser-specific plugins depending on your needs (e.g., BrowserStack Plugin).
- Configure JDK: Define a Java installation for running your Selenium tests.

2. Preparing your Selenium Tests:

- Organize your tests: Structure your tests into well-defined modules or classes depending on your testing framework.
- Manage dependencies: Ensure your test scripts have access to required libraries and resources.
- Consider using a testing framework: Frameworks like TestNG or JUnit help manage dependencies and parallel execution.

3. Creating a Jenkins Job:

- Choose a job type: Select "Pipeline" for declarative builds or "Freestyle Project" for a more traditional configuration.
- Define job triggers: Choose how you want the job to run (e.g., manually, upon code changes, scheduled builds).
- Configure build steps:
  - Download code: Use the "Git Plugin" to fetch code from your version control system.
  - Install dependencies: Download and install required libraries for your tests (e.g., Maven build step).
  - Execute tests: Use a "Shell" or "Execute Windows batch command" step to run your Selenium tests.
  - Use environment variables to specify browser configurations and other test parameters.
  - Capture test results and logs for reporting.

**Publish reports**: Utilize plugins like "JUnit" or "XUnit" to publish test results in Jenkins dashboard.

4. Additional Considerations:

- Parallel execution: Utilize tools like Selenium Grid or cloud testing services for efficient parallel execution.
- Security: Securely store credentials and sensitive information using Jenkins credentials management.
- Reporting and analysis: Integrate reporting tools and dashboards for better visualization and analysis of test results.

**[⬆ Back to Top](#questions)**

341. ## What is the purpose of the Page Factory in Selenium?

1. Initialization:

- It eliminates the need for manually finding web elements using find_element or find_elements methods in every test method. Instead, you use annotations like @FindBy to declare and locate elements within your page object classes.
- Page Factory then automatically initializes these elements during the first interaction with the page object, reducing boilerplate code and improving readability.

2. Improved Readability:

- By separating element declaration and logic within page objects, your test scripts become more focused and easier to understand. You can clearly see which actions belong to each page and how they interact with the elements.

3. Maintainability:

- If the structure of a web page changes, you only need to update the element locators within the page object class, keeping your test scripts independent of UI changes. This helps maintain your automation suite as your application evolves.

4. Reusability:

- Page objects can be reused across different test cases, promoting code reuse and reducing redundancy.

5. Additional Features:

- Some Page Factory implementations offer additional functionalities like custom waits, implicit waits, and error handling, further enhancing your testing experience.

Overall, Page Factory plays a crucial role in making your Selenium tests more modular, readable, maintainable, and reusable. It streamlines the implementation of the POM and promotes efficient test automation practices.

**[⬆ Back to Top](#questions)**

342. ## Describe the Significance of TestNG in Selenium.

**Enhanced Organization and Readability**:

- Annotations: TestNG relies heavily on annotations like @Test, @BeforeTest, and @AfterTest to clearly define test methods, setup/teardown procedures, and group related tests. This improves code organization and readability compared to traditional methods.
- Grouping: You can group tests based on functionality, criticality, or any other relevant criteria for organized execution and reporting.

**Powerful Features for Efficient Testing**:

- Data-Driven Testing: TestNG excels at data-driven testing, allowing you to parameterize test data and execute the same test with different sets of data using the @DataProvider annotation. This streamlines repetitive tests and increases test coverage.
- Parallel Testing: TestNG allows parallel execution of tests across multiple threads or machines, significantly reducing test execution time, especially for large test suites. This is crucial for modern web applications with complex functionalities.
- Dependencies and Sequencing: You can control the order of test execution and define dependencies between tests using annotations like @DependsOnMethods. This ensures tests run in a specific order and only when their prerequisites are met.

**Improved Reporting and Debugging**:

- Detailed Reports: TestNG generates comprehensive HTML reports with detailed information about each test, including status, execution time, and stack traces for failures. This aids in analyzing test results and identifying issues efficiently.
- Logging: TestNG integrates seamlessly with logging frameworks like Log4j, allowing you to log test events and debug issues more effectively.

**Beyond these core features, TestNG brings additional benefits**:

- Flexibility: It supports various programming languages and integrates well with other testing tools and frameworks.
- Open-Source: Being open-source, it's accessible and free to use, making it a popular choice for many projects.

In conclusion, TestNG's rich feature set and focus on efficient test execution make it an ideal choice for Selenium automation. It helps you write more organized, maintainable, and data-driven tests while offering valuable tools for reporting and debugging.

**[⬆ Back to Top](#questions)**

343. ## How do you handle Synchronization in Selenium WebDriver?

1. Implicit Waits:

- Like setting a general timeout: Selenium will patiently wait a certain amount of time for elements to appear before giving up.
- Good for simple tasks: It's easy to use, but it might waste time if the website is usually fast.

2. Explicit Waits:

- Like checking for specific signs: Selenium looks for specific conditions, like a certain button being clickable, before proceeding.
- More efficient and focused: It doesn't waste time waiting unnecessarily, but it requires more instructions.

3. Fluent Waits:

- Like a customizable waiting game: Selenium can adjust its waiting strategy based on how the website behaves, making it even more adaptable.
- Very flexible but can be tricky: It offers a lot of control, but it takes more effort to set up correctly.

4. Thread.sleep():

- Like taking a nap: Selenium just pauses for a fixed time, regardless of what's happening on the website.
- Not a good idea: It can cause unreliability and slow down tests, so it's generally avoided.

Remember, choosing the right waiting strategy helps Selenium work smoothly and accurately, ensuring your tests run reliably and efficiently!

**[⬆ Back to Top](#questions)**

344. ## What are the Benefits of using Selenium Grid or Selenium Tool Suite?

Here's why using Selenium Grid is a good idea:

- Speeding things Up: Imagine running your cleaning, cooking, and laundry all at once! Grid lets you run your tests on different browsers and devices at the same time, making them much faster, especially for long test lists.
- Testing Everywhere: Just like you wouldn't clean only one corner of your house, Grid lets you test your website on different browsers, operating systems, and even real devices like phones and tablets. This ensures your website works smoothly for everyone, no matter what they use.
- Sharing is Caring: Instead of each helper needing their own cleaning supplies, Grid shares resources efficiently. This means less waste and better use of your testing machines and browsers.
- Growing with you: Need more helpers for a big spring cleaning? Grid lets you easily add or remove testing machines as needed, making it flexible and adaptable to your testing needs.
- Saving Money: Buying lots of cleaning supplies can be expensive! Grid lets you use cloud services to test on real devices without actually buying them, saving you money.
- Building Something Awesome: Just like a clean and well-maintained house makes you feel good, Grid helps you catch problems in your website before they affect real users, leading to a more reliable and high-quality website.

**[⬆ Back to Top](#questions)**

345. ## Explain the Purpose of the 'assert' statement in Selenium.

Imagine Selenium as a friendly robot that's testing your website for you. It's like a teacher checking your homework, but for websites!

Here's how Selenium uses assert statements to make sure your website is working correctly:

- Selenium does something on the website: Like a student solving a math problem, Selenium interacts with the website, such as clicking buttons, filling forms, or reading text.
- Selenium expects a certain result: Just like a teacher has the answer key, you tell Selenium what the correct outcome should be after each action, like a certain message appearing or a page opening.
- Selenium double-checks with assert: The assert statement is like Selenium raising its hand to say "I'm done!" It compares the actual result it got with the expected outcome you provided.
- Test passes or fails: If everything matches, the test passes, like getting a good grade on a test! If not, the test fails, meaning something might be wrong with the website.

For more refer -'assert' statement in Selenium

**[⬆ Back to Top](#questions)**

346. ## What are the limitations of Selenium testing?

With concerning all these advantages of Selenium include some Limitation of selenium. which are as follows:

- Cross Browser Compatibility: Selenium can give regular best results across multiple browsers, but sometimes it's restricted in that the web browsers understand and use the HTML and CSS differently from the respective browsers.
- Slow Test Execution: Because the automation depends on the various drivers with the browser that causes the process to slow. Selenium will be slow to respond when running tests on big web applications or websites
- Difficulty in Handling Dynamic Web Elements: Selenium has difficulties in interacting with dynamic web elements like ID that will change on a web page sometime which causes the test script failure while testing the same.
- Limited Support for Mobile Applications: Selenium will not provide the automation on the mobile application testing, so developers choose the other tools or frameworks for the automation purpose.
- Limited Support for Windows-based Applications: Developers will have to depend on the third-party tools or libraries for Automation testing in desktop apps using Selenium.

**[⬆ Back to Top](#questions)**

347. ## Differentiate between WebDriver and WebElement.

| Feature              | WebDriver                                                                  | WebElement                                                                            |
| -------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **Purpose**          | Controls the browser itself                                                | Represents an element within a web page                                               |
| **Scope**            | Browser window or tab                                                      | Specific element like a button, text field, or image                                  |
| **Interactions**     | Opens/closes browsers, navigates to URLs, refreshes pages, manages windows | Clicks, enters text, retrieves text, submits forms, interacts with element attributes |
| **Example**          | `driver.get("https://www.example.com")`                                    | `element = driver.find_element_by_id("my_button")`                                    |
| **Analogy**          | Like a remote control for your TV                                          | Like a specific button or channel on your Television                                  |
| **Selenium Methods** | `get()`, `navigate()`, `quit()`, `switch_to()`                             | `click()`, `send_keys()`, `text()`, `get_attribute()`, `is_displayed()`               |

**[⬆ Back to Top](#questions)**

348. ## How do You Perform Database Testing Using Selenium?

Selenium can't peek directly into your website's database, but we can be clever detectives! Here are some ways to check the database indirectly:

1. **Action, reaction, verification**:

- Use Selenium to perform actions on the website (like adding an item to a cart).
- Peek into the database afterwards using separate tools or queries to see if the expected changes happened. Imagine checking your bank balance after a purchase

2. Mocking the database:

- Think of this as setting up a fake database with controlled responses.
- Tools like Mockito help create this "pretend database" that responds to Selenium's actions the way the real one should.
- This lets you test how your website interacts with the database without going near the real one.

3. Speaking the database language:

- Libraries like JDBCTest allow you to talk directly to the database, but it's like learning a new language!
- This gives you fine-grained control, but be prepared to put in some extra effort.

4. Testing frameworks lend a hand:

- Imagine Robot Framework or Cypress as assistants who already know how to talk to databases.
- They offer shortcuts and modules to make database testing smoother within your Selenium tests.

**[⬆ Back to Top](#questions)**

349. ## Discuss the Role of the Cucumber Framework in Selenium.

Imagine trying to explain test scripts to your boss who doesn't know code? That's where Selenium and Cucumber come in, working together like a dream team for web testing!

**Selenium**: Think of it as a robot ninja, flawlessly controlling the browser and doing all the clicking, typing, and navigating. But for most people, its code can be like hieroglyphics!

**Cucumber**: Enter the superhero translator, Cucumber, who speaks plain English! It uses Gherkin, a special language that reads like a story, describing how users interact with the website. This makes tests clear for everyone, not just coding experts.

Together, they're unstoppable:

- Communication Boost: With Cucumber, everyone (testers, developers, even your boss!) can understand the test scenarios. No more confusion, just clear expectations!
- Focus on What Matters: Forget the code details, Cucumber lets you focus on how the website should behave from a user's perspective. Easier to write, easier to understand, easier to maintain!
- Living Documentation: The Gherkin scenarios double as documentation, always showing what the website should do. No more outdated docs, just clear instructions for everyone!
- Flexibility: Whether you prefer Behavior-Driven Development (BDD) or Test-Driven Development (TDD), Cucumber works with both, adapting to your team's style.

**[⬆ Back to Top](#questions)**

350. ## What are the Considerations for Headless Browser Testing in Selenium?

Headless browser testing with Selenium sounds amazing - imagine tests running super fast without needing all those open browser windows! But before you jump in, let's talk about what to watch out for:

**The Good Stuff:**

- Lightning Speed: No fancy graphics means tests fly through, especially for long lists. Need to test on 10 browsers? Headless makes it a breeze!
- Scale Up, Save Big: Run tests on multiple machines or browsers at once, even without fancy displays. This saves resources and lets you test more efficiently.
- Automation Rockstar: Want to automatically take screenshots or measure website performance? Headless can handle it, freeing you up for other tasks.
- Cost Cutter: Testing mobile websites often requires actual devices, which can be expensive. Headless lets you use virtual versions, saving you money.

**The Not-So-Good Stuff:**

- Seeing is Believing: Headless can miss visual details like layout, animations, or hover effects. These might still need separate testing.
- Debugging Detective: Fixing problems can be trickier without seeing what's happening on the screen. Think of it like solving a crime scene in the dark!
- JavaScript Jitters: Some complex JavaScript interactions or libraries might not work quite right in headless mode. Test carefully!
- Not Everyone's Invited: Older browsers or specific versions might not play nice with headless testing. Make sure everyone's compatible.
- Security Matters: Running tests on cloud platforms? Double-check your security measures to keep things safe.

**[⬆ Back to Top](#questions)**

351. ## Examine the Challenges and Solutions of Handling Dynamic Tables.

Imagine a web page with a table that keeps changing its data, rows, or even structure. Testing that with Selenium can feel like fighting a shapeshifting monster! But worry not, we have tools and strategies to overlap these Gap.

The Challenges:

- Finding the right element: Tables rarely have unique IDs or names, making them hard to pinpoint. It's like trying to find a specific grain of sand on a beach!
- Paging through data: If information spills across multiple pages, navigating and testing each one adds complexity. Think climbing Mount Everest, one page at a time!
- Sorting and filtering chaos: Sorting and filtering can scramble the table's layout, breaking your identification methods. It's like the table rearranging itself just to confuse you!
- Extracting the right info: Grabbing specific data within the table can be tricky. It's like finding a hidden treasure in a maze!

The Solutions:

- Think like a detective: Use relative locators like CSS selectors or XPath that rely on the table's structure and relationships between elements. Think Sherlock Holmes, using clues to identify the culprit!
- Plan your attack: Prepare test data beforehand and compare it to the actual table data to see if everything matches. It's like having a blueprint of the treasure chest to know what you're looking for!
- Wait patiently: Use explicit waits like WebDriverWait until specific elements appear or conditions are met before interacting. It's like waiting for the right moment to strike, not rushing in blindly!
- Javascript to the rescue: Sometimes, using Javascript within your tests can manipulate the table or directly extract data. It's like having a secret weapon to unlock the treasure chest!
- Specialized tools: Consider libraries like robotframework-table or TableAU designed specifically for handling these dynamic tables. They're like special tools Indiana Jones would use to navigate ancient tombs!
- Frame it right: If the table is within a frame, switch to the correct frame before interacting with it. It's like entering the right room in a museum to find the specific exhibit!

For more refer - Handling Dynamic Tables

**[⬆ Back to Top](#questions)**

352. ## How to Capture Screenshots in Selenium?

1. Using the TakesScreenshot Interface:

This is the most basic and widely used approach:

```python
import org.openqa.selenium.OutputType;
import org.openqa.selenium.TakesScreenshot;
import org.openqa.selenium.WebDriver;

public class ScreenshotExample {

    public static void main(String[] args) throws Exception
    {
        // Set up your WebDriver instance
        WebDriver driver = ...;

        // Navigate to the URL
        driver.get("https://www.example.com");

        //screenshot of the entire page
        TakesScreenshot screenshot = (TakesScreenshot) driver;
        byte[] screenshotBytes = screenshot.getScreenshotAs(OutputType.BYTES);

        // Save the screenshot to a file
        FileUtils.writeByteArrayToFile(new File("screenshot.png"), screenshotBytes);

        // Quit
        driver.quit();
    }

}
```

2. Using Third-Party Libraries:

Libraries like Apache Commons IO and SikuliX offer additional functionalities:

- Apache Commons IO: Provides efficient byte array handling for saving screenshots.
- SikuliX: Captures screenshots of specific screen regions based on visual elements.

3. Browser Developer Tools:

- While not ideal for automated tests, browser developer tools allow manual screenshot capture during debugging.

For more refer - Capture Screenshots in Selenium.

**[⬆ Back to Top](#questions)**

353. ## What are the Benefits of Using a Data-Driven Framework in Selenium?

Benefits:

- One-Time Setup, Endless Possibilities: Write your test script once, then feed it different ingredients (data sets) to create countless flavor combinations (test cases). No more repetitive recipe writing!
- Taste Everything on the Menu: Effortlessly test different data combinations to uncover hidden flavors (bugs) and ensure every dish is perfect (broader test coverage).
- Easy Recipe Adjustments: When you need to change an ingredient (update test data), simply edit the recipe book (data file), not the whole kitchen (test script).
- Clear Instructions for Everyone: Separate ingredients (data) from cooking instructions (test logic) so anyone can follow the recipe (understand the test).
- Share Your Secret Sauce: Shareable recipe books (data sets) and reusable cooking techniques (test logic) mean your team can collaborate and cook faster together.

How it Works:

- Stock Your Pantry: Store your ingredients (test data) in separate containers like Excel spreadsheets, CSV files, or databases.
- Follow the Recipe: Your test script reads the recipe book (data), grabs the right ingredients, and uses them to cook the dish (perform actions on the website).
- Taste Test: Compare the final dish (actual results) with the expected taste (expected values) from the recipe book (data).

**[⬆ Back to Top](#questions)**

354. ## Explain the concept of Object Repository in Selenium.

Imagine you're a detective testing a website for clues. Memorizing the location of every door, window, and secret passage would be tough, right? That's where an object repository in Selenium comes in!

Think of it like a map:

- Each web element (door, window) has a unique address (locator) stored in the map (repository).
- Instead of remembering every address, you simply consult the map to find what you need.

Benefits of using this map:

- Easy updates: Website changes? No problem! Update the address on the map (repository), and your tests automatically find the right element.
- Reuse the map: Need to check the same window in different tests? No need to draw a new map, just reuse the existing one (share locators between tests).
- Clear instructions: Separate the addresses (locators) from your detective work (test logic), making your notes (scripts) easier to understand for everyone.
- Be flexible: Use different search methods (locator strategies) to find elements, choosing the most reliable one for each situation.

**[⬆ Back to Top](#questions)**

355. ## How can you Perform Mouse Hover Actions in Selenium?

1. Using the Actions class:

This is the most common and built-in method. Here's how it works:

```python
// Import necessary libraries
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.interactions.Actions;

public class HoverAndClickExample {
public static void main(String[] args) {
// Set up your WebDriver instance (e.g., ChromeDriver)
System.setProperty("webdriver.chrome.driver", "path/to/chromedriver.exe");
WebDriver driver = new ChromeDriver();

        try {
            // Navigate to the desired webpage
            driver.get("https://www.example.com"); // Replace with your target URL

            // Find the element to hover over
            WebElement elementToHover = driver.findElement(By.id("hoverElement")); // Replace with the actual ID

            // Create an Actions object
            Actions actions = new Actions(driver);

            // Move the mouse over the element
            actions.moveToElement(elementToHover).perform();

            // Wait for sub-menu to be visible (if necessary)
            Thread.sleep(1000); // Adjust the time as needed

            // Click on a sub-menu item
            actions.click(driver.findElement(By.xpath("//li[text()='SubMenu Item']"))).perform(); // Replace with actual submenu item

        } catch (InterruptedException e) {
            e.printStackTrace();
        } finally {
            // Quit the browser
            driver.quit();
        }
    }

}
```

2. Using JavaScript:

In specific cases, you might prefer using JavaScript for more fine-grained control:

```javascript
// Import necessary libraries
import org.openqa.selenium.By;
import org.openqa.selenium.JavascriptExecutor;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

public class HoverExample {
public static void main(String[] args) {
// Set up your WebDriver instance (e.g., ChromeDriver)
System.setProperty("webdriver.chrome.driver", "path/to/chromedriver.exe");
WebDriver driver = new ChromeDriver();

        try {
            // Navigate to the desired webpage
            driver.get("https://www.example.com"); // Replace with your target URL

            // Find the element to hover over
            WebElement elementToHover = driver.findElement(By.id("hoverElement")); // Replace with the actual ID

            // Cast the WebDriver to JavascriptExecutor
            JavascriptExecutor js = (JavascriptExecutor) driver;

            // Execute JavaScript to hover over the element
            js.executeScript("arguments[0].dispatchEvent(new MouseEvent('mouseover'));", elementToHover);

            // Optionally, you can perform another action after hovering
            // For example, clicking another element after hovering
            // WebElement anotherElement = driver.findElement(By.id("anotherElementId"));
            // anotherElement.click();

        } finally {
            // Quit the browser
            driver.quit();
        }
    }

}
```

**[⬆ Back to Top](#questions)**

## Panda Interview Questions

356. ## What are Pandas?

Pandas is an open-source Python library that is built on top of the NumPy library. It is made for working with relational or labelled data. It provides various data structures for manipulating, cleaning and analyzing numerical data. It can easily handle missing data as well. Pandas are fast and have high performance and productivity.

**[⬆ Back to Top](#questions)**

357. ## What are the Different Types of Data Structures in Pandas?

The two data structures that are supported by Pandas are Series and DataFrames.

Pandas Series is a one-dimensional labelled array that can hold data of any type. It is mostly used to represent a single column or row of data.
Pandas DataFrame is a two-dimensional heterogeneous data structure. It stores data in a tabular form. Its three main components are data, rows, and columns.

**[⬆ Back to Top](#questions)**

358. ## List Key Features of Pandas.

Pandas are used for efficient data analysis. The key features of Pandas are as follows:

Fast and efficient data manipulation and analysis
Provides time-series functionality
Easy missing data handling
Faster data merging and joining
Flexible reshaping and pivoting of data sets
Powerful group by functionality
Data from different file objects can be loaded
Integrates with NumPy

**[⬆ Back to Top](#questions)**

359. ## What is Series in Pandas?

Ans: A Series in Pandas is a one-dimensional labelled array. Its columns are like an Excel sheet that can hold any type of data, which can be, an integer, string, or Python objects, etc. Its axis labels are known as the index. Series contains homogeneous data and its values can be changed but the size of the series is immutable. A series can be created from a Python tuple, list and dictionary. The syntax for creating a series is as follows:

```python
import pandas as pd
series = pd.Series(data)
```

**[⬆ Back to Top](#questions)**

360. ## What are the Different Ways to Create a Series?

Ans: In Pandas, a series can be created in many ways. They are as follows:

Creating an Empty Series

An empty series can be created by just calling the pandas.Series() constructor.

```python
# import pandas as pd
  import pandas as pd

  # Creating empty series
  print(pd.Series())
```

Output:

```bash
Series([], dtype: float64)
Creating a Series from an Array
```

In order to create a series from the NumPy array, we have to import the NumPy module and have to use the array() function.

```python
# import pandas and numpy
  import pandas as pd
  import numpy as np

  # simple array
  data = np.array(['g', 'e', 'e', 'k', 's'])

  # convert array to Series
  print(pd.Series(data))
```

```bash
Output:

0    g
1    e
2    e
3    k
4    s
dtype: object
```

**Creating a Series from an Array with a custom Index**

In order to create a series by explicitly proving the index instead of the default, we have to provide a list of elements to the index parameter with the same number of elements as it is an array.

```python
# import pandas and numpy
  import pandas as pd
  import numpy as np

  # simple array
  data = np.array(['g', 'e', 'e', 'k', 's'])

  # providing an index
  ser = pd.Series(data, index=[10, 11, 12, 13, 14])
  print(ser)

Output:

10    g
11    e
12    e
13    k
14    s
dtype: object
```

**Creating a Series from a List**

We can create a series using a Python list and pass it to the Series() constructor.

```python
# import pandas
  import pandas as pd

  # a simple list
  list = ['g', 'e', 'e', 'k', 's']

  # create series form a list
  print(pd.Series(list))
```

```bash
Output:

0    g
1    e
2    e
3    k
4    s
dtype: object
```

**Creating a Series from Dictionary**

A Series can also be created from a Python dictionary. The keys of the dictionary as used to construct indexes of the series.

```python
# import pandas
  import pandas as pd

  # a simple dictionary
  dict = {'Geeks': 10,
  'for': 20,
  'geeks': 30}

  # create series from dictionary
  print(pd.Series(dict))
```

```bash
Output:

Geeks    10
for      20
geeks    30
dtype: int64
```

**Creating a Series from Scalar Value**

To create a series from a Scalar value, we must provide an index. The Series constructor will take two arguments, one will be the scalar value and the other will be a list of indexes. The value will repeat until all the index values are filled.

```python
# import pandas and numpy
  import pandas as pd
  import numpy as np

  # giving a scalar value with index
  ser = pd.Series(10, index=[0, 1, 2, 3, 4, 5])

  print(ser)
```

```bash
Output:

0    10
1    10
2    10
3    10
4    10
5    10
dtype: int64
```

**Creating a Series using NumPy Functions**

The Numpy module's functions, such as numpy.linspace(), and numpy.random.randn() can also be used to create a Pandas series.

```python
# import pandas and numpy
  import pandas as pd
  import numpy as np

  # series with numpy linspace()
  ser1 = pd.Series(np.linspace(3, 33, 3))
  print(ser1)

  # series with numpy linspace()
  ser2 = pd.Series(np.random.randn(3))
  print("\n", ser2)
```

```bash
Output:

0     3.0
1    18.0
2    33.0
dtype: float64
 0    0.694519
1    0.782243
2    0.082820
dtype: float64
```

**Creating a Series using the Range Function**

We can also create a series in Python by using the range function.

```python
# import pandas
  import pandas as pd
  print(pd.Series(range(5)))
```

```bash
Output:

0    0
1    1
2    2
3    3
4    4
dtype: int64
```

**Creating a Series using List Comprehension**

Here, we will use the Python list comprehension technique to create a series in Pandas. We will use the range function to define the values and a for loop for indexes.

```python
# import pandas
  import pandas as pd
  ser = pd.Series(range(1, 20, 3),
  index=[x for x in 'abcdefg'])
  print(ser)
```

```bash
Output:

a     1
b     4
c     7
d    10
e    13
f    16
g    19
dtype: int64
```

**[⬆ Back to Top](#questions)**

361. ## How can we Create a Copy of the Series?

Ans: In Pandas, there are two ways to create a copy of the Series. They are as follows:

**Shallow Copy** is a copy of the series object where the indices and the data of the original object are not copied. It only copies the references to the indices and data. This means any changes made to a series will be reflected in the other. A shallow copy of the series can be created by writing the following syntax:

```python
ser.copy(deep=False)
```

**Deep Copy** is a copy of the series object where it has its own indices and data. This means nay changes made to a copy of the object will not be reflected tot he original series object. A deep copy of the series can be created by writing the following syntax:

```python
ser.copy(deep=True)
```

The default value of the deep parameter of the copy() function is set to True.

**[⬆ Back to Top](#questions)**

362. ## What is a DataFrame in Pandas?

Ans: A DataFrame in Panda is a data structure used to store the data in tabular form, that is in the form of rows and columns. It is two-dimensional, size-mutable, and heterogeneous in nature. The main components of a dataframe are data, rows, and columns. A dataframe can be created by loading the dataset from existing storage, such as SQL database, CSV file, Excel file, etc. The syntax for creating a dataframe is as follows:

```python
import pandas as pd
dataframe = pd.DataFrame(data)
```

**[⬆ Back to Top](#questions)**

363. ## What are the Different ways to Create a DataFrame in Pandas?

Ans: In Pandas, a dataframe can be created in many ways. They are as follows:

Creating an Empty DataFrame

An empty dataframe can be created by just calling the pandas.DataFrame() constructor.

```python
# import pandas as pd
  import pandas as pd

  # Calling DataFrame constructor
  print(pd.DataFrame())
```

```bash
Output:

Empty DataFrame
Columns: []
Index: []
```

**Creating a DataFrame using a List**

In order to create a DataFrame from a Python list, just pass the list to the DataFrame() constructor.

```python
# import pandas as pd
  import pandas as pd

  # list of strings
  lst = ['Geeks', 'For', 'Geeks', 'is',
  'portal', 'for', 'Geeks']

  # Calling DataFrame constructor on list
  print(pd.DataFrame(lst))
```

```bash
Output:

      0
0   Geeks
1     For
2   Geeks
3      is
4  portal
5     for
6   Geeks
```

**Creating a DataFrame using a List of Lists**

A DataFrame can be created from a Python list of lists and passed the main list to the DataFrame() constructor along with the column names.

```python
# import pandas as pd
  import pandas as pd

  # list of strings
  lst = [[1, 'Geeks'], [2, 'For'], [3, 'Geeks']]

  # Calling DataFrame constructor
  # on list with column names
  print(pd.DataFrame(lst, columns=['Id', 'Data']))
```

```bash
Output:

   Id   Data
0   1  Geeks
1   2    For
2   3  Geeks
```

**Creating a DataFrame using a Dictionary**

A DataFrame can be created from a Python dictionary and passed to the DataFrame() constructor. The Keys of the dictionary will be the column names and the values of the dictionary are the data of the DataFrame.

```python
import pandas as pd

  # initialise data of lists.
  data = {'Name':['Tom', 'nick', 'krish', 'jack'], 'Age':[20, 21, 19, 18]}

  # Print the dataframe created
  print(pd.DataFrame(data))
```

```bash
Output:

    Name  Age
0    Tom   20
1   nick   21
2  krish   19
3   jack   18
```

**Creating a DataFrame using a List of Dictionaries**

Another way to create a DataFrame is by using Python list of dictionaries. The list is passed to the DataFrame() constructor. The Keys of each dictionary element will be the column names.

```python
# import pandas as pd
  import pandas as pd

  # list of strings
  lst = [{1: 'Geeks', 2: 'For', 3: 'Geeks'},
  {1: 'Portal', 2: 'for', 3: 'Geeks'}]

  # Calling DataFrame constructor on list
  print(pd.DataFrame(lst))
```

```bash
Output:

        1    2      3
0   Geeks  For  Geeks
1  Portal  for  Geeks
```

**Creating a DataFrame from Pandas Series**

A DataFrame in Pandas can also be created by using the Pandas series.

```python
# import pandas as pd
  import pandas as pd

  # list of strings
  lst = pd.Series(['Geeks', 'For', 'Geeks'])

  # Calling DataFrame constructor on list
  print(pd.DataFrame(lst))
```

```bash
Output:

       0
0  Geeks
1    For
2  Geeks
```

**[⬆ Back to Top](#questions)**

364. ## How to Read Data into a DataFrame from a CSV file?

Ans: We can create a data frame from a CSV file - "Comma Separated Values". This can be done by using the read_csv() method which takes the csv file as the parameter.

```python
pandas.read_csv(file_name)
```

Another way to do this is by using the read_table() method which takes the CSV file and a delimiter value as the parameter.

```python
pandas.read_table(file_name, deliniter)
```

**[⬆ Back to Top](#questions)**

365. ## How to access the first few rows of a dataframe?

Ans: The first few records of a dataframe can be accessed by using the pandas head() method. It takes one optional argument n, which is the number of rows. By default, it returns the first 5 rows of the dataframe. The head() method has the following syntax:

```python
df.head(n)
```

Another way to do it is by using iloc() method. It is similar to the Python list-slicing technique. It has the following syntax:

```python
df.iloc[:n]
```

**[⬆ Back to Top](#questions)**

366. ## What is Reindexing in Pandas?

Ans: Reindexing in Pandas as the name suggests means changing the index of the rows and columns of a dataframe. It can be done by using the Pandas reindex() method. In case of missing values or new values that are not present in the dataframe, the reindex() method assigns it as NaN.

```python
df.reindex(new_index)
```

**[⬆ Back to Top](#questions)**

367. ## How to Select a Single Column of a DataFrame?

Ans: There are many ways to Select a single column of a dataframe. They are as follows:

By using the Dot operator, we can access any column of a dataframe.

```python
Dataframe.column_name
```

Another way to select a column is by using the square brackets [].

```python
DataFrame[column_name]
```

**[⬆ Back to Top](#questions)**

368. ## How to Rename a Column in a DataFrame?

Ans: A column of the dataframe can be renamed by using the rename() function. We can rename a single as well as multiple columns at the same time using this method.

```python
DataFrame.rename(columns={'column1': 'COLUMN_1', 'column2':'COLUMN_2'}, inplace=True)
```

Another way is by using the set_axis() function which takes the new column name and axis to be replaced with the new name.

```python
DataFrame.set_axis(labels=['COLUMN_1','COLUMN_2'], axis=1, inplace=True)
```

In case we want to add a prefix or suffix to the column names, we can use the add_prefix() or add_suffix() methods.

```python
DataFrame.add_prefix(prefix='PREFIX_')
DataFrame.add_suffix(suffix='_suffix')
```

**[⬆ Back to Top](#questions)**

369. ## How to add an Index, Row, or Column to an Existing Dataframe?

Ans: Adding Index

We can add an index to an existing dataframe by using the Pandas **set_index()** method which is used to set a list, series, or dataframe as the index of a dataframe. The set_index() method has the following syntax:

```python
df.set_index(keys, drop=True, append=False, inplace=False, verify_integrity=False)
```

**Adding Rows**

The **df.loc[]** is used to access a group of rows or columns and can be used to add a row to a dataframe.

```python
DataFrame.loc[Row_Index]=new_row
```

We can also add multiple rows in a dataframe by using **pandas.concat()** function which takes a list of dataframes to be added together.

```python
pandas.concat([Dataframe1,Dataframe2])
```

**Adding Columns**

We can add a column to an existing dataframe by just declaring the column name and the list or dictionary of values.

```python
DataFrame[data] = list_of_values
```

Another way to add a column is by using df.insert() method which take a value where the column should be added, column name and the value of the column as parameters.

```python
DataFrameName.insert(col_index, col_name, value)
```

We can also add a column to a dataframe by using df.assign() function

```python
DataFrame.assign(**kwargs)
```

**[⬆ Back to Top](#questions)**

370. ## How to Delete an Index, Row, or Column from an Existing DataFrame?

Ans: We can delete a row or a column from a dataframe by using df.drop() method. and provide the row or column name as the parameter.

To delete a column

```python
DataFrame.drop(['Column_Name'], axis=1)
```

To delete a row

```python
DataFrame.drop([Row_Index_Number], axis=0)
```

**[⬆ Back to Top](#questions)**

371. ## How to set the Index in a Panda dataFrame?

Ans: We can set the index to a Pandas dataframe by using the set_index() method, which is used to set a list, series, or dataframe as the index of a dataframe.

```python
DataFrame.set_index('Column_Name')
```

**[⬆ Back to Top](#questions)**

372. ## How to Reset the Index of a DataFrame?

Ans: The index of Pandas dataframes can be reset by using the reset_index() method. It can be used to simply reset the index to the default integer index beginning at 0.

```python
DataFrame.reset_index(inplace = True)
```

**[⬆ Back to Top](#questions)**

373. ## How to Find the Correlation Using Pandas?

Ans: Pandas dataframe.corr() method is used to find the correlation of all the columns of a dataframe. It automatically ignores any missing or non-numerical values.

```python
DataFrame.corr()
```

**[⬆ Back to Top](#questions)**

374. ## How to Iterate over Dataframe in Pandas?

Ans: There are various ways to iterate the rows and columns of a dataframe.

**Iteration over Rows**

In order to iterate over rows, we apply a iterrows() function this function returns each index value along with a series containing the data in each row. Another way to iterate over rows is by using iteritems() method, which iterates over each column as key-value pairs. We can also use itertuples() function which returns a tuple for each row in the DataFrame.The first element of the tuple will be the row’s corresponding index value, while the remaining values are the row values.

**Iteration over Columns**

To iterate columns of a dataframe, we just need to create a list of dataframe columns by using the list constructor and passing the dataframe to it.

**[⬆ Back to Top](#questions)**

375. ## What are the Important Conditions to keep in mind before Iterating?

Ans: Iterating is not the best option when it comes to Pandas Dataframe. Pandas provides a lot of functions using which we can perform certain operations instead of iterating through the dataframe. While iterating a dataframe, we need to keep in mind the following things:

- While printing the data frame, instead of iterating, we can use DataFrame.to_string() methods which will display the data in tabular form.
- If we are concerned about time performance, iteration is not a good option. Instead, we should choose vectorization as pandas have a number of highly optimized and efficient built-in methods.
- We should use the apply() method instead of iteration when there is an operation to be applied to a few rows and not the whole database.

**[⬆ Back to Top](#questions)**

**Pandas Interview Questions for Experienced**

376. ## What is Categorical Data and How it is represented in Pandas?

Ans: Categorical data is a set of predefined data values under some categories. It usually has a limited and fixed range of possible values and can be either numerical or textual in nature. A few examples of categorical data are gender, educational qualifications, blood type, country affiliation, observation time, etc. In Pandas categorical data is often represented by Object datatype.

**[⬆ Back to Top](#questions)**

377. ## How can a DataFrame be Converted to an Excel File?

Ans: A Pandas dataframe can be converted to an Excel file by using the to_excel() function which takes the file name as the parameter. We can also specify the sheet name in this function.

```python
DataFrame.to_excel(file_name)
```

**[⬆ Back to Top](#questions)**

378. ## What is Multi-Indexing in Pandas?

Ans: Multi-indexing refers to selecting two or more rows or columns in the index. It is a multi-level or hierarchical object for pandas object and deals with data analysis and works with higher dimensional data. Multi-indexing in Pandas can be achieved by using a number of functions, such as **MultiIndex.from_arrays, MultiIndex.from_tuples, MultiIndex.from_product, MultiIndex.from_frame**, etc which helps us to create multiple indexes from arrays, tuples, dataframes, etc.

**[⬆ Back to Top](#questions)**

379. ## How to select Specific Data-types to Include or Exclude in the DataFrame?

Ans: The Pandas select_dtypes() method is used to include or exclude a specific type of data in the dataframe. The datatypes to include or exclude are specified to it as a list or parameters to the function. It has the following syntax:

```python
DataFrame.select_dtypes(include=['object','float'], exclude =['int'])
```

**[⬆ Back to Top](#questions)**

380. ## How to Convert a DataFrame into a Numpy Array?

Ans: Pandas Numpy is an inbuilt Python package that is used to perform large numerical computations. It is used for processing multidimensional array elements to perform complicated mathematical operations.

The pandas dataframe can be converted to a NumPy array by using the to_numpy() method. We can also provide the datatype as an optional argument.

```python
Dataframe.to_numpy()
```

We can also use .values to convert dataframe values to NumPy array

df.values

**[⬆ Back to Top](#questions)**

381. ## How to Split a DataFrame according to a Boolean Criterion?

Ans: Boolean masking is a technique that can be used in Pandas to split a DataFrame depending on a boolean criterion. You may divide different regions of the DataFrame and filter rows depending on a certain criterion using boolean masking.

```python
# Define the condition
condition = DataFrame['col_name'] < VALUE
# DataFrame with rows where the condition is True
DataFrame1 = DataFrame[condition]
# DataFrame with rows where the condition is False
DataFrame1 = DataFrame[~condition]
```

**[⬆ Back to Top](#questions)**

382. ## What is Time Series in Pandas?

Ans: Time series is a collection of data points with timestamps. It depicts the evolution of quantity over time. Pandas provide various functions to handle time series data efficiently. It is used to work with data timestamps, resampling time series for different time periods, working with missing data, slicing the data using timestamps, etc.

Pandas Built-in Function

| **Function**                                | **Operation**                                                                              |
| ------------------------------------------- | ------------------------------------------------------------------------------------------ |
| `pandas.to_datetime(DataFrame['Date'])`     | Convert 'Date' column of DataFrame to datetime dtype                                       |
| `DataFrame.set_index('Date', inplace=True)` | Set 'Date' as the index                                                                    |
| `DataFrame.resample('H').sum()`             | Resample time series to a different frequency (e.g., hourly, daily, weekly, monthly, etc.) |
| `DataFrame.interpolate()`                   | Fill missing values using linear interpolation                                             |
| `DataFrame.loc[start_date:end_date]`        | Slice the data based on timestamps                                                         |

**[⬆ Back to Top](#questions)**

383. ## What is Time Delta in Pandas?

Ans: The time delta is the difference in dates and time. Similar to the timedelta() object in the datetime module, a Timedelta in Pandas indicates the duration or difference in time. For addressing time durations or time variations in a DataFrame or Series, Pandas has a dedicated data type.

The time delta object can be created by using the timedelta() method and providing the number of weeks, days, seconds, milliseconds, etc as the parameter.

```python
Duration = pandas.Timedelta(days=7, hours=4, minutes=30, seconds=23)
```

With the help of the Timedelta data type, you can easily perform arithmetic operations, comparisons, and other time-related manipulations. In terms of different units, such as days, hours, minutes, seconds, milliseconds, and microseconds, it can give durations.

```bash
Duration + pandas.Timedelta('2 days 6 hours')
```

**[⬆ Back to Top](#questions)**

384. ## What is Data Aggregation in Pandas?

Ans: In Pandas, data aggregation refers to the act of summarizing or decreasing data in order to produce a consolidated view or summary statistics of one or more columns in a dataset. In order to calculate statistical measures like sum, mean, minimum, maximum, count, etc., aggregation functions must be applied to groups or subsets of data.

The agg() function in Pandas is frequently used to aggregate data. Applying one or more aggregation functions to one or more columns in a DataFrame or Series is possible using this approach. Pandas' built-in functions or specially created user-defined functions can be used as aggregation functions.

```python
DataFrame.agg({'Col_name1': ['sum', 'min', 'max'], 'Col_name2': 'count'})
```

**[⬆ Back to Top](#questions)**

385. ## Difference between merge() and concat()

Ans: The following table shows the difference between merge() and concat():

| **Function**           | **.merge()**                                                                             | **.concat()**                                                                                                    |
| ---------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Use Case**           | Used to join exactly 2 DataFrames based on a common column or index.                     | Used to join 2 or more DataFrames along a particular axis (rows or columns).                                     |
| **Join Types**         | Supports inner join, outer join, left join, and right join.                              | Performs concatenation by appending DataFrames one below the other (along rows) or side by side (along columns). |
| **Axis Specification** | Join types and column names must be specified.                                           | By default, performs row-wise concatenation (`axis=0`). Column-wise concatenation can be done with `axis=1`.     |
| **Column Matching**    | Merges based on shared column(s) or index, and multiple columns can be merged if needed. | Does not perform any matching or joining based on column values.                                                 |
| **Purpose**            | Used when combining data based on shared columns or index is necessary.                  | Commonly used to combine DataFrames vertically or horizontally without matching criteria.                        |

**[⬆ Back to Top](#questions)**

386. ## Difference between map(), applymap(), and apply()

Ans: The map(), applymap(), and apply() methods are used in pandas for applying functions or transformations to elements in a DataFrame or Series. The following table shows the difference between map(), applymap() and apply():

| **Function**   | **map()**                                                                   | **applymap()**                                                          | **apply()**                                                                        |
| -------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| **Definition** | Defined only in Series                                                      | Defined only in DataFrame                                               | Defined in both Series and DataFrame                                               |
| **Purpose**    | Used to apply a function or a dictionary to each element of the Series.     | Used to apply a function to each element of the DataFrame.              | Used to apply a function along a specific axis of the DataFrame or Series.         |
| **Scope**      | Works element-wise on Series.                                               | Works element-wise on DataFrame, applying the function to each element. | Works on rows or columns of a DataFrame or Series (element-wise or aggregated).    |
| **Use Case**   | For simple transformations or mappings applied to each element of a Series. | For applying a function to each individual element of a DataFrame.      | For applying a function that aggregates or transforms data across rows or columns. |
| **Example**    | `Series.map(lambda x: x * 2)`                                               | `DataFrame.applymap(lambda x: x * 2)`                                   | `DataFrame.apply(np.sum, axis=0)`                                                  |

**[⬆ Back to Top](#questions)**

387. ## Difference between pivot_table() and groupby()

Ans: Both pivot_table() and groupby() are powerful methods in pandas used for aggregating and summarizing data. The following table shows the difference between pivot_table() and groupby():

| **Function**      | **pivot_table()**                                                                                  | **groupby()**                                                                                       |
| ----------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **Purpose**       | Summarizes and aggregates data in a tabular format.                                                | Performs aggregation on grouped data of one or more columns.                                        |
| **Functionality** | Used to transform data by reshaping it based on column values.                                     | Groups data based on categorical variables, then applies aggregation functions.                     |
| **Flexibility**   | Can handle multiple levels of grouping and aggregation, providing flexibility in summarizing data. | Groups data into a GroupBy object, allowing various aggregation functions (e.g., sum, mean, count). |
| **Use Case**      | Used when comparing data across multiple dimensions.                                               | Used to summarize data within groups.                                                               |
| **Example**       | `DataFrame.pivot_table(values='value', index='index', columns='column', aggfunc='mean')`           | `DataFrame.groupby('column').sum()`                                                                 |

**[⬆ Back to Top](#questions)**

387. ## How can we use Pivot and Melt Data in Pandas?

Ans: We can pivot the dataframe in Pandas by using the pivot_table() method. To unpivot the dataframe to its original form we can melt the dataframe by using the melt() method.

**[⬆ Back to Top](#questions)**

388. ## How to convert a String to Datetime in Pandas?

Ans: A Python string can be converted to a DateTime object by using the to_datetime() function or strptime() method of datetime. It returns a DateTime object corresponding to date_string, parsed according to the format string given by the user.

Using Pandas.to_datetime()

```python
import pandas as pd

# Convert a string to a datetime object

date_string = '2023-07-17'
dateTime = pd.to_datetime(date_string)
print(dateTime)
```

```bash
Output:

2023-07-17 00:00:00
```

Using datetime.strptime

```python
from datetime import datetime

# Convert a string to a datetime object

date_string = '2023-07-17'
dateTime = datetime.strptime(date_string, '%Y-%m-%d')
print(dateTime)
```

```bash
Output:

2023-07-17 00:00:00
```

**[⬆ Back to Top](#questions)**

389. ## What is the Significance of Pandas Described Command?

Ans: Pandas describe() is used to view some basic statistical details of a data frame or a series of numeric values. It can give a different output when it is applied to a series of strings. It can get details like percentile, mean, standard deviation, etc.

```python
DataFrame.describe()
```

**[⬆ Back to Top](#questions)**

390. ## How to Compute Mean, Median, Mode, Variance, Standard Deviation, and Various Quantile Ranges in Pandas?

Ans: The mean, median, mode, Variance, Standard Deviation, and Quantile range can be computed using the following commands in Python.

- DataFrame.mean(): To calculate the mean
- DataFrame.median(): To calculate median
- DataFrame.mode(): To calculate the mode
- DataFrame.var(): To calculate variance
- DataFrame.std(): To calculate the standard deviation
- DataFrame.quantile(): To calculate quantile range, with range value as a parameter

**[⬆ Back to Top](#questions)**

391. ## How to make Label Encoding using Pandas?

Ans: Label encoding is used to convert categorical data into numerical data so that a machine-learning model can fit it. To apply label encoding using pandas we can use the pandas.Categorical().codes or pandas.factorize() method to replace the categorical values with numerical values.

**[⬆ Back to Top](#questions)**

392. ## How to make Onehot Encoding using Pandas?

Ans: One-hot encoding is a technique for representing categorical data as numerical values in a machine-learning model. It works by creating a separate binary variable for each category in the data. The value of the binary variable is 1 if the observation belongs to that category and 0 otherwise. It can improve the performance of the model. To apply one hot encoding, we greater a dummy column for our dataframe by using get_dummies() method.

**[⬆ Back to Top](#questions)**

393. ## How to make a Boxplot using Pandas?

Ans: A Boxplot is a visual representation of grouped data. It is used for detecting outliers in the data set. We can create a boxplot using the Pandas dataframe by using the boxplot() method and providing the parameter based on which we want the boxplot to be created.

```python
DataFrame.boxplot(column='Col_Name', grid=False)
```

**[⬆ Back to Top](#questions)**

394. ## How to make a Distribution Plot using Pandas?

Ans: A distribution plot is a graphical representation of the distribution of data. It is a type of histogram that shows the frequency of each value in a dataset. To create a distribution plot using Pandas, you can use the plot.hist() method. This method takes a DataFrame as input and creates a histogram for each column in the DataFrame.

```python
DataFrame['Numerical_Col_Name'].plot.hist()
```

**[⬆ Back to Top](#questions)**

395. ## How to Sort a Dataframe?

Ans: A dataframe in pandas can be sorted in ascending or descending order according to a particular column. We can do so by using the sort_values() method. and providing the column name according to which we want to sort the dataframe. we can also sort it by multiple columns. To sort it in descending order, we pass an additional parameter 'ascending' and set it to False.

```python
DataFrame.sort_values(by='Age',ascending=True)
```

**[⬆ Back to Top](#questions)**

396. ## How to Check and Remove Duplicate Values in Pandas.

Ans: In pandas, duplicate values can be checked by using the duplicated() method.

```python
DataFrame.duplicated()
```

To remove the duplicated values we can use the drop_duplicates() method.

```python
DataFrame.drop_duplicates()
```

**[⬆ Back to Top](#questions)**

397. ## How to Create a New Column Based on Existing Columns?

Ans: We can create a column from an existing column in a DataFrame by using the df.apply() and df.map() functions

**[⬆ Back to Top](#questions)**

398. ## How to Handle Missing Data in Pandas?

Ans: Generally dataset has some missing values, and it can happen for a variety of reasons, such as data collection issues, data entry errors, or data not being available for certain observations. This can cause a big problem. To handle these missing values Pandas provides various functions. These functions are used for detecting, removing, and replacing null values in Pandas DataFrame:

- isnull(): It returns True for NaN values or null values and False for present values
- notnull(): It returns False for NaN values and True for present values
- dropna(): It analyzes and drops Rows/Columns with Null values
- fillna(): It let the user replace NaN values with some value of their own
- replace(): It is used to replace a string, regex, list, dictionary, series, number, etc.
- interpolate(): It fills NA values in the dataframe or series.

**[⬆ Back to Top](#questions)**

399. ## What is groupby() Function in Pandas?

Ans: The groupby() function is used to group or aggregate the data according to a category. It makes the task of splitting the Dataframe over some criteria really easy and efficient. It has the following syntax:

```python
DataFrame.groupby(by=['Col_name'])
```

400. ## What are loc and iloc methods in Pandas?

Ans: Pandas Subset Selection is also known as Pandas Indexing. It means selecting a particular row or column from a dataframe. We can also select a number of rows or columns as well. Pandas support the following types of indexing:

- Dataframe.[ ]: This function is also known as the indexing operator
- Dataframe.loc[ ]: This function is used for label-based indexing.
- Dataframe.iloc[ ]: This function is used for positions or integer-based indexing.

**[⬆ Back to Top](#questions)**

401. ## How to Merge Two DataFrames?

Ans: In pandas, we can combine two dataframes using the pandas.merge() method which takes 2 dataframes as the parameters.

```python
import pandas as pd

# Create two DataFrames

df1 = pd.DataFrame({'A': [1, 2, 3],
'B': [4, 5, 6]},
index=[10, 20, 30])

df2 = pd.DataFrame({'C': [7, 8, 9],
'D': [10, 11, 12]},
index=[20, 30, 40])

# Merge both dataframe

result = pd.merge(df1, df2, left_index=True, right_index=True)
print(result)
```

```bash
Output:

    A  B  C   D

20 2 5 7 10
30 3 6 8 11
```

**[⬆ Back to Top](#questions)**

402. ## Difference between iloc() and loc()

Ans: The iloc() and loc() functions of pandas are used for accessing data from a DataFrame.The following table shows the difference between iloc() and loc():

| **Attribute**        | **iloc()**                                                                                          | **loc()**                                                                                       |
| -------------------- | --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| **Selection Method** | Indexed-based selection method.                                                                     | Label-based selection method.                                                                   |
| **Access**           | Allows access to rows and columns of a DataFrame by their integer positions.                        | Allows access to rows and columns of a DataFrame using their labels or names.                   |
| **Indexing**         | Indexing starts from 0 for both rows and columns.                                                   | Indexing is based on row labels, column labels, or a combination of both.                       |
| **Usage**            | Used for integer-based slicing with single integers, lists, or arrays for specific rows or columns. | Used for label-based slicing with single labels, lists, or arrays for specific rows or columns. |
| **Syntax**           | `DataFrame.iloc[row_index, column_index]`                                                           | `DataFrame.loc[row_label, column_label]`                                                        |

**[⬆ Back to Top](#questions)**

403. ## Difference between join() and merge()

Ans: Both join() and merge() functions in pandas are used to combine data from multiple DataFrames. The following table shows the difference between join and merge():

| **Attribute**      | **join()**                                                                      | **merge()**                                                                              |
| ------------------ | ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| **Operation**      | Combines DataFrames on their indexes.                                           | Combines DataFrames by specifying the columns as a merge key.                            |
| **Joining Method** | Joining is performed on the DataFrame's index and not on any specified columns. | Joining is performed based on the values in the specified columns or indexes.            |
| **Flexibility**    | Does not support merging based on column values or multiple columns.            | Supports merging based on one or more columns or indexes, allowing for more flexibility. |

**[⬆ Back to Top](#questions)**

404. ## Difference between the interpolate() and fillna()

Ans: The interpolate() and fillna() methods in pandas are used to handle missing or NaN (Not a Number) values in a DataFrame or Series. The following table shows the difference between interpolate() and fillna():

| **Attribute**   | **interpolate()**                                                                                         | **fillna()**                                                                                  |
| --------------- | --------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **Operation**   | Fill in the missing values based on interpolation or estimate values based on existing data.              | Fill missing values with specified values that can be based on some strategies.               |
| **Methods**     | Performs interpolation based on various methods such as linear, polynomial, and time-based interpolation. | Replaces NaN values with a constant like zero, mean, median, mode, or any other custom value. |
| **Application** | Applied to both numerical and DateTime data, often for time series or logical relationships.              | Can be applied to both numerical and categorical data.                                        |

**[⬆ Back to Top](#questions)**
