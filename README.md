# Embedded-Systems


     This project creates a functioning termostat, it solves several problems.  It takes a temapture from a sensor that reads it
     from the room it is in.  Also, the progam takes input from two buttons which when pressed modify the desired tempature.  The
     buttons are checked for a press every 200ms, and the tempature is checked every 500ms.  When the tempature is checked it is
     also compared to the desired tempature and if this is above the current tempature the heater is turned on.  The display is
     updated every second.
     
     I did well in setting up the timers and converting the system to run as state machines.  I am not really sure, but I am still
     not sure that the state machines were needed.  An improvement may be to remove them.  I have left the original code in that
     was used before I developed the state machines, it is commented out.  However, I do think having the state machine diagrams
     lend to people understanding the way the program works.  It is really a toss up.
     
     For me working with embedded systems really got me thinking of how many things work in the world, like street light systems,
     electronic locks with keypad, motion detetor activated security systems, and much more.  The coding from the state diagrams
     was really straight forward for me and designing the diagrams is has mostly been enjoyable.  In my opinion they have a slight
     challenge to them which I like; some are more complicated than others.  Once they are done, however, as I stated above, the
     coding for them is really just cut and paste.
     
     I am not sure how this will translate to other course work, as it did use an external board, and this code runs on an endless
     loop.  It is facinating and I do hope to use it again, I would love to work in a feild that programs state machines because I
     really seemed to pick it up with out much difficulty.
     
     To make this project maintainable readable, and adaptable I thourgoly commented the code I wrote.  I explained the intent of
     how the thermostat could be adapted to comunicate with a server in my paper; I could see it being able to be adjusted remotely
     as well.  The diagrams submitted show how the data flows for clairity, and the video shows a demonstraion of the thermostat in
     action.
