# Prime-number

nums = int(input(""))
if nums > 1:
    for i in range(2, nums):
        if nums % i == 0:
           print("{} is not a prime number".format(nums))
           break
    else:
        print("{} is a prime number".format(nums))
        
else:
    print("{} is not a prime number".format(nums))
