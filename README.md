This repository was created as the practical part of our official exam paper for the Blockchain Developer & Architect course @ Howest. Read our full exam paper at https://www.kareldesmet.be/assets/files/BC-project-ykman-desmet.pdf to learn more about the business logic and how to interpret and run this code.
In short, this repository represents a modified [*fabric-samples*](https://github.com/hyperledger/fabric-samples) folder, which is used in its original form as a basis for running sample applications that interact with a Hyperledger Fabric network. We found it very dangerous to limit the contents of this repository to only contain our modified example, as some examples rely on the files from other examples. Believe me, we've tried. I can't remember how many times I've installed and instantiated the chaincode, only to find out that something wasn't working and to start all over again. That's why serving this folder as a whole was a safer bet for the submission of our final paper.
## Warning
Be warned: the exam paper above is over 30 pages long and contains significant detail with regards to how you can interact with a blockchain network. However, as we have noticed, Hyperledger Fabric is a project which is in constant development and requires a significant amount of fine-tuning. The slightest version bump might render the code and/or terminal commands from our paper useless. Therefore, it is extremely important that you use Hyperledger Fabric v1.4 to run the network with which the application will interact. At the time of writing, the latest version of Hyperledger Fabric is already v2.2 so please do not use this repository, nor an outdated Hyperledger Fabric version, as a basis for anything which you might want to use in production!
