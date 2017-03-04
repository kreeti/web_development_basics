## Development Enviornment
* Use Linux enviornment.
* Use emacs / atom / sublime as editor.
* Install RVM.
* Install latest version of Ruby.
* Use project specific gemset.

## HTML & CSS project
* The look and feel of the web page should be responsive and as per the UI provided by us.
You can use the Responsive Design View available in major browsers (Firefox in particular).

* Bootstrap framework should be used for the layout and styling.
* HTML and CSS should be written manually and not with the help of some editor or code generator.
* HTML and CSS should be valid.
  To check the validation you can use:
   * HTML - https://validator.w3.org/
   * CSS - https://jigsaw.w3.org/css-validator/
* HTML and CSS should be semantic and properly indented.
* No inline styles should be used.

## Rails project

* Try to follow DRY - Din't Repeat Yourself.
* Convention over Configuration.
* Follow Two space indentation, no tabs.
* Use boolean tests: don't use "and" and "or", always use "&&" and "||"
* If anything is obvious - don't explain it.
* Remove old commented code.
* All variables and function names are "Snake Case" (lowercase_words_seperated_by_underscore)
* All Class Names are Camel Case: ClassName
* All constants should be like ALL_UPPERCASE = true
* Avoid negated conditions
```
while ! @printer.ready?
  ..
end

# More ideomatic way

until @printer.ready?
  ..
end

```
* Use each, NOT for
```
colors = ['green', 'red', 'blue']

# don't do this
for color in colors
  puts color
end

# use each
colors.each do |color|
 puts color
end

```

* Follow Ruby convention
```
@user.name = '' unless @user.name.nil?

# The Ruby way
@user.name ||= ''

```

## <a href="https://github.com/kreeti/coding_convention">Coding Convention</a>
