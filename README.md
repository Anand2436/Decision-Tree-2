# Decision_Tree_2

There is a slight error in the code when we are trying to display feature number in recursive calls.

the code should be :

if ans_feature in feature_added:
  n = ans_feature
  while(n in feature_added):
    n = n+1
  print("Splitting on feature X",n," with gain ratio ")
                features_added[n] = True
