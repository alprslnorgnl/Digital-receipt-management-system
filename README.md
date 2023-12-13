# Digital-receipt-management-system
We want to design a digital receipt management system that we think will replace the paper receipts given to us as a document of our purchases and offer this system as a mobile application.

## Introduction
Trees have been the energy of humanity throughout human history, and they have also played an important role in meeting the basic needs of humanity in many ways. Trees are used as the main raw material in the paper production process, which shows the value of the tree for us. However, today the value of green has become even more valuable due to many reasons such as the use of fossil fuels, deforestation and industrial processes. The World Economic Forum shared the 10 risks the world expects over the next decade in its report titled ["Global Risks Report 2023"](https://www.weforum.org/publications/global-risks-report-2023/digest/) dated January 11, 2023. In this report, 4 out of the top 5 and 6 out of the 10 are environmental risks. This being the case, paper receipts are issued for informational purposes during our shopping and banking transactions.

While our world is facing such serious risks, it is not understandable that we are spending our tree reserves for an application that has the opportunity to be digitalized, like a receipt. The harms of using plugs not only consume our tree reserves, but also cause many problems such as carbon, water, chemicals and waste. A recent study shows that 80% of the US population receives one to three receipts per day, 11% of which are immediately thrown away. Considering that America's retailers produce approximately 228.7 million pounds of receipt paper annually, that means 22.87 million pounds of paper immediately becomes trash. Additionally, as seen in Chart 1, market research on thermal POS device papers predicts that POS device paper prices will increase.


![Graph 1](/assets/ss.png)

In this study, it is aimed to reduce the use of paper receipts and to develop a mobile application where the end user can see their expenses and provide analysis based on historical data.

### Aims and Goals
The main purpose of this project is to develop a system that will reduce and eliminate paper usage while presenting shopping data to the user. In this direction;

a) Developing a system that will completely eliminate receipts, automatically send them to mobile phones during shopping, and store all receipts in a central system.

b) Considering that the use of receipts will continue for a while during the transition to this system, and trying to digitally store the data from the receipt with OCR solutions.

c) It is about developing a Flutter-based cross-platform mobile application where users can view and analyze their receipts.

When these goals are successfully completed, a solution that eliminates paper receipts and can be easily controlled via a mobile application will emerge.

## METHOD
The digital receipt management system consists of three basic processes; These are the user registration and login process, the process of obtaining the receipt information, and the process of accessing the data requested by the User.

Our mobile application will be based on Flutter and in accordance with microservice architecture.

![Microservice Arch](/assets/microservice.png)

### User Registration and Login Process

![service 1](/assets/service1.png)

### Process of Obtaining Receipt Information

![service 2](/assets/service2.png)

### The Process of  obtaining the information the user wants

![service 3](/assets/service3.png)
