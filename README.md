# cli-productivity
Everything To Have CLI-based Productivity Workstation In An Office

# Goals
Every user should have the ability to be the most productive, in the environment of their choice.  Often times, the CLI is lacking in this regard, as some believe nobody uses that anymore.

I say to this,"NO MORE!", and am documenting what tools I use to have a producivity workstation, that can be ran solely from the CLI, X Windows optional.

# Scripts
In this repo will also be a set of "glue scripts" and config files that work well.

# Email
Email client of my choice is Alpine Mail.  However, more might be interested in Mutt, as it can also handle the calendaring aspect present in many groupware solutions.

# Chat
The very popular suite,"Pidgin", has a lesser-known cousin named "Finch".  Curses-based, and experimental mouse support.

# Calendar
I prefer calcurse, although some prefer khal.  I couldn't get khal to work, personally.  Newer versions of calcurse include calcurse-caldav, which allows for integration with caldav servers (Like Zimbra).

# Browser
Well, the browser is...  Sad.  Links2 offers a graphical option, which can use the framebuffer.  However, most websites are broken, as they were not designed for keyboard-based interaction.

So, you can settle for minimal web use, which is almost a non-starter these days, or you can configure xinit to launch your browser of choice, full screen.  One benefit to this, is when you kill the browser, X shuts down, saving resources on your machine.
