# JunctionX Seoul 2020 | Weco | Team Telepa-see

Weco, a video conferencing software, connects everyone's echo. Weco will help anyone inclusively communicate with Weco's promising features. 

### Background and Problem Definition

Since the ourbreak COVID-19 pandemic, our work environment has shifted closer and closer to online. With technology, we have still maintained a level of productivity and settled into video conferencing platforms for remote work. While video conferencing ensures safety and productivity, we are still facing problems in creating an inclusive society. 

Someone you may know cannot freely express themselves in a video conference just because they require special needs of hearing, seeing, or speaking in another language.

### Our Solution
With Weco, our video conferencing, everyone's voice can be bridged, hear, and echoed. 

Everything we talk about in video conferences is updated in real-time with a translatable and exportable transcript, and anyone can send their message in "voice to text" or "text to voice" form and easily interact with other users.

We are delivering inclusiveness to those who are incapable of speaking, reading, or understanding in a video conferencing session.


### Technologies
Weco handles features mentioned above with Microsoft Azure Cognitive Services. In order to transcribe speech accurately from users into text, Weco implemented Spech to Text API and deployed this service on the Azure portal. On the other hand, in order to convert text to natural sounding voices in the transcript, we used Text to Speech API. Lastly, Speech Translation API is used to implement the chat and transcript translation, providing a fair and equal opportunity for everyone in the world to communicate.

In order to develop our solutions that mentioned in [project proposal](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/blob/master/project-proposal.pdf), we implemented these above features: 
+ [Speech to Text API](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/tree/master/STT)
+ [Text to Speech API](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/tree/master/STT)
+ [Translation API](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/tree/master/translation) that implemented 2 languages English and Korean


### More Detailed Description can be found below
Project Proposal Link: [Weco Proposal File](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/blob/master/project-proposal.pdf)

Main Video: [Weco Main Video](https://youtu.be/7XLksyDRivk)

Prototype Video: [Weco Prototype Video](https://youtu.be/px1pHuXSqB0)

Git Repository Link: [Weco Git Repository](https://github.com/JuntionXSeoul2020Telepasee)

### Acknowledgements
We would like to express our very great appreciation to people from JunctionxSeoul for their valuable support and organize many activities. We would like to express our deep gratitude to mentors from Microsoft for their enthusiastic encouragement and Azure Microsoft credits for us to use API services in the Azure platform to develop this project.

### License 
Weco is [MIT licensed](https://github.com/JuntionXSeoul2020Telepasee/TelepaSee-Backend/blob/master/LICENSE)
