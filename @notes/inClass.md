# INCLASS NOTES - DevMountain 

## Git
for getting onto your branch

	// git push origin <nameOfBranch>

git branch <nameOfBranchToCreate>



### html / css

html = skeleton of webapp/website
css = hair/skin visuals

every html element has default properties (e.g., margin/padding,etc.)
thing have defaults (know the defaults to use the proper tag)
	knowing the defaults == cleaner code

	html5 == try to make more semantic tag

	<footer></footer>		<— can be used in multiple places 

	<ol>
	  <li></li>
		</ol>  <—— ordered list

		<ul>
		  <li></li>
			</ul>  <—— unordered list

				// caniuse.com // <— to check for compatibility 

### classes and id’s 

reuse class
id == don’t use id’s if you can help it

as a general rule you don’t want to throw out a style to all div’s

	for SPECIFICITY YOU DON’T WANT A HIGH NUMBER (e.g., 120+ in the specificty calculator)

### inline styles  <—- don’t use it
  don’t do it.

	something that is even worse
		using !important   <—- as a general rule
				// using important to debug only

					^ the specifity and you don’t see the !important (which is infinite specific) it eliminates a specifity issue


					!! width is specific to the container it’s in
						it has to be defined, e.g., you have to define the body (it’s parent) in order to make it work)

						when to use pixels > percentages would be a design that is set at a fixed amount
							e.g., a sidebar that’s 310px
									don’t want to use, case example would be using a very large hi-res screen

### background-image
	background-size: cover
				or contain
						background-repeat: no-repeat;

						background: url(stuff.image) no-repeat;


						will be using float: left || right

						you will generally float the parent instead of using overflow: auto, etc.,

# 2015-04-01 - InClass w01d03 - Wed










