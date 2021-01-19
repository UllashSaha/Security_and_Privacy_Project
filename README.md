# Efficient Privacy Preserving Approach
The use of credit cards or RFID cards for transaction payment has become ubiquitous in recent years. This transactional data is stored in the form of a trajectory, including a sequence of locations at which the customer used the credit card. Such datasets are sensitive since they store customer's locations and purchasing patterns. Releasing this type of dataset without proper anonymization may breach individual's privacy. Moreover, an adversary can attack the dataset with partial trajectory knowledge to reveal sensitive information about a person. We study trajectory data anonymization techniques for this problem, where a data publisher can construct a safe dataset with minimum information loss. A global suppression algorithm was proposed in the literature for trajectory data anonymization. The algorithm is computationally expensive for large trajectory datasets. We propose a tree-based data structure that significantly reduces the computational cost of the global suppression algorithm. In an experiment with a real-world dataset, our data structure performs global suppression in 50% less time than the state- of-the-art algorithm.
## Technologies and Design  
Project is created with:
* Core Java
* Java 1.7
* Object-Oriented Design 
## Running the application locally
* Install [JDK 1.7](https://www.oracle.com/ca-en/java/technologies/javase/javase-jdk8-downloads.html)
* Run the TrajectoryMain class from your IDE.
## Publication 
[Hassan, Md Yeakub, et al. "Efficient Privacy-Preserving Approaches for Trajectory Datasets." 2020 IEEE Intl Conf on Dependable, Autonomic and Secure Computing, Intl Conf on Pervasive Intelligence and Computing, Intl Conf on Cloud and Big Data Computing, Intl Conf on Cyber Science and Technology Congress (DASC/PiCom/CBDCom/CyberSciTech). IEEE, 2020.](https://ieeexplore.ieee.org/abstract/document/9251201)
