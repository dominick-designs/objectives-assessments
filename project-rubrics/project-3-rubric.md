<table class="table">

<thead>

<tr>

<th></th>

<th class="grade-below">

### Needs Work

</th>

<th class="grade-meets">

### Meets Expectations

</th>

<th class="grade-exceeds">

### Exceeds Expectations

</th>

</tr>

</thead>

<tbody class="markdown-zone">

<tr>

<td>jQuery</td>

<td>

*   Project does not use jQuery.

</td>

<td>

*   Project includes jQuery and utilizes it in at least some aspect of the form.

</td>

<td>

*   N/A

</td>

</tr>

<tr>

<td>Focus on the first field</td>

<td>

*   On page load, the cursor does not appear in the “Name” field.

</td>

<td>

*   On page load, the cursor appears in the "Name" field, ready for a user to type.

</td>

<td>

*   N/A

</td>

</tr>

<tr>

<td>Job Role Section</td>

<td>

*   No text field appears when user selects "Other" from the "Job Role" drop down menu.

</td>

<td>

*   "Your job role" text field appears when user selects "Other" from the Job Role menu.

</td>

<td>

*   N/A

</td>

</tr>

<tr>

<td>T-Shirt Section</td>

<td>

*   The “Color” drop down menu doesn't change when a T-Shirt theme is selected.
*   Colors are listed in the drop down menu when the "Select Theme" option is selected from the "Design" menu.

</td>

<td>

*   Until a theme is selected from the “Design” menu, no color options appear in the “Color” drop down and the “Color” field reads “Please select a T-shirt theme”.
*   When a new theme is selected from the "Design" menu, the "Color" field and drop down menu is updated.

</td>

<td>

*   “Color” drop down menu is hidden until a T-Shirt design is selected.

</td>

</tr>

<tr>

<td>Activity Registration</td>

<td>

*   User can select two activities that are at the same time.
*   The total cost of selected activities is not calculated or displayed.

</td>

<td>

*   User cannot select two activities that are at the same time.
*   Total cost of selected activities is calculated and displayed below the list of activities.

</td>

<td>

*   N/A

</td>

</tr>

<tr>

<td>Displaying payment sections</td>

<td>

*   All three "Payment Info" sections display at all times.
*   The credit card payment method is not selected by default.
*   Payment option in the select menu does not match the payment option displayed on the page.

</td>

<td>

*   The "Credit Card" payment option is selected by default.
*   Payment option in the select menu matches the payment option displayed on the page.
*   When a user chooses a payment option, the chosen payment section is revealed and the other payment sections are hidden.

</td>

<td>

*   N/A

</td>

</tr>

<tr>

<td>Form Validation</td>

<td>

*   Form can be submitted (the page refreshes when the submit button is clicked) even with incorrect information, such as:
    *   Name field is blank
    *   Email is not formatted correctly
    *   No checkbox selected in “Register for Activities” section
    *   If credit card payment method is selected, the credit card, zip code and/or CVV fields are blank or filled in with letters instead of digits.

</td>

<td>

*   Form cannot be submitted (the page does not refresh when the submit button is clicked) until the following requirements have been met:
    *   Name field isn’t blank.
    *   Email field contains validly formatted e-mail address: (doesn’t have to check that it's a real e-mail address, just that it's formatted like one: [dave@teamtreehouse.com](mailto:dave@teamtreehouse.com), for example).
    *   At least one checkbox under "Register for Activities" section must be selected.
    *   If "Credit Card" is the selected payment option, the three fields accept only numbers: a 13 to 16-digit credit card number, a 5-digit zip code, and 3-number CVV value.

</td>

<td>

*   N/A

</td>

</tr>

<tr>

<td>Form Validation Messages</td>

<td>

*   On submission, the form provides no indication of a validation error, or only includes error messages for some of the required validation fields.

</td>

<td>

*   On submission, the form provides an error indication or message for each field that requires validation:
    *   Name field
    *   Email field
    *   “Register for Activities” checkboxes
    *   Credit Card number, Zip code, and CVV, only if the credit card payment method is selected.

</td>

<td>

*   Form provides at least one error message in real time, before the form is submitted. For example, the error message appears near the email field when the user begins to type, and disappears as soon as the user has entered a complete and correctly formatted email address.

*   Form provides at least one error message that changes depending on the error. For example, the email field displays a different error message when the email field is empty than it does when the email address is formatted incorrectly. *This is accomplished without the use of HTML5's built-in field validation.

</td>

</tr>

<tr>

<td>Form Works Without JavaScript</td>

<td>

*   One or more form fields or payment information is missing when JavaScript is disabled.

</td>

<td>

*   When JavaScript is disabled, all form fields and payment information is displayed, including the "Other" field under the "Job Role" section.

</td>

<td>

*   N/A

</td>

</tr>

</tbody>

</table>