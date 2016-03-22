### Can I use this library to uniquely identify users?
#### _ No, you cannot. This library is built to be able to associate string identifiers with devices.
Since there are a lot of identical devices, you will get a lot of identical identifiers. _

### OK, I get it, I cannot _uniquely_ identify users, but can I identify users at all?
#### _ No, you cannot. This library is strictly for non-deterministic device identification. _


### How good is your library? Can you guarantee that different devices will have different identifiers?
#### _ This library is not good. It has an error margin of 10-20% _

### Can you improve the library to be 100% accurate for device identification?
#### _ I don't think it is possible now and don't think it will be possible in the future. _

### Can you improve the library to be more accurate (since you cannot make it 100% accurate)?
#### _ I can, but it takes a lot of time. I need a lot of devices, enviroments and more importantly - time.
Since this is my hobby project, I spend very little time on it. _

### How can I build a complete identification solution?
#### _ You should either use commercial services, such as https://augur.io, or develop such service yourself.
If you don't know how to do it, please use StackOverflow. _