# gui_maker_gui
GUI Builder

This is a simple Python script that allows you to build a graphical user interface (GUI) using PySimpleGUI. The script provides a simple interface for choosing different types of GUI elements, such as buttons and input fields, and then customizing the appearance and behavior of those elements.
Usage

To use this script, simply run the main() function in the script file using Python. This will launch a GUI window that allows you to select and customize different GUI elements.

To add a new GUI element, click the "Add Element" button and select the type of element you want to add from the dropdown menu. This will bring up a new window where you can customize the appearance and behavior of the element.

Once you have added all the elements you want, click the "Create Layout" button to generate a preview of your custom GUI. You can then further customize or finalize the layout by clicking the "finalize" button.
Supported Elements

The following GUI elements are currently supported by this script:

    Button
    InputText
    Checkbox

To add support for more elements, you can modify the create_element_by_type() function in the script.
Customization

You can customize the appearance and behavior of each GUI element by filling out the settings in the element's configuration window. Each element type has its own unique settings, which are listed in the get_desc() function in the script.

If you want to modify the behavior of the GUI builder itself, you can modify the main() function in the script. For example, you could add additional buttons or change the layout of the GUI.
Dependencies

This script requires the PySimpleGUI library to be installed. You can install PySimpleGUI using pip:

pip install PySimpleGUI
