# Spark-question-help-from-FB-

# Question from peer: Hi All,

Recent interview question:
input
name
10srinu200

output
10s200
10r200
10i200
10n200
10u200

can anyone help one spark or HQL query to get above output.

Thanks
srinu



## PS. My udf in the notebook is static and will work perfectly for names which have the same number of characters as 'srinu'. if you have varying lengths of names, then more udfs can be made for those varying names and you can us a when/otherwise clause for each udf by using F.length as the condition for the particular udf..
