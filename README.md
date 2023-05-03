# Advanced-Approval-for-Selected-SharePoint-Item

You can download the solution (unmanaged), import it to your environment, and start building on the top of preconfigured flow.

## The solution contains the following components:
- Flow:

**Advanced Approval for Selected SharePoint Item** - The main flow with approval process

- Connection referencies:

**Approvals** - connection reference for approval actions

**Microsoft Teams** - connection reference for Teams actions (i.e. publish a card)

**Office 365 Outlook** - connection reference for Outlook (i.e. for send email in case of errors)

**Office 365 Users** - connection reference for Office 365 Users to get email of the user triggered the flow

**SharePoint** - connection reference for SharePoint (trigger and some actions like get item data and update item)

- Environment Variables:

**SharePoint site** - store URL of your SharePoint site

**SharePoint list** - store the name of your SharePoint list where the flow should work


*Please keep in mind that you should import this solution to the Default environment to be able to launch the flow for selected item in the SharePoint list*