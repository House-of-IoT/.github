## Welcome to House Of Iot 👋

<img align = "center" width = "200px" src ="https://github.com/House-of-IoT/HOI-WebClient/blob/master/Frontend/src/Img/bot.png"/>

Do you dislike having to use a ton of mobile apps to control your store bought smart devices?

Would you like to build your own smart devices/systems and control them from one central interface?

# More In-Depth
House of Iot is a collection of custom smart device automation software. When this software collection is put together it creates
a central point of control for all devices along with other autonomous perks. The software is fully user configurable and 
lightweight, the full suite could be hosted on a single raspberry pi with certain limitations.

### Main Software Components
- The [HOI-GeneralServer](https://github.com/House-of-IoT/HOI-GeneralServer) - controls all devices and manages them.
- The [ExternalController](https://github.com/House-of-IoT/ExternalController) - implementation of ChainControlling.
- The [HOI-WebClient](https://github.com/House-of-IoT/HOI-WebClient) - Web Interface - Shifting to Collaborative IoT Frontend for main usage.
- The [HOI-MobileClient](https://github.com/House-of-IoT/HOI-MobileClient) - Mobile Interface - shifting to collaborative IoT for main support.

### Main Features
- [ChainControlling](https://github.com/House-of-IoT/HOI-GeneralServer/blob/master/Docs/ChainControlling.MD)
- [AutoScheduling](https://github.com/House-of-IoT/HOI-GeneralServer/blob/master/Docs/AutoScheduling.MD)
- Recurring AutoScheduling
- Three authentication leveling system
- Real time passive data collection
- [Real time notifications](https://github.com/House-of-IoT/HOI-GeneralServer/blob/master/Docs/Notifications.MD)
- Grafana Integration
- Device Blueprinting

### What If I don't have the skills to design and implement custom systems/devices?
We provide a ["recipe-book"](https://github.com/HOI-Devices) of custom devices created by the community, this recipe book contains 
different types of devices that could come in handy in automating your home/life.

Every device in the recipe-book have custom peer reviewed tutorials for setting up the hardware and the software to run the system/device properly. 

Want to collaborate with others on your IoT server? Check out [Collaborative-IoT](https://github.com/Collaborative-IoT) which was built by the same creator and has integrations for the platform!
