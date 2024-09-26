# survey-form

Objective: Build an app that is functionally similar to <https://survey-form.freecodecamp.rocks>. Do not copy this demo project.

User Stories:

1. You should have a page title in an h1 element with an id of title
2. You should have a short explanation in a p element with an id of description
3. You should have a form element with an id of survey-form
4. Inside the form element, you are required to enter your name in an input field that has an id of name and a type of text.
5. Inside the form element, you are required to enter your email in an input field that has an id of email.
6. If you enter an email that is not formatted correctly, you will see an HTML5 validation error.
7. Inside the form, you can enter a number in an input field that has an id of number.
8. The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
9. If you enter numbers outside the range of the number input, which are defined by the min and max attributes, you will see an HTML5 validation error.
10. For the name, email, and number input fields, you can see corresponding label elements in the form, that describe the purpose of each field with the following ids: id="name-label", id="email-label", and id="number-label."
11. For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field.
12. Inside the form element, you should have a select dropdown element with an id of dropdown and at least two options to choose from.
13. Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the name attribute.
14. Inside the form element, you can select several fields from a series of checkboxes, each of which must have a value attribute.
15. Inside the form element, you are presented with a textarea for additional comments.
16. Inside the form element, you are presented with a button with an id of submit to submit all the inputs.

Fulfill the user stories and pass all the tests below to complete this project. Give it your own personal style. Happy Coding!

1. You should have an h1 element with an id of title.
2. Your #title should not be empty.
3. You should have a p element with an id of description.
4. Your #description should not be empty.
5. You should have a form element with an id of survey-form.
6. You should have an input element with an id of name.
7. Your #name should have a type of text.
8. Your #name should require input.
9. Your #name should be a descendant of #survey-form.
10. You should have an input element with an id of email.
11. Your #email should have a type of email.
12. Your #email should require input.
13. Your #email should be a descendant of #survey-form.
14. You should have an input element with an id of number.
15. Your #number should be a descendant of #survey-form.
16. Your #number should have a type of number.
17. Your #number should have a min attribute with a numeric value.
18. Your #number should have a max attribute with a numeric value.
19. You should have a label element with an id of name-label.
20. You should have a label element with an id of email-label.
21. You should have a label element with an id of number-label.
22. Your #name-label should contain text that describes the input.
23. Your #email-label should contain text that describes the input.
24. Your #number-label should contain text that describes the input.
25. Your #name-label should be a descendant of #survey-form.
26. Your #email-label should be a descendant of #survey-form.
27. Your #number-label should be a descendant of #survey-form.
28. Your #name should have a placeholder attribute and value.
29. Your #email should have a placeholder attribute and value.
30. Your #number should have a placeholder attribute and value.
31. You should have a select field with an id of dropdown.
32. Your #dropdown should have at least two selectable (not disabled) option elements.
33. Your #dropdown should be a descendant of #survey-form.
34. You should have at least two input elements with a type of radio (radio buttons).
35. You should have at least two radio buttons that are descendants of #survey-form.
36. All your radio buttons should have a value attribute and value.
37. All your radio buttons should have a name attribute and value.
38. Every radio button group should have at least 2 radio buttons.
39. You should have at least two input elements with a type of checkbox (checkboxes) that are descendants of #survey-form.
40. All your checkboxes inside #survey-form should have a value attribute and value.
41. You should have at least one textarea element that is a descendant of #survey-form.
42. You should have an input or button element with an id of submit.
43. Your #submit should have a type of submit.
44. Your #submit should be a descendant of #survey-form.
