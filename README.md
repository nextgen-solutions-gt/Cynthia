## Cynthia Style for phpBB 3.1.x

The Cynthia style is a simple and pleasant style, also has an easy to use interface.
It has corrected several bugs that were reported in version 1.0.1, have been implemented large improvements among which we highlight.

It has integrated full FontAwesome icons here theme where they explain their implementation [Utilize Font Awesome icons where icons are needed to simplify server requests] (http://area51.phpbb.com/phpBB/viewtopic.php?f=81&t=45671)

There are 2 separate logos to the main header.

The design has been improved, is simpler and more professional.

RTL support for people who use languages Arabic, Persian, etc.

#### Customise

FontAwesome icons are defined by using their unicode values, like `\f004`. You can add your own rules for your own icons, or change the existing codes. The quickest way to find the unicodes you need is to use the [FontAwesome cheatsheet] (http://fontawesome.io/cheatsheet/). You need to copy the last 4 characters of the code string after the icon you want, and prefix it with a `\`. So "home" is `\f015`.

You can use this method to add icons to just about every element. A commonly used example is for the phpBB Pages extension, when you want to assign icons to your page links (in the header/footer/etc). Add the following code to your `colours.css` file:
````
.small-icon.icon-page-xxx > a:before { content: '\f0ac'; }
````
Change the `xxx` to the "route" of your custom page

## Style Support

If you have questions or need help you can visit my official site [Melvin Garcia] (http://www.melvingarcia.com/).

### Credits

The integration of the Font Awesome, is thanks to [PayBas] (https://github.com/PayBas/).
