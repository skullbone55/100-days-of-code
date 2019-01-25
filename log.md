# 100 Days Of Code - Log

### Day 1: January 21, 2019

**Today's Progress**: Environment setup (VS 2017). Initial commit of web app. Progressed in MVC tutorial and initial commit.

**Thoughts:** Day number one.  I have high hopes for this challenge.  I am excited and a little nervous.  I overestimated what I actually knew about ASP.NET.  I can recall the terminology, but I'm a bit lost of where to begin.  I've decided to take a couple days to refresh my memory with tutorials.

**Link to work:** <br> 
[MealPlanner](https://github.com/delsuckahh/meal-planner)<br>
[MvcMovie](https://github.com/delsuckahh/MvcMovie)

### Day 2: January 22, 2019

**Today's Progress**: Followed along Microsoft's MVC tutorial and finished up two sections.

**Thoughts:** Today was a good day.  I determined what my "problem" was yesterday; I can read and understand c# just fine, I just don't quite understand the MVC model yet.  I made really good progress in understanding the relationship between Models, Views, and Controllers today.  I spent some time throughout the day passively reading documentation about MVC.  Then tonight, during my allotted coding time, I spent time in the interactive tutorial my Microsoft.  I'm still not sure about the async/await keywords and what EXACTLY they do.  I did think this was really cool, though:
```
@{
    ViewData["Title"] = "Welcome";
}

<h2>Welcome</h2>

<ul>
    @for (int i = 0; i < (int)ViewData["NumTimes"]; i++)
    {
        <li>@ViewData["Message"]</li>
    }
</ul>
```
Combining HTML and some actual programming is pretty saucy.

**Link to work:** <br> 
[MvcMovie](https://github.com/delsuckahh/MvcMovie)<br>
[Microsoft Tutorial](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/adding-view?view=aspnetcore-2.1&tabs=visual-studio)

### Day 3: January 23, 2019

**Today's Progress**: Continued with Microsoft's MVC tutorial, finished one more section. 

**Thoughts:** I did a LOT of reading today.  I spent some time throughout the day finishing up the tutorial at TutorialsPoint, which gave a good overview of the interacting pieces of ASP.NET.  I went off a bit of a tangent from the Microsoft Tutorial and read up on Async/Await.  The documentation I've been reading hasn't covered that in detail even though it's present in the code.  I feel pretty comfortable with that terminology now, and I'm on track to finish the tutorial by the end of the week.  I've got high hopes and ambitions for my web app idea of a meal planner, so I'll be excited to get started on that here soon.

**Link to work:** <br>
[MvcMovie](https://github.com/delsuckahh/MvcMovie/tree/master/MvcMovie)<br>
[Microsoft Tutorial](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/adding-view?view=aspnetcore-2.1&tabs=visual-studio)<br>
[TutorialsPoint](https://www.tutorialspoint.com/asp.net/)

### Day 4: January 24, 2019

**Today's Progress**: Finished up Microsoft's MVC tutorial. 

**Thoughts:** Another reading/tutorial heavy day.  I can already see the benefit in going through the tutorials; I was even able to use what I've learned so far at work today.  An application that we support uses .NET and Oracle, and I was able to follow along and help a co-worker (shoutout to my boi Sposi) debug an issue today.  I was able to identify and understand lambda functions, async/await calls, and the interactions between models, views, and controllers.  I didn't spend quite an hour this evening in tutorials.  I finished a bit early, but since my next step is to actually start on my project, I'm going to wait until tomorrow so I can dedicate more uninterrupted time towards it.  Tomorrow I hope to progress in creating a login for my webapp using the SQL Server functionality built in the ASP.NET framework.  

**Link to work:** <br>
[MvcMovie](https://github.com/delsuckahh/MvcMovie/tree/master/MvcMovie)<br>
[Microsoft Tutorial](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/adding-view?view=aspnetcore-2.1&tabs=visual-studio)<br>
