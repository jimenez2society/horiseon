# Horiseon Homepage design revision

## Changes that needed to be made

### **HTML code**

- **Semantic Code** was not implemented therefore it's neccesary to convert the current code into a more meaningful structure

* **Page Title** was not descriptive enough to tell users the location or to help seo
* **Img alt tags** was not implemented causing problems for seo and screen readers
* **Heading tags** was not in descending order expept for one in the footer element.

#### Elements that need chaning

- The **div** that has the **links** to sections of the page needs to be changed to a **nav** element
- The **div** that has a class of **content** needs to be changed to a **main** element
- All of the immediate children **divs** that are in the **.content** need to be changed to a **section** element
- The **div** that has a **benefits** class needs to be changed to an **aside** element
- All of the immediate children **divs** that are in the **.benefits** need to be changed to a **section** element
- The **div** with the class **footer** needs to be changed to a **footer** element
- The **h2** in the **footer** element needs to be change to meet the requirements of descending order of heading elements.

### **CSS code**

- **CSS code** needs to be changed to adapt to the newly implemented HTML code
- Alot of CSS code is being repeated so I refactored it to reduce the code that was used
