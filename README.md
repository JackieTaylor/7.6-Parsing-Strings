# 7.6-Parsing-Strings
7.6 warm up
my_str = input('Enter input string:\n')
while my_str != 'q':
    while ',' not in my_str:
        print('Error: No comma in string.\n')
        my_str = input('Enter input string:\n')
    my_str = my_str.replace(' ', '')
    my_str = my_str.split(',')
    print('First word: {0}'.format(my_str[0]))
    print('Second word: {0}\n'.format(my_str[1]))
    my_str = input('Enter input string:\n')
