# CS 360 Mobile App Portfolio

## Inventory Tracker App

For this course, I developed an Android inventory tracker app. The goal of the app is to help users manage inventory from a phone or tablet. The app allows a user to create an account, log in, choose whether to allow SMS alerts, add inventory items, view current stock, update item quantities, and remove items that are no longer needed. The main user needs this app was designed to address were simple inventory tracking, quick quantity updates, and low-stock awareness.

## Screens and Features

The app includes a login screen, an SMS permission screen, and an inventory screen. The login screen lets users create an account or log in with saved information. The SMS permission screen gives users the choice to allow or decline SMS alerts. The inventory screen includes text fields, buttons, and a current inventory list so users can add items, select rows, increase or decrease quantities, type an exact quantity, and remove selected items.

These screens were necessary because they separate the main parts of the app into a clear flow. Instead of putting every feature on one screen, the app starts with login, moves to permission choice, and then brings the user to the inventory tools. This helped keep the design easier to follow and more user-centered.

## Design Approach

My design approach was to keep the app simple and organized. I wanted the user to understand what each screen was for without needing extra instructions. The inventory screen was designed around the actions a user would need most: adding items, viewing stock, updating quantities, and removing items. The low-stock alert also helps users quickly notice when an item needs attention.

## Development Approach

My coding approach was to build the app one part at a time. I started with the screen layouts, then connected the buttons and text fields to Java code. After that, I added the local database so the app could save login information and inventory items. I also added update and delete functions for the inventory list, then tested the SMS permission flow.

Breaking the project into smaller steps made it easier to find and fix problems. For example, I tested adding items before moving on to updating quantities, and I tested the plus and minus buttons before adding the typed quantity update. This made the project less overwhelming and helped me understand how the user interface and code work together.

## Testing

I tested the app in the Android Emulator to make sure the main features worked correctly. I tested creating an account, logging in, adding inventory items, updating quantities, removing items, and checking low-stock behavior. I also tested allowing and declining SMS permission to make sure the app still worked even when SMS alerts were not allowed.

Testing was important because small issues were not always obvious until I used the app like a real user. It helped reveal problems with button behavior, quantity updates, and the overall screen flow. Testing also helped confirm that the database saved and displayed inventory information correctly.

## Challenges and What I Learned

One challenge was connecting the visual layout to the actual app logic. It was one thing to design the screens, but another thing to make sure the buttons, database, permissions, and inventory list all worked together. I had to slow down and test each feature instead of trying to finish everything at once.

One area where I think I was successful was the inventory update feature. The app allows users to select an item, use plus or minus quantity buttons, or type an exact number and press the keyboard Done/checkmark button. This made the inventory screen more flexible and easier to use.

## Future Improvements

In the future, I could improve the app by adding barcode scanning, cloud backup, better login security, multiple users, report exporting, and reorder reminders. I could also test the app on more Android devices and screen sizes to make sure the layout works well outside of the emulator.

## Submitted Artifact

The completed Project Three Android Studio ZIP file is included in this repository.# CS-360
