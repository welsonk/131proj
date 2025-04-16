## Functional Requirements
1. A Sign Up form must be implemented to collect a user's username, password, and email. 
2. A Log In form will allow users to login using their email and password.
3. The system must provide the the user the option to Log Out.
4. A New Recipe form prompts the user for a recipe title, description, ingredients, and instructions.
5. The website should provide a feature to allow users to see and edit their own recipes.
6. 
7. 
8. 
9. 
10. 


## Non-functional Requirements
1. The system should notify the user if their Sign Up info doesn't follow security requirements.
2. Passwords must be hashed to ensure user security.
3. The Log Out option must ensure all authenticated access is taken back to prevent unauthorized access.
4. A New Recipe should save/publish to the database within 1 second.
5. Changes to an Existing Recipe should save/publish to the database within 1 second.
6. 
7. 
8. 
9. 
10. 


## Use Cases
Welson (1-5)

1. User Registration
- **Actor(s):** User and system.
- **Pre-condition:** User has unused username, password, and email.
- **Trigger:** User selects Sign Up option.
- **Primary Sequence:**
  1. User enters username, password, and email.
  2. System saves info into database.
  3. The user is notified of their account creation.
  4. The user is sent to the main page.
- **Primary Postconditions:** The user has authenticated access to the rest of the website.
- **Alternate Sequence:**
  1. User enters username, password, and email.
  2. The password does not meet complexity requirement(s).
  3. The system prompts the user to enter a different password.
---
2.  User Login
- **Actor(s):** User and system.
- **Pre-condition:** User knows their email and password.
- **Trigger:** User selects Log In option.
- **Primary Sequence:**
  1. User enters email and password.
  2. The system matches the entered values to the database.
  3. The system gives the user access and notifies the user that they are logged in.
  4. The user is sent to the main page.
- **Primary Postconditions:** The user has authenticated access to the rest of the website.
- **Alternate Sequence:**
  1. User enters email and password.
  2. The system doesn't match the entered values to the database.
  3. The system prompts the user to retry a different email/password.
---
3. User Logout
- **Actor(s):** User and system.
- **Pre-condition:** User wants to log out.
- **Trigger:** User selects Log Out option.
- **Primary Sequence:**
  1. The system asks the user if they are sure they want to log out.
  2. The user selects "Yes".
  3. The system removes the user's authenticated access.
  4. The user is redirected back to the login page.
- **Primary Postconditions:** The user's authenticated access is removed and has to login for it again.
- **Alternate Sequence:**
  1. The user appears to still be logged in.
  2. The system fails due to a network issue.
  3. The system notifies the user and is asked to try again.
---
4. Create Recipe
- **Actor(s):** User and system.
- **Pre-condition:** User has a recipe.
- **Trigger:** User selects Create Recipe option.
- **Primary Sequence:**
  1. The system prompts the user to enter their recipe with a form.
  2. User enters their recipe's title, description, ingredients, and instructions.
  3. The user clicks Save.
  4. The system adds the new recipe to the database.
- **Primary Postconditions:** The newly created recipe can be seen by all authenticated users.
- **Alternate Sequence:**
  1. The system prompts the user to enter their recipe with a form.
  2. The user fills out the form unfinished.
  3. The user clicks Save.
  4. The system prompts the user to properly fill out the form.
---
5. Edit Recipe
- **Actor(s):** User and system.
- **Pre-condition:** User has an existing recipe they want to change.
- **Trigger:** User selects Change Recipe.
- **Primary Sequence:**
  1. The system shows the user the selected recipe in an editable form.
  2. The user makes changes to the recipe.
  3. The user selects Save.
  4. The system overwrites the existing recipe into the database.
  5. The user is sent back to the main page.
- **Primary Postconditions:** The changed recipe can now be viewed in replacement of the old recipe by all authenticated users.
- **Alternate Sequence:**
  1. The system shows the user the selected recipe in an editable form.
  2. The user deletes the title.
  3. The user selects Save.
  4. The system prompts the user to not leave any field blank.
---
6. 
- **Actor(s):** 
- **Pre-condition:** 
- **Trigger:** 
- **Primary Sequence:**
  1. 
- **Primary Postconditions:** 
- **Alternate Sequence:**
  1. 
---
7. 
- **Actor(s):** 
- **Pre-condition:** 
- **Trigger:** 
- **Primary Sequence:**
  1. 
- **Primary Postconditions:** 
- **Alternate Sequence:**
  1. 
---
8. 
- **Actor(s):** 
- **Pre-condition:** 
- **Trigger:** 
- **Primary Sequence:**
  1. 
- **Primary Postconditions:** 
- **Alternate Sequence:**
  1. 
---
9. 
- **Actor(s):** 
- **Pre-condition:** 
- **Trigger:** 
- **Primary Sequence:**
  1. 
- **Primary Postconditions:** 
- **Alternate Sequence:**
  1. 
---
10. 
- **Actor(s):** 
- **Pre-condition:** 
- **Trigger:** 
- **Primary Sequence:**
  1. 
- **Primary Postconditions:** 
- **Alternate Sequence:**
  1. 

