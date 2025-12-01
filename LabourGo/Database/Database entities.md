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
- isVerified
- isCriminal record verified
- hirer_id

### 🎯 Skills
- id
- name
- createdAt
- UpdateAt
- entity_id (labor id)
- entity_type (laborer/ ngo/thekedar)
- is row deleted
### 🎯 Skills events
- id
- skill_id
- created_at
- updated_at
- isRowDeleted
### 🧑‍💼 Employer (our customer)

- id
- profile
- reviews
- email
- contact number
- isverified
- created_at
- updated_at

### hirer (NGO/ thekedar)
- id
- isVerified
- address
- category (NGO/ thekedar)
- 
### 📦 Job (Request)

- id
- title
- customer_id
- description
- location (address wise)
- skills (json)
- h3 index 
- scheduled / urgent
- status (open, assigned, completed, cancelled)
- created_at 
- updated_at
- images 
- payment type

### 🗺️ Job assigned
- id
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
- createdat
- updated at
- entityid(customer / labor)