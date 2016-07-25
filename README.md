# sg-example-002-glob-pipeline

How to set up Globalization Pipeline service on Bluemix
(General Availability version)

# 1
Login to your account on https://console.ng.bluemix.net/ then go to your Bluemix Dashboard, then click *Catalog* tab.

![01](./assets/images/01.png)
# 2
Create *Language Translation* service under *Watson* catalog

![02](./assets/images/02.png)
# 3
Check the *Space* is correct and *CREATE*.

In a minute, the *Language Translation* service is created and its home page is shown.  Go ahead and click *DASHBORD* tab and go back to your dashboard page.

![03](./assets/images/03.png)
# 4
Confirm the *Language Translation* service tile has been created in your space.

![04](./assets/images/04.png)
# 5
Go to *CATALOG* again and scroll down to *DevOps* catalog.

Click the *Globalization Pipeline* service.  Note that *BETA* service might still exist, but it’ll be decommissioned shortly.  Please make sure to use the GA version.

![05](./assets/images/05.png)
# 6
On the *Globalizaiton Pipeline* dashboard, the default setting should be good.  Please confirm that the *Space* is correct and *App: Leave unbound* is set, then *CREATE*.

In 20 seconds – 1 min., the *Globalization Pipeline* dashboard will open.


![06](./assets/images/06.png)
# 7
On the *Globalization Pipeline* dashboard, click *Machine Translation Configuration* tab.

![07](./assets/images/07.png)
# 8
Under *Add Watson Language Translation Machine engine* pull-down list, select the *Translation* service you created in the step 3 and 4.  Make sure the *instance name* matches with the *Service name* you set in the step 3.

*Enable* it.

![08](./assets/images/08.png)
# 9
*Confirm*.

![09](./assets/images/09.png)
# 10
Go to *API Users* page.  There is one default Admin user. Click *New API User* button to create a new user with *Administrator* type.

![10](./assets/images/10.png)
# 11
Set *Display name* and *Administrator* type, then, *SAVE*.

![11](./assets/images/11.png)
# 12
Click the eye icon to open the user’s configuration page.

![12](./assets/images/12.png)
# 13
On the user configuration page, open the left command column by clicking the upper arrow.

![13](./assets/images/13.png)
# 14
Click *Service Credentials* command in the left command column.

![14](./assets/images/14.png)
# 15
Copy the credential JSON object notation and save it.  You can paste it directly to **strong-globalize/lib/local-credentials.json**.

![15](./assets/images/15.png)
