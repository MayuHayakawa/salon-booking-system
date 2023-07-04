```
backend
├── index.js
├── config
│   └── db.js
├── controller
│   ├── auth.js --{ userRegister, staffRegister, userLogin, staffLogin, refresh } //not useing staffLogin and refresh
│   ├── booking.js --{ getBooking, addBooking, updateBooking, deleteBooking } //not using updateBooking
│   ├── menu.js --{ getMenu, addMenu, updateMenu, deleteMenu }
│   ├── staff.js --{ getAllStaff, getStaffProfile, updateStaffProfile, deleteStaffProfile } //not using getStaffProfile
│   ├── staffschedule.js //not using for now --{ getSchedule, addSchedule, updataSchedule, deleteSchedule }
│   └── user.js --{ getUserProfile, updateUserProfile }
├── middleware
│   ├── authentication.js
│   ├── checkStaff.js //not using for now 
│   └── checkUser.js //not using for now
├── model
│   ├── booking.js
│   ├── menu.js
│   ├── staff.js
│   └── user.js
├── route
│   ├── auth.js
│   ├── booking.js
│   ├── menu.js
│   ├── staff.js
│   └── user.js
├── Util
│   ├── jwtUtil.js
│   └── passwordUtil.js
├── .env
├── MernStack.postman_collection.json
├── package-lock.json
└── package.json
```