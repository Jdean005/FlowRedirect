# FlowRedirect
Aura Component to surface redirects. (Custom redirect in Screenflows)

To use this component simply create a screenflow and add a final screen component that you will use to host this redirect component. 

On your final screen, search for the element called "FlowRedirect", drag and drop that component on the screen, add your API name {note: this can be any value that is acceptable for API names and has no impact on the functionality of this redirect}, then enter your reference to the record ID of which you wish to navigate. This can be a hardcoded Salesforce record ID, or a variable that contains your record ID such as the create record variable from a record created in your flow! 

![image](https://user-images.githubusercontent.com/58155079/147129409-e926505c-facc-46cf-a5f9-2ef94f2f0111.png)
