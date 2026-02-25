## The Story of Swift Select

This is not my first Add-In, but it is my first majorly useful add-in. Here is the story. 

It all started back around December 20th in 2025. Everyone getting ready for the holidays and then I see this reddit post of this genius making extraordinary art using just triangles in PowerPoint. I was amazed. I looked at the art and thought: "what if this user wanted to change the color of 200 of these triangles?" I knew using vba, that such a feat was possible but vba is not that easy to just jump into for everyone. Even if the code is provided, it can still be difficult to ensure it runs specifically for the user. It was at this point that Swift Select was actually considered.

It was a simple concept. Make an add-in that will select all the same shape type, the same color and allow users to select with a rectangle lasso. I could slam this little bugger out in a day. But it didn't take a day.. Oh no. As I started talking with real PowerPoint designers and a little online research I quickly realized that this add-in needed to be something truly useful and close the gap once and for all on the lack of selection tools with PowerPoint. 

I hit to reddit and showed the concept saying we need better selection tools. I was able to have some minimal conversation with some users including some really well known PowerPoint users. I took their feedback very seriously. I was even encouraged by another amazing developer to take a selection utility idea they made and to basically take it further. This type of support and motivation was all I needed to get started. 

Now most of this code was written from previous tools that I use for my cartoons but that was such a minimal help because I needed to make sure this add-in would help actual PowerPoint users. I left a good amount of those tools in it but teal users need things that matter t like font.  Font? So all that are bold or a different color. Font family, size? This became huge because I wanted the. User to be able to select any combination of font but also the ability to only have rectangles with that font and such. It took an extensive amount of architecture. More than I had ever coded in vba before. 

Fast forward to the time of writing this. The functions were all on the add-in but the thought of even adding anything else was so daunting and I was really not sure how I could get it to do everything. I completely restructured my code base that I had been writing for 2 months.  To be continued... 

The actual tool sets have changed so much and by the time it was all decided. Practically every shape property can be usd for selecting items. I had it all figured out now I just need to code it out. 

So while I could list every single hurdle that I encountered in the 3 months to build this I will not do that. Just know that I had to fit a lot of buttons on a small user form  

To be continued... I just continued to marvel at the art. I love making art in PowerPoint and recently started seeing all these artists. I had always thought that most would never consider using PowerPoint for such a task. I was wrong. There was a huge community out there of extremely talented users that like me, push PowerPoint beyond its limits. 

I had released my Point Map add-in and on the search for the next one to write. Swift Select was born. 

The original concept was simple. Select shapes by fill clp. 