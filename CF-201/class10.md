# Debugging

## What went wrong? Troubleshooting JavaScript

From:[What went wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

Generally speaking, when you do something wrong in code, there are two main types of error that you'll come across:

Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!
Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

- Name some key differences between a Syntax Error and a Logic Error.

Syntax usually involves spelling or punctuation issues and usually provide an error message. Logic errors are when the code is writen correctly.

- List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

I had made variables intened to be the same variable but i had strung together slightly different wording in camel case. Another time I had forgotten a few semicolons and the code wasn't running properly.

- How will this topic continue to influence your long term goals?

I want to get better at stopping error before they happen by naming variables consistanty and checking syntax punctuation.

## What are browser developer tools?

From: [What are browser developer tools?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools#the_javascript_debugger)

macOS: ⌘ + ⌥ + I

The developer tools usually open by default to the inspector, which looks something like the following screenshot. This tool shows what the HTML on your page looks like at runtime, as well as what CSS is applied to each element on the page. It also allows you to instantly modify the HTML and CSS and see the results of your changes reflected live in the browser viewport.

The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.

The Call stack section shows you what code was executed to get to the current line. You can see that the code is in the function that handles a mouse click, and that the code is currently paused on the breakpoint.

- How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

It is similar to spellcheck in word edditors.

- Define what a breakpoint is.

It is a point in the debugger that you decide for code to stop running. This would be used to check if your code is working up to a certain point.

- What is the call stack?

It it the code that is being involved with a certain line. You can use it to see all the code that is involved with a click.

## Bookmark and Review

From: [Debugging HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)

From: [Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)
