my_list=[]
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print('after_append:',my_list)
my_list.insert(1,15)
print(my_list)
new=[50,60,70]
my_list.extend(new)
print('after_extension:',my_list)
my_list.remove(70)
print(my_list)
my_list.sort()
print(my_list)
index=my_list.index(30)
print('item_index:',index)
