# Travel Memory

`.env` file to work with the backend after creating a database in mongodb: 

```
MONGO_URI='ENTER_YOUR_URL'
PORT=3001
```

Data format to be added: 

```json
{
    "tripName": "Incredible India",
    "startDateOfJourney": "19-03-2022",
    "endDateOfJourney": "27-03-2022",
    "nameOfHotels":"Hotel Namaste, Backpackers Club",
    "placesVisited":"Delhi, Kolkata, Chennai, Mumbai",
    "totalCost": 800000,
    "tripType": "leisure",
    "experience": "Lorem Ipsum, Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum, ",
    "image": "https://t3.ftcdn.net/jpg/03/04/85/26/360_F_304852693_nSOn9KvUgafgvZ6wM0CNaULYUa7xXBkA.jpg",
    "shortDescription":"India is a wonderful country with rich culture and good people.",
    "featured": true
}
```


For frontend, you need to create `.env` file and put the following content (remember to change it based on your requirements):
```bash
REACT_APP_BACKEND_URL=http://localhost:3001
```
![AWS-EC2](https://github.com/user-attachments/assets/24e74aaf-0837-4f40-8dad-989f2ca9512a)


Imgaes created for both back and frontend servers.
<img width="1656" height="947" alt="image" src="https://github.com/user-attachments/assets/21c2b116-ccfe-42dd-939a-b29599cdb23d" />

Target Groups are created for both frontend and backend servers.
<img width="1656" height="947" alt="image" src="https://github.com/user-attachments/assets/7cfa4b18-d9fc-44b8-aeef-673693330306" />


LoadBalcer for travel memory 
<img width="1648" height="945" alt="image" src="https://github.com/user-attachments/assets/ae018139-1d09-4529-b5ab-0de688d8fb8f" />



