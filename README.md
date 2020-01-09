# mycssframework
    This repo consists of the different css files for the development and design of websites very easily.
# Idea:
    * Add classes of requirement to the html elements and get the style applied to it.

# Points to be noted : 
     you can add the custom styles as well .
     please include the fonts and fontawesome icons which are along with this package
 
# Fonts:
    poppins
    poppinsblackitalic
    poppinsbold
    poppinsbolditalic
    poppinslight
    poppinsextralight
    pacifico
    hind
    satisfy
    jos

# varaibles:
    --color-green:#2ecc71;
    --color-turq:#1abc9c;
    --color-pomo:#e77e72;
    --color-cloud:#ecf0f1;
    --color-lavender:#D980FA;
    --color-med:#1289A7;
    --color-sunflower:#FFC312;
    --color-teal:#55E6C1;
    --color-black:rgb(40, 41, 40);
    --color-dark:rgba(15, 15, 15, 0.808);
    --color-orange:#ec5747d5;
    --color-slate:#2c3e50;
    --color-glamour:#ff7675;
    --color-blue:#74b9ff;
    *********************
    --font-poppins:poppins;
    --font-poppinsbold:poppinsbold;
    --font-poppinsblackitalic:poppinsblackitalic;
    --font-poppinslight:poppinslight;
    --font-poppinsextralight:poppinsextralight;
    --font-jos:jos;
    --font-pacifico:pacifico;
    --font-satisfy:satisfy;
    --font-india:hind;

# Classes list:

# Backgorund Colors Classes:
    background-blue
    background-orange
    background-dark
    background-black
    background-glamour
    background-med
    background-slate
    background-teal
    background-sunflower
    background-lavender
    background-cloud
    background-teal
    background-turq
    background-green

# Font sizes:
    font-vsmall : 0.25rem;
    font-small : 0.5rem;
    font-regular : 1rem;
    font-large : 1.5rem;
    font-vlarge : 2.5rem;

# Width sizes:
    small-width : 25%;
    semi-width:50%;
    threequarter-width : 75%;
    regular-width:100%;
    one-onefourth-width:125%;
    vlarge-width:200%;

# Containers:
    *** it is important to note that we should include the container class compulsoru inorder to use its derivative classes.
# Container-sizes-orientation : 
        small-container-right : 25% width and aligns the contents inside it to the right
        semi-container-right  : 50% width and aligns the contents inside it to the right
        threequarter-container-right  : 75% width and aligns the contents inside it to the right
        regular-container-right  : 100% width and aligns the contents inside it to the right
        small-container-left : 25% width and aligns the contents inside it to the left
        semi-container-left  : 50% width and aligns the contents inside it to the left
        threequarter-container-left  : 75% width and aligns the contents inside it to the left
        regular-container-left  : 100% width and aligns the contents inside it to the left

# Buttons:
    no-border-button  ==> this class applies the border of 2px solid and transparent;
    signin  ==> sign in button with a nice font family
    signup ==> signup button with a nice font family
    submit ==>for a submit button
    newslettersignin ==> new letter form setup { 
        the html should be as follows : 
                    <form class="newslettersignin">
                        <input type="text" placeholder="example@exmail.com">
                        <button class="submit">Subscribe</button>
                    </form>
        this form element spans the whole width of the parent div if we want to get the smaller width wrap this form element inside of                                                                    another  div for the modification.
    }

# Nav : 
    no need of adding the li tag in html
    defaultly it is given the colors
    nav classes:
    ===========
    navbar-links-left : this makes the nav with 100% of width and the contents are aligned to the left;
    navbar-links-right : this makes the nav with 100% of width and the contents are aligned to the right;

# Links :
    link-active : it gives the green color for the link
    link-deactive : it gives the lavender color for the link
    link-quit : it gives the glamour color for the link
    link-silent : it gives the slate color for the link

# Soical Links Container:
    social-container  ==> this is the parent div that is to be populated with links
    social-link ==> this is the link 
