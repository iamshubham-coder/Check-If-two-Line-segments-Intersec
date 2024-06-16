# Check-If-two-Line-segments-Intersect
GFG POTD 17-06-2024
Given the coordinates of the endpoints(p1,q1, and p2,q2) of the two line segments. Check if they intersect or not. If the Line intersects return true otherwise return false.

Examples

Input: p1=(1,1), q1=(10,1), p2=(1,2), q2=(10,2)
Output: false
Explanation:The two line segments formed by p1-q1 and p2-q2 do not intersect.
Input: p1=(10,0), q1=(0,10), p2=(0,0), q2=(10,10)
Output: true
Explanation: The two line segments formed by p1-q1 and p2-q2 intersect.



basic beginer approach to solve this problem is to check that their slope is equal or not if equal then return false otherwise true;
we create two array to store the value and to check their value is equal or not
