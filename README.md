# frapi

Frynd API

| Key | Value |
| --- | ---: |
| Version | 0.0.1 |
| Language | Java |
| Framework | Spring Boot |
| Database | MongoDB |
| Deployment | Azure |

## Get Started

Install Java 8 JDK if you haven't already:

- Mac: `$ brew tap caskroom/versions && brew update && brew cask install java8`
  - If you don't already have Homebrew: `$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Install Maven if you haven't already:

- Mac: `$ brew install maven`

Install MongoDB if you haven't already:

- Mac: `$ brew install mongodb`

### Build

Build the JAR file: `$ mvn clean package`

### Run Locally

Run `frapi-core` locally: `$ mvn spring-boot:run`

## Deployment

### Development Ecosystem (*Azure App Service*)

**NOT FINISHED**

Deploy to Azure App Service: `$ mvn azure-webapp:deploy`
