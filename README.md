This is user model

{
    
    firstName: { type: String, minlength: 2, maxlength: 200, required: true },
    
    lastName: { type: String, minlength: 2, maxlength: 200 },
    
    email: { type: String, required: true, unique: true },
    
    dateOfBirth: { type: String },

    password: { type: String, minlength: 8, maxlength: 16, required: true },
    
},

You can use postman collection for your requests (Siz so'rovlaringiz uchun postman collection dan foydalana olasiz)

Api

![image](https://github.com/user-attachments/assets/2c582384-432d-4d0d-b96b-02251e2c1803)
