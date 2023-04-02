# Web UI
## Running locally
The Web UI is meant to be a way of viewing the database from a desktop computer at home connected to the Internet.  In order to start up the Web UI locally as a developer:

1. Download the [Web UI repository](https://github.com/Field-Day-2022/field-day-2022-webUI) if you haven't already and check out the branch you want to work on
2. In the Web UI directory, open a terminal
3. Enter the following command:
> npm run dev
4. Go to the URL provided in the terminal (by default, the current version of Vite makes this http://localhost:5173/)
5. Login with your ASU email.  This will be authenticated by Google, so it must be valid.

## Developing code
The majority of the code is uses React and is distributed among JSX components.  Most of the logic is found in the [components](https://github.com/Field-Day-2022/field-day-2022-webUI/tree/main/src/components) directory.  After modifying a component, stop the process in the terminal (ctrl + c) and re-run "npm run dev".  When testing your code, be sure to view the browser's console (F12) to look for errors.

## Resources
[Official React Documentation](https://react.dev/)
[W3Schools JavaScript general tutorial](https://www.w3schools.com/js/)
[W3Schools React tutorial](https://www.w3schools.com/REACT/DEFAULT.ASP)


## Individual components
The Web UI's [html document](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/index.html) will rarely need to be modified.  It does little more than load the [main JSX file](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/main.jsx), which in turn is only meant to load every component.

[Button](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[Card](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[DataTable](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[Dropdown](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[LogoutButton](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[Modal](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[Notifier](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[Pagination](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[TabBar](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[TableEntry](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[TableTools](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[TextRevealIconButton](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[TopNav](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
[UserImage](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - 
