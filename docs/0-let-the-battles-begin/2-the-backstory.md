## 🐈 A Little Bit Backstory

_Bla Bla_ Inc. is an entertaiment company that creates games to make people happy! With xx number of people...

A couple of developers from the company created this fun app for their friends and families: PetBattle. They hacked around so that the authors can `Cat versus Cat` battle each other in a simple online form. A _My cat is better than your cat_ type of thing. There were very few bells and whistles to the initial architecture — there was a simple web-based user interface and an API layer coupled with a NoSQL database.

<img src="0-let-the-battles-begin/images/petbattle-initial-architecture.png" width="500">

One day, they realized that their app becomes a big hit! Nearly overnight, there was a drastically increased number of players, the PetBattle server crashes, and malicious pictures of not cats start appearing on the child-friendly application. 

The company had decided to own the app and develop a business around it. Developers of the app had started an exciting journey embracing [DevOps Culture and Practices](https://www.redhat.com/en/services/training/do500-devops-culture-and-practice-enablement). After a couple of months, they turned this simple hobbist application into a good business. 

<img src="0-let-the-battles-begin/images/pet-battle-architecture.png" width="700">

The app is now more secure and resilient now!

![pet-battle](images/petbattle-ui.png)

_For more detailed journey: https://www.redhat.com/en/engage/devops-culture-practice-openshift-ebooks_
## All the cool kids are playing Pet Battle!
Buuuut since PetBattle became super hype, the development team started having hard times to keep up with the feature requests or bugs reports while maintaining the app on production. Incidents started to occur due to unexpected high load, lack of high availability or scalability. They needed to figure out things like security, scalability, operability, reliability to match with their external and internal end users needs!
