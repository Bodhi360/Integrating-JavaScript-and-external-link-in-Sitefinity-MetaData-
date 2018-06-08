# Integrating-JavaScript-and-external-link-in-Sitefinity-MetaData-
                               Integrating JavaScript and external link in Sitefinity (MetaData)
Here we are using metadata.ascx file in sitefinity . It is using to connect the external file in sitefinity like JavaScript, CSS link Google Script.
Create metadata.ascx file in App_Master Folder.
Use the Following Code in metadata file Heading:<br/>
<%@ Control Language="C#" %>
<img src="https://github.com/Bodhi360/Integrating-JavaScript-and-external-link-in-Sitefinity-MetaData-/blob/master/Picture1.png">
After using the heading code we use the script and link in metadata.
Next we also use following code in .master file to link metadata link
Use it on the top
<%@ Master Language="C#" %><br/>
<%@ Register Src="~/App_Data/Sitefinity/WebsiteTemplates/grill/App_Master/MetaData.ascx" TagPrefix="uc" TagName="MetaData" %><br/>
<%@ Register Assembly="Telerik.Sitefinity" Namespace="Telerik.Sitefinity.Web.UI" TagPrefix="sf" %><br/>
<%@ Register Assembly="Telerik.Sitefinity" Namespace="Telerik.Sitefinity.Web.UI.PublicControls" TagPrefix="sf" %><br/>
Use it in head tag
<head id="Head1" runat="server"><br/>
            <meta charset="utf-8"/><br/>
    <uc:MetaData runat="server" ID="MasterMetaData" /><br/>
        <title>Grill Responsive Web Template</title><br/>
        <meta name="description" content=""/><br/>
        <meta name="viewport" content="width=device-width"/>
        
        <link href='http://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800' rel='stylesheet' type='text/css'/>

<img src="https://github.com/Bodhi360/Integrating-JavaScript-and-external-link-in-Sitefinity-MetaData-/blob/master/Picture2.png">        

<a href="http://www.bodhi360.cloud/">Bodhi360</a>                Atul kumar              
