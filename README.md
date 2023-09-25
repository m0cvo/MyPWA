# MyPWA

Using Visual Studio 2022 v.17.7.4, I have created a small Blazor PWA app.

As well as the standard Blazor package that VS creates for you with Counter, FetchData and Index razor components, I have also added one page called Test
which can be accessed via the Nav Menu on the Index Page.  This page then accesses two further components - Dialog.razor and HealthApp.razor.  The Dialog 
app includes a button that both writes to the console (right click and <inspect>) and appends a message to the screen.  The HealthApp is a BMI Calculator.

Once compiled and published, this app can also be used offline as a PWA.

Copyright (c) Nigel Booth 2023.
