# Forms and JS Events

[Back to Main Page](README.md)

## Forms

- forms allow users to interact with dynamic websites

- users can input text such as searching or passwords

- users can make choices like doing an online quiz

- users can submit or confirm things

### How They Work

1. name of each form control is sent to server with input values

1. server process info

1. server returns a new page to send user to base on given info

### Structure

- `<form>` is where the form controls live

- `<method="get/post>` determines where info is sent to the server or pushed to the user

- `<input>` is how you'll create something for the user to interact with and return

- `type="radio"` creates a bubble user can check or not

- `<select>` creates a drop down list

- `type="submit"` is used to send contents of a form to the server

- forms can also be validated to confirm your user provided the correct info

- `type="date"` allows user to select a date

## Lists, Tables & Forms

- `list-style-type` lets you change the placeholder before a list item

- you can also use images for bullets

- the marker can be positioned inside or outside a text box

### Table Properties

- you can change width, padding, text, letter spacing, font sizes, borders, text alignment and more

- `empty-cells: hide` let's you hide empty cells

- `separate` allows you to create space between individual cells

### Styling Forms

- making forms pretty encourages users to actually use them

- with text you can change font colors, background color of the text input etc.

- subit buttons have these same options plus the `hover` option when the user mouses over

- `cursor:` changes what the cursor looks like when a user hovers over it

## Events

-browsers can be told to register different events of things happenening on screen and be told to respond (ex. you spend 5 minutes with a fancy pair of shoes in your cart but don't buy them. The server may be triggered to send you an emaiol with a special deal)

### Types of Events

- UI events are things like the page being loaded or resized

- Keyboard events for when users press keys

- Mouse events for when the mouse is moved or clicked

- Form events for when a user interacts with a form 

- Mutation events for when changes have been made to the DOM

### How Events Trigger JS Code

1. Indicate element nodes you want the script to respond to

1. Indicate which event will trigger the desired response

1. State the code you wanna run

- or 

1. Select Element

1. Specify event

1. Call code

- `element.onevent = function;`

- event listensers are a more encompassing way to handle events but aren't suppoorted by older browsers

### Event Flow

- HTML elements all nest inside of their parents so if you click a link in a paragraph you'll also be selecting the paragraph

- flow is important because when multiple listeners are added conflicts will be created if not structured properly

### Event Delegation

- because events affect parents elements you can place them in the containing elements and use the event object's target property to figure out which child the event occurred on

- this is important because it will simplify your code drastically

- `preventDefault()` stops the normal function of an event like clicking on a link not sending you to a different page
