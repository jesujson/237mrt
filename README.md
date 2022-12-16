<h1 align="center"> Herkese Merhaba, Ben Jesus</h1>


```js
import { life } from "world"

life.findOne({people: "237mrt"}, async(err, res) => {
    if(err) return console.error(err)

    
        
    if(res) return res
    else{

        const config = {
            languages:["JavaScript", "C#", "Python", "Php"],
            extra:["NodeJs", "React", "Tailwind", "Boostrap"]
        }

        const addPeople = new life({
            name:"Mert",
            age:18,
            languages: config.languages,
            extra: config.extra
        })
        addPeople.save().catch(err => { console.error(err) })
    }

})
```
