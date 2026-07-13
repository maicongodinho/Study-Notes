# Lesson 009

**Title:** Schema Builder in Salesforce: How to add fields using Schema Builder?

## Notes

- Access **Schema Builder** via:
  - `Setup → Objects and Fields → Schema Builder`
- Schema Builder provides a visual interface for managing objects and fields.
- Use **Select From** to filter which objects are displayed (e.g., Custom Objects only).
- Enable **Display Element Names** to show API names (e.g., `Employee__c`).
- Enable **Show Relationships** to visualize relationships between objects.
- Show or hide the legend as needed.
- Zoom in/out and freely navigate around the canvas.
- Drag and drop field types from the **Elements** panel to create new fields.
- Not all Salesforce field types are available in Schema Builder.
- Use the object's **gear icon** to edit or delete the object.
- Right-click a field to:
  - Edit field properties.
  - Delete the field.
  - Manage Field-Level Security (FLS).
- Schema Builder is generally faster than Object Manager when creating multiple fields.
- Fields created in Schema Builder are **not automatically added** to the Page Layout.
- To display new fields:
  - `Setup → Object Manager → Employee → Page Layouts → Employee Detail`
- Page Layouts allow you to:
  - Add or remove fields.
  - Reorder fields.
  - Organize sections.
- Metadata changes (fields or layouts) may take a few moments to appear in the UI.

## Mock Questions

### Question 1

Cloud Kicks has a custom object called **Employee__c**. An administrator creates a new custom field using **Schema Builder**, but users cannot see the field when viewing Employee records.

What should the administrator do?

A. Refresh the browser until the field appears.

B. Add the field to the appropriate Page Layout.

C. Deploy the object using a Change Set.

D. Enable **Show Relationships** in Schema Builder.

**Correct Answer:** B

**Explanation:**

Schema Builder creates the field, but it does **not** automatically add it to the Page Layout. The administrator must manually place the field on the layout before users can see it.

---

### Question 2

A developer wants to review the relationships between several custom objects while documenting the application's data model.

Which Schema Builder feature should the developer enable?

A. Display Element Names

B. Show Relationships

C. Show Legend

D. Field History Tracking

**Correct Answer:** B

**Explanation:**

**Show Relationships** displays the links between related objects, making it easier to understand the data model.

---

### Question 3

Universal Containers plans to add 20 new custom fields to an existing custom object during a workshop.

Which approach is the most efficient?

A. Create every field from Object Manager individually.

B. Use Schema Builder and drag field types onto the object.

C. Export the metadata, edit the XML manually, and deploy it.

D. Clone the object and rename the cloned fields.

**Correct Answer:** B

**Explanation:**

Schema Builder provides a fast, visual drag-and-drop interface, making it the most efficient option for creating many fields.

---

### Question 4

A developer creates a custom field in Schema Builder and immediately opens an Employee record. The new field is not visible.

Which two actions should the developer perform first?

A. Verify the field was added to the Page Layout.

B. Wait a few moments for metadata changes to propagate.

C. Recreate the field using Object Manager.

D. Delete the browser cache.

**Correct Answer:** A and B

**Explanation:**

Fields must be added to the Page Layout, and Salesforce metadata updates may take a short time before appearing throughout the UI.

---

### Question 5

An administrator needs to:

- View API names instead of labels.
- Visualize relationships between custom objects.
- Quickly create several new custom fields.

Which combination of Schema Builder features satisfies all of these requirements?

A. Enable **Display Element Names**, enable **Show Relationships**, and use the **Elements** panel to create fields.

B. Enable **Show Legend** and modify the Page Layout.

C. Use Object Manager exclusively because Schema Builder cannot create fields.

D. Enable **Display Element Names** and create the fields using Reports.

**Correct Answer:** A

**Explanation:**

- **Display Element Names** shows API names.
- **Show Relationships** displays object relationships.
- The **Elements** panel allows new fields to be created using drag and drop.

## Result

- Score: 5/5 (100%)
```
