# DIY-Walnut-cracking-machine
![image](https://user-images.githubusercontent.com/19898602/138895556-fac273e4-c69e-4989-be01-a04ab8d3021b.png)

Walnut are very delicious to eat but at same time its quite hard time to crack them, 
its more painful if you have plate full of walnut to crake

So I decide to build a machine which can crack walnut for me.

for this I used high torque motor and com hardware to built this machine



# COMPONENT USED

> High torque DC motor

> Cuustom PCB for speed control

> 6mm Acrylic sheet

> 6x10 Alu. strip

> 20mm Wooden base

> M16 nut & bolt

> M12 Liner bearing

> brass spacers

> Nylon gears



# Circuit design & Custom PCB

In this project we have used a simple Geared DC motor for this motor we need to do speed control

for this task I have designe a uuniversal DC motor speed controller PCB 

So first of we will see some basic of this circuit

This the circuit diagram of speed control PCB 

![image](https://user-images.githubusercontent.com/19898602/129914741-251cba90-415a-484a-8a38-b94a992b960e.png)

This is a pretty cool circuit that allows you to control the speed a DC motor of considerable size

Followings are the component used in the circuit


![image](https://user-images.githubusercontent.com/19898602/129915282-53214abf-5f2d-4d99-9c3c-0bec60176886.png)

DC motor may be a purely inductive Load so if you would like to regulate the speed of the DC motor then we've to upper / lower the voltage for higher / lower speeds. 

but in practically higher voltage and lower voltage isn't that sort of possible so, during this case,

we use another sort of method which is named PWM better referred to as pulse width modulation.



The word PWM is additionally referred to as Pulse Width Modulation. Suppose there's a voltage of 5 volts which is popping on and off in an interval. 

This on / off signal is especially presented as duty cycles now if there's a 50% duty cycle within the output voltage are going to be 50% of 5 volts so it'll be nearly 2.5 volts. The duty cycle are often 25% of fifty or 90% or maybe 100%. 

so now you'll calculate what the voltage is going to be when the duty cycle is going to be during a certain percentage. Now this PWM Pulses runs the transistor and it runs the Motor.


![image](https://user-images.githubusercontent.com/19898602/129915627-2d14fafc-3ff7-434d-aa31-7e932ee2b321.png)

![image](https://user-images.githubusercontent.com/19898602/129915648-55bc75a4-dd7c-41fb-9109-a3f386c30347.png)


Here are Some Pictures for creating the Circuit. I even have made the DC Motor Speed Controller Circuit within the PCB for creating the circuit as simple as possible. 

you'll also make the circuit within the Breadboard. But there could also be loose connection So I even have Directly Soldered all Components. 

So, there'll not be any loose connection.

I always prefer visit [JLCPCB.com](https://jlcpcb.com/IAT) because they offering high quality PCB in reasonable price in very short time so why go elsewhere 
visit [JLCPCB.com](https://jlcpcb.com/IAT) for High quality PCB and discount coupons on first order.


![image](https://user-images.githubusercontent.com/19898602/129916137-da650983-277d-4ccd-b31a-75ad9a5e2c36.png) ![image](https://user-images.githubusercontent.com/19898602/129916214-084ea734-5112-4413-8549-c08ed65e49b6.png) ![image](https://user-images.githubusercontent.com/19898602/129916509-12b63531-5643-4db5-a0b9-779b94285da0.png) ![image](https://user-images.githubusercontent.com/19898602/129916646-484321c3-ad7e-486b-9158-dae533940d88.png)







# DC MOTOR Details

![image](https://user-images.githubusercontent.com/19898602/138900524-b60915bd-3e94-4cf7-a3e0-276b5b96dd28.png)

I have used this 12V geared DC motor

**Orange 12V 60 RPM Johnson Geared DC Motor**

> Base Motor RPM: 18000


> Operating Voltage: 6-18 V


> Rated Voltage: 12 V


> Rated Torque: 157.6 N-cm


> Stall Torque: 850 N-cm


> Gearbox Dimensions: 29×37 (LxW) mm



![image](https://user-images.githubusercontent.com/19898602/138900026-ce87fde6-e575-40bf-96bd-3bef08bcc4c9.png)
![image](https://user-images.githubusercontent.com/19898602/138900079-f53c3ba4-8d47-476d-aef8-0275db7f4cb3.png)


first of all I got 20mm thick wooden block. and cut it in desire shape using my mini table saw

I polished the wooden block using 1000 grit sandpaper so it will look nice also I champers the edge of 
wooden block



![image](https://user-images.githubusercontent.com/19898602/138899425-6b20d32c-36bf-429d-9ddc-b136d4b3f887.png)
![image](https://user-images.githubusercontent.com/19898602/138899496-1f7dc461-d688-4ab0-b1ef-9c3c2c014d07.png)





I have used High torque DC motor in this project but I need some more torque to decide to cut some acrylic and create my own gear box

I design 3D part in onshape 3d designing android app and export it in stl file.
then I used fusion 360 software for CAM operation.

I have generated G-code in fusion 360 and cut the acrylic part in my home made cnc router machine



![image](https://user-images.githubusercontent.com/19898602/138903918-c9ae7f19-3b2e-4d9b-934b-189b36f0fe43.png)
![image](https://user-images.githubusercontent.com/19898602/138903978-12ec8b25-fa7e-49b9-91f1-bc96469d0e03.png)

This is the full assembly of gear box


![Nested Sequence 01](https://user-images.githubusercontent.com/19898602/138904436-661012a9-efc6-44cb-8b64-eebd1f9f9bee.gif)

This is how walnut pressing mechanism looks like.
I trim down the 16mm nut to 12mm using my mini lathe machine, 
Then I used 12mm linear bearing to slide this bolt one end of this smooth bolt is connected with the crank shaft 

and further this crank shaft is connected with our gear box, and other end of bolt which is head portion is used 
to press the walnut against one end

![image](https://user-images.githubusercontent.com/19898602/138905762-bb390405-246c-4a4c-b294-e336faf1e78b.png)

For the other end I cut M16 bolt in small length and 3D printed some part to hold this bolt

This bolt is adjustable so the we can increase or decrease the default distance between rigid end and dynamic end of bolt

In this way construction of machine is completed our machine is ready to crack walnut.


![MVI_0003](https://user-images.githubusercontent.com/19898602/138906495-4efb2680-7d5f-4071-b822-f711e3d4ec2c.gif)


