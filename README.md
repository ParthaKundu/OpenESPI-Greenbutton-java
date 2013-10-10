OpenESPI-Greenbutton
======================

The Open Energy Services Provider Interface (ESPI) Green Button Repository Providing implementations of the interface used to share energy usage information.

## Setup

First clone the project from github:

```bash
git clone https://github.com/energyos/OpenESPI-Greenbutton-java.git
cd OpenESPI-Greenbutton-java/
git submodule update --init
```

Install the project dependencies:

```bash
export MAVEN_OPTS="-Xmx512m -XX:MaxPermSize=256m"
mvn clean install
```

Start tomcat7 using maven:

```bash
mvn tomcat7:run
```

Now the applications should be available at:
 - DataCustodian: [http://localhost:8080/DataCustodian](http://localhost:8080/DataCustodian).
 - ThirdParty: [http://localhost:8080/ThirdParty](http://localhost:8080/ThirdParty).

### Eclipse Setup

Open Eclipse and import a Maven project (File > Import... > Maven > Existing Maven Projects).

### Spring Tool Suite Setup

Open Spring Tool Suite and import a Maven project (File > Import... > Maven > Existing Maven Projects).

### IntelliJ Setup

Open IntelliJ and open the project (File > Open...).
