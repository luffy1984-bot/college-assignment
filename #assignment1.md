fruits = ["apple", "banana", "cherry", "mango"]
veggies = ("carrot", "lettuce", "potato", "cabbage")
namedict = {
    "Name" : "Chuck",
    "Age" : 67,
    "Job" : "Electrician",
    "Married" : False
}
#operations on list 'fruits':
fruits.append("orange") #adding an item at end of list
print(fruits)
fruits.remove("apple") # removing item
print(fruits)
fruits.pop(0) # alternate method
print(fruits)
#tuple operations:
y = list(veggies)
y.append("bitter gourd")
y.remove("carrot")
y.pop(0)
veggies = tuple(y)
print(veggies)
#dictionary operations:
namedict["Salary"] : 6767 #adding an item
print(namedict)
namedict.pop("Job") #removing an item
print(namedict)
