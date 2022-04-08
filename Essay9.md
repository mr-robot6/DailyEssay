say-

Day 12


Today there was no session, so it was just me completing the figma layout. I started working on the seller app. I had to encapsulate data like inventory addition and editing, and also take care of food items like cakes and pastries which can only be delivered in the radius surrounding the seller, while items like accessories and plants can be delivered across. This is solved by using the check pin code availability added to the product list in the consumer app. I also have to add a shipment tracker and map to the consumer app. Further, I learned about MVVM, which is Model- view-view model. MVVM is a design pattern architecture, Model: It represents the data and the business logic of the Android Application. It consists of the business logic - local and remote data source, model classes, repository. View: It consists of the UI Code(Activity, Fragment), XML. It sends the user action to the ViewModel but does not get the response back directly. To get the response, it has to subscribe to the observables which ViewModel exposes to it. ViewModel: It is a bridge between the View and Model(business logic). It does not have any clue which View has to use it as it does not have a direct reference to the View. So basically, the ViewModel should not be aware of the view who is interacting with. It interacts with the Model and exposes the observable that can be observed by the View.

MVVM architecture is a Model-View-ViewModel architecture that removes the tight coupling between each component. Most importantly, in this architecture, the children don't have the direct reference to the parent, they only have the reference by observables. The MVVM pattern provides the distribution of data and UI which gives benefits such as flexibility and reusability of the code as well as data.

I'm writing a report on MVVM, so this is what I understood till now. My mentor is using this architecture for their application so I think I could also inculcate this method into mine too. 

After that there was a presentation about Networking and hardware by Arun, where he explained how networking works and what are the different types of networking used and how they work. The 4 types of networking are 

1.LAN(Local Area Network)

2.PAN(Personal Area Network)

3.MAN(Metropolitan Area Network)

4.WAN(Wide Area Network)

Briefly explaining these, Local Area Network is a group of computers connected to each other in a small area such as a building, office. Personal Area Network is a network arranged within an individual person, typically within a range of 10 metres. Personal Area Network is used for connecting the computer devices of personal use is known as Personal Area Network.

A metropolitan area network is a network that covers a larger geographic area by interconnecting a different LAN to form a larger network.


