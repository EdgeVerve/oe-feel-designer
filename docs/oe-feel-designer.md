# ***OE Component Manager***

It is a plugin for oe-studio that helps to create and manage ui related components.
Here is the Landing Page.

![Component Management](/images/landing_page.png)

## ***Component Creation***
Click on `Create/Manage Components` which will show the existing list of components and new components can be created by clicking on `Add Component` button on top right of the list screen.

![Component Management](/images/create_component_page.png)

Give a name for the page, search the model which will be associated with the component/form.
Here in the below example `Address` model is used and the page name is `my-addr`.

![Component Management](/images/create_component_with_model_page.png)

Click on `NEXT` button to choose a template.
Select a template from the available list of templates.

![Component Management](/images/choose_template_for_cpmponent_page.png)

Click on save to create a component/form.
The form that we created above using Address model looks like below image.

![Component Management](/images/component_page.png)

***Note :*** A component can be created without associating a model to it.The default page will contain blank screen instead of showing all the properties associated with the model and one needs to add fields to it manually.

### ***Field Addition***

A new field can be added to the form/page.On the bottom right corner of the screen there is a text box where the new field's Id or name can be specified.

![Component Management](/images/add_field_page.png)

Click on `+screen` button next to the text field will add it to the screen which will open a editor specific to the field just added.
Change the `Label` at the top of the editor and click on `Apply` to add the field to the form.

![Component Management](/images/add_field_save_page.png)

The new form will look like below image with the new added field.

![Component Management](/images/saved_form_page.png)

To add a field to the existing model's schema enter the field's name/Id just like above case and instead of `+screen`, press `+model`.

![Component Management](/images/add_new_model_property.png)

This will open the model creation dialog which can be filled up with required data and saved to update the model schema.

![Component Management](/images/add_new_model_property_save_page.png)

Click on `SAVE` button to save the new schema.

***Note :*** To add a field/property to a model, `oe-model-manager` is required.

### ***Field Operations***

Once we select(click) any field present on the form a editor opens on the right hand side of the screen.
This editor can be used carry certain operations on the field like changing the label, container, UIType, etc.
Click on `Apply` button so that the changes will reflect on the screen and click on the save button to persist the changes.

![Component Management](/images/field_operations_page.png)

Here in the above image we have selected property/field `Line1` then on the property editor we changed the Label to `Street One`(check on top of the screen).Then click on `Apply` button so that the changes will reflect on the screen and then just below it is the `Save` button(marked just below the `Apply` button in the image) click on it to make changes persist.

![Component Management](/images/field_operations_saved_page.png)

The order of the fields can be altered by dragging them in the right hand side editor shown in the below image.After carrying out those operations click on the `Save` button present at the bottom panel of the screen(already explained above)

![Component Management](/images/field_order_page.png)

There are redo and undo options to redo or undo the operations carried on the form/page.

![Component Management](/images/redo_undo_field_operations_page.png)

### ***Add route to form or page***

The form that we created above can be assigned a route.Click on the settings button highlighted in the below image to open a dialog which takes the route definitions.
Fill in the route definitions and click on `SAVE` button to save the route.

![Component Management](/images/add_route_to_form_page.png)

