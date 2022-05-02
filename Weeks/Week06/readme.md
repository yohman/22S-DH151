# Week 6 Midterms

## Today's agenda:

- Concerns/questions/comments, all welcome!
- Let's meet! My office hours are Thursdays from 1-3, or by email appointment ([schedule here](https://calendly.com/yohda/officehours))

### Midterm Presentations

Order to be determined during class:

Group | Members
--|--
The Avengers of Data | Christina Cha, Cynthia Gong, Daniel Fouladian, Kristina Thabet
BTSTrackerSquad | Alyssa Simmons, Yahaira Cortez, Hannah Kim, Mariana Orozco-Berber
_____ (TBD) | Tianna Chan, Leonela Aguilar, Irvin Ramirez, Michelle Kung
CIA | Audrey Tey, Evelyn Hu, Laura Lu, Keona Pablo
Laborinth | Annika Sial, Jack Witherspoon, Edryna Ahmed
Stadium Spectacle| Alex Bezirjyan, Cameron Jewett, Yvonne Nguyen, and Camille Wong

Order randomizer:

```js
function shuffle(arra1) {
	var ctr = arra1.length, temp, index;

	// While there are elements in the array
	while (ctr > 0) {
		// Pick a random index
		index = Math.floor(Math.random() * ctr);
		
		// Decrease ctr by 1
		ctr--;
		
		// And swap the last element with it
		temp = arra1[ctr];
		arra1[ctr] = arra1[index];
		arra1[index] = temp;
	}
	return arra1;
}
var myArray = ["The Avengers of Data","BTSTrackerSquad","_____ (TBD)","CIA","Laborinth","Stadium Spectacle"];
console.log(shuffle(myArray));
```

## Assignments

### Individual assignment: Provide feedback to two midterm projects

Go to the discussion section and navigate to the [midterm assignments](https://github.com/yohman/22S-DH151/discussions/13). Provide feedback to **two other midterm projects**, making sure to include the following:

- What you liked about the project. Be specific!
- What you recommend the project can work on/improve on for the final (features, additional layers, design/interactive components, improved layout, narrative flow, etc)

Do not provide feedback to a project that already has more than six comments!

### Thinking cap

Topic: Design Justice

Read [Design Justice: towards an intersectional feminist framework for design theory and practice](https://github.com/albertkun/21S-ASIAAM-191A/blob/main/Week_6/Materials/Design_Justice.pdf)

Submit a "thinking cap" reaction to the reading. Specifically, discuss the following:

- How does the topic of design justice influence you personally, based on your own lived experiences?

Be prepared to share your reactions to the class next week.

Submit your thinking cap assignment [here](https://github.com/yohman/22S-DH151/discussions/14).
