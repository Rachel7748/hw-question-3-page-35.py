
i = 1
while i<=5:
    temp = int(input('please enter a number'))
    if -5<temp<40:
        print('right temp')
        continue
    if -5>temp>40:
        break
    print('false temp')

i = i+1



