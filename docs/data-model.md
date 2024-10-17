# Data Model

## Product Catalog Service

```
Product
- id: UUID
- name: String
- description: String
- price: Decimal
- inventory: Integer
- category: String
```

## Order Service

```
Order
- id: UUID
- userId: UUID
- status: Enum (CREATED, PROCESSING, SHIPPED, DELIVERED, CANCELLED)
- totalAmount: Decimal
- createdAt: DateTime
- updatedAt: DateTime

OrderItem
- id: UUID
- orderId: UUID
- productId: UUID
- quantity: Integer
- price: Decimal
```

## User Service

```
User
- id: UUID
- username: String
- email: String
- password: String (hashed)
- firstName: String
- lastName: String
- address: String
- createdAt: DateTime
- updatedAt: DateTime
```