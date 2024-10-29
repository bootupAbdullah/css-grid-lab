## CSS Grid Lab


## References:
<details>
(1) https://developer.mozilla.org/en-US/
 - Using media queries

(2) ChatGPT
- Checking syntax errors, asking for help in better understanding concepts of grid and media queries.

<br/>

</details>

#### I attempted to emulate the CTA design from wireframing

#### I worked my way up from mobile design. This was the initial html and css:


<br/>

HTML:

<body>
    <div id="h1"><h1>Ready to get started?</h1></div>
    <div id="p"><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt beatae recusandae provident?</p></div>
    <div id="button"><button>Start free trial</button></div>
</body>
</html>

<br/>

CSS: 
<details>
body {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    font-family: "Crimson Text", serif;
    font-weight: 400;
    font-style: normal;
}


#container-1 {
    display: grid;
    grid-area: 2/2;
}

#h1 {
    display: flex;
    justify-content: center;
    padding-right: 30px;
    grid-area: 2/2;
    /* padding-left: 20%; */
    padding: auto;
}

#p {
    grid-area: 3/2;
    /* font-size: */
    /* padding-left: 10%; */
    padding: auto;
}

#button {
    display: flex;
    justify-content: center;
    grid-area: 4/2;
    border-radius: 5px;
    width: 60%;
    length: 80%;
    padding-left: 10%;
    padding: auto;
}

button {
    /* padding-left:; */
    background-color: black;
    color: white;
    font-family: "Crimson Text", serif;
    font-weight: 100;
}
</details>


### I then added the following media queries to help with larger screens:

<details>

@media (min-width: 700px) {
        h1{
            padding-right: 10%;
        }

        p{
            display: flex;
            justify-content: center;
            padding-right: 10%;
        }
    }

</details>


### Grid is a challenging concept, it took an extended amount of time, trial and error to learn how to center the elements. This is primarily why I am submitting one deisgn.