# improved-adventure
a = int(input())
d = {}
for i in range(a):
    keys= input().split()
    if keys[0] in d:
        d[ keys[0] ] += int(keys[1])
    else:
        d[ keys[0] ] = int(keys[1])
list_of_keys = d.keys()
        

for key in sorted(d.keys()):
	print(key, d[key])
