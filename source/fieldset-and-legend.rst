Fieldset and legend
===================

When to use a fieldset and legend
---------------------------------

**You should use the <fieldset> and <legend> elements when:**

* You have a single multiple choice question (using radio buttons or checkboxes).
* You have several questions relating to the same topic (like text boxes, or any other type of field).

When not to use a fieldset and legend

**You should not use the <fieldset> and <legend> when:**

* You have a single form field that asks for a single piece of information.
* When used correctly, the <fieldset> and <legend> elements tie related form fields together in a way that is accessible to people who cannot see the visual layout of the form.


https://accessibility.blog.gov.uk/2016/07/22/using-the-fieldset-and-legend-elements/

https://govuk-elements.herokuapp.com/form-elements/

.. code-block:: html

  <div class="form-group">
    <fieldset>
      <legend>
        <h3 class="heading-medium">Which types of waste do you transport regularly?</h3>
        <span class="body-text">Select all that apply</span>
      </legend>
      ...
    </fieldset>
  </div>


