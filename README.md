# COMP90050-Tutor
# CS Assignment Tutor/Help
# Wechat: csprojhelp 备注: github

COMP90050专业辅导1v1助攻

Question 1: [4 Marks] In one paragraph, discuss the importance of disks in DBMS design in its early years.

nested

Question 2: [6 Marks] We have seen two join algorithms in class. Describe in your own words how each of these algorithms work given two tables to join, with one paragraph to describe each algorithm. Then explain which one of these algorithms commonly works more efficiently than the other and why this is the case, explain with one paragraph.

Question 3: [6 Marks] Given the following transaction history h we are told that a, b, c, d, e, f, and g are transactions, and operations are Read and Write operations which are labeled as R and W, and operations are done on the objects labeled as x, y, z, v, u, t. Here h is equal to

<(a,R,x),(c,W,x),(c,W,y),(f,R,t),(d,R,y),(a,W,z),(b,W,u),(e,R,z),(e,R,v),(g,W,v),(f,W,t)> Please find the DEP(h) and draw as a simple graph version as well. Then using the concept of wormholes explain whether this history is equal to a serial history or not, i.e., if this history is not equal to a serial history then give a wormhole example, and if it is then give a serial execution of these transactions that this history is equal to. Briefly explain your steps with sentences while answering this question.

AS2 

PL

Question 4: [5 Marks] What is the difference between Two-phase locking and a locking strategy where all locks are taken at the beginning of a transaction and released at the end of a transaction? Compare the two approaches in a few paragraphs, i.e. their benefits and disadvantages. Would there be any concurrency if the second method mentioned above is used. Briefly explain.

Question 5: [6 Marks] Given the R-tree below with point data, where black labeled dots represent spatial coordinate data, and the tree structure is shown on the left of the figure, we also give a nearest neighbor query point “q” (and the circles represent distances of different entities to this query point). Run the nearest neighbor query that we saw in class with a priority queue step by step until the third nearest neighbor object is found. Explain briefly as well.

Question 6: [4 Marks] What are the properties of an ideal hash function that we discussed in class. Describe each briefly. Then discuss why these properties are important for hash indices.

Question 7: [4 Marks] Describe why a bank may prefer to refer to ACID properties than BASE properties in its database systems. At the same time why would an online shopping system may be built with mainly BASE properties in mind? Briefly explain each.

Question 8: [3 Marks] Shadow paging is a mechanism one can use in database recovery. Despite its promise to be a fast recovery system discuss why it did not become a common recovery mechanism used by DBMS designers.

Question 9: [3 Marks] We have seen the supermodule concept in class with repairs. Explain in your own words even when we have disks where failures per disk may happen almost every other year, a supermodule using these disks may be fault tolerant at the level of many years or even hundreds of years. Briefly explain your rationale.

W R→ 

+ R

。

Question 10: [6 Marks] Give an example concurrent execution of transactions, using three transactions of your choice/design, where the execution is an example for Degree 2 isolation and an unrepeatable read occurs. Show all the relevant details such as locks taken etc and briefly explain. Note: use a table where as time progresses transactions take their individual actions in time and they run concurrently.

Question 11: [3 Marks] In the following figure we see an expression a DBMS is using to execute a query:

What happens if the DBMS does the selection operation later in the execution sequence given above, and in that case the last join operation given above gets to be done before the selection. Briefly explain.
