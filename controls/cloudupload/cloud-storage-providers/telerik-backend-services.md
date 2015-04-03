---
title: Telerik Backend Services
page_title: Telerik Backend Services | UI for ASP.NET AJAX Documentation
description: Telerik Backend Services
slug: cloudupload/cloud-storage-providers/telerik-backend-services
tags: telerik,backend,services
published: True
position: 2
---

# Telerik Backend Services



[ Telerik Backend Services (formerly Everlive) ](http://www.telerik.com/backend-services) connects your applications to backend cloud storages of Telerik's Cloud Services Platform. Integration with __RadCloudUpload__ is easy and requires only an __API Key__.

## Adding References

In order to be able to use the Telerik Backend Services Cloud Storage Provider, you would need the download the __dll files__ from [ here ](https://www.everlive.com/Files/SDK/Windows/EverliveSDK.Windows.Net35.zip).

>note Telerik Backend Services requires reference to __Telerik.Everlive.Sdk.dll__ and __Newtonsoft.Json.dll__ .
>When Web Application is used the Copy Local property in the Reference Properties dialog box, available from the References pane of the Project Designer must be set to __True__ .
>


## Configuration



1. From the __RadCloudUpload__'s smart tag choose Everlive as provider and open the Configuration Wizard: ![cloudupload-everlive](images/cloudupload-everlive.png)

1. In the Configuration Wizard dialog enter Everlive __API Key__. ![cloudupload-everlive-configuration](images/cloudupload-everlive-configuration.png)Specifying the __Uncommitted Files Expiration Period__(TimeSpan Structure), you could easily configure the time, after which the unprocessed files will be removed from the storage.This will add configuration setting in the __web.config__ file:

````XML
	            <telerik.web.ui>
	                <radCloudUpload>
	                    <storageProviders>
	                        <add name="Everlive" type="Telerik.Web.UI.EverliveProvider" AppKey="" uncommitedFilesExpirationPeriod="2"/>
	                    </storageProviders>
	                </radCloudUpload>
	            </telerik.web.ui>
````



>note Telerik Backend Services doesn't support uploading in chunks - files are uploaded at once. In case you want to upload files, larger than 4MB refer to this[article]({%slug cloudupload/application-scenarios/uploading-large-files%}).
>


# See Also

 * [Custom Storage Providers]({%slug cloudupload/custom-cloud-storage-providers/overview%})

 * [Custom Telerik Backend Services Provider]({%slug cloudupload/custom-cloud-storage-providers/custom-telerik-backend-services-provider-%})

 * [Troubleshooting]({%slug cloudupload/troubleshooting%})