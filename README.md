# 🥗 Jazrah Project

A project focused on food products, orders, and user management with role-based access and future payment integration.

---

## 📊 1. Analysis Phase

### 👤 Users Account

| Table        | Fields |
|--------------|--------|
| **`location`** | — |
| **`user`** | `name`, `date_of_birth`, `gender`, `phone_number`, `location_id`, `email`, `bank_account`, `type_id`, `permissions_id` |
| **`type`** | `name` |
| **`permission`** | — |

#### 👥 User Types
- 🛠️ **Admin**
- 📦 **Manager** — can manage categories and add new products
- 🛒 **Customer** — can view products, recipes, and place orders

---

### 🛍️ Products Plan

| Table           | Fields |
|------------------|--------|
| **`category`** | `name`, `active` |
| **`subcategory`** | `category_id`, `name`, `active` |
| **`product`** | `sub_category_id`, `name`, `image`, `price`, `description`, `expiry_date`, `tag`, `calories` |

---

### 💳 Payment

- 🚧 **Coming Soon**

---

### 📦 Orders

| Table        | Fields |
|--------------|--------|
| **`order`** | `user_id`, `items_list`, `payment_method`, `total`, `UUID`, `deliver_status`, `deliver_type` |
| **`items`** | `product[name, price]`, `amount`, `total` |

---

## 🎨 2. Design Phase

