
##👋🏽 Hey y'all, I'm Harnish! Since 2016, I've been living and breathing design. As of now, out here coding modern user interfaces and helping to make this world a little better through design & code [@Codegrid](https://www.youtube.com/codegrid)

```javascript
import { Harnish, Bio } from "portfolio"

class AboutMe extends Harnish.Bio {
  const getDailyKnowledge = () => {
    return (
		[
		    id: 1, name: 'SCSS',
		    id: 2, name: 'JavaScript',
		    id: 3, name: 'React',
		    id: 4, name: 'GSAP'
		 ]
	   )
     }

    render (
      return (
	 <div>
	    {getDailyKnowledge().map(item => {
		return(
		  {item.id} {item.name}
		)
	    })}
	 </div>
	)
    )
}

export default AboutMe
```
