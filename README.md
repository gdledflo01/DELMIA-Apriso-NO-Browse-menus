# DELMIA-Apriso-NO-Browse-menus
<img width="591" alt="image" src="https://github.com/user-attachments/assets/b10a022f-43c1-4f16-baff-b8ca29a0f5ef">


System administrator may configure Role-based access to the Find a screen functionality. To do so, add the AllowQuickSearchFlexpartRole key in the <FlexNet.SystemServices.Security> section of the Central Configuration, and provide the Role that is authorised to access the functionality as value of the key, as seen in the example below:

<FlexNet.SystemServices.Security>
<add key="AllowQuickSearchFlexpartRole" value="Portal Administrator" />
</FlexNet.SystemServices.Security>



Refresh cache – gets the latest list of FlexParts from the server (use this option if any recently-added FlexParts are not visible)

Restricting Access to Personalization Settings
Follow these steps to restrict the access to personalization settings in DELMIA Apriso Desktop Client:

Add the PersonalizationSupervisorRole key in the <FlexNet.SystemServices.Security> section of the Central Configuration file.
Specify the name of the Role required to access the personalization settings as the value of the PersonalizationSupervisorRole key.
Restart DELMIA Apriso Services.

<img width="615" alt="image" src="https://github.com/user-attachments/assets/9a72ada0-195e-4f5f-9773-522263dfb55e">
