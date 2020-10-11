# JunctionX Seoul 2020 | Weco | Team Telepa-see

Weco, a video conferencing software, connects everyone's echo. We contribute to an inclusive society. 

### Microsoft Azure Cognitive Services

This backend has already completed our main features by using Microsoft Azure Cognitive Services. Firsly, Weco deployed Azure Cognitive Service on Azure portal. Secondly, we brainstormed to choosing technologies from Azure services, then selected some API services from Microsof Azure Cognitive Services to tackle our issues and develop our solutions.
In order to develop our solutions that mentioned in [project proposal](https://drive.google.com/file/d/1FYdHjCYG57b0U-Go4lhKOeZSk-0WucPX/view), we implemented these features: 
+ Speech to Text API [source code](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/tree/master/STT)
+ Text to Speech API [source code](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/tree/master/STT)
+ Translation that implemented 2 languages English and Korean [source code](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/tree/master/translation)

### Future Plan

Because of the short time, we have just implemented 3 features from Microsoft Azure Cognitive Service and we have a plan to improve this project through some other features from Microsoft Azure services such as Azure databases and Azure server in the future. 

### More Detailed Description can be found below
Project Proposal Link: [Weco Proposal File](https://drive.google.com/file/d/1FYdHjCYG57b0U-Go4lhKOeZSk-0WucPX/view?usp=sharing)

Main Video: [Weco Main Video](https://youtu.be/Jxf5ISGTHdc)

Prototype Video: [Weco Prototype Video](https://youtu.be/px1pHuXSqB0)

Git Repository Link: [Weco Git Repository](https://github.com/JuntionXSeoul2020Telepasee)

### Acknowledgements
We would like to express our very great appreciation to people from JunctionxSeoul for their valuable support and organize many activities. We would like to express our deep gratitude to mentors from Microsoft for their enthusiatic encouragement and Azure Microsoft credits for us to use API services in Azure platform to develop this project.

### Why We Select this Dev Stack?
This server implemented a video call using socketio for StateFull based on Flask Framework.

When selecting a technology stack, the following criteria were set.
1. It should be able to be organized based on the group to participate in the call room.
2. Network protocol with low delay should be used for video calls.
3. You have to write down the running curve.
4. Must be web-based.

So after considering it, I decided to make Socketio based on Flask.

Socketio chose the back-end technology stack because it is stateful and easy to manage and control users based on multi-tenancy architecture in addition to low running curves.
So this server is based on a multi-tenancy architecture.

### Major Features

The wecho backend uses Azure's Congitive Service to provide a total of three major functions of wecho. The first is the function that the user tells the callers by chatting instead. Second one is the ability to transcribe what the user says into the chat room. The third function is to translate what the user says into Korean and interpret it from the side of the interpreter.

These features were created using Azure's Creative Service API above.

### License 
Weco is [MIT licensed](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/blob/master/LICENSE)
