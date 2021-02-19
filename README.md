# training-revenue-milestones
Revenue Milestones
We keep track of the revenue we make every day, and we want to know on what days we hit certain revenue milestones. 
Given an array of the revenue on each day, and an array of milestones we want to reach, return an array containing the days on which we reached every milestone.

Signature

int[] getMilestoneDays(int[] revenues, 
int[] milestones)

Input

revenues is a length-N array representing how much revenue we made on each day (from day 1 to day N). milestones is a length-K array of total revenue milestones.

Output

Return a length-K array where K_i is the day on which we first had milestones[i] total revenue. If the milestone is never met, return -1.

Example

revenues = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100]

milestones = [100, 200, 500]

output = [4, 6, 10]

Explanation

On days 4, 5, and 6, we had total revenue of $100, $150, and $210 respectively. Day 6 is the first time that we had >= $200 of total revenue.
