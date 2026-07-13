# Lesson 009

**Title:** Schema Builder in Salesforce: How to add fields using Schema Builder?

## Notes

- Access Schema Builder via:
  - Setup → Objects and Fields → Schema Builder
- Provides a visual interface for managing objects and fields.
- Filter displayed objects using **Select From** (e.g., Custom Objects only).
- Enable **Display Element Names** to show API names (e.g., Employee__c).
- Enable **Show Relationships** to visualize relationships between objects.
- Show or hide the legend.
- Zoom and navigate freely around the canvas.
- Drag and drop field types from the **Elements** panel to create new fields.
- Not all field types are available in Schema Builder.
- Use the object's gear icon to edit or delete the object.
- Right-click a field to:
  - Edit field properties.
  - Delete the field.
  - Manage field-level security.
- Schema Builder is faster than Object Manager for creating multiple fields.
- Fields created in Schema Builder are **not** automatically added to the Page Layout.
- Add new fields manually:
  - Setup → Object Manager → Employee → Page Layouts → Employee Detail
- Page Layouts allow:
  - Reordering fields.
  - Adding/removing fields.
  - Organizing sections.
- Metadata changes may take a short time to appear.

## Mock Questions

### Question 1

A Salesforce administrator creates several custom fields for the Employee__c object using Schema Builder. The users report that they cannot see the new fields on the record page.

**Correct Answer:** B

**Explanation:** Fields created in Schema Builder must be manually added to the Page Layout before users can see them.

---

### Question 2

A developer wants to inspect how several custom objects are related to each other while reviewing the data model.

**Correct Answer:** B

**Explanation:** Enable **Show Relationships** to display object connections.

---

### Question 3

Your team needs to create 15 new custom fields on an existing custom object as quickly as possible.

**Correct Answer:** B

**Explanation:** Schema Builder provides the fastest visual workflow for creating multiple fields.

---

### Question 4

A developer creates a custom field using Schema Builder and immediately opens a record page, but the field is still not visible.

**Correct Answer:** A and B

**Explanation:** Verify the Page Layout and allow time for metadata changes to propagate.

---

### Question 5

An administrator needs to view API names, visualize relationships, and create new fields quickly.

**Correct Answer:** A

**Explanation:** Use Display Element Names, Show Relationships, and the Elements panel together.

## Result

- Score: 5/5 (100%)
