# Tinhtientro
A=float(input("Nhập số tiền phòng: "))
a=float(input("Nhập số điện đầu tháng: "))
b=float(input("Nhập số điện cuối tháng: "))
c=float(input("Nhập đơn giá 1 số điện: "))
B=(b-a)*c
x=float(input("Nhập số nước đầu tháng: "))
y=float(input("Nhập số nước cuối tháng: "))
z=float(input("Nhập đơn giá 1 số nước: "))
C=(y-x)*z
D=A+B+C 
print(f"Tổng số tiền phòng trọ của 1 tháng: {D:,.2f} đồng")
