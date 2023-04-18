Go to tools -> Create and Package New IP:
![image](https://user-images.githubusercontent.com/84331501/224053787-61eab334-1fb9-4029-a150-36eb5a1644d6.png)
Click forwards until you reach "Create AXI4 Peripheral":
![image](https://user-images.githubusercontent.com/84331501/232921592-ca117abc-f047-4d04-aaaf-c83b268c99e0.png)
Naming isn't important and default directory works:
![image](https://user-images.githubusercontent.com/84331501/232921708-52c5e68d-e4ee-444e-a452-ffac971519d3.png)
Registers are where data is written to the block and where the block writes out of, interrupts can also be set preemptively at this time:
![image](https://user-images.githubusercontent.com/84331501/232921906-51500a81-dc70-4208-a1c3-0d2dc4a686fe.png)
You will generally want to edit the IP right away:
![image](https://user-images.githubusercontent.com/84331501/232924727-6ed9a725-d9ff-4242-9c99-75b7c85f4585.png)


IMPORTANT IP BLOCKS

This block is necessary for PS: 

![image](https://user-images.githubusercontent.com/84331501/232920282-3a697d9d-ead7-44d0-aca9-296fb8fdbd7a.png)

AXI GPIO is used very often:

![image](https://user-images.githubusercontent.com/84331501/232920485-85feca31-e367-4e1b-9973-82fc2739f891.png)

How to enable interrupts

After double clicking on the block (example: AXI GPIO):
![image](https://user-images.githubusercontent.com/84331501/232920583-064e7756-ce75-41c2-980e-90a3e4f62c76.png)

Then enable an interrupt in the PS after double clicking on it:
![image](https://user-images.githubusercontent.com/84331501/232920784-5f8062eb-0bdb-4cbd-aba3-d29a6d7e35ec.png)
