# Pizza ordering app<br/>

Urpizzas is a mern (mongodb-express-reactjs-nodejs) web app. It is a ordering app with payment gateway (stripe - currently in test mode). <br/>The app is associate with admin panel. <br/>

The admin hase control over the menu items, user list, order status.<br/>
admin page<br/>
![admin](https://user-images.githubusercontent.com/97933338/203781747-ecf9395c-df4f-4af4-9222-9d0804408602.png)
<br/>
User page<br/>

![user](https://user-images.githubusercontent.com/97933338/203782037-8b9e448b-d3c1-4f8b-9ed3-d685f140ac6e.png)

credentials<br/>
1.admin<br/>
username: admin@gmail.com<br/>
password: 1234<br/>
2.user<br/>
username: user@gmail.com<br/>
password: 1234<br/>

The user can regsiter and login to place order and pay.<br/>

As mentioned the application is in test mode for payment gateway.<br/>
The testing card details can be used:<br/>

| BRAND	| NUMBER | CVC | DATE |<br/>
| --- | --- | --- | --- |<br/>
| Visa	| 4242424242424242 | Any 3 digits |	Any future date |<br/>
| Mastercard	| 5555555555554444 | Any 3 digits |	Any future date |<br/>

For more testing card number you can vist <a href="https://stripe.com/docs/testing?numbers-or-method-or-token=card-numbers">Stripe testing card docs</a> <br/>

The app is currently deployed in heroku. <a href="https://urpizzas.herokuapp.com/">Ur pizzas</a><br/>
