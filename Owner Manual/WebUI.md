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

[Button](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Button.jsx) - General purpose button

[Card](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Card.jsx) - Informational card

[ColumnSelector](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/ColumnSelector.jsx) - Subcomponent of ColumnSelectorButton

[ColumnSelectorButton](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/ColumnSelectorButton.jsx) - Column UI button used by DataManager tool

[Dropdown](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Dropdown.jsx) - General purpose dropdown menu

[InputField](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/InputField.jsx) - General purpose input field

[LogoutButton](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/LogoutButton.jsx) - Logs the user out

[Modal](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Modal.jsx) - Used for building forms

[Notifier](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Notifier.jsx) - Displays toasts, used directly by App.jsx

[Pagination](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Pagination.jsx) - Divides results into pages

[Tab](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Tab.jsx) - Individual navigation tab used by TabBar

[TabBar](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/TabBar.jsx) - Contains all navigation tabs

[Table](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/Table.jsx) - Spreadsheet displayed to user

[TableEntry](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/TableEntry.jsx) - Logic for individual entry in table

[TableHeading](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/TableHeading.jsx) - Top row of table

[TableTools](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/TableTools.jsx) - TablePage component, used for utility buttons

[TopNav](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/TopNav.jsx) - Navigation tools at top of page

[UserImage](https://github.com/Field-Day-2022/field-day-2022-webUI/blob/main/src/components/UserImage.jsx) - Displays user image
