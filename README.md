# unbxd
def length_of_longest(A):
  p1=0
  used_char={}
  ans=0
  for i in range(len(A)):
    if A[i] in used_char :
      p1=used_char[A[i]]+1
    else:
      ans=max(ans,i-p1+1) 
      used_char[A[i]]=i
  return ans     
x=length_of_longest("pwwkew")
print(x)
Difference between knn and kmeans
K means is a unsupervised algorithm (clustering) and knn is supervised algorithm.
Kmeans used to unlebbeled cluster dataset.group based on relative similarity.
Knn used for label dataset.
Difference between l1 and l2
L2 regularization update weights slowly near the zero as gradient is very less .L1 regularization is fast .
L1 regularization is fast as it makes redundant features weights to zero not in the case of L2 regularization.
Time complexity of l1 regularizatin is less compare to l2.
L1 is a sparse compare to l2.


