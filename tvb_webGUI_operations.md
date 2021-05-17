


## TVB WebGUI workflows:

Step 0: 

I suggest that Dr. Simmons you can use my account to do all the tests since it would be much more convenient and you don't have to upload the data file again.

My account: TVB_Yile

My Password: TVBTVB


### Workflow 1. [simplest] 2D model:

In Simulator page, we need to change the parameters below (for the rest of the parameters, we can keep them as default):

1. conduction velocity: 10.0
2. alpha (a): [0.02]
3. local dynamic model: Generic 2D Oscillator
4. Integration scheme: Stochastic Heun
5. D: 0.00001
6. Monitors: check Raw Recording and Temporal Average

**ALL the parameters are listed below**
![Screenshot from 2021-05-16 23-54-22](https://user-images.githubusercontent.com/37648360/118434131-1fd5e200-b6a2-11eb-8f29-1aa5a66065d6.png)
![Screenshot from 2021-05-16 23-54-31](https://user-images.githubusercontent.com/37648360/118434133-206e7880-b6a2-11eb-906b-ef979f366db4.png)
![Screenshot from 2021-05-16 23-54-36](https://user-images.githubusercontent.com/37648360/118434134-206e7880-b6a2-11eb-9d34-e4eb3079f980.png)
![Screenshot from 2021-05-16 23-54-39](https://user-images.githubusercontent.com/37648360/118434135-21070f00-b6a2-11eb-9fb5-940a8744da62.png)



### Workflow 2. [medium complexity] scaling factor on SJ 3D model:

1. conduction velocity: 10.0
2. alpha (a): [0.001, 0.01, 0.001]
3. local dynamic model: Stefanescu-Jirsa 3D
4. Integration scheme: Stochastic Heun
5. D: 0.00001
6. Monitors: check Raw Recording and Temporal Average

**ALL the parameters are listed below**

![Screenshot from 2021-05-16 23-55-57](https://user-images.githubusercontent.com/37648360/118434237-54499e00-b6a2-11eb-9d85-b269892e82d9.png)
![Screenshot from 2021-05-16 23-56-05](https://user-images.githubusercontent.com/37648360/118434238-54499e00-b6a2-11eb-811b-ed9fb7cdf4b9.png)
![Screenshot from 2021-05-16 23-56-09](https://user-images.githubusercontent.com/37648360/118434239-54e23480-b6a2-11eb-9255-245b11f6b84e.png)
![Screenshot from 2021-05-16 23-56-15](https://user-images.githubusercontent.com/37648360/118434240-54e23480-b6a2-11eb-9675-4a538fa5563c.png)



### Workflow 3. [most complex] BOLD signal simulation:

1. conduction velocity: 10.0
2. alpha (a): [0.001, 0.01, 0.001]
3. local dynamic model: Stefanescu-Jirsa 3D
4. Integration scheme: Stochastic Heun
5. Monitors: check Temporal Average and bold
6. sampling rate: 2000.0
7. Equation: Hrf Kernel: Gamma Kernel
8. Simulation Length: 60000.0

**ALL the parameters are listed below**

![Screenshot from 2021-05-16 23-57-09](https://user-images.githubusercontent.com/37648360/118434329-7e02c500-b6a2-11eb-8f5b-8616cc1df06e.png)
![Screenshot from 2021-05-16 23-57-15](https://user-images.githubusercontent.com/37648360/118434332-7e9b5b80-b6a2-11eb-81cb-ab41d784b34e.png)
![Screenshot from 2021-05-16 23-57-20](https://user-images.githubusercontent.com/37648360/118434333-7e9b5b80-b6a2-11eb-8316-2e67384b815a.png)
![Screenshot from 2021-05-16 23-57-27](https://user-images.githubusercontent.com/37648360/118434334-7e9b5b80-b6a2-11eb-9db6-6a83b67f5e4d.png)
![Screenshot from 2021-05-16 23-57-30](https://user-images.githubusercontent.com/37648360/118434336-7f33f200-b6a2-11eb-9842-b6b5701978d3.png)





