# watson-discovery-sdu-301

# What we will cover

## Watson Discovery service creation

https://mediacenter.ibm.com/media/Watson+Discovery+Service+Overview+Demo/1_namrnv94  (old tooling from 5/18)

### Talking points

Combines:

* Document conversion
* Retrieve & Rank
* Natural Language Understanding

## Basic UI to access Watson News

* https://github.com/IBM/watson-discovery-news

Notes:

* Uses default Watson News
* Node app using React/Express with `watson-react-components`
* Testing with Jest
* Uses Yarn

## UI to access user data and WKS

* https://github.com/IBM/watson-discovery-food-reviews

Notes:

* Uses WKS to create a custom annotator
* Deploy WKS model to Discovery
* Load and enrich data into Discovery
* Node app using React/Express with Semantic UI
* Testing with Jest
* Uses NPM

## How to apply SDU to a document (owner's manual)

Notes:

* Use `ecobee` thermostat owner's manual

## How to create UI to access the SDU data

Notes:

* Standard search dialog, showing enrichments and allowing search query

## How to create chabot to access the SDU data using Assistant w/ Cloud Functions, Webhooks and Search Skill

Notes:

* Chatbot interface
* Uses provided "Customer Care Dialog Skill"
* Adds dialog node to handle users question about using the thermostat
* Sends request to Discovery
