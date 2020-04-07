# summary class 09

## functionl programming
is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.
- the benefit of pure function is the code’s definitely easier to test.
- immutable data
const string = " I will be a url slug   ";

const slugify = string =>
  string
    .toLowerCase()
    .trim()
    .split(" ")
    .join("-");

slugify(string); 
- **pure functions + immutable data = referential transparency**
- Example on Higher order function:
1. map
2. filter
3. basic reduce and advance reduce


## Refactoring JavaScript for Performance and Readability
- take long URl and return short URL
