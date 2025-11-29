## 3️⃣ **Design the Core Domains (Entities / Models)**

Your product needs these fundamental models:

### 👷‍♂️ Laborer

- id
- name
- phone
- availability
- current location
- h3 index
- created at
- updated
- isDisabled

### 🎯 Skills
- id
- name
- createdAt
- UpdateAt
- entity_id
- entity_type (laborer/ ngo/thekedar)
- is row deleted
### 🎯 Skills events
- id
- skill_id
- created_at
- updated_at
- isRowDeleted
### 🧑‍💼 Thekedaar/ NGO

- profile
- reviews

### 📦 Job (Request)

- title
- description
- location
- h3 index
- scheduled / urgent
- status (open, assigned, completed)

### 🗺️ Matching

- job_id
- laborer_id
- distance
- accepted / rejected

### 🔔 Notification

- job_id
- laborer_ids (array)
- read / unread

### ⭐ Rating
- laborer_id
- rating
- review