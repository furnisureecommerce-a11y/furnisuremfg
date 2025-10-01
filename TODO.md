# TODO: Add Phone Number to Customer Details in Admin Order Page

## Tasks:
- [x] Edit OrderManager.tsx to display phone number in the customer details dialog
- [x] Modify backend getAllOrders to populate phone from user profile if not in order
- [ ] Test the changes by running the frontend dev server and checking the order details modal

## Details:
- Frontend: Frontend/src/components/adminComponents/OrderManager.tsx - Added phone display in dialog.
- Backend: Backend/src/controllers/orderController.js - Added logic to fetch phone from ClerkUser if order.phone is empty and user_id exists.
- Testing: Navigate to admin panel > Orders > Click "Details" on an order to verify phone displays (from order or profile).
