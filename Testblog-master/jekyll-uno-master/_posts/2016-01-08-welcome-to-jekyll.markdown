---
title:  "Welcome to Jekyll!"
date:   2016-01-08 15:04:23
categories: [jekyll]
tags: [jekyll]
---
In the last chapter of Parameterization in Cucumber, we learned how to parameterize data. But with that trick only limited functionality can be achieved of Data Driven. As the test can be run multiple times. But by now that you know the anatomy of a Data-Driven test, here’s a trick that simplifies the process of Data Driven testing using Cucumber. Cucumber inherently supports Data Driven testing by the use of the Scenario Outline and Examples section. It is with these keywords that Cucumber allows for easy Data Driven testing to be completed where no changes need to be made to the Java file. In this tutorial we learn, How to Implement Scenario Outline in Data Driven testing using Examples Keyword?

Example keyword can only be used with the Scenario Outline Keyword.

Scenario Outline – This is used to run the same scenario for 2 or more different set of test data. E.g. In our scenario, if you want to register another user you can data drive the same scenario twice.
Examples – All scenario outlines have to be followed with the Examples section. This contains the data that has to be passed on to the scenario.
To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

``` ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
