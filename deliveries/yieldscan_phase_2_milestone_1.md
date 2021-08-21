# Milestone Delivery :mailbox:

**The [invoice form :pencil:](https://docs.google.com/forms/d/e/1FAIpQLSfmNYaoCgrxyhzgoKQ0ynQvnNRoTmgApz9NrMp-hd8mhIiO0A/viewform) has been filled out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/Grants-Program/blob/master/docs/milestone-deliverables-guidelines.md).**  

* **Project Name:** YieldScan Phase 2
* **Application Document:** https://github.com/w3f/Grants-Program/blob/master/applications/yieldscan_phase_2.md 
* **Milestone Number:** 1
* **Link to the open-source code/delivery**
    * **Live URL:** https://yieldscan.app
    * **Repos**:
        1. [yieldscan-frontend](https://github.com/yieldscan/yieldscan-frontend)
        2. [yieldscan-backend-crawler](https://github.com/yieldscan/yieldscan-backend-crawler)
        3. [yieldscan-backend-api](https://github.com/yieldscan/yieldscan-backend-api)

> Please provide a list of all deliverables of the milestone extracted from the initial application and a link to the deliverable itself. Ideally all links inside the below table should include a commit hash, which will be used for testing. If you don't provide a commit hash, we will work off the default branch of your repository. Thus, if you plan on continuing work after delivery, we suggest you create a separate branch for either the delivery or your continuing work. 
> 
> If there is anything particular about any of the deliverables we or a future reader should know, use the respective `Notes` column.

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 0a. | License | <ul><li>[yieldscan-frontend](https://github.com/yieldscan/yieldscan-frontend/blob/master/LICENSE.md)</li><li>[yieldscan-backend-crawler](https://github.com/yieldscan/yieldscan-backend-crawler/blob/master/LICENSE.md)</li><li>[yieldscan-backend-api](https://github.com/yieldscan/yieldscan-backend-api/blob/master/LICENSE.md)</li></ul> | All repos listed here are open source under the GNU General Public License v3.0 |
| 0b. | Documentation | **TODO:** Help needed from [@sahilnanda1995](https://github.com/sahilnanda1995) |  |
| 0c. | Testing Guide | **TODO:** Help needed from [@sahilnanda1995](https://github.com/sahilnanda1995) |  |
| 0d. | Article/Tutorial | <ul><li>[YieldScan Help Center F.A.Qs](https://intercom.help/yieldscan/en/collections/3054128-f-a-qs-from-the-community)</li></ul> | <ul><li>Most tutorials on yieldscan are embedded within the platform's UX flow itself for a more cohesive end user experience. This can be seen in the "Notes" column of deliverables 1 & 2.</li><li>The few things which didn't fit the flow are documented as FAQs in our help center.</li></ul> | 
| 1. | Controller Account Support | https://yieldscan.app/ | <ul><li>Users who have already set up separate stash and controller keys can now stake in a couple of clicks through yieldscan.</li><li>New users or users who haven't setup a separate controller account for staking, now have the option to choose between "Express" and "Secure":<br><br><img width="350" alt="Staking mode prompt" src="https://user-images.githubusercontent.com/40575379/130315712-8ff73da7-8d45-49d4-9c7e-557b61e4e310.png"><br><br></li><li>"Express" mode allows users to proceed to staking with the same account as both stash and controller for quicker and simpler onboarding.</li><li>"Secure" mode guides the user step by step through the process of setting up a controller:<br><br><img width="350" alt="Secure staking steps" src="https://user-images.githubusercontent.com/10279686/129223577-376334e0-d63e-4e1c-9ec3-15bf11bbcbe4.png"><br><br></li></ul> | 
| 2. | Ledger Wallet Support | https://yieldscan.app/ | <ul><li>Ledger users are guided step by step for connecting their ledger device through the polkadot{.js} extension to yieldscan on the [wallet setup page](https://yieldscan.app/setup-wallet): <br><br> <img width="350" alt="Ledger onboarding" src="https://user-images.githubusercontent.com/40575379/130315433-ddb7d916-f1ed-4a59-a9a8-d3806cf8d0b5.png"><br><br></li><li>We added a soft patch to the transaction confirmation step, which asks ledger users to sign transactions one by one instead of batching them together:<br><br><img width="350" alt="Account source prompt" src="https://user-images.githubusercontent.com/40575379/130315567-b20707c5-4226-4594-a5b7-e4bc06509bc5.png"><br><br><img width="350" alt="Ledger signing patch" src="https://user-images.githubusercontent.com/40575379/130315578-b7bb1473-bb42-4d70-b58c-dc40379132fd.png"><br><br></li><li>**Additional info:** *We intend to remove this patch once batch transactions are completely supported on ledger devices.*</li></ul> |
| 3. | Docker| **TODO:** Help needed from [@sahilnanda1995](https://github.com/sahilnanda1995)  |
