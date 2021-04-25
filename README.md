  

# Medical Resource API (FrontEnd Question)
<br/>

<br/>

  *  *  *  *  *
### Requirements

- Initially you need to create Two types of User
	- Doctor
	- Patient
	
    ### Authentication Endpoints
    -  #### POST api/auth/signUp 
        > Signup will take necessary data for users and most important it will take users credential and role once the request get sucessfully we need a Token for authentication and a message saying "User Sucessfully logged in

    -  #### POST api/auth/login
        > Login will take necessary users credential, once the request get sucessfully we need a Token for authentication and a message saying "User Sucessfully logged in"

    ### Other Endpoints
    - #### POST api/appointment/requestAppointment/:id
        **Only for patients**
        > This Endpoint will Post a request and Patient will send the date and time of the appointment

    -  #### POST api/appointment/acceptAppointment/:id
        **Only for doctors**
        > This endpoint will accept all the appointments that a user requested to doctors

    -  #### GET api/appointment/myAppointments 
        > This endpoint will show all the appointments made by user and accepted my doctor and for doctors it will show all the appointments made to that particular doctor

    -  #### GET api/appointment/requestedAppointments
        > This endpoint will show all the appointments made by users both to user and patient (user can see the requests they had made and patient can see there appointments)


