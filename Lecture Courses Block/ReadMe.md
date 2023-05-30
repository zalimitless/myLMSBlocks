# Moodle Block Component: Custom Course Card 

Welcome to our Moodle Block Component designed to create a unique block that displays your Moodle courses in a stylish card format. This block provides a visually pleasing alternative to the standard list format and enhances the user experience.

## What does this code do?

This JavaScript-based component renders a block on your Moodle page that presents your courses as a set of custom cards. 

Each card represents a course and includes:

- A clickable tile that links to the course.
- A background image that can be specified per course.
- The instructor's name.

The cards are dynamically created and populated using the provided courses data, fetched from the Moodle system.

Additionally, the block includes a section title that states the total number of courses. This section is collapsible, allowing you to toggle the visibility of the course cards.

Finally, there is a placeholder card that is displayed while the actual course cards are being loaded. This provides a better user experience by indicating that content is loading.

## How to Customize the Block

This code can be customized according to your requirements. Below are some key customizations you can make:

**Changing the Block Title:**

You can change the title of the block to fit your needs. By default, the title is set to "My Lecture Courses". To change this, look for the following line at the top of the script:

```javascript
var title = "My Lecture Courses";
```

Replace "My Lecture Courses" with your desired title. For example, if you want the title to be "National Pages", change it to:

```javascript
var title = "National Pages";
```

**Changing the Course Pattern:**

By default, this component uses a regular expression pattern to match and display certain courses. The pattern and its application can be changed according to your requirements. 

To display courses that do not match the courses pattern, the title can be set to "National Pages", with this set `negatePattern` to `true`. Here is how you do it:

```javascript
var negatePattern = true;
```

Remember, `negatePattern` should be set to `false` if you want to display courses that match the pattern. 

## Final Remarks

Feel free to dive deeper into the code to make more specific customizations according to your preferences and requirements. This is an open-source component, and we encourage you to modify it to fit your needs. 

However, please remember to follow the licensing terms and guidelines provided with the repository. Happy coding!
