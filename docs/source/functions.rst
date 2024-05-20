List of LimeOS unique functions
===============================

This doc contains a list of functions unique to LimeOS and their usage.

.. code-block:: luau

  local Service = GetService(ServiceName)

This function returns a Luau service if a valid Luau service name is provided.

.. code-block:: luau

  local Win = CreateWin(WindowName, IconID) -- IconID is optional.

This function returns a Window object, named WindowName and with the icon provided by IconID, with a default icon of a question mark.

.. code-block:: luau

  local UIElement = CreateUI(Parent, ElementName)

This function returns a UI object, with a type of ElementName, and with a parent of Parent.
