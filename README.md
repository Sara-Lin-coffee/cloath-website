# Cloth Website
It is time limit practice to create a common online shopping mall without using bootscrtrap. The purpose is to practice positioning and RWD.

[check it to see the website](https://sara-lin-coffee.github.io/cloath-website/)
 
## < header > 

< header > is positioned by position: fixed to fix this section at the top of website and adjusted content by flex.

## #select-section, #paginator 

Those two sections are positioned by flex and using @media to acheive RDW.

## #cards 
This section is positioned cards by grid and using auto-fit to acheive RDW.
```
#cards {
/*positioning*/
display: grid;
grid-template-columns: repeat(auto-fit, minmax(300px,1fr));
grid-template-rows: repeat(auto-fit, 350px);
grid-gap: 1rem;
}
```
## #banner & < footer > 
Those two sections are positioned by text-align.


