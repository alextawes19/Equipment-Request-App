# Equipment Request App
An application which allows users to request new equipment and devices. Made for Rogers Electric while I was the IT intern. Implemented software engineering approaches and strategies. Worked closely with a test group and a team to get user feedback and define requirements for the application. 

Made with Microsoft Power Apps, Power Fx and Power Automate.

## Home Screen
![image](https://github.com/alextawes19/Equipment-Request-App/assets/61715901/3f76b1dd-f7fd-44cc-b6ef-99eed214b83c)

## Example Request Screen
![image](https://github.com/alextawes19/Equipment-Request-App/assets/61715901/fa5691e7-6b03-4aff-9483-f2e14170017f)
When user presses the "Request Tablet" button, a function sends and email to the help desk email with the reason for the request as the subject, comments as the body, and a default of what device is requested in the body.
```
EquipmentRequest.Run(DropdownTablet.Selected.Value, TextTablet.Text, "tablet") + Reset(TextTablet) + Navigate(ConfirmationScreen)
```

