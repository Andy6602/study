# study
study
#创建和使用具有返回值的函数
def calculateTax(price,tax_rate):
    total = price + (price * tax_rate)
    return total

my_price = float(input(("输入价格："))

totalPrice = calculateTax(my_price,0.06)
print("price = ",my_price,"Total price = ", totalPrice) # 这里报错
