# BreakingtheRecords

Maria plays college basketball and wants to go pro. Each season she maintains a record of her play. She tabulates the number of times she breaks her season record for most points and least points in a game. Points scored in the first game establish her record for the season, and she begins counting from there.
Example 

Scores are in the same order as the games played. She tabulates her results as follows:
![image](https://user-images.githubusercontent.com/33404432/120767995-ef1cf600-c545-11eb-8923-adbb71601083.png)

Given the scores for a season, determine the number of times Maria breaks her records for most and least points scored during the season.

Function Description:
Complete the breakingRecords function in the editor below.
breakingRecords has the following parameter(s):
>> int scores[n]: points scored per game

Returns
>> int[2]: An array with the numbers of times she broke her records. Index 0 is for breaking most points records, and index 1 is for breaking least points records.

Input Format:
The first line contains an integer n, the number of games. 
The second line contains n space-separated integers describing the respective values of:
![image](https://user-images.githubusercontent.com/33404432/120768400-4d49d900-c546-11eb-9831-b8d2b9e78f98.png)

Constraints:
![image](https://user-images.githubusercontent.com/33404432/120768462-5f2b7c00-c546-11eb-924d-550afbabd8ec.png)

>>Sample Input: 
9
10 5 20 20 4 5 2 25 1

>>Sample Output:
2 4

**Explanation:**
The diagram below depicts the number of times Maria broke her best and worst records throughout the season:

![image](https://user-images.githubusercontent.com/33404432/120768980-deb94b00-c546-11eb-80b6-a403397f62b0.png)
She broke her best record twice (after games 2 and 7) and her worst record four times (after games 1, 4, 6, and 8), so we print 2 4 as our answer. Note that she did not break her record for best score during game 3, as her score during that game was not strictly greater than her best record at the time.
