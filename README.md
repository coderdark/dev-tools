# dev-tools
opening the console window mac `command + options + c`

## Panels
+ Element Panel
  + View HTML and CSS
  + Can change classes and ids
  + Update styles
  + Modify HTML
  + If you have an long page with many elements, you can use two finder in your track pad/left mouse to get a context menu, select `scroll into view` to show you the element you selected.
  + `H` to hide the selected element
  + `Delete` to remove the selected element
  + Simulate state (anchor <a>), by clicking the `:hov` from the righ side panel under `Styles`
    <img width="467" alt="Screenshot 2024-12-29 at 8 21 43 PM" src="https://github.com/user-attachments/assets/a05d63ee-ef5f-4475-81c5-7c9a519b7a4c" />
  + You can add a new class by selecting the `+` icon on the right side panel, once you selected an element
    <img width="470" alt="Screenshot 2024-12-29 at 8 28 39 PM" src="https://github.com/user-attachments/assets/317e5914-bc36-41eb-b056-609283728f82" />
  + Click on the `Computed` to see ALL the styles applied to the selected element according to  CSS Specificity (https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity#selector_weight_categories)
    + Click on the style to expand and see all the styles that are applied
    + Click on the error next to the style value to go to it. See below...
    <img width="422" alt="Screenshot 2024-12-29 at 8 41 39 PM" src="https://github.com/user-attachments/assets/98e6cd61-2ca0-452a-8c75-252e2d227957" />
  + HTML Breakpoints
    + Select the element and then use two finders on your trackpad or left button on your mouse to get the context menu, select `break on` and then select 1 of the 3 options: `subtree modifications`, `attribute modifications` or `node removal`.  See image below.  This will show you what JS script is making changes to the html.
    <img width="402" alt="Screenshot 2024-12-29 at 8 46 24 PM" src="https://github.com/user-attachments/assets/64566b7c-f491-4086-9331-65a431da4acf" />

+ Console Panel
  + Can be use to execute javascript
  + Typing `$0` in the console will give you the last element selected in the Elmement Panel. $1,$2 and so on are the previous selections.  If no previous selection then $1 or $2 are undefined
+ Source Panel
  +
+ Application Panel
  + Can view storage, cookies, service workers for PWA (Progressive Web App)
