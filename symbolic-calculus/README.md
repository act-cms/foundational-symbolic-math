Lesson 2: Essentials of Calculus in Python
==========================================

The purpose of this lesson is to help students develop foundational skills for
performing symbolic and numerical calculus in Python, with some brief
applications to scientific problem solving.

## Lesson Information
### Lesson Learning Outcomes (LOs)
#### Cyberinfrastructure LOs
By the end of this lesson, students will be able to perform the following cyberinfrastructure (CI) tasks:

1. Encode mathematical functions of one or more variables into SymPy expressions
2. Perform symbolic derivatives of scalar functions of one or more variables in SymPy
3. Perform symbolic indefinite integration of scalar functions of one or more variables in SymPy
4. Perform symbolic definite integration of scalar functions of one or more variables in SymPy
5. Perform numerical quadrature to evaluate definite integrals of one or more variables with SciPy

#### Content LOs

This lesson is primarily meant to introduce the cyberinfrastructure skills for
_performing calculus in Python_, rather than serving as a detailed introduction
to the calculus concepts themselves. However, some brief conceptual
introductions to calculus topics are included throughout as a way to ensure
students have a common foundation.

### Lesson Prerequisites

#### Cyberinfrastructure Prereq's

Before beginning this lesson, students are expected to have the following CI skills:

1. Basic Python syntax: variable assignment, calling Python functions, loops, conditional statements
    * [Introduction to Programming for Molecular Scientists, Lesson 1: Introduction to Python](https://act-cms.molssi.org/portal/lessons/foundational-intro-python/)
2. Symbolic Algebra in SymPy
    * [Lesson 1: Introduction to Symbolic Algebra in Python](https://act-cms.molssi.org/portal/lessons/foundational-symbolic-math/#material-1)

#### Content Prereq's

Students are expected to be able to perform by hand the following operations from single-variable calculus:
- Limits of scalar functions of a single variable
- Ordinary derivatives of scalar functions of a single variable
- Indefinite integrals of scalar functions of a single variable
- Definite integrals of scalar functions of a single variable

> [!IMPORTANT] Author Note: No Familiarity with Multivariate Calculus Assumed
> No familiarity with the calculus of scalar functions of multiple variables is
> assumed. Instead, these concepts are introduced as natural extensions of the
> calculus of scalar functions of a single variable.


### Resources

Students should refer to the following resources for additional discussion:

#### Cyberinfrastructure Resources

* [MolSSI Workshop: Python Scripting for Computational Molecular Sciences](https://education.molssi.org/python_scripting_cms/)
* [MolSSI CMS Python Workshop: Introduction](https://education.molssi.org/python_scripting_cms/01-introduction/index.html)
* [Algebra with SymPy Documentation](https://gutow.github.io/Algebra_with_Sympy/algebra_with_sympy.html)
* [Demonstrations of ``algebra_with_sympy`` functionality with the ``Equation`` class](https://gutow.github.io/Algebra_with_Sympy/Demonstration%20of%20equation%20class.html)

#### Content Resources

* [OpenStax Calculus Volume 1](https://openstax.org/details/books/calculus-volume-1)
* [OpenStax Calculus Volume 2](https://openstax.org/details/books/calculus-volume-2)
* [OpenStax Calculus Volume 2](https://openstax.org/details/books/calculus-volume-3)
* [OpenStax Chemistry 2e](https://openstax.org/details/books/chemistry-2e)
* [OpenStax Atoms-First Chemistry 2e](https://openstax.org/details/books/chemistry-atoms-first-2e)

### References
Portions of this lesson were inspired by or adapted from: 
* [OpenStax Calculus Volume 1](https://openstax.org/details/books/calculus-volume-1)
* [OpenStax Calculus Volume 2](https://openstax.org/details/books/calculus-volume-2)
* [OpenStax Calculus Volume 2](https://openstax.org/details/books/calculus-volume-3)

## Lesson Versions & Intended Modalities

Three versions of this lesson are provided, each with a different intended
modality of instruction and associated implementation strategies.

| Modality     | Pedagogy                | Role of Instructor                                                       | Lesson Version            |
|--------------|-------------------------|---------------------------------------------------------------------------|--------------------------|
| Asynchronous | Guided Inquiry Learning | N/A (independent student learning)                                       | `student-async.ipynb`     |
| Synchronous  | Guided Inquiry Learning | Facilitate student process, answer questions, ensure nobody falls behind | `student-sync-gil.ipynb`  |
| Synchronous  | LiveCoding              | Demonstrate & narrate process, control pacing, etc.                      | `student-sync-live.ipynb` |

Also provided to support adopting instructors are
- `instructor-key.ipynb`: Instructor "key" notebook with completed code cells and full instructor commentary in Markdown cells
- `instructor-notes.ipynb`: Author notes for adopting instructors, including implementation strategies, common issues & workarounds, piloting notes, etc.

See the `instructor-notes.ipynb` For more information about implementation
strategies from the lesson author.


