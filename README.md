# st2_linux_user_management
StackStorm pack for user management on linux systems






Installation Steps

Login to the ST2 server
Clone this project
cd st2_linux_user_management
Replace <st2-username> and <password> with valid credentials and run bellow command.
export ST2_AUTH_TOKEN=`st2 auth -t <st2-username> -p <password>`
st2 pack install file://$PWD



