# Common Mistakes in R Programming

1. **Using `=` and `<-` inconsistently**  
    Use `<-` for assignment in course materials.
2. **Forgetting that indexing starts at 1**  
    `x[0]` returns an empty result.
3. **Confusing `==` with assignment**  
    `x == 5` checks equality; `x <- 5` assigns value.
4. **Mixing types in one vector unintentionally**  
    Coercion may silently change data type.
5. **Confusing `*` with `%*%`**
6. **Forgetting 1-based indexing**
7. **Mixing incompatible dimensions**
8. **Assuming non-square matrices can be inverted**
9. **Ignoring row/column names in interpretation**
10. **Assuming `df["col"]` and `df$col` are identical objects**
11. **Forgetting to check structure with `str()`**
12. **Filtering without checking number of rows returned**
13. **Adding rows with wrong column order or names**
14. **Overwriting important columns by accident**
15. **Confusing `[ ]` with `[[ ]]`**
16. **Expecting `sapply()` to always return a vector**
17. **Forgetting that `NULL` removes list elements**
18. **Using `unlist()` and accidentally losing structure**
19. **Not naming elements in larger lists**
20. **Using `1:length(x)` instead of `seq_along(x)`**
21. **Forgetting to initialize output object before loop**
22. **Using `[` instead of `[[` for list element extraction**
23. **Overwriting loop variable inside loop body**
24. **Assuming loop runs at least once even for empty inputs**
25. **Forgetting to update variable in condition**
26. **Writing condition that can never become `FALSE`**
27. **Using `next` before update logic (causing stuck loop)**
28. **Changing wrong variable inside loop**
29. **Not initializing accumulators**
30. **forgetting to return a value when needed,**
31. **unclear function names,**
32. **mixing many tasks in one function,**
33. **no input checks,**
34. **relying on global variables by accident.**
35. **wrong working directory,**
36. **misspelled file name or extension,**
37. **wrong separator (`","` vs `";"` vs tab),**
38. **forgetting `row.names = FALSE` on export,**
39. **skipping inspection after import.**
40. **forgetting to assign result to a new object,**
41. **mixing row and column logic in one step,**
42. **using too many operations inside one `mutate()`,**
43. **not checking missing values before calculations or sorting,**
44. **writing long code without pipes or comments.**
45. **forgetting `na.rm = TRUE` in summaries,**
46. **forgetting to `ungroup()` before next steps,**
47. **mixing row-level and summary-level logic in one pipeline,**
48. **accidental grouping by too many variables,**
49. **expecting `summarise()` to return many rows per group.**
50. **selecting wrong columns in `across()`,**
51. **forgetting `na.rm = TRUE` in numeric summaries,**
52. **confusing `if_any()` with `if_all()`,**
53. **overusing very broad selectors without checking output,**
54. **writing column-wise code without inspecting result names.**
55. **slicing before ordering,**
56. **not handling missing values before ranking,**
57. **using global ranking when grouped ranking is needed,**
58. **dropping ties accidentally or keeping too many rows unintentionally,**
59. **deduplicating without defining which row should be kept.**
60. **joining on wrong key column,**
61. **using `inner_join()` when `left_join()` was needed,**
62. **ignoring duplicate keys,**
63. **not checking unmatched rows,**
64. **assuming row count should never change.**
65. **using inequality join without understanding many-to-many expansion,**
66. **not validating join relationship,**
67. **wrong direction in rolling joins (`>=` vs `<=`),**
68. **ignoring duplicate keys before advanced joins,**
69. **using `cross_join()` accidentally (huge row explosion).**
70. **forgetting to handle `NA` in conditions,**
71. **putting broader `case_when()` rule before narrower one,**
72. **using `==` with decimals instead of `near()`,**
73. **using exact-match tools for range logic,**
74. **forgetting that sequence helpers depend on row order.**
75. **using `bind_cols()` when key-based logic is needed,**
76. **forgetting key uniqueness before `rows_update()`/`rows_upsert()`,**
77. **applying updates without checking row counts,**
78. **deleting rows without keeping reproducible code.**
79. **adding too much formatting too early,**
80. **not rounding numbers,**
81. **table without clear title/caption,**
82. **exporting without checking output,**
83. **choosing style that hides key values.**
84. **selecting wrong columns in `pivot_longer()`,**
85. **forgetting that keys must identify rows in `pivot_wider()`,**
86. **ignoring duplicate keys before widening,**
87. **dropping `NA` too early.**
88. **dropping missing values too early,**
89. **filling with default values without documenting meaning,**
90. **using wrong separator in `separate()`,**
91. **forgetting that `separate_rows()` increases row count,**
92. **ignoring row count checks after each step.**
93. **adding too much formatting too early,**
94. **not rounding numbers,**
95. **table without clear title/caption,**
96. **exporting without checking output,**
97. **choosing style that hides key values.**
