## Indexing
A list is a sequenced collection of different objects such as integers, strings, and even other lists as well. The address of each element within a list is called an `index`. An `index` is used to access and refer to items within a list.

To create a list, type the list within square bracket `[]`, with your content inside the parentesis and separated by commas.

```
# Create a list

L = ["The Bodyguard", 7.0, 1992]
L 

==> ['The Bodyguard', 7.0, 1992]
```

We can use negative and regular indexing with a list:

# Print the elements on each index

print('the same element using negative and positive indexing:\n Postive:',L[0],
'\n Negative:' , L[-3]  )
print('the same element using negative and positive indexing:\n Postive:',L[1],
'\n Negative:' , L[-2]  )
print('the same element using negative and positive indexing:\n Postive:',L[2],
'\n Negative:' , L[-1]  )

==> the same element using negative and positive indexing:
 Postive: The Bodyguard 
 Negative: The Bodyguard
the same element using negative and positive indexing:
 Postive: 7.0 
 Negative: 7.0
the same element using negative and positive indexing:
 Postive: 1992 
 Negative: 1992