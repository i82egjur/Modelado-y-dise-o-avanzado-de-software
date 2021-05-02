Hello, I'm Rafael egea Jurado, and I'm going to present this project  that has been made in colaboration with Jesús Izquierdo Estévez and Elena Álvarez
Sánchez from the spanish group.

pasar 

In this operation we are going through this steps: Indice:


pasar


Lets remember the system interfaces operations extracted from the use cases with their associated operations

pasar

In this slide we can see our fixxed initial architecture, which show the components of our system,  and how are they related 



pasar

from the initial architectura, we identified certain operations fdor the system operations. We have to discover the operations of the business interfaces and produce a specification.

In our system we have identified certain operations such us updateCourt, payCourt or eraseBankInfo. For modeling the interaction between the 
component objects that support certain interfaces, we are going to use the UML sequence diagrams.  

Here we show the signature of update court, that receive an integer idcourt, and the court info wich is represented with the shown data type.

The objective of this operation is to update the information of the court that we have selected through the IDCourt, with the new information that the function receives.

pasar

Here we can see the operation paycourt, wich signature shows the input parameters reservation details and account information which referes to the data types of BankAccountInformation and Reservation details.

 The purpose of this operation is to pay for a reservation, therefore the parameters to be entered are those of the reservation as well as the data of the user who has made the reservation. Once paid, the reservation is saved


pasar


The signature of this function show an input parameter which is an Integer that represent the identification number of a customer.

The objective of this operation is to delete the bank information of the user wich identifier matches with the provided one .


pasar

In order to keep the referential integrity we have created certain constraint which indicates that profile system, tenis court and reservation system always access  the same instance of the business component.

pasar

In this slide, we show the system and business interfaces with the operation signatures. I have to say that we have commited an error with the stereotypes, we have stereotyped them only as an interface, not as an interface type. 

pasar. 

Now we are going to start with the 3 stage of the component specification workkflow. 

It is impoortant to have in mind our business type model since it will be used to extract the IIMs

pasar


The first thing that we have done in order to make the IIM is extracting the core types and the business interfaces associated to them from the Busines type model. In this slide we can see this asociation with the identified operations in previous steps for each interface next to the required data types
for them

pasar

Now, we have to take a look again at the btm in order to identify and decide wich information is going to be managed by each interface.

 We have decided that the ICompanyMgt concerns itself with tennis court and reservation against the courts and ICustomerMGT, concerns itself with managing the customers

pass 

in this slide, at the left we are showing the information that manage the interface ICompanyMgt and the id of the customer that is required in certain operations.

At the right, we can see the information managed by the interface type ICustommerMgt, that as we can see is only about custommers.


Now, lets talk about snapshots, we are showing here a few of the created ones by us which are for example eraseBankInfo, pay court or updateCourt.

eraseBankInfo, lets imagine that our system only have one instance of a customer with id equal 2 with the bank information shown, after the operation, 
the customer will continuous in our system but the bankinformation will disapeard.

paycourt. Our system have a company which manages a tenniscourt that apparently does not have any reserve from the customer with id 10. After
paying for the court, the reserve will be saved in the system as we modeled,

update court. Imagine that our system has an instance of a company that manage a tennis court and throw the operation updateCourt, after that, 
the information of the court will change for instance the name goes from pista tenis to tenis pista.



Until now, we have only talk about business interfaces, but system interfaces need to be specified too.
For that reason, we have to follow a process similar to the previous one, in this slide, we can see some examples of system interfaces specification, 
such us IUpdateCourt, IPayCourt and IEraseCourt, the information that it manages and the operation that it provides, Besides, here we can appreciate a little bit of redundance in the representation since for example IEraseCourt and IUpdateCourt manages a very similar information. For that reason we have to refined it

pasar
Finally, due to the previous reason, here we can see a generalization relationship between IEraseCourt, IAddCourt, IUpdateCourt in ICourt.

pasar

This have been done too with IaddBankinfo, IEraseBankData and IUpdateCustomer.



Thank you for attention, bye.
