# Tallis-Kinrade
Add all comments for future programmes

# 12/08/2021
Have been working on the user interface and setting up all the frame and labels. Started out by writing out all of the labels individually, 

    ## ip_title = Label(initinputfrm, text="INITIAL PARAMETERS:", font=("Ariel", 14), bg="coral").grid(sticky="NESW", row=0, padx=5, pady=5)
    ## i_v = Label(initinputfrm, text="initial velocity", bg="coral").grid(sticky="W", row=1, column=0, padx=5, pady=5)
    ## i_h_v = Label(initinputfrm, text="initial horizontal velocity", bg="coral").grid(sticky="W", row=2, column=0, padx=5, pady=5)
    ## i_v_v = Label(initinputfrm, text="initial vertical velocity", bg="coral").grid(sticky="W", row=3, column=0, padx=5, pady=5)
    ## angle = Label(initinputfrm, text="angle of launch", bg="coral").grid(sticky="W", row=4, column=0, padx=5, pady=5)
    ## i_h = Label(initinputfrm, text="initial height", bg="coral").grid(sticky="W", row=5, column=0, padx=5, pady=5)
    ## g_acc = Label(initinputfrm, text="gravitational acceleration", bg="coral").grid(sticky="W", row=6, column=0, padx=5, pady=5)
    ## t_of_f = Label(initinputfrm, text="time of flight", bg="coral").grid(sticky="W", row=7, column=0, padx=5, pady=5)
    ## d = Label(initinputfrm, text="distance", bg="coral").grid(sticky="W", row=8, column=0, padx=5, pady=5)
    ## max_h = Label(initinputfrm, text="maximum height", bg="coral").grid(sticky="W", row=9, column=0, padx=5, pady=5)
    
but then thought that i could probably do it using lists and for loops and changed it to make it more concise.
Had trouble with the validation and am going to leave that for the moment till i can get a second opinion. Im really struggling to get it to connect to my database.
Someone helped me with the code to add a new user, now just have to sort out the creating of the database.
