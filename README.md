Hall Booking API

View Available Room : https://hall-booking-6kjl.onrender.com/rooms

Creating New Room: https://hall-booking-6kjl.onrender.com/rooms
POST Method: Sample Data: 
{
            "roomId": "3",
            "seatsAvailable": "20",
            "amenities": "Home Theatre",
            "pricePerhr": "300"
}                       
View Booked Details: https://hall-booking-6kjl.onrender.com/viewbooking

List Customed with booked date: https://hall-booking-6kjl.onrender.com/customers

Book Room By ID: https://hall-booking-6kjl.onrender.com/booking/:id

POST Method : Path Variable : id, Sample Data:
{
    "customer":"maha",
    "bookingDate":"20/10/2023",
    "startTime": "12:00pm",
    "endTime": "11:59am"
}

No. of times Customed Booked: https://hall-booking-6kjl.onrender.com/customers/maha
