Menu Application Design

Please install this pdf extention https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf

Design Choices for [text](<Home Page.pdf>) and [text](<Dish Insight.pdf>)

Font Types 

Chef Name - Cormorant Garamond
All other text - Sans Serif

Text Size 

Main Heading - 30
Dish Headers - 18
Date - 14
Basic Text 16

Color Pallete (minimalistic color pallete features gold and Black to inspire a higher class feel)

Headers - #FE9A00
Date - #E17100
Basic Text #D6D3D1

Consistent Design Choices through out the application in regards to the Color Pallete, Font Size, Font type. To ensure easy readibilty and allow a user freindly User Interface

Home Page Description 

- A Home page Menu That showcases The chefs name along side a brief introduction. The date is displayed below that to ensure users know they are viewing the correct menu for that night. Below that are 3 Options Starters, Mains and desserts each with a collapsable drop down that list what dishes are available for that course. 

- Each dish is followed with a price. 

Dish Insight page

- If a dish is clicked on by the user they are redirected to a seperate page which Displays the Dish name, a photo of the dish, price, a brief description on how the dish is prepared and lastly followed by an ingrediant list. Dish Insight.

App Navigation Diagram

- A simple Navigation Diagram Showcasing The different steps and routes the user can use to navigate through the application

![alt text](<Navigation Diagram.jpg>)

Gui Elements 

Home Screen

Imports

Navigation

- NavigationContainer - enables navigation for the applicatiom
- createNativeStackNavigator() - creates a stack which just creates multiple pages in which im able to navigate
- Stack.Screen - Lables each screen
initialRouteName="Home" - ensures the application starts on the homepage

Layout Essentials

- View - main container for layout
- Text - displays text
- TouchableOpacity - creates a clickable button
- navigation.navigate("Menu") → moves user to Menu screen

Styling and Layout Essentials 


- flex: 1 - fills the screen
- justifyContent - vertical alignment
- lignItems - horizontal alignment
- padding and margin - spacing for the text

Drop Down

- isOpen - controls if you can see the dropdownw
- selectedCategory - stores chosen category

Menu Data

 { id: 1, name: "Carpaccio", category: "Starters", description: "Fresh tomato dish" },

    { id: 2, name: "Scallops", category: "Starters", description: "Seafood starter" },

    { id: 3, name: "Halibut", category: "Mains", description: "Fish main course" },

    { id: 4, name: "Ribeye", category: "Mains", description: "Steak dish" },

    { id: 5, name: "Lemon Tart", category: "Desserts", description: "Sweet dessert" }];

- Array to store all the dish information

Image insertion

- Image
- import { Image } from 'react-native';

