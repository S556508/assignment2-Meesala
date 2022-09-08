# assignment2-Meesala
# AdiLakshmi Meesala 

###### National Museum Delhi 

The National Museum in New Delhi, also known as the **National Museum**, of India, is one of the largest museums in India. **Established in 1949**, it holds a variety of articles ranging from pre-historic era to modern works of art.

------

# The way to Airport to Museum

# step by step directions for traveling to the museum from the airport
1. Head west toward T3 Arrival Rd
2. Continue onto T3 Arrival Rd
3. Continue onto Indira Gandhi International T3 Rd
4. Continue onto IGI Rd/Northern Access Rd
5. Turn left Destination will be on the right

# Other locations directions around the museum

- Keep right at the fork and merge onto NH 48
- Take the exit
- Keep right at the fork
- Slight left after Pillar Number LLP10
- Turn Right Destination will be on the right

*[About me](AboutMe.md)*

---
# Tables
The below table gives the information on the name of a city, important location to visit in the city and the amount of time to spend visiting the important location  

| City Name | Location | Time|
|--- |--- |--- |
| Agra | Taj Mahal | 5 hours |
| Delhi | Red Fort | 3 hours |
| Amritsar | Sri Harmandir Sahib | 6 hours |
| Mysuru | Mysore Palace | 8 hours |

---

# Pithy Quotes
> Start before you’re ready

*Steven Pressfield*

> Difficulties mastered are opportunities won

*Winston Churchill*

---
# Code Fencing
> String replace in Sass

[String replace in Sass](https://stackoverflow.com/questions/12728634/string-replace-in-sass)

```
@function str-replace($string, $search, $replace: '') {
  $index: str-index($string, $search);
  
  @if $index {
    @return str-slice($string, 1, $index - 1) + $replace + 
    str-replace(str-slice($string, $index + str-length($search)), $search, $replace);
  }
  
  @return $string;
}
```

[Str-replace Function](https://css-tricks.com/snippets/sass/str-replace-function/)