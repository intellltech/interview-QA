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

185. # How to delete a file using Python?

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

200. ## Difference between for loop and while loop in Python

The “for” Loop is generally used to iterate through the elements of various collection types such as List, Tuple, Set, and Dictionary. Developers use a “for” loop where they have both the conditions start and the end. Whereas, the “while” loop is the actual looping feature that is used in any other programming language. Programmers use a Python while loop where they just have the end conditions.

**[⬆ Back to Top](#questions)**
