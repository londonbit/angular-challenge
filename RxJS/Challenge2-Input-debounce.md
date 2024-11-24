# Task 2: Reactive Input Field
Objective
Learn how to use RxJS to create a reactive input field that dynamically reacts to user input, processes it efficiently, and updates the UI. This task introduces the concepts of fromEvent, debounceTime, and distinctUntilChanged to optimize handling of frequent events (e.g., keystrokes).

### Acceptance Criteria (AC)
- The input field should capture the user's input in real-time.
- The value should only update in the UI after the user stops typing for a specified delay (e.g., 300ms).
- Consecutive duplicate values should be ignored (no updates for repeated input).
- The app should display the current input value after processing.
- The implementation should handle subscriptions properly (unsubscribe on component destruction).

### Testing the Task
Functional Tests:

- The UI should update only after the user stops typing for 300ms.</br>
  Typing the same value consecutively should not trigger updates.
- Clear the input field and ensure the UI reflects the changes.</br>

### Performance Tests:
Verify no performance issues when typing quickly.
Check that the subscription is unsubscribed properly by navigating away from the component.

### Bonus Challenge
- Add error handling:<br/>
_Display a message if the input contains invalid characters (e.g., special symbols)._
