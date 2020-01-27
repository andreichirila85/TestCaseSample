# TestCaseSample
Install the Vivino app from App Store

Verify that the application is installed without errors.

Requires iOS 10.0 or later.	

Steps to reproduce:
1. Open App store and search for Vivino app.
2. Tap on Get button in order to install the app.
3. Navigate on the phone where new applications are installed and open the app.
	
Expected results:		
The Vivino icon is present, the app is opened.

--------------------------------------------------------------

Incoming calls interruptions

Verify that the app returns to the same point before receiving the call.

Requires a second phone to call the test device. App must be installed and running.

Steps to reproduce:
1. Initiate a call from a second phone to the test device.
2. Answer the call on the test device and conduct a conversation.
3. End the call.
4. Check if the app returns to its previous state.

Expected results:
The app successfully returns to the same point before receiving the call.

---------------------------------------------------------------

Sign-up with valid email and password

Verify that user is able to create a new account by filling the mandatory fields with valid inputs.

Steps to reproduce:
1. Open app and tap on Get started button.
2. Fill the mandatory fields(email, password) with valid data and tap next.
3. Fill the mandatory fields(first name, last name) with valid data.
4. Agree to the terms of use by changing the switch from OFF to ON position and tap done.

Expected results:
User is signed up. A pop-up dialog box is dispayed whether the user prefers or not notifications.

-----------------------------------------------------------------

Logged out

Verify that user remains logged out when he choose to sign out.

Requires user to be logged in.

Steps to reproduce:
1. Open app and tap on Profile menu.
2. Tap on Settings icon.
3. Scroll down the page and tap on Sign out.
4. User must confirm to log out by taping Sign out.

Expected results:
User is succesfully logged out.

-------------------------------------------------------------------

Access camera

Verify that user is able to access apps camera.

Steps to reproduce:

1. Open app and tap the on-screen camera icon.
2. Tap on Open Settings.
3. Allow app to access camera by switching camera's position from OFF to ON.
4. Open the app again and tap the on-screen camera icon.

Expected results:
User is able to access apps camera in order to scan a wine.

-----------------------------------------------------------------

Scan a wine label in portrait mode

Verify that user can successfully scan a wine label in portrait mode.

Requires user to be logged in.

Steps to reproduce:
1. Open app and tap on camera icon.
2. Position the wine label within the frame, in portrait mode and tap on camera icon again.
3. Tap on Use button in order to find the scanned wine.

Expected results:
User successfully scanned a wine label in portrait mode.

--------------------------------------------------------------------

Undoing an action

Verify that user is able to undo an action when any wrong item is touched.

Steps to reproduce:
1. Randomly search for a wine and tap on it.
2. Tap back button from top left corner or swipe right in order to undo the action.

Expected results:
User is able to undo an action.
