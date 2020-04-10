# Pop-up-window-in-RShiny
How to create easily create pretty popup messages (modals) in RShiny

## Overview:
A brand new shiny package has entered the world: shinyalert. It does only one thing, but does it well: show a message to the user in a modal (aka popup, dialog, or alert box). Actually, it can do one more thing: shinyalert can also be used to retrieve an input value from the user using a modal.

## Use:
shinyalert uses the sweetalert JavaScript library to create simple and elegant modals in Shiny. Modals can contain text, images, OK/Cancel buttons, an input to get a response from the user, and many more customizable options. A modal can also have a timer to close automatically.

Simply call shinyalert() with the desired arguments, such as a title and text, and a modal will show up. In order to be able to call shinyalert() in a Shiny app, you must first call useShinyalert() anywhere in the app’s UI.
