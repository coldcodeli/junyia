# junyia
interview

第一題:
a=str(input("Input a string:"))
a=a[::-1]
print(a)

a=str(input("Input a string:"))
list1=a.split(" ")
for i in range(len(list1)):
    list1[i]=list1[i][::-1]
str1=" ".join(list1)
print(str1)


第二題:
a=int(input("Input a number:"))
b=[]
for i in range(1,a+1):
    if(i%3==0)or(i%5==0):
        if(i%a==0):
            print(i)
            b.append(i)
        else:
            continue
    else:
        print(i)
        b.append(i)
print(len(b))


第三題:
先選擇標示混合的袋子，因題目說標示都是錯的，所以可知這一袋絕對不是混合，
若拿出來是鉛筆，則這一袋就全是"鉛筆"，而邊是原子筆那一袋則是"混合"，標示鉛筆的就是"原子筆"。


第四題:
題目的式子，是用來誤導的，我們先不要看，
三人各出270，270*3=810，810為三人出錢總額，
此時我們要看餐點特價後的價格=750，三人出錢810減去被暗槓的60，810-60=750。
跟900沒有關係，不要被他騙了。
