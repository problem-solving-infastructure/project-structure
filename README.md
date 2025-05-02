# Project structure

## General recommendations

To maintain documentation, it doesn't matter if you use GitHub or another service for storing code, we recommend using [Markdown](https://en.wikipedia.org/wiki/Markdown).

We recommend starting each top-level README file with title, about section, and links to your profile on service belongs to repository.

```markdown
# leetcode-java

## About

Some solved problems from [LeetCode](https://leetcode.com) on Java.

## Links

Profile on LeetCode: [fartem](https://leetcode.com/fartem/).
```

After the introductory information, you need to create a table with links to the task and its solution, as well as divide everything into categories from your source.

For example, for [LeetCode](https://leetcode.com), the division will be into `Easy`, `Medium`, and `Hard`.

```markdown
## Problems

### Easy

| Name                 | Link to LeetCode                                         | Link to solution                                                                      |
| -------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| 1. Two Sum           | [Link](https://leetcode.com/problems/two-sum/)           | [Link](./src/main/java/com/smlnskgmail/jaman/leetcodejava/easy/TwoSum.java)           |
| 9. Palindrome Number | [Link](https://leetcode.com/problems/palindrome-number/) | [Link](./src/main/java/com/smlnskgmail/jaman/leetcodejava/easy/PalindromeNumber.java) |

### Medium

| Name                                              | Link to LeetCode                                                                      | Link to solution                                                                                                  |
| ------------------------------------------------- | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| 2. Add Two Numbers                                | [Link](https://leetcode.com/problems/add-two-numbers/)                                | [Link](./src/main/java/com/smlnskgmail/jaman/leetcodejava/medium/AddTwoNumbers.java)                              |
| 3. Longest Substring Without Repeating Characters | [Link](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | [Link](./src/main/java/com/smlnskgmail/jaman/leetcodejava/medium/LongestSubstringWithoutRepeatingCharacters.java) |
```

For [Codewars](https://www.codewars.com), the sections will be different - `8 kyu`, `7 kyu` and so on for each difficulty level.

```markdown
## Katas

### 8 kyu

| Name                             | Link to Codewars                                               | Link to solution                                                                                   |
| -------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Abbreviate a Two Word Name       | [Link](https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3) | [Link](./src/main/java/com/smlnskgmail/jaman/codewarsjava/kyu8/AbbreviateATwoWordName.java)        |
| Age Range Compatibility Equation | [Link](https://www.codewars.com/kata/5803956ddb07c5c74200144e) | [Link](./src/main/java/com/smlnskgmail/jaman/codewarsjava/kyu8/AgeRangeCompatibilityEquation.java) |

### 7 kyu

| Name                  | Link to Codewars                                               | Link to solution                                                                          |
| --------------------- | -------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| All Inclusive?        | [Link](https://www.codewars.com/kata/5700c9acc1555755be00027e) | [Link](./src/main/java/com/smlnskgmail/jaman/codewarsjava/kyu7/AllInclusive.java)         |
| Alphabetical Addition | [Link](https://www.codewars.com/kata/5d50e3914861a500121e1958) | [Link](./src/main/java/com/smlnskgmail/jaman/codewarsjava/kyu7/AlphabeticalAddition.java) |
```

## Language / Framework specific recommendations

Different programming languages and frameworks can use their own structure to work with project files.

We recommend using the general rules for working with a project for your programming language or framework.

The only rule that applies here is that you don't need to mix all the code in one folder. Divide your solutions by complexity categories, or by topics (working with lists, binary trees, and search).

In addition to explicitly dividing the files into different sections, name the files using the task number (if they exists). Some programming languages ([Dart](https://dart.dev) for example) contain a basic linter rule for naming files, where it is forbidden to use numbers in the file name. If you don't need the rule except in this case, disable it in the linter settings.

We need this rules for easy viewing your files. If you are searching solution from LeetCode, it is easy to navigate by problem number, not its name.

```shell
100_same_tree.dart
101_symmetric_tree.dart
104_maximum_depth_of_binary_tree.dart
108_convert_sorted_array_to_binary_search_tree.dart
110_balanced_binary_tree.dart
111_minimum_depth_of_binary_tree.dart
112_path_sum.dart
118_pascals_triangle.dart
13_roman_to_integer.dart
14_longest_common_prefix.dart
1_two_sum.dart
20_valid_parentheses.dart
21_merge_two_sorted_lists.dart
263_ugly_number.dart
27_remove_element.dart
3280_convert_date_to_binary.dart
3516_find_closest_person.dart
35_search_insert_position.dart
500_keyboard_row.dart
58_length_of_last_word.dart
66_plus_one.dart
67_add_binary.dart
69_sqrt_x.dart
70_climbing_stairs.dart
83_remove_duplicates_from_sorted_list.dart
88_merge_sorted_array.dart
94_binary_tree_inorder_traversal.dart
9_palindrome_number.dart
```

## Feedback

If you have a question, issues, or comment, write to artem.fomchenkov@outlook.com.
