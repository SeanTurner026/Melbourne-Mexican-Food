## General Assembly Capstone Project

Ever since moving to Melbourne from New York, I have been keenly aware of the lack of good Mexican food in Melbourne. Overtime, this sentiment encouraged me to try and find the best Mexican food by webscraping Zomato.com for every review of Mexican restaurants I could find.

I was able to scrape about 6,700 reviews. Unfortunately, I found that almost 3,500 reviews did not have numerical review scores. Instead, as a result of Zomato purchasing Urbanspoon.com in 2015, these review ratings consisted of a sentiment, positive or negative. Zomato encourages former Urbanspoon users to update their reviews to reflect a numerical score, but this doesn't appear to be happening. 

I think this is a big deal for Zomato. While they almost certainly utilise the data from the sentiment reviews already, the sentiment isn't factored into a restaurant's rating. That said, I found that there was a substantial difference in a restaurant's score on Zomato, and the score derived by the average of all review scores. 

The below plots conveys a lot of information to this point. 
- Each 'bubble' is a restaurant, and the size of the bubbles is determined by how many reviews there are. 
- The first plot score corresponds to Zomato's score for the restaurant, and generates size utilising all reviews (regardless of if the review score is numerical or sentimental). 
- The second plot score corresponds to the average of review scores for each restaurant, and determines size based on how many numerical review scores each restaurant had.
- The color of each bubble is consistent across plots and restaurants, and bubble movement demonstrates changes in score.

![Image](https://raw.githubusercontent.com/SeanTurner026/Zomato-and-Melbourne-Mexican-Restaurants/master/Images/subplots1.png)

Interestingly, the first plot (Zomato score) has a trend where higher ratings are generally associated with more expensive restaurants.  

Given that I still had 2,500 reviews which had text, I decided to try and make use of the Urbanspoon reviews, of which there are thousands do not contribute.



You can use the [editor on GitHub](https://github.com/SeanTurner026/Zomato-and-Melbourne-Mexican-Restaurants/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SeanTurner026/Zomato-and-Melbourne-Mexican-Restaurants/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
