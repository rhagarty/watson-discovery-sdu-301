# watson-discovery-sdu-301

* Create "what you will learn" video


# 1. Watson Discovery service creation

Use this video? https://mediacenter.ibm.com/media/Watson+Discovery+Service+Overview+Demo/1_namrnv94  (old tooling from 5/18)

## Talking points

Combines:

* Document conversion
* Retrieve & Rank
* Natural Language Understanding

# 2. Basic UI to access Watson News

* https://github.com/IBM/watson-discovery-news

Notes:

* Uses default Watson News
* Node app using React/Express with `watson-react-components`
* Testing with Jest
* Uses Yarn

# 3. UI to access user data and WKS

* https://github.com/IBM/watson-discovery-food-reviews

Notes:

* Uses WKS to create a custom annotator
* Deploy WKS model to Discovery
* Load and enrich data into Discovery
* Node app using React/Express with Semantic UI
* Testing with Jest
* Uses NPM

# 4. How to apply SDU to a document (owner's manual)

Notes:

* Use `ecobee` thermostat owner's manual
* Create video and screenshots

# 5. How to create UI to access the SDU data

Notes:

* Standard search dialog, showing enrichments and allowing search query
* Create video and screenshots

# 6. How to create chabot to access the SDU data using Assistant w/ Webhooks and Search Skill

Notes:

* Webhooks is beta, but will be offered in lite plan
* Create Cloud Functions Action
* Chatbot interface
* Uses provided "Customer Care Dialog Skill"
* Use Assistant V2 API
* Adds dialog node to handle users question about using the thermostat
* Create Webhook to call CF Action
* Create Assistant object from Dialog Skill
* Sends request to Discovery
* Create video and screenshots

# 7. How to create chabot to access the SDU data using Search Skill

Notes:

* Search Skill is beta, and only available with paid plan
* Chatbot interface
* Uses provided "Customer Care Dialog Skill"
* Use Assistant V2 API
* Adds dialog node to handle users question about using the thermostat
* Create Search Skill and combine with Dialog Skill into Assistant object
* Sends request to Discovery
* Create video and screenshots
