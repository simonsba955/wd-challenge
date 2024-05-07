## Web Design Challenge

> Using CSS Grid, how quickly can you build a **responsive** web page?

## Duplicating The Starter Repo

Click the USE THIS TEMPLATE button to make a copy of the starter repo.

Verify in GitHub Desktop that GitHub duplicated the starter repo for you on your workstation.

## Directions

In VS Code, build a **responsive** web page that:

- has a header with a responsive background image
- has a footer containing copyright info
- three content areas [see example] (https://docs.google.com/presentation/d/1TDYDbRxldPtBEo6Se2vBrAuCrbnmurkEbBTHGhxNAP8/edit?usp=sharing)
- has responsive images in the content areas
- uses a media query to switch between desktop and mobile view

## Desktop View

Defining your container DIV:

- height: 100**vh**
- 3 columns with a width of 1 **fr** each
- 4 rows with heights of: 1**fr** 1**fr** 1**fr** auto
- grid template areas named:
  - header
  - content-lgo
  - content-sm-a
  - content-sm-b
  - footer
- gap: 5 pixels
- padding: 10 pixels

## Mobile View

- Add a media query to the bottom of your style sheet
- Use the media query to switch to mobile view

Set up your media query as follows:

- takes effect when width of browser window is less than (<) 768 pixels
- number of grid columns: 1
- number of grid rows: 5 (with widths of 125**px** auto auto auto 100**px**)
- grid template areas:
  - same names as for desktop view but stacked in a single column
    - header
    - content-lg
    - content-sm-a
    - content-sm-b
    - footer
 
## General Reminders

- Add a CSS reset rule to the top of your style sheet
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```
- Write a CSS rule to style the page body
  - Specify a font family
  - Set page font to 20 pixels

