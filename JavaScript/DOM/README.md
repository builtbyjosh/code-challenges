# JavaScript DOM

## Part 1: Conceptual questions
1. What is the DOM?
    Document Object Model - a tree-like JavaScript object that allows us to get to elements in HTML
2. Why is it useful? What does it do for our apps?
    Helps us treat HTML elements as objects
3. How do we manipulate the DOM?
    1) get stuff off the DOM
    2) do stuff to the elements obtained in step 1
    3) put it back in the DOM
4. When we manipulate the DOM, are we changing the html source code?
    Yes

## Part 2: Coding Challenge - Manipulating the DOM
* Visit this website: https://en.wikipedia.org/wiki/Algorithmic_art
* Using the developer console, accomplish the following:
1. Change the background color of the Contents div to grey
    1) document.querySelector('#content').style.backgroundColor = 'grey'
    or
    2) document.getElementById('content').style.backgroundColor = 'grey'
2. Create an <li> with the text "Bonus Chapter"

3. Add this <li> as the last item in the Contents div
4. Remove the page header (everything above "Algorithmic Art")
5. Change one of the images on the page to this image: https://cdn.facilityexecutive.com/wp-content/uploads/2019/10/Thumbs.Up_.jpg

* FEEL FREE TO TEST ALL THE CHANGES OUT IN THE ELEMENTS TAB BEFORE WRITING THE JAVASCRIPT VERSION!

## Bonus: 
* Change all images on the page to image from #5. How can you programmatically change all the images at once?
* Change all mentions of the word "art" on the page to word "smiles"