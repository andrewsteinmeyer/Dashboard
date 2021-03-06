# SmartDash

Kanban style dashboard.  Code included is front-end only.  Backend was written in Javascript, MongoDB and Meteor.js.  I designed and developed the entire frontend and all supporting backend calls.

The user could search for an address in the search bar and the dashboard would filter the cards and update in realtime using Meteor DDP.  The user could also switch views using the button toggle in the top right or switch territory views using the dropdown selector.

## Estimate View

The estimate view was used to keep track of repair estimates.  The cards automatically progress through the columns as the status is updated.  When the estimate turns into a work order, the card moves from this screen to the work order view.

![Estimate View](https://user-images.githubusercontent.com/6377577/77596909-b3af8200-6ed3-11ea-9746-dd2c3c4b1f9b.png)

## Workorder View

The workorder view was used by the field and territory managers to manage jobs that were in progress.  The cards update as items are marked off on each repair job.  

![Workorder View](https://user-images.githubusercontent.com/6377577/77597944-c5deef80-6ed6-11ea-9d8f-2d21d1002bcb.png)

## Invoice View

The invoice view was used to keep track of outstanding invoices.  Cards automatically moved columns based upon age of invoice.  User could toggle between the column view or row view.

#### Column View
![image](https://user-images.githubusercontent.com/6377577/77598017-0d657b80-6ed7-11ea-8ee8-feb8eb93da57.png)

#### Row View
![image](https://user-images.githubusercontent.com/6377577/77602258-59b6b880-6ee3-11ea-8b1b-85ebb6cb74d4.png)

## Notifications

Users received notifications triggered upon events such as estimates being approved and invoices getting paid.

![image](https://user-images.githubusercontent.com/6377577/77598816-338c1b00-6ed9-11ea-8a99-6f836a3de9b5.png)

