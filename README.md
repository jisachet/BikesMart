# Bikesmart
## FUNCTIONS
## Customer
- Customer can view/search products without login.
- Customer can also add/remove product to cart without login (if customer try to add same product in cart. It will add only one)
- When customer try to purchase product, then he/she must login to system.
- After creating account and login to system, he/she can place order.
- Customer can check their ordered details by clicking on orders button.
- Customer can see the order status (Pending, Confirmed, Delivered) for each order  
- Customer can Download their order invoice for each order
- Customer can send feedback to admin (without login)
---
### Admin
- First admin will login ( for username/password run following command in cmd )
- Admin can add/delete/view/edit the products.
- Admin can view/edit/delete customer details.
- Admin can view/delete orders.
- Admin can change status of order (order is pending, confirmed, out for delivery, delivered)
- Admin can view the feedbacks sent by customers.
---
### Other Features
- customer places order and admin deleted that user(fraud detection), then their orders will automatically deleted
- suppose 1 customer places 4 products order and admin deleted 2 product from website, then that 2 product order will
    also be deleted and other 2 will be their
- If user click on purchase button without having products in their cart, then website will ask to add product in cart first.

## HOW TO RUN THIS PROJECT
- Install Python (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
pip install django
pip install django-widget-tweaks
pip install xhtml2pdf

```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```
## UML Diagrams
![image](https://github.com/jisachet/Bikesmart/assets/75719262/c4be13e5-8488-4073-bfb6-a02d7338dbbc)  
Fig.: Use Case Diagram  
![image](https://github.com/jisachet/Bikesmart/assets/75719262/1f8a8354-be29-4f91-b61b-1d73591d09d5)  
Fig.: Data Flow Diagram  
![image](https://github.com/jisachet/Bikesmart/assets/75719262/70b6f20a-736c-483c-a669-c63abd1cf0ce)  
Fig.: Sequence Diagram  
![image](https://github.com/jisachet/Bikesmart/assets/75719262/2d4fb8c0-630f-43ba-8536-6ec3f79d6525)  
Fig.: ER Diagram  


## Drawbacks/LoopHoles
- When user edit their profile then he/she must login again because their username/password is updated in db.
- Popup of product is added to cart is shown when click on Ecommerce logo (soon i will fix it)

## Contributor
- [Sachet Manandhar](https://github.com/jisachet)

## Feedback
Any suggestion and feedback is welcome. You can message me on teams.
- [Teams](https://teams.microsoft.com/_#/conversations/48:notes?ctx=chat)
- [Contact on Facebook](https://fb.com/jisachet4)
