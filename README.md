# Uberkiller
Our uberkiller system is based on handshake between backend and frontend to parse data and modifY the items in DynamoDB. 

In order to run the code, you need to install some dependency package in the folder. We use npm command to install express, socket.io, elasticbeanstalk, awssdk. Simply run node .js to open a local host window. 

First, you could login as a passenger and search for the realtime driver around you. Once you cofirm the request. You could see it in your request in your waiting list waiting for the driver to confirm your trip. The driver could login his account and see someone in the waiting list waiting for the driver's confirmation. Go to the making confirmation page and click the passenger you may want to give a ride for. Therefore, in the driver and passenger's confirmed page. There would be a list indicating that you two have made a deal. 

Besides of the realtime pooling. Riders and passengers could also post their future plan so that others could probably search for the satisfied post. 

Use npm init to generate package.json and tar all the file into one package then upload zipfile to elasticbeanstalk in aws before which you have already built up a nodejs environment.