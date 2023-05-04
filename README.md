Download Link: https://assignmentchef.com/product/solved-cs69012-assignment7-hadoop-combiner
<br>
Hadoop Combiner● Hadoop Combiner is also known as “Mini-Reducer” that summarizes the Mapper output record with the same Key before passing to the Reducer.● The combiner in MapReduce is also known as ‘Mini-reducer’Combiners

Data Set:● The dataset describes chat sessions data from Facebook.com.● There are 10 files.○ “day1.txt”, “day2.txt”, …, “day10.txt”○ “dayx.txt” has the logs of chat sessions on xth day○ Total: 300 users

Task 1: Strongly connected chat network● 300 users in total● Find the pair of users who have chatted at least 30 times in the 10 days● You have to use combiner in this assignment● (deliverables: mapper1.py, combiner1.py, reducer1.py, network.txt)Task 2: Number of mutual friends● Find the number of mutual friends for each pair of nodes in the chatnetwork● E.g. in the shown network○ #mutualFriends(v1,v2)=1○ #mutualFriends(v2,v3)=2● (deliverables: mapper2.py, reducer2.py, friends.txt)Task 3: Number of triangles● Find out the number of triangles through each node in the chat network● E.g. in the shown network○ #triangles(v1)=1○ #triangles(v2)=2○ #triangles(v3)=2○ #triangles(v4)=1● (deliverables: mapper3.py, reducer3.py, triangles.txt)


