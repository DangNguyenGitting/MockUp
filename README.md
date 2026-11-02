Assignment 6

Palette:
Page Background: Cream - #FCF8F3
Page Placeholders (Elements) - #D9D9D9
Footer and Buttons - #3A3639
Text Color: #2A2A2A
Icon Inside Color: #766A5B
Icon Outline / Node Color and Footer Text: #FFEBF3

Type Sizing: 
Loren Ipsum Filler Body: 10 px
Contact Header: 10 px
Slogan Text: 15 px
Header 2 (Our Story, Bestsellers,and Seasonal): 20 px
Image Subtext: 11 px

Spacing:
Carousel Repeating Spaces: 12 px
Margins All Around Page: 8 px
Section Spacing: About 20 px on average
Card Width for Carousel: 138 px
Card Height: 121 px

Sections of Mock-Up:
1. Header
2. Main
    - Seasonal Section
    - Bestsellers
3. Footer

Regions: I kept it basic with the three essentials.
    - Header
    - Main
    - Footer

Gallery minmax choice: I chose minmax(130, 1fr)
1. This is because the original mock-up was for a Phone 15, and each card was identified as 138 px (W) x 121 px (H) with gap sizing of 12 px.
2. 200 px displayed not enough cards so I lowered it to 130.
3. Columns:
    Max Width: 3
    Half Width: 3
    Lowest: 3

Mock Up:
[Image of Original Mock-Up](images/MockUp.png)

Primary Changes / Differences:
1. The logos for the icons were a bit inconvinient to add and would require additional content such as the OCN. I thought it a bit annoying - so I opted to use type face for it instead.
2. The sandwich menu was not exactly the most accurate version as I opted to use an image screenshot (and of course it is not animated either). 

I built the page mobile-first, so it starts as one column and gets more columns as the screen gets wider. I found each breakpoint by dragging the browser wider and writing down where the layout stopped looking good.

- 430px - gallery goes from 1 to 2 columns.** At this width the single-column cards were the worst-looking part of the page. Each card was about 414px wide, which is too big for one image on a phone. With two columns the cards are about 200px wide and fit better.
- 530px - story goes from 1 to 2 columns.** Around this width the video stacked on top of the text started to look off. Putting the video and text side by side fixes it. Each side is about 250px wide.
- 700px - gallery goes from 2 to 3 columns.** I checked 699px and 700px. At 700px the three cards are about 220px wide and look balanced. The Featured Arrangements row also switches to two columns here so it has a wide spot and a narrow spot.

Tested at 800px wide. “Signature Bouquet” (slot about 500px) showed a 4:3 image and a larger caption. “Seasonal Pick” (slot about 250px) stayed square with the smaller caption. Same card code, different results, so each card responds to its own space.