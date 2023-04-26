# How to update a photo on Firebase profile

## Upload the image to Firebase Storage
### Upload a photo file using the Firebase console 
### Upload a photo file using the Firebase Storage SDK

## Get the photo file download URL
You can do this by calling the `getDownloadURL()` method on the `StorageReference` object that represents your image

## Update the user's profile in Firebase Authentication
You need to update the user's profile in Firebase Authentication.
You can do this by calling the `updateProfile()` method on the `FirebaseUser` object that represents the user. 
In this method, you can set the user's display name and photo URL using the `displayName` and `photoURL` properties.
Check [Cloud Storage for Firebase / Web / Manage users / Update a user's profile](https://firebase.google.com/docs/auth/web/manage-users#update_a_users_profile)


## Display the user's profile in your app's UI
You can do this by using the photo URL that you obtained in step 2 to display the user's new profile picture.
