# The Big Features

This repository includes backups of our customized Big Feature stories with notes, tips, and resources for accomplishing similar feats of design elsewhere.

## Table of Contents
- Trump's 100 Days of Deadly Coronavirus Denial - [live link](https://www.motherjones.com/politics/2020/04/trump-coronavirus-timeline/) - [100-days/](100-days/)
- Trump Killed My American Dream: 8 Stories From the War on Immigrants – [live link](https://www.motherjones.com/politics/2020/10/trump-american-dream-election-2020-war-on-immigrants/) – [american-dream/](american-dream/)
- One Family’s Escape From Trump’s Border Hell: A 130-Week Diary - [live link](https://www.motherjones.com/politics/2021/06/trump-immigration-legacy-mpp-remain-in-mexico-impact-family/) - [asylum-mpp/](asylum-mpp/)
- Bad Bosses - [live link](https://www.motherjones.com/politics/2021/09/bad-bosses-workers-fought-back-asshole-managers-nurse-guard-amazon-microsoft/) - [bad-bosses/](bad-bosses/)
- The Biblical Flood That Will Drown California] - [live link](https://www.motherjones.com/environment/2020/08/california-flood-arkstorm-farmland-climate-change/) - [california-flood/](california-flood/)
- Anxious? Furious? Hopeful? So Are We. – [live link](https://www.motherjones.com/politics/2020/11/come-feel-election-day-feelings-with-mother-jones-staff/) - [election-feelings/](election-feelings/)
- GreatSchools Wanted to Disrupt Online School Ratings. But Did It Make Neighborhood Segregation Worse? - [live link](https://www.motherjones.com/politics/2020/09/greatschools-testing-segregation/) - [great-schools/](great-schools/)
- The Heroes and Monsters of 2020 - [live link](https://www.motherjones.com/politics/2020/12/the-heroes-and-monsters-of-2020/) - [heroes-monsters/](heroes-monsters/)
- What the Pandemic Has Given Us: The Good, the Bad, and the Stupid - [live link]](https://www.motherjones.com/politics/2021/07/what-the-pandemic-has-given-us-the-good-the-bad-and-the-stupid/) - [love-it-or-leave-it/](love-it-or-leave-it/)
- The Women Asked ICE for Soap. They Got Pepper-Sprayed Instead. - [live link](https://www.motherjones.com/coronavirus-updates/2020/04/ice-pepper-spray-lasalle/) - [pepper-spray/](pepper-spray/)
- "I Should Not Be a Pawn in a Game": Workers Explain Why They Quit in Protest in the Middle of a Plague - [live link](https://www.motherjones.com/politics/2020/09/quitting-2020-coronavirus-protest-labor-bonappetit-teacher-cop-bojangles-pawn-workers/) - [quitting-time/](quitting-time/)
- A Century Ago, One Lawmaker Went After the Most Powerful Cops in Texas. Then They Went After Him. - [live link](https://www.motherjones.com/crime-justice/2020/07/a-century-ago-one-lawmaker-went-after-the-most-powerful-cops-in-texas-then-they-went-after-him/) - [rangers/](rangers/)
- The Shot in the Eye Squad - [live link](https://www.motherjones.com/anti-racism-police-protest/2021/06/photoessay-eyes-shot-police-brutality-protests/) - [shot-in-the-eye/](shot-in-the-eye/)
- Superspreader in Chief - [live link](https://www.motherjones.com/politics/2020/10/trump-coronavirus-covid-denial-timeline/) - [superspreader/](superspreader/)
- Template: _copy [template/](template/) to add a new story to the repo_

## Commonly requested CSS adjustments

#### Remove the newsletter signup blurb from the top of an article
```
.mj-text-cta {
    display: none;
}
```

#### Adjust the line break in a headline
Split Layout:
```
.single.title-split #header-text {
    padding: 1rem 1.5rem;
}
```
Adjust the left-right padding to widen or narrow the space for the header text.

#### Make an element span the full width of the screen
```
.mpp-fullwidth-illustration {
     position: relative; 		// keeps the element in the document flow
     min-width: 100vw;   		// makes it 100% of the viewport width
     margin: 0 -50vw;	 		// relocates the the element to the left edge of the viewport 
     left: 50%;					// ''
}
```

#### Add a custom font to a post
```
@import url(https://use.typekit.net/zvz7sxb.css);
```
Use a typekit or google font link for this, and put it in the Custom CSS field like any other customizations.


## Resources
- [Specificity - CSS | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
- [Inheritance - CSS | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance)

