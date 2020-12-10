# Scraping College Reviews
 Scraped websites to collect reviews of colleges in India 

Initial part involved scraping links of individual college review pages from collegedunia.com/reviews\
I Scraped 25000 links and dumped them into all_review_links.txt -> can be scaled to get all 2 lakh reviews on the website

Scraped these links to get college name, course name, and reviews. Reviews were split into 14 columns based on their sub-headings:
```
LOAN/ SCHOLARSHIP PROVISIONS
PLACEMENT WING
COURSE CURRICULUM OVERVIEW
INTERVIEW EXPERIENCE
ADMISSION
HOSTEL FACILITIES
CAMPUS LIFE
REMARKS
INTERNSHIPS OPPORTUNITIES
ALUMNI
FACULTY
FEE STRUCTURE AND FACILITIES
ENTRANCE PREVIEW 
COLLEGE EVENTS 
```

The data scraped was organised in an excel sheet. The 1st column is college name. 2nd column is course name and subsequent columns are reviews broken down into 14 components mentioned above in the same order.