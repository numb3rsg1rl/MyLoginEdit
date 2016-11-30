Team One! (a.k.a. Team9) Project Phase 1 Sumbission Readme
Features implemented
1) A MainActivity landing page that links to registration and sign-in pages

2) A SignUPActivity registration page that saves the username and password to an SQLite database in local storage.

3) A SignINActivity sign-in page that prompts the user to enter a previously saved username and password, 
which are checked against the local SQLite database. Successful sign-in is required to continue to the Hike list page, 
at which point the user is autmatically redirected there.

4) A list of Hikes with names and descriptions, implemented via the combination of a HikeActivity, 
a HikeFragment, a custom RecyclerViewAdapter, and a cutom Hike object that processes information 
about hikes that is stored on a remote MySQL server, via a webservice connection. 

5) A logout button on the same page that closes the HikeActivity page and redirects the user to 
the MainActivity landing page, at which point they will need to sign in again to return to the list of hikes.

Use Cases implemented:
We have implemented our first two use cases, in altered form. 
For Use Case 1, we are currently using locally-stored rather than Google Sign-in accounts. 
For Use case 2, we have implemented only browse, rather that true search functionality for the list of hikes.
We anticipate implementing search funtionality at a later date.