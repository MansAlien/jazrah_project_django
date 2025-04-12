# Jazrah project

## 1. Analysis phase

### Users_account
- location 
- user (name, date_of_birth, gender, phone_number, location_id, email, bank_account, type_id, permissions_id)
- type (name, )
- permission

### User_type
- Admin 
- Manager (category CRUD, add the new products)
- Customer (products, recipies, order)

---

### products plan
- Category (name, active)
- SubCategory (category_id, name, active)
- product (sub_category_id, name, image, price, description, expiry_date, tage, calories)

---

### payment
- Comming Soon

---

### Orders
- order (user_id, items_list, payment method, total, UUID, deliver_status, deliver_type)
- items (product[name, price], amount, total)

---

## 2. Design phase
