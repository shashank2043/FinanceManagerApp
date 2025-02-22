Removed Console Logs

All console.log statements were removed from the code.
Improved Error Handling in fetchAllTransactions

Added toast.error inside the catch block for better error feedback when fetching transactions fails.
Date Validation for Custom Date Range

Added a validation to ensure startDate is not later than endDate. If invalid, an error toast is displayed.
Disabled Submit Button During Loading

The "Submit" button in the modal is disabled when loading is true.
Cleared Form on Modal Close

Reset the form values and closed the modal when the transaction is successfully submitted.
Fixed Transaction Title Input Value Bug

Changed value={values.name} to value={values.title} in the title input field to match the state variable.
Toast Notification for Successful Data Fetch

Added a success toast notification after transactions are successfully fetched.
Improved Reset Functionality

Reset function now also clears type, startDate, endDate, frequency, and sets view back to "table".
Modal Accessibility Enhancements

Added aria-labelledby and aria-hidden attributes to the modal for improved accessibility.
Loading Spinner Inside Submit Button

Displayed a spinner inside the submit button when loading is in progress

Changed the word expense with debit.
