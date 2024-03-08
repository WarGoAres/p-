# p-
p級數
# p series p 級數

#微積分(級數收斂)

# n<=1,發散 (divergent)
# n>1,收斂 (convergent)

#數列 1,1/2,1/3,1/4.......
#(有沒有加在一起)
#級數 1+1/2+1/3+.....

#1+1/2+1/3 .....(收斂發散???)


i=1 #n變成i
sum=0
for i in range(1,201):
  i=1/(i**2)
  sum=sum+i
  print(sum)

