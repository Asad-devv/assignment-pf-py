# assignment-pf-py
list1 = ["a", "b", "c", "d", "e"] 
list2 = [7,4,2,9,8]
alternated_list = []
if len(list1)==len(list2):
for i in range(0, len(list1)):
 alternated_list .append(list1[i])
 alternated_list .append(list2[i])
print("The zig-zag printing of elements\n”+str(alternated_list ))
else:
print("Please enter same number of elements in both lists.")
