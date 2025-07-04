# Introduction to HTML

## Lecture 10
- Updates

## Lecture 11
- **HTML**: Hyper Text Markup Language
  - **HT**: *hyper text* are text which guides to new page after they are clicked; used to link multiple web pages in a website 
  - **ML**: *markup language* is used by scripting content into tags in place of quotation marks

## Lecture 12
- Course Resources

## Lectures 13
- **Heading Element**
> - \<h1>Heading 01\</h1>
> - \<h2>Heading 01\</h2>
> - \<h3>Heading 06\</h3>
> - \<h4>Heading 01\</h4>
> - \<h5>Heading 06\</h5>
> - \<h6>Heading 06\</h6>
- **Tags**: text inside anchor brackets are called tags, i.e. opening tag \<tag>, closing tag \</tag>, self-closing or empty tag \<tag />
-  **Element**: entire syntax containing opening tag, content, closing tag is called element, i.e. \<tag> Content \</tag>
- Used for section heading
- Hierarchies is available
- Use only one h1, don't skip levels, do not use heading elements to resize text
### Exercise 01
> <img src="./Ex.01_Heading-Element/assets/images/goal.png">
<big>Solution:</big>
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ex.01: Heading Element</title>
</head>
<body>
  <h1>Book</h1>
  <h2>Chapter 1</h2>
    <h3>Section 1</h3>
    <h3>Section 2</h3>
  <h2>Chapter 2</h2>
    <h3>Section 1</h3>
      <h4>Diagram 1</h4>
  <h2>Chapter 3</h2>
    <h3>Section 1</h3>
    <h3>Section 2</h3>
</body>
</html>
```

## Lecture 14
- **Paragraph Element**
> - \<p>Paragraph 01\</p>
> - \<p>Paragraph 02\</p>
- Used to group text in code
- Lorem Ipsum
### Exercise 02
> <img src="./Ex.02_Paragraph-Element/assets/goal.png">
<big>Solution:</big>
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ex.02: Paragraph Element</title>
</head>
<body>
    <p>First paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
    aliqua. Arcu cursus vitae congue mauris. In nisl nisi scelerisque eu ultrices vitae auctor eu augue. Nisi est sit amet
    facilisis magna. Diam sit amet nisl suscipit adipiscing bibendum est ultricies integer. Quis ipsum suspendisse ultrices
    gravida dictum fusce ut. Euismod elementum nisi quis eleifend. Habitant morbi tristique senectus et. Amet nisl suscipit
    adipiscing bibendum est ultricies integer. Viverra orci sagittis eu volutpat odio facilisis mauris sit. Nisi quis
    eleifend quam adipiscing. Neque convallis a cras semper auctor neque vitae. Magna fermentum iaculis eu non. Vivamus arcu
    felis bibendum ut tristique et. Justo nec ultrices dui sapien eget mi. In vitae turpis massa sed elementum tempus. Eu
    facilisis sed odio morbi quis commodo. Sagittis aliquam malesuada bibendum arcu vitae elementum curabitur vitae.</p>
    <p>Second paragraph. Suscipit adipiscing bibendum est ultricies. Tortor aliquam nulla facilisi cras fermentum. Eget aliquet nibh praesent
    tristique magna. In hac habitasse platea dictumst vestibulum. Ornare quam viverra orci sagittis eu. Sit amet est
    placerat in. Proin fermentum leo vel orci porta non pulvinar neque laoreet. Turpis in eu mi bibendum neque egestas
    congue. Enim eu turpis egestas pretium aenean pharetra magna ac placerat. Ultrices sagittis orci a scelerisque purus
    semper eget duis at. Egestas egestas fringilla phasellus faucibus scelerisque eleifend donec pretium. Condimentum
    lacinia quis vel eros donec ac odio.</p>
    <p>Third paragraph. Nisl purus in mollis nunc sed id semper risus. Ipsum a arcu cursus vitae congue mauris rhoncus aenean. Ridiculus mus
    mauris vitae ultricies leo integer malesuada nunc. In tellus integer feugiat scelerisque. Lectus mauris ultrices eros in
    cursus turpis massa. Sollicitudin ac orci phasellus egestas. Massa massa ultricies mi quis hendrerit dolor. Quam
    elementum pulvinar etiam non quam lacus suspendisse faucibus interdum. Iaculis nunc sed augue lacus viverra. Id ornare
    arcu odio ut sem nulla pharetra. Amet luctus venenatis lectus magna fringilla urna porttitor. Eu nisl nunc mi ipsum
    faucibus vitae aliquet nec ullamcorper. Nunc mattis enim ut tellus elementum sagittis. Mauris augue neque gravida in
    fermentum et sollicitudin. Pellentesque habitant morbi tristique senectus. Tristique senectus et netus et. Turpis
    egestas sed tempus urna et pharetra pharetra. Feugiat vivamus at augue eget arcu dictum varius duis at. Lacus sed
    viverra tellus in hac habitasse platea dictumst vestibulum. Nisl condimentum id venenatis a condimentum vitae sapien.</p>
</body>
</html>
```

## Lecture 15
- **Void Element**
- Elements with no content and consisting of only single tag
- Horizontal Rule: Adds a horizontal line
> - \<hr>
- Break Rule: Adds a break rule, shifts content on new line
> - \<br>
- **[Difference Checker](diffchecker.com)**: Used to compare two contents
- Don't use break elements for new paragraph instead use seperate paragraph elements
### Exercise 03
> <img src="./Ex.03_Self-Closing-Tags/assets/goal.png">
<big>Solution:</big>
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ex.03: Self-Closing-Tags</title>
</head>
<body>
    <h1>William Blake</h1>
    <p>17 south molton street <br>
    London <br>
    W1K 5QT <br>
    UK <br></p>
    <hr>
    <p>William Blake (28 November 1757 – 12 August 1827) was an English poet, painter, and printmaker. Largely unrecognised
    during his life, Blake is now considered a seminal figure in the history of the poetry and visual art of the Romantic
    Age. What he called his "prophetic works" were said by 20th-century critic Northrop Frye to form "what is in proportion
    to its merits the least read body of poetry in the English language".[2] His visual artistry led 21st-century critic
    Jonathan Jones to proclaim him "far and away the greatest artist Britain has ever produced".[3] In 2002, Blake was
    placed at number 38 in the BBC's poll of the 100 Greatest Britons.[4] While he lived in London his entire life, except
    for three years spent in Felpham,[5] he produced a diverse and symbolically rich collection of works, which embraced the
    imagination as "the body of God"[6] or "human existence itself".[7]</p>
    <p>Although Blake was considered mad by contemporaries for his idiosyncratic views, he is held in high regard by later
    critics for his expressiveness and creativity, and for the philosophical and mystical undercurrents within his work. His
    paintings and poetry have been characterised as part of the Romantic movement and as "Pre-Romantic".[8] In fact, he has
    been said to be "a key early proponent of both Romanticism and Nationalism".[9] A committed Christian who was hostile to
    the Church of England (indeed, to almost all forms of organised religion), Blake was influenced by the ideals and
    ambitions of the French and American revolutions.[10][11] Though later he rejected many of these political beliefs, he
    maintained an amiable relationship with the political activist Thomas Paine; he was also influenced by thinkers such as
    Emanuel Swedenborg.[12] Despite these known influences, the singularity of Blake's work makes him difficult to classify.
    The 19th-century scholar William Michael Rossetti characterised him as a "glorious luminary",[13] and "a man not
    forestalled by predecessors, nor to be classed with contemporaries, nor to be replaced by known or readily surmisable
    successors".[14]</p>
</body>
</html>
```

## Lecture 16
- **[Favourite Movie Project](https://dhruv-janakala.github.io/movie-ranking-project/)**
- List of recommended movies based on my interest.
> - Elements contained:
> \<h1>, \<h2>, \<h3> \<br>, \<hr>, \<p>

## Lecture 17
- Course Guidance
