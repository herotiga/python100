# if语句


```python
usr = input('请输入用户名:')
pwd = input('请输入密码:')
if usr == 'admin' and pwd == 'password' :
    print('welcome:admin!')
else:
        print('login failed!')
```

    请输入用户名:admin
    请输入密码:password
    welcome:admin!



```python
gender = input('please enter your gender:')
if gender == 'male':
    print('you are man')
elif gender == 'female':
    print('you are woman')
elif gender != 'male' or gender != 'female' :
    print('error input!')
```

    please enter your gender:dog
    error input!



```python

```
