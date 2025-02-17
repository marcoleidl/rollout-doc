---
slug: /posdealers/getting-started/operator-onboarding/invitation-process
title: Invitation process
---
# Invitation process

:::info summary
After reading this, you can invite a single PosOperator and perform a bulk invitation for several PosOperators.
:::

## Introduction

As described in the section [business model](../../overview/business-model.md) _"we are happy to support you (as a PosCreator) in the development of POS-Systems"..."For PosDealers, we offer the fiskaltrust.Portal, which can be used free of charge, as a platform on which the POS-Systems of the PosCreators can be accessed. You as a PosDealer can purchase additional products and product packages in the store of the fiskaltrust.Portal. If your PosOperators are invited to use the fiskaltrust.Portal, the fiskaltrust.products can be transferred to these accounts."_
So you, as a PosDealer, get an invitation by a PosCreator to the fiskaltrust.Portal and your PosOperators get their invitation from you. The invitation of a single PosOperator is possible, for example, for testing in the sandbox or for a new contact. A bulk invitation is your option when you want to invite several PosOperators.

Please note that you cannot delete an E-Mail address entirely in the fiskaltrust.Portal. Therefore, you cannot transfer a formerly used E-Mail address to any other account. So we strictly recommend testing in the sandbox to avoid trouble with E-Mail addresses in the productive system. 

## Preparation of Invitations

You, as a PosDealer, can do the invitation of a PosOperator only; neither PosCreator nor consultant can invite PosOperators.
Both parties can additionally activate the role of a PosDealer. Thus they extend the respective options in the FTP. In case of doubt, please refer to [Company Roles](../company-roles.md)

There are two ways to add and assign PosOperators to your account as a PosDealer:

| Steps | Description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](../../images/numbers/circle-1o.png) |Choose `PosOperator` / `Overview`.  |
|![Number 2](../../images/numbers/circle-2o.png) |A list of the already assigned PosOperators is shown.  |
|![Number 3](../../images/numbers/circle-3o.png) |With `PosOperator` / `Invitation` you will find options to add PosOperators.   |
|![Number 4](../../images/numbers/circle-4o.png) |To add a single PosOperator, perform the preparations as described in this chapter and then switch to  [_Invitation of a single PosOperator_](#invitation-of-a-single-posoperator).  |
|![Number 5](images/Numbers/circle-5o.png) |For adding several PosOperators, perform the preparations as described in this chapter and change then to [_Invitation of PosOperators_](#bulk-invitation-of-posoperators).  |
|![Number 6](images/Numbers/circle-6o.png) |Checking or changing the settings for the invitations is **inevitable for both ways**. Therefore, regardless of the further way, prepare the settings first.  To do this, select `PosOperator` / `Invitation`.    |
|![Number 7](images/Numbers/circle-7o.png) |Control or change the settings for the invitation.  |

![invitation process preparation](images/11-onboarding-portal.png "https://portal-sandbox.fiskaltrust.TLD/PosOperator/PosOperators")  


| options | description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](../../images/numbers/circle-1o.png)| `PDF-Attachment`: Avoid confusing your PosOperators when they receive an E-Mail invitation from an expectable unknown source like sandbox@fiskaltrust.TLD or robot@fiskaltrust.TLD. Explain in an accompanying letter that you, as PosDealer, are extending your offers and invite your PosOperators to register with the fiskaltrust.Portal via the confirmation link. With `Choose file...`and `Import`, you add your document as an attachment to the invitation.  |
|![Number 2](../../images/numbers/circle-2o.png)| `additional information`:  You extend the automated E-Mail invitation to your PosOperator with your text ([see preview](invitation-process.md#preview-of-the-E-Mail-invitation)). Use this text block of up to 400 characters to inform your PosOperators personally. Explain that you as a PosDealer extend your offers and invite your PosOperators to register with the fiskaltrust.Portal via the confirmation link. Your additional information will help reduce any mistrust when their POs receive messages from an unknown source, such as sandbox@fiskaltrust.topleveldomain or robot@fiskaltrust.TLD. |
|![Number 3](../../images/numbers/circle-3o.png)| `Surrogate rights`:  Set the rights you should have as PosDealer after switching to the PosOperator's account to `FULL`. Otherwise, you would have access to the PosOperator's account, but you would not be able to conclude contracts on his behalf. But these are necessary for cooperation with third parties.  |

## Invitation of a single PosOperator

### Overview individual invitation

![invitation process individual](images/1-onboarding-individual-relaunch.png "https://portal-sandbox.fiskaltrust.TLD/PosOperator/PosOperators")  

### Explanation of individual invitation

The single invitation is particularly interesting for the on-site support you as a PosDealer give if a PosOperator wants to use the fiskaltrust.Services immediately - in connection with the commissioning of a POS-System. Further, you may want to learn about and test the portal and its processes in the sandbox. Hence, the invitation of a single PosOperator is also helpful here.  
Under country-specific circumstances, when a PosOperator is first registered, the other master data can be retrieved from the relevant authority and checked by entering a tax number.

### Work steps individual invitation


| Steps | Description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](images/Numbers/circle-1o.png) |Choose `PosOperator` / `Invitation`.  |
|![Number 2](images/Numbers/circle-2o.png) |Check the settings previously described [_here_](#preparation-of-invitations).  |
|![Number 3](images/Numbers/circle-3o.png) |Choose `Add`.  |
|![Number 4](images/Numbers/circle-4o.png) |The following fields are mandatory fields. They must be filled in to guarantee that the PosOperator can be found correctly in the fiskaltrust.Portal via his E-Mail address and can be assigned: <ul><li>Company data - Company name</li><li>E-Mail address</li><li>Address line 1</li><li>Postal code</li><li>City</li><li>Country</li><li>User data - First name</li><li>Last name</li><li>Contact E-Mail address</li></ul>  |
|![Number 5](images/Numbers/circle-5o.png) |The commercial identification is no mandatory field for the invitation. But for the correct management of the cash register systems, these data (AccountIdVat, ~IdGln, ~UStIdNr) and their validation are **essential**.|
|![Number 6](images/Numbers/circle-6o.png) |Save your values with `Save` |
|![Number 7](images/Numbers/circle-7o.png) |Choose `Assign all PosOperators`|
|![Number 8](images/Numbers/circle-8o.png) |If the invitation should not reach the PosOperator or get lost, please read the chapter [_Managing the invitations_](#managing-the-invitations)

### Preview of the E-Mail invitation 


import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import PreviewAT from '../../_markets/at/getting-started/operator-onboarding/invitation-process/_preview-email.mdx';
import PreviewFR from '../../_markets/fr/getting-started/operator-onboarding/invitation-process/_preview-email.mdx';
import PreviewDE from '../../_markets/de/getting-started/operator-onboarding/invitation-process/_preview-email.mdx';

<Tabs groupId="market">

  <TabItem value="AT" label="Austria">
    <PreviewAT />
  </TabItem>

  <TabItem value="FR" label="France">
    <PreviewFR />
  </TabItem>

  <TabItem value="DE" label="Germany">
    <PreviewDE />
  </TabItem>

</Tabs>


## Bulk invitation of PosOperators

### Overview bulk process

![Invitation of PosOperators in a bulk process](images/2-onboarding-bulk-relaunch.png "Invitation of PosOperators in a bulk process")  

### Explanation of bulk process

Inviting PosOperators to a PosDealer account with an import file is especially interesting if you want to invite many business partners. Since the invitations are created and sent automatically via the fiskaltrust.Portal, the information of your business partners is relevant. Therefore, please note the section on preparation to avoid irritation, loss of time or effort due to invitations mistakenly treated as SPAM. We described the necessary structure of the CSV file using an example. You can obtain this example in the fiskaltrust.Portal. 

### Work steps bulk process

![invitation via csv file](images/6-onboarding-portal.png "https://portal-sandbox.fiskaltrust.TLD/PosOperator/PosOperators invitation via csv file")  


| Steps | Description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](../../images/numbers/circle-1o.png) |Choose the fiskaltrust.Portal and `PosOperator` / `Invitation`|
|![Number 2](../../images/numbers/circle-2o.png) |Check the configurations of the invitations as previously described [_here_](#preparation-of-invitations) |
|![Number 3](../../images/numbers/circle-3o.png) |Use `Download demo CSV file`.  |
|![Number 4](../../images/numbers/circle-4o.png) |Open the the demo CSV file.  |
|![Number 5](../../images/numbers/circle-5o.png) |See the explanations [_below_](#fields-of-the-csv-file), add the requested data of the PosOperators and save the date as a CSV file.  |
|![Number 6](../../images/numbers/circle-6o.png) |Change  again to the fiskaltrust.Portal and choose `PosOperator` / `Invitation`.|
|![Number 7](../../images/numbers/circle-7o.png) |In the section named `PosOperators that should be invited` use `Choose file...` to set your CSV file.  |
|![Number 8](../../images/numbers/circle-8o.png) |With `Import` the data are uploaded and analyzed to avoid duplicate or incomplete records. You can control or add data to each record.  |
|![Number 9](../../images/numbers/circle-9o.png) |Choose `Assign all PosOperators` to send the invitation-E-Mail to each business partner in your CSV file.  For a preview to the sent E-Mails refer [here](invitation-process.md#preview-of-the-E-Mail-invitation)  |
 
### Fields of the CSV file

import FieldsAT from '../../_markets/at/getting-started/operator-onboarding/invitation-process/_fields-details.mdx';
import FieldsFR from '../../_markets/fr/getting-started/operator-onboarding/invitation-process/_fields-details.mdx';
import FieldsDE from '../../_markets/de/getting-started/operator-onboarding/invitation-process/_fields-details.mdx';

<Tabs groupId="market">

  <TabItem value="AT" label="Austria">
    <FieldsAT />
  </TabItem>

  <TabItem value="FR" label="France">
    <FieldsFR />
  </TabItem>

  <TabItem value="DE" label="Germany">
    <FieldsDE />
  </TabItem>

</Tabs>

### Handling error messages

![Import errors ](images/7-onboarding-portal.png "https://portal-sandbox.fiskaltrust.TLD/PosOperator/PosOperators/import errors")

* You must fill out all of the mandatory fields of the ~.csv-file; otherwise, error messages will show a note for the wrong or missing data.
* Please note the error messages and add the necessary data in the respective lines of the CSV file 

| messages | description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](../../images/numbers/circle-1o.png) |Email-address is required! |
|![Number 2](../../images/numbers/circle-2o.png) |Address line 1 is required! |
|![Number 3](../../images/numbers/circle-3o.png) |ZIP-code is required!  |
|![Number 4](../../images/numbers/circle-4o.png) |City is required!  |
|![Number 5](../../images/numbers/circle-5o.png) |Country is required!  |

## Managing the invitations

### Explanation 

If you have all preparations done, the invitation process should work automatized. However, if problems arise, you can fix most of them yourself. For example, look at the protocol of invitations, if a PosOperator claims that there was no E-Mail invitation for him.  
There are several ways to help.

### Troubleshooting 

#### status or error messages 

![8-onboarding](images/8-onboarding-portal.png "https://portal-sandbox.fiskaltrust.TLD/PosOperator/PosOperators")

| Steps | Description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](../../images/numbers/circle-1o.png) |Check the status of the invitation. You recognize an unsent E-Mail invitation by a red symbol.|
|![Number 2](../../images/numbers/circle-2o.png) |Use `Assign` to send / resend this single E-Mail invitation or `Assign all PosOperators` to send all.|
|![Number 3](../../images/numbers/circle-3o.png) |If you can not assign an E-Mail invitation to the PosDealers account, use `Edit`. This opens a screen to edit the data of the PosOperator if they are not correct or complete.|
|![Number 4](../../images/numbers/circle-4o.png) |Use `Delete` to remove the data of a not yet assigned PosOperator.|
|  |If `This E-Mail address already exists` appears, see [Onboarding of existing PosOperators](./invitation-process.md#onboarding-of-existing-posoperators) .|

### Assigning PosOperators in a bulk process

![9-onboarding](images/9-onboarding-portal.png "https://portal-sandbox.fiskaltrust.TLD/PosOperator/PosOperators")

| Steps | Description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](../../images/numbers/circle-1o.png) |By clicking on `Assign all PosOperator users` the E-Mail invitation can be sent to **all**  PosOperators who have not yet been invited.  |
|![Number 2](../../images/numbers/circle-2o.png) |`+Add` is used for a manual invitation, see chapter [_Invitation of a single PosOperator_](#invitation-of-a-single-posoperator). |
|![Number 3](../../images/numbers/circle-3o.png) |Choose `History` for control or also repair of E-Mail invitations.|

### Onboarding of existing PosOperators 

![15-onboarding](images/15-onboarding-already-existing-PosOperators.png "https://portal-sandbox.fiskaltrust.TLD/PosOperator")

| Steps | Description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](../../images/numbers/circle-1o.png) |By clicking on `Assign all PosOperator users` (`PosOperators`/ `Invitation`) the E-Mail invitation can be sent to **all**  PosOperators who have not yet been invited. If you get the message `This E-Mail address already exists`, another PosDealer has onboarded the PosOperator.|
|![Number 2](../../images/numbers/circle-2o.png) |**Do not, under any circumstances, invite this PosOperator again using a different e-mail address.** This will cause problems verifying business identifications used to authenticate tax authorities or third-party services.|
|![Number 3](../../images/numbers/circle-3o.png) |Inform the PosOperator to add your account as new or further PosDealer.|
|![Number 4](../../images/numbers/circle-4o.png) |PosOperators open the fiskaltrust.Portal and choose `PosOperator` / `Search PosDealer/Consultant`.|
|![Number 5](../../images/numbers/circle-5o.png) |PosOperators enter search terms like the name or E-Mail address of your account as a PosDealer.|
|![Number 6](../../images/numbers/circle-6o.png) |After checking name, E-Mail address and access rights, they choose `Request assignment PosDealer`.|
|![Number 7](../../images/numbers/circle-7o.png) |You as a PosDealer have to choose `PosOperator` / `Overview`, search the new PosOperator and tick `Accept`. The result is an active link, which you can use for surrogating.|

### Options with invited PosOperators

![10-onboarding](images/10-onboarding-portal.png "https://portal-sandbox.fiskaltrust.TLD/PosOperator/PosOperators")

After choosing `PosOperator` / `Invitation`
 / `History` the Protocol for assignments of PosOperators offers you several features:

| options | description                                                                                                                |
|:----------------------:|-------------------------------------------------------------------------------------------------------------------------------------|
|![Number 1](../../images/numbers/circle-1o.png) |The start date of the log overview can be restricted using this field.    |
|![Number 2](../../images/numbers/circle-2o.png) |The last date of the log overview can be restricted using this field. Start the search with `Invoke protocol`. You will see the whole protocol if you do not use any filter. Entering a text filter at the `Search table` reduces the overview. You will get the complete overview data by deleting all entered data in the search field.   |
|![Number 3](../../images/numbers/circle-3o.png) |Check the details of the data of a PosOperator.    |
|![Number 4](../../images/numbers/circle-4o.png) |Resend the E-Mail invitation for this data record.    |
|![Number 5](../../images/numbers/circle-5o.png) |Delete the data record. Please note that you cannot delete an E-Mail address entirely in the fiskaltrust.Portal. Therefore, you cannot transfer a formerly used E-Mail address to any other account.   |
|![Number 6](../../images/numbers/circle-6o.png) |Shows a window with the direct link for the invitation. You can copy that link and send it to your PosOperator by direct message.      |

Return to the Invitation module with [Overview of PosOperator].
