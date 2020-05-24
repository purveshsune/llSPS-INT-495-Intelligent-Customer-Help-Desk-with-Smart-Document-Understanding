Node-RED UI link - https://node-red-vbynq.eu-gb.mybluemix.net/ui/

Link to YouTube video - https://youtu.be/m4Xlusj1OsE

Project Description:

The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems.

To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries.

Scope of Work:

1) Use Smart Document Understanding to build an enhanced Watson Discovery collection.
2) Create an IBM Cloud Functions web action that allows Watson Assistant to post queries to Watson Discovery.
3) Create a customer care dialog skill in Watson Assistant.
4) Build a web application with integration to all these services & deploy the same on IBM Cloud Platform.
