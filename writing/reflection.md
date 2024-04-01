# Containment Checking

TODO: Make sure that you delete all of the TODO markers from this file and
either rewrite or delete the prompts. When you are finished writing the content
in this reflection you should ensure that your document does not have any
mistakes in spelling, grammar, or Markdown syntax. Ultimately, your final
version of your technical writing should be suitable for publication on your
professional web site.

## Add Your Name Here

## Program Output

### Report at least five examples of program output to demonstrate that your `containmentcheck` program works correctly

TODO: Document and justify your choice for all of the experiment parameters
TODO: Make sure that you provide five different command-lines to demonstrate
how your program runs experiments and produces output

#### First output from running the `containmentcheck` program

TODO: Give the exact command-line that resulted in this output
TODO: Provide a fenced code block with one output from running the program

#### Second output from running the `containmentcheck` program

TODO: Give the exact command-line that resulted in this output
TODO: Provide a fenced code block with one output from running the program

#### Third output from running the `containmentcheck` program

TODO: Give the exact command-line that resulted in this output
TODO: Provide a fenced code block with one output from running the program

#### Fourth output from running the `containmentcheck` program

TODO: Give the exact command-line that resulted in this output
TODO: Provide a fenced code block with one output from running the program

#### Fifth output from running the `containmentcheck` program

TODO: Give the exact command-line that resulted in this output
TODO: Provide a fenced code block with one output from running the program

## Experiment Design

TODO: Explain the setup for your experiment that you plan to run to
characterize the performance of the different configurations of containment
checking algorithms. Remember, a containment check determines whether or not a
specified value exists inside of some type of data container! For instance, you
should consider the following parameters as a part of your experiment:

- The data container: `set`, `list`, and `tuple`
- The size of the data container: small values (e.g., 1 million numbers) to big
  values (e.g., 32 million numbers)
- Whether or not the value that it being searched for is in the list
- The maximum value of the numbers that are inside of the data container

TODO: You must justify every part of your experiment design and then furnish
output examples to demonstrate that your program generates correct data!

TODO: The output examples that you give are in an earlier subsection of this file.

## Research Questions

TODO: Clearly state at least three research questions that you want to ask and
answer by using the `containmentcheck` program. You should provide the research
questions in a list with three entries that each start with "RQ" and end with a
question mark. Bearing in mind that it must be feasible for you to answer the
research questions, You should aim to write three research questions for which
there is a knowledge gap about the performance of the `in` operator in Python.

## Data Tables

TODO: Use Markdown to provide one or more data tables that summarize the results
from running the `containmentcheck` program in different configurations. You
should provide enough data tables and output values to ensure that you can
answer all of your research questions and use the empirical results to classify
the likely worst-case time complexity of each of the algorithms.

## Performance Analysis

### Empirical Evaluation

TODO: Provide at least three paragraphs that explain which containment checking
algorithm is fastest, by how much it is faster, and how you knew that it was
faster, referencing the data in the aforementioned command outputs and the data
tables to support your response. You should make sure that you answer each of
the at least three research questions that you posed in a previous section.

TODO: Make sure that your responses explain WHY certain configurations are faster!
TODO: It is NOT sufficient to ONLY explain WHICH configuration is faster!

### Analytical Evaluation

TODO: Using the provided source code for the different containment check
algorithms, your textbook, your experimental results, and any relevant online
resources that you cite in this reflection, define the worst-case time
complexity, using the big-O notation, for the three containment check
algorithms called `containment_check_tuple`, `containment_check_list`, and
`containment_check_set`. You should justify why you picked that complexity.

## Source Code

### Describe in detail how the provided source code works

TODO: Use a fenced code block to provide the requested source code
TODO: Write at least one paragraph to explain the provided source code

```python
number_runs = 10
number_repeats = 3
execution_times = timeit.Timer(containment_check_lambda).repeat(
    repeat=number_repeats, number=number_runs
```

### Describe how you implemented the following function

```python
def calculate_average_values(data_list: List[float], data_count: int) -> List[float]:
```

TODO: Write at least one paragraph to explain the source code that you wrote for this function

## Professional Development

### What is the most challenging task when designing an experiment to evaluate an algorithm's performance?

TODO: Provide a one-paragraph response that answers this question in your own words.

### Why is it necessary to perform both an analytical and an empirical evaluation of an algorithm?

TODO: Provide a one-paragraph response that answers this question in your own words.

### How do the empirical results suggest that you don't yet know the entire story about the performance of containment checking?

TODO: Provide a one-paragraph response that answers this question in your own words.
