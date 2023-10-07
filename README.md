# BORED

#Group 24

#Group Members:

-> Rushendra Sidibomma
-> Vishnu Priya
-> Sudha Sree
-> Nehul Singh
-> Yasin Shaik

#How to run:  
-> Download the zip file  
-> Extract the zip file in a location and open it in your IDE  
-> In the terminal, enter the following command: npm start  
-> Go to your browser (preferably chrome) and in the searchbar, enter "localhost:3000/"  
-> This will take you to the homapage of the website.  


#We have used MongoDB Atlas which is a cloud-based database and it has been linked using the connection.js file under the Database folder


docker build -t bored-1 .

docker run -d -p 5000:3000 --name=bored-1 bored-1 npm run ec2 -- --host=0.0.0.0

efeqof9qe