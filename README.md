## General Assembly Capstone Project

Ever since moving to Melbourne from New York, I have been keenly aware of the lack of good Mexican food in Melbourne. Overtime, this encouraged me to try and find the best Mexican food by webscraping Zomato.com for every review of Mexican restaurants I could find.

In the end, I was able to scrape about 6,700 reviews. Unfortunately, I found that almost 3,500 reviews did not have numerical review scores. Instead, as a result of Zomato purchasing Urbanspoon.com in 2015, these review ratings consisted of a sentiment, positive or negative. Zomato encourages former Urbanspoon users to update their sentiment reviews to reflect a numerical score, but this doesn't appear to be happening. 

While Zomato certainly utilises the data from the sentiment reviews already, the sentiment is not factored into a restaurant's rating. Given that over half of the reviews didn't have scores, this is substantial. Fortunately, there is an alternative: use machine learning techniques and existing data to predict the review scores for the sentiment reviews.

I began by using a bubble plot to examine the difference between a restaurant's score on Zomato, and the average of all review scores for a given restaurant. 
- Each 'bubble' is a restaurant, and the size of the bubbles is determined by how many reviews each restaurant has. 
- The scores on the first plot corresponds to Zomato's score for the restaurant, and determines bubble size by counting all reviews (numerical and sentimental) for each restaurant. 
- The scores on the second plot corresponds to the average of review scores for each restaurant, and determines bubble size by **only** counting the numerical reviews each restaurant had.
- The color of each bubble is consistent across plots and restaurants, and shows shifts in bubbles.

![Image](https://raw.githubusercontent.com/SeanTurner026/Zomato-and-Melbourne-Mexican-Restaurants/master/Images/subplots1.png)

Interestingly, the first plot (Zomato score) has a trend where higher ratings are generally associated with more expensive restaurants. Additionally, the colors show that some restaurants have a dramatically different score.  

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
