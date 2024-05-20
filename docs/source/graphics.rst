Graphics
========

LimeOS provides a API for creating Graphical Objects.

You can create a new window using:

.. code-block:: luau

   local Win = CreateWin(WindowName, IconID) -- IconID is optional.

You can add a UI Element to your window using:

.. code-block:: luau

   local UIElement = CreateUI(Win, ElementName)

Some valid ElementNames are: TextLabel, TextButton, ImageLabel, etc.
Example: Hello world GUI application.
-------------------------------------

.. code-block:: luau

   local Win = CreateWin("Hello world")
   local UIElement = CreateUI(Win, "TextLabel")
   UIElement.Size = UDim2.fromScale(1,1)
   UIElement.Text = "Hello, World!"
