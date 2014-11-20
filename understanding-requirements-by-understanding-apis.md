In the world of software development, desired tasks or features can appear quite simple yet in reality require very complex sharing of information between different systems and databases.  A useful way we learned to distill the technical requirements for a desired feature, was to consider the feature in terms of the chunks of information needed to complete the feature.  Understanding the underlying smaller bits of information required allows for a better understanding of the complexity of the feature as well as prioritizing which features to develop first.  For example, Uber is a brilliantly simple application built to provide a one-button interface to summon personal transportation.  Press button.  Car shows up.  Simple.  However, when understanding this feature in terms of application programming interface requirements (APIs), the feature reveals its true complexity.  Some of the requirements of information required from the user's mobile device include:
* verification of user's identity
* physical location of user
* desired location of pickup
* user's desired destination
* user's rating by other drivers
* user's phone number
* payment information
* confirmation of pickup
* confirmation of drop-off
* confirmation of payment sent
* rating of driver
    
Additionally, information that must be sent to the user’s device upon opening the application includes:
* physical location of available driver
* physical location of driver accepting user’s request
* description of pickup vehicle including driver name, vehicle make and       model, and license plate number
* driver’s rating from previous customers

Understanding the API requirements for a feature like Uber’s request a ride button, helps clarify the technological challenges involved.  Knowing this is incredibly helpful from a management perspective in understanding the risks and timelines associated with developing features for applications. 

![CHUNK](http://i.huffpost.com/gen/573105/thumbs/o-GOONIES-570.jpg?4)
