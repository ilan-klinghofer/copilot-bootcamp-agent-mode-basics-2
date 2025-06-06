### :keyboard: Activity: Adding MUI instructions and updating docs

In this exercise, you'll use GitHub Copilot's Agent mode to add React's component library, and create a new component with it.

### :keyboard: Activity: Create a table without guiding copilot to use MUI

We will first create a table without explicitly instructing copilot to use the MUI component library.

1. Open the **Copilot** chat panel and switch to **Agent** mode using the dropdown menu.

2. Use the following prompt to ask Copilot to convert the existing item section to a vanilla HTML table:

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Convert our item-section to a table
   > ```

3. Copilot will analyze your codebase and implement:
   - Updating the `App.js` to implement a table in place of the current `item-section`

4. When Copilot finishes making the changes, review what was modified:
   - `App.js`

5. Run the application with `npm run start` in the root directory to test the new functionality.

### Success Criteria

To complete this exercise successfully, ensure that:
   - `App.js` was updated with a vanilla HTML `table` implementation

If you encounter any issues, you can:
- Ask Copilot to fix specific problems
- Check the developer console for any errors
