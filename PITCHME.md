<a target="_blank" href="https://www.makeschool.com/"><img src="logo-grey.png" width = "25%" align="left"></a>
<br><br>
# Linked List
- what is a list “array” and what it's types?
- why do we need a _Linked one?_

---
@title[Add A Little Imagination]
@snap[north-west span-50 text-center]
#### Outcomes
@snapend

@snap[west span-55]
@ul[list-hide-fragments text-07]
By the end of class, students will be able to:
- Compare and contrast between Array (List) vs. Linked List.
- Differentiate between Static Arrays (Lists), Dynamic Arrays (Lists).
- Understand Memory allocation, Linked List is not contiguous.
@ulend
@snapend

@snap[east span-45]
![IMAGE](assets/img/conference.png)
@snapend

---
@title[Add A Little Imagination]
@snap[north-west span-50 text-center]
#### Outcomes
@snapend

@snap[west span-55]
@ul[list-spaced-bullets text-09]
- Write and apply Linked List main functions.
- Explain what the Big-O benefits in some methods compared to the arrays.
- Explain the differences only from Singly vs. Doubly linked List (Not the code for the doubly) this will be in the next sessions. 
@ulend
@snapend

---
### Teacher Talk
![IMAGE](assets/img/presentation.png)

---?color=linear-gradient(180deg, white 75%, black 25%)
@title[Customize Slide Layout]

@snap[west span-55]
## Customize the Layout
@snapend

@snap[north-east span-45]
![IMAGE](assets/img/presentation.png)
@snapend

@snap[south span-100]
Snap Layouts let you create custom slide designs directly within your markdown.
@snapend
---
@snap[north-east span-100 text-pink text-06]
Let your code do the talking!
@snapend

```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend


---?image=assets/img/code.jpg&opacity=60&position=left&size=45% 100%

@snap[east span-50 text-center]
## Now It's **Your** Turn
@snapend

@snap[south-east span-50 text-center text-06]
[Download GitPitch Desktop @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend

