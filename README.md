# PHP Too Many Tabs

Like many people, John loves to have multiple tabs open in his browser and almost never closes them. Well, over time there were a lot of open tabs and Endra had a hard time finding the tab he wanted to open. It's like looking for a needle in a haystack. To simplify his life as a programmer who likes to be creative, John made a simple program to group tabs. Tabs from the same domain will be grouped into one tab group.


## Inputs
- The first line is **T** number of test cases, 1 <= T <= 100
- The next line **T** is the URL tabs that Endra opened for the test case. Each line is separated by a space.

## Outputs

For each test case, print one line with the format Case #i: tab_group_count, where i is the test case number (starting at 1) and tab_group_count is the tab_group number

## Rules
- URL not prefixed with protocol **http://** or **https://**.
- URLs are considered equal if the domains match exactly, i.e. **www.domain.com** and **domain.com** are different.

## Example
```
2
www.google.com www.google.com/id www.google.co.id www.google.co.id/account www.ruangguru.com/ruangbelajar roboguru.ruangguru.com roboguru.ruangguru.com/faq
www.google.com www.google.com/id www.google.com/id/account www.google.com/id/account/reset www.google.com/id/account/forget_password
Sample Output
Case #1: 4
Case #2: 1
```
Explanation, Untuk test case pertama ada 4 tab group:
- www.google.com
- www.google.co.id
- www.ruangguru.com
- roboguru.ruangguru.com
