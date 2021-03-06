# README
In this section, we will be setting up our backend services required to store the safety incidents. Our goal is to model the backend artifacts that we need and to also publish the services required to expose the backend artifacts as rest and odata.

## Step 1 - Access the TA Landing Page

(*****At this point, you should have a dedicated user for the next 5 weeks****)

**Open a New Browser Window and use the following Link...note you will need to put your USERID where the 4 XXXXs are.**

https://virtual-scp-roadshow.cfapps.eu10.hana.ondemand.com/P00XXXX


For this scenario, we will be using the new Business Application Studio so click on the "Let's Go" within the BAS Tile

![BASONLANDINGPAGE](../Images/TALandingBAS.jpg)

You should be prompted with a screen like this one where you will now create a Dev Space by clicking the "Create Dev Space" Button.
![Business APplication Studio](../Images/BASDEV.jpg)

From here, you will select the SAP Cloud Business Application Template and provide a name for your Dev Space. We would suggest you make this name unique by including your UserName in the name and append something at the end. 

### Suggest you use P00XXXX_DS for the name. 

After you specify the name and select the "SCP Cloud Business Application template", Click the button "Create Dev Space"

![Dev Sapce](../Images/BASDEVCAP.jpg)

After you hit the "Create Dev Space" button, you should get a screen that looks like this one indicating that your Dev Space is being prepared in the cloud.
![Dev space being created](../Images/DevSpaceCreate.jpg)

After 1-2 minutes, you should see the status of your creation change from started to running which means your Dev Space is now ready. In the background, the Dev Space has been prepared with all of the necessary components that you would otherwise have to install on your laptop. For example, Node JS, CDS, etc...
![Dev Space Created](../Images/DevSpaceCreated.jpg)

Once the Dev Space, says created, you will see that the Dev Space Name becomes clickable (far left of screen next to the cloud symbol). Click on the name to open it and proceed to use Business Application Studio. If you are ready to continue, click here to jump to the next exercise:

[Next Exercise](Part%201%20-%20Setting%20up%20BAS.md)
