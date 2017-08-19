# jersey-rest-responseBuilder
A simple Jersey REST Service explaining on how to use Response Builders

This Project explains how to use Response Object efficiently to return a reponse from the service 
and how we can sent a Status code and location headers along with the response object.

Response.status(Status.<CREATED>).entity(<RETURN_OBJECT>).build();
