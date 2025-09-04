## Day 1 ---   09/02/25
### Tiffany

Created new branches to work on different parts of the site without disturbing main (i.e, "components", "pages") - be sure to keep main as a working file.  Main should never be broken and a deployment only comes from main and no other branch.

```python

git switch –c <name of branch>
```
The file was created using a winesapi file from the 4th day of week 21.  This had the backend set up with all the containers and db. It also had a rough front end. 

I played around with styling.  Changed the titel and color of the background which is in index.css.

I added .jpg of some cat paws to the home page.  I had to add the .jpg to the assets folder and then created an image on the app.jsx. # I may change this to the home page and refer to the homepage from app.jsx.



## Day 2 --- 09/03/25

### GMO

Created a new branch called "components" and will create others for "pages" and what ever is needed.

Watching video from week 20 day 1 Tiffany - React Router Review.  This talks about bootstrap router.

In main.jsx changed "strict mode" to "broswerRouter" after importing: 
```python
import {browserRouter as Router} from 'react-router-dom'
```
This wraps "APP" in browserRouter.  There should not be other changes to main.jsx at this point.

Breaks when changed to browserRounter but now make changes to app.jsx

Created a file called NavBar in components and will call on it in app.jsx




























