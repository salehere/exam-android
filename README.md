# Proxumer - Android Developer Interview Question

Please recreate a View from given screenshots
Requirement:

- Your View must contain four tabs
  1. recreate the first tab to be the same as `view-home.jpg`
  2. recreate the third tab to be the same as `view-achievement.jpg`
  3. leave the second and fourth tab blank
- On clicking the `New Goal` button, your View should route to the page that looks the same as `view-goal.jpg`
- Create a notification badge counter on the fourth tab
  1. You **must** use Socket IO to implement this feature, and it must listen for new data from the following endpoint: https://px-socket-api.herokuapp.com/
  2. You can use the following endpoint to test updating badges on your View: https://px-socket-emitter.herokuapp.com/update
     - The event name that will be emitted is "new-notification"
     - You do not need to implement a UI for this feature; it is provided to you for testing purposes only.
       Submission:
- Please submit both your source code and the compiled APK.
