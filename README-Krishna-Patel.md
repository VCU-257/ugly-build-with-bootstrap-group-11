# Student Name: [Your First and Last Name]

## 1. My Assigned Work
*The specific screens and html files I did were-*
**Description.html** *- The description page for a product when clicking on a product*
**Wishlist.html** *- The wishlist page of users that can track their wishlisted item in one place*

## 2. Bootstrap Implementation
*For pages of Item Description and Wishlist, I stuck to the plan from Table 1 and used  default Bootstrap 5 components, but also used some Bootstrap components not listed. I decide to not include the image Bootstrap component due to this being a ugly build, but will intend to use in later implementations* 

**Components Used:** *Cards, Buttons, Flexbox, Margin/Pdding ,and Postion*
*Cards - Used on the Item page to wrap the Description and Specifications sections*
*Buttons - Used throughout for Add to Cart, Buy Now, Wishlist, and the X remove button(`btn`, `btn-outline-secondary`, `rounded-pill`, `rounded-circle`)*
*Flexbox - Used `d-flex`, `flex-grow-1`, `flex-shrink-0`, and `align-items-center` to build the wishlist row layout*
*Margin/Pdding - used `pe-5`, `px-4`, `mb-3`, `gap-2`, etc. to control spacing between elements*
*Postion - used `position-relative` and `position-absolute` with `top-0 end-0` to pin the X button to the corner of each wishlist row and to have the core information center of the page*
*There are other Bootstarp componets used, but I didn't implement them my teamates did(navbar)*

## 3. Technical Challenges & Solutions
*When doing my pages I feel as if I didn't have the problems listed in table 4. The hardest part of doing these 2 pages would have to be creating the wishlisted items. Getting all the buttons, boxes, and text to be at the correct position I wanted was tricky. After creating one wishlisted item I could just copy it and paste another underneath to create another wishlisted making the following step easier. This could be used as a way so that a function could be able to create a wishlist item. Beside that It seemed very easy to use after looking how the components work and how it can be used*

## 4. AI / LLM Usage

**Did you use an AI tool to help write or debug your code?**
*Yes I used AI to help me write and debug my code*

**What I asked the AI:**
1. *I have two buttons overlapped with each other one being buy now and the other being the X button for the wishlisted item. How do I keep the same layout but not have these two overlapped.*

2. *Is there a bootstrap class for when hovering a object it changes tranprency*

3. *How to implement a Bootstrap Modal so the product image pops out*

4. *What each Bootstrap class in the generated code does, line by line*


**How it helped & What I learned:** 
1. *The LLM said that adding the class `pe-5` to the buttons column would move it left of the X. We do this because the X button is stuck in the corner with "position-absolute top-0 end-0." I found out where to correctly place the Bootstrap spacing component, so that it allowed me to add space between elements.*

2. *For the hover transparency, I learned that Bootstrap does not have a built-in hover opacity utility class. So the solution was to create a `<style>` block in the `<head>` and the core logic being `{ background-color: #c8c8c8 !important; }`. Where !important overrides any other conflicting styles like `bg-secondary bg-opacity-25`.*

3. *For the Modal question the LLM showed me how `data-bs-toggle="modal"` and `data-bs-target="#fullViewModal"` on the image box connects it to the Modal component. The Bootstrap's JS bundle handles all the open and close behavior automatically with no extra JavaScript needed. I believe that this could be useful for many parts of the website and also very glad to learn this.*

4. *I made sure I understood the code by asking LLM to explain specific classes whenever something was not behaving as expected, and by testing changes. This not only helped me learn but also help me catch bugs throughout my code and better implementation*

## 5. Live Site Link
*Provide the GitHub Pages link to the specific page(s) you built.*
* **Live URL:** 
Description page - https://vcu-257.github.io/ugly-build-with-bootstrap-group-11/description.html

Wishlist page - https://vcu-257.github.io/ugly-build-with-bootstrap-group-11/wishlist.html 

