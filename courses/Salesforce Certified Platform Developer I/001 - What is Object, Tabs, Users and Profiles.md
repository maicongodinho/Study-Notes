# Lesson 006

**Title:** What is Object, Tabs, User and Profiles in Salesforce: Quick overview

## Notes

- Object = Database table.
- Field = Column of an Object.
- Record = Row of an Object.
- A Tab provides quick access to an Object.
- An App is a collection of Tabs and related features.
- Salesforce provides standard Apps (Sales, Service, Marketing, etc.).
- Every User must have exactly one Profile.
- A Profile defines a user's baseline permissions.
- Profiles control access to Apps, Tabs and Objects.
- Profiles define CRUD permissions (Create, Read, Update and Delete).
- Permission Sets extend permissions beyond the Profile.
- A User can have multiple Permission Sets.
- Salesforce includes standard Profiles.
- Custom Profiles can be created.
- Profiles can be cloned.
- User settings: Setup → Users → Users.
- Profile settings: Setup → Users → Profiles.
- Changing a Profile changes the Apps and features visible to the User.

## Mock Questions

### Q1
**What is an Object in Salesforce?**
- A. A screen used to navigate the application
- **B. A database table that stores data** ✅
- C. A permission assigned to users
- D. A collection of Profiles

**Explanation:** An Object represents a database table used to store records.

### Q2
**Which statement about Profiles is correct?**
- A. A User can exist without a Profile.
- B. Profiles only control page layouts.
- **C. Every User must have exactly one Profile.** ✅
- D. Profiles replace Permission Sets.

**Explanation:** Every User requires exactly one Profile. Additional permissions are granted through Permission Sets.

### Q3
**What is the main purpose of a Tab?**
- A. Store records
- B. Create new Profiles
- **C. Provide easy access to an Object.** ✅
- D. Execute Apex code

**Explanation:** Tabs provide quick access to Objects in the UI.

### Q4
**Which permission is NOT part of CRUD?**
- A. Create
- B. Read
- **C. Execute** ✅
- D. Delete

**Explanation:** CRUD stands for Create, Read, Update and Delete.

### Q5
**What is the relationship between Profiles and Permission Sets?**
- A. Permission Sets replace Profiles.
- B. Profiles extend Permission Sets.
- **C. Permission Sets grant additional permissions beyond the Profile.** ✅
- D. Only one Permission Set can be assigned to a User.

**Explanation:** Permission Sets complement Profiles and users may have multiple Permission Sets.

## Result

- Score: **5/5 (100%)**