
Problem statement: Generally in Teamcenter Item and Item Revision have same attributes like object_name and object_desc. how to synchronize the values if it is required to synchronize?

Solution: Use Propagation rules of project to inherit also these properties.

![image](https://user-images.githubusercontent.com/76819369/134428142-ab88b306-0fd0-4431-bfc7-9cd14734cc05.png)
![image](https://user-images.githubusercontent.com/76819369/134428214-28462562-f6a8-494b-b5be-7f8b9894079d.png)

under Fnd0PropertyGroupNames we can add a new security group
![image](https://user-images.githubusercontent.com/76819369/134428331-5f9048e0-b148-463f-b6e9-61087e238aff.png)


when ever a project assignment happens the attributes object_name and object_desc from Item revision get synchroized to the Item.
