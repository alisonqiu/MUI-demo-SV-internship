# This is a Demo for MUI autocomplete dropdown text search, tables, and cards

## Getting started
frontend: `npm i && npm start`

backend: (probably not necessary but) `node server`

To get started with MUI, 

run `npm install @mui/material @emotion/react @emotion/styled`

read more from the official documentation (https://mui.com/material-ui/getting-started/overview/).

## autocomplete + dropdown 
Can be found at: `src/Components/Dropdown.js`

After fixing the CORS issues, I'm planning on using this for the autocomplete component for the final project.

### autocomplete

<img width="306" alt="Screen Shot 2022-05-31 at 4 49 10 PM" src="https://user-images.githubusercontent.com/90943803/171290098-31afb644-84b6-4324-a4b3-a6d293c25973.png">


<img width="500" alt="Screen Shot 2022-05-31 at 5 00 14 PM" src="https://user-images.githubusercontent.com/90943803/171291400-bd112920-287f-4314-b5d0-04871d67d8bc.png">

Since API doesn't work, the data is currently stored in `top100Films`. You can access the values being typed in through `params.inputProps.value` Each time the value changes, `setTestInput` resets `textInput` and I'm trying to trigger a query to the backend each time.

### dropdown

<img width="306" alt="Screen Shot 2022-05-31 at 4 48 52 PM" src="https://user-images.githubusercontent.com/90943803/171290101-1b37f66b-2921-426f-8f77-3ed294771e46.png">

Dropdown is made using a FormControl MUI component. When users select a different input, the `handleChange` function updates `name` to display the variable selected


## tables
Can be found at: `src/Components/Tabledemo.js`

<img width="956" alt="Screen Shot 2022-05-31 at 5 03 53 PM" src="https://user-images.githubusercontent.com/90943803/171291743-7144f6ca-c369-4568-bdb1-e2b2df72793a.png">

## cards
Can be found at: `src/Components/Carddemo.js`

<img width="639" alt="Screen Shot 2022-05-31 at 5 03 41 PM" src="https://user-images.githubusercontent.com/90943803/171291790-fc72584f-666e-4f6d-bc49-3bde2a0f8f66.png">


This is not comprehensive so ask me if you have more questions.
