# new-tow
#first-尝试
exercise
num = input("请输入一个数字：")

while True:
   if int(num) < 20:
       print("太小了,")
       num = input("重输一个数字：")
   elif  int(num) > 80:
       print("太大了")
       num = input("再重输一个数字：")
   else:
       print("OK")
       break
