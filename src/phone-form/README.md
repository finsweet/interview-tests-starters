# Phone Form interview task

Create a fully functional country phones dropdown without using any third party pre-made solution.

Finished result as a reference: https://interview-tests.webflow.io/final/phone-form

## How to start

- Clone this repository. It has some built-in developer tools that you can use.
- Use the existing `phone-form.html` page to develop the solution.

## Requirements

The dropdown must:

- Get the countries' data from a public API.
- Dynamically populate all the options in the dropdown.
- Detect the user's location and set his country as the default option.
- Set a default selection when the geolocation fails.Display the country code in the options list.
- Display the country phone prefix in the selected option.
- Update a hidden input with the country code selection.
- Add the CSS class `selected` to the currently selected option in the list.
- Close if the user clicks outside the dropdown when it's open.
- Focus the first option that starts with any pressed key. For example: If the user presses the "C" letter, the browser must focus the "CM" (Cameroon) option.

Optionally, the dropdown should:

- Be fully accessible for keyboard navigation and screen reader users.
- Store the user's selection in a cookie or the local storage of the browser. If a stored selection exists, it must be displayed as the default option instead of geolocating the user.

## We're expecting your best code!
Invest some time in making sure your code is efficient and follows industries' best practises!

## Webflow gotchas
Developing in Webflow is not a usual development workflow, as the platform has some gotchas. Please take some time to checkout this video were we give you some recommendations!

https://www.loom.com/share/9ee9157d39964917ab276aec43ebd8a1