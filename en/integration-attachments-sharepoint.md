# Send Attachments to SharePoint

trustkey supports the sending of an action packs attachments directly to a SharePoint Document Library (Office 365)

This is a 2 part process consisiting of

1. Microsoft Power Automate receving attachments from trustkey and storing to your document library
2. Creating of a template with both a File Attachment component and the SharePoint component


Send of the attachments is manually initated on the action pack. You can initiate the sending of attachments multiple times, if required.


To send documents to your SharePoint document library you must first create a Microsoft Power Automate template which specifies the document library to store the attachments.  The template can be found on the Microsoft Power Automate library or by contacting trustkey support.

To use the upload feature perform the following

1. Create the Microsoft Power Automate Template
2. Make a note of the HTTP URL from that template  (we need that in a moment)
3. In trustkey navigate to **Builder**
4. Create a new template
5. Add a **File Attachment** component
6. Select the **SharePoint** component
7. Enter a title and description as you desire
8. Paste in the Power Automate HTTP URL which you have taken from the Power Automate Template
9. Enter the document library.  This is optional but provides a good point of reference
10. Enter an optional folder to store your documents  (if the folder does not exist it will be created)


You are now ready to use the template as an Action Pack.

All attachments will be sent to your SharePoint Document Library.  This is manually initated on the Action Pack. We recommend always putting the SharePoint component at the end of the template as the last action to be done before the Action Pack is completed.

