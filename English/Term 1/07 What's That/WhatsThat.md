Level 3

#What's That

__Introduction__
6. Create this script:

```scratch

		next costume
	(end repeat)
```

###Test Your Project
 Do you get different costumes every time? Sometimes you’ll get the same costume twice in a row, but that’s OK. You’ll also notice that you can see the sprite flicker as it changes costume. We’ll fix that in the next step.





		next costume
	(end repeat)
	set score to 110
	repeat until score = 0
		change score by -10
		set pixelate effect to score
		set colour effect to score
		show
		wait 1 secs
	(end repeat)
```



```scratch

		next costume
	(end repeat)
	set answer to costume
	set score to 110
	repeat until score = 0
		change score by -10
		set pixelate effect to score
		set colour effect to score
		show
		wait 1 secs
	(end repeat)
```
__Now we need to add the sprites that the player can click on.__
￼￼4. Rename this sprite to __answer1.__ (This makes it easier to talk about.)


	(end if)
```



```


```


		next costume
	(end repeat)
	set answer to costume
	set score to 110
	set won to 0
	repeat until score = 0 or won? =1
		change score by -10
		set pixelate effect to score
		set colour effect to score
		show
		wait 1 secs
	(end repeat)
	
	When I receive won
	set won to 1
	clear graphics effects
	say join Congratulations! You scored score
```



Save your project







