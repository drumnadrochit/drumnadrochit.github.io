# Transparent Data Encryption with Microsoft SQL Server on Windows, Linux and Azure SQL Managed Instance.

Based on a couple of recent customer engagements we decided to prepare an end2end scenario with TDE encrypted databases hosted on the different platforms Microsoft SQL Server is available. The scenario includes three TDE Certificates one created on SQL Server running on Windows, one created on SQL running on Linux as an Ubuntu Docker Container and one created in Azure SQL Managed Instance. There are three WideWorldimporters database each one hosted encrypted on these three platforms of Microsoft SQL Server.  First we will explain how to export the certificates and import them on the other platforms. In the end all platforms will have all certificates. Then we will backup the encrypted databases and will restore them on the different platforms, ending up with 3 databases on each platform.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

SQL on Linux
```
docker exec -it sql /bin/bash
```
SQL on Windows
```
docker exec -it sql /bin/bash
```
Azure SQL MI
```
docker exec -it sql /bin/bash
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
