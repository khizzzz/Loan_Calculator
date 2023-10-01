# Loan_Calculator
Create a loan Calculator using Python
x = input()
print("Enter your name =", x)
print("Enter your Salary =")
BS=int(input())/1000

if(BS >= 100):
    AL=(BS*0.5,BS*0.2,BS*0.3)
elif(BS>=50):
    AL=(BS*0.4,BS*0.3,BS*0.2)
elif(BS>=30):
    AL=(BS*0.6,BS*0.5,BS*0.4)
GS=BS
for i in range (3):
    GS += (AL(i))
TAX=0
if(GS>=150) :
    NS=GS*0.4
elif(GS>=100):
    NS=(GS*0.3)
elif(GS*80):
    NS=(GS*0.2)
NS=GS-TAX

loan=NS*0.2

print("Your Basic Salary was = ",BS*1000)
print("Your Gross Sale will be =",GS*1000)
print("Your Tax you will pay will be = ",TAX*1000)
print("The Maximum Loan you can get is:=",loan*1000)





