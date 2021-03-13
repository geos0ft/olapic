# olapic
Repository for Olapic assessment
1. First it was important understand what data the API returned.
2. Once the data set was returned then it was straight forward to understand how to drill down to the media array component. Our are of interest was under data -> _embedded -> media. The actual userable image could then be obtained under images -> normal for each media element.
3. To select the most appropriate image, the normal component needed to be chosen.
4. There was an issue with the code base in that the last line of the iteration loop was included along with closing parenthesis and this caused some confusion.
5. The width of the carousel was not sufficient to display all four images swas increase to max.
6. For the navigation arrows, the parameter was set to false by default so needed to be set to true. Also the arrows were located in the middle of the carousel to classes owl-prev and .owl-next of the DOM needed to be configured appropriately.