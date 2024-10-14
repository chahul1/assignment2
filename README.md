# assignment2.
Q1
# Calculation of total Infiltration by Horton's Equation
fo = float(input("Enter the value of initial Infiltration Rate:"))
fc= float (input("Enter the value of Final infiltration Rate:")
t= int(input("Enter the value of Time:"))
kh= float(input("Enter the value of Decay Coefficient:"))
# The total Infiltration is given by:
Fp= fc't+ (fo -fc)/kh
print ("The value of Total Infiltration is:", Fp)

Q2
 Calculation of Mean precipitation by theissen's polygon Method
 The value of precipitation at Each station is
 p1=int(input("Enter the value of rainfall at Station 1:")
 p2= int(input("Enter the value of rainfall at Station 2:")
 p3 =int(input("Enter the value of rainfall at Station 3:")
 p4 =int(input("Enter the value of rainfall at Station 4:"))
 p5 =int(input("Enter the value of rainfall at Station 5:"))
 #Area for each station
 A1= int(input("Enter the value of Catchment Area for raingauge station 1:")
 A2= int(input("Enter the value of Catchment Area for raingauge station 2:")
 A3 =int(input("Enter the value of Catchment Area for raingauge station 3:")
 A4=int(input("Enter the value of Catchment Area for raingauge station 4:")
 A5= int(input("Enter the value of Catchment Area for raingauge station 5:"))
 The total catchment area is
 A=A1 + A2 + A3 + A4+ A5
 print ("The value of Total Catchment area is:", A)
 # Runoff Volume
 The volume shall be multiplied by the coefficient 2500 to cater scale effects
 #Runoff Volume
 V= (p1* Al+ p2* A2+ p3* A3+ p4 *A4+p5* A5)*2500
 print ("The runoff volume from the given catchment is:", V)
 # Mean Precipitation
 p (p1 A1+ p2 A2 p3 A3+ p4A4+ p5 A5)/A
 print ("The value of Mean Precipitalon is:", p)

 Q3
 #Calculation of Mean precipitation by Isohytel Method
 #The value of precipitation at Each station i
 p1=int(input("Enter the value of rainfall at Station 1")
 D2= int(input("Enter the value of rainfall at Station 2:"))
 D3=Int(Input("Enter the value of rainfall at Station 3")
 p4=int(input("Enter the value of rainfall at Station 4:")
 p5= int(input("Enter the value of rainfall at Station 5")
 p6=int(input("Enter the value of rainfall at Station 6:")
 p7= Int(input("Enter the value of rainfall at Station 7:")
 p8=int(input("Enter the value of rainfall at Station 8:")
 # Area for each station
 A1= int(input("Enter the value of Catchment Area for raingage station 1:"))
 A2= int(input("Enter the value of Catchment Area for raingauge station 2:")
 A3= int(input("Enter the value of Catchment Area for raingauge station 3:")
 A4=int(input("Enter the value of Catchnent Area for reingauge station 4:")
 A5= int(input(" Enter the value of Catchment Ares for raingauge station 5:")
 A6= Int(input("Enter the value of Catchment Area for raingeuge station 6:"))
 A7= int (input("Enter the value of Catchment Area for reingauge station 7:")
# The total catchment area is
 A= A1+ A2+ A3+ A4+ A5+ A6+ A7
 prínt ("The value of Total Catchment ar ea is :"4)
# Mean Precipitation
 p=((p1+p2) *A1/2 + (p2+p3)*A2/2+ (p3-p4)*A3/2+ (p4+p5)* A4/2 + (p5+p6) "AS/2 + (p6+p7) "A6/2+ (p7+p8)*A7/2)/A
print ("the value of Mean Precipitalon is:")
